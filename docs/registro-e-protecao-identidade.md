# Registro de denúncia e proteção da identidade — SpeakUp

## Objetivo

Definir o comportamento previsto para registrar denúncias e proteger a identidade do denunciante perante a organização responsável.

## Dados do registro

Conforme o RF-003, o registro da denúncia deverá contemplar:

- Descrição do problema.
- Localização.
- Categoria correspondente.
- Opção de proteção da identidade.

A denúncia deverá permanecer vinculada internamente à conta que a registrou.

## Proteção da identidade

Conforme o RF-015 e a RNE-004, quando a proteção estiver ativa, os colaboradores da organização responsável não poderão visualizar o nome, o e-mail ou outros dados que identifiquem o denunciante.

A proteção da identidade representa uma restrição de acesso aos dados pessoais. Ela não significa eliminar o vínculo entre o usuário e a denúncia.

O modelo prevê o atributo `anonima` na entidade Denúncia para representar a opção de proteção da identidade.

## Acompanhamento pelo denunciante

Conforme o RF-016 e a RNE-005, o usuário autenticado deverá continuar podendo consultar suas próprias denúncias e acompanhar o andamento, mesmo quando a identidade estiver protegida.

O vínculo interno deverá permitir a consulta do histórico e das atualizações disponíveis sem expor os dados identificadores aos colaboradores da organização responsável.

## Acesso aos dados

Conforme a RNE-006, o acesso deverá respeitar as permissões de cada perfil:

- O usuário comum poderá consultar suas próprias denúncias.
- Os colaboradores poderão consultar ocorrências encaminhadas à sua organização, respeitando as restrições de identidade.
- O administrador geral poderá executar as operações administrativas autorizadas.

## Requisitos relacionados

RF-003, RF-015, RF-016, RNE-004, RNE-005 e RNE-006.

## Verificação documental

A especificação deverá ser conferida em conjunto com os requisitos, as regras de negócio e o modelo de dados. Não foram realizados testes de software por esta documentação, e a proteção efetiva depende de implementação e validação futuras.
