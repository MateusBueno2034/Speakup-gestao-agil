# Cadastro e autenticação de usuários — SpeakUp

## Objetivo

Esta documentação consolida o comportamento previsto para cadastro e autenticação no SpeakUp. O conteúdo serve de referência para o desenvolvimento futuro e não significa que essas funcionalidades já estejam implementadas.

## Cadastro de usuário

Conforme o RF-001 e as regras RNE-001 e RNE-003, o cadastro deverá exigir:

- Nome.
- E-mail.
- Senha.

Antes de concluir o cadastro, o sistema deverá verificar se os campos obrigatórios foram preenchidos e se o e-mail atende aos critérios definidos para criação da conta.

O modelo de dados prevê o atributo `senha_hash` para representar o armazenamento da senha em formato protegido. Os detalhes técnicos de implementação deverão ser definidos na etapa de desenvolvimento.

## Autenticação

Conforme o RF-002 e a RNE-002, o acesso às funcionalidades internas deverá exigir autenticação.

O fluxo previsto deverá:

1. Receber as credenciais informadas pelo usuário.
2. Verificar se as credenciais são válidas.
3. Liberar o acesso somente após a autenticação.
4. Respeitar o perfil e as permissões associados à conta.

Credenciais inválidas não deverão liberar acesso às funcionalidades restritas.

## Perfis e permissões

O modelo de dados prevê o atributo `perfil` na entidade Usuário. As permissões deverão distinguir as funcionalidades acessíveis a cada perfil.

Os colaboradores vinculados às organizações possuem regras próprias de consulta e atualização, detalhadas na documentação de controle de acesso do projeto.

## Requisitos relacionados

- RF-001 — Cadastro de usuários.
- RF-002 — Login.
- RNE-001 — Validação dos campos obrigatórios.
- RNE-002 — Autenticação e controle de acesso.
- RNE-003 — Validação dos dados de cadastro.
- RNF-006 — Segurança dos dados.

## Verificação documental

A especificação deve permitir identificar os campos obrigatórios, as validações previstas e a relação entre autenticação e permissões. Esta documentação não comprova testes de software nem implementação funcional.
