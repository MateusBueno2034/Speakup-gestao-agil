# Acompanhamento e histórico das denúncias — SpeakUp

## Objetivo

Consolidar a especificação do acompanhamento de ocorrências, dos estados das denúncias e do registro histórico das atualizações.

## Status das denúncias

Conforme o RF-007, os estados previstos são:

- Em análise.
- Em andamento.
- Resolvido.

O status atual deverá indicar a situação da ocorrência e estar disponível ao usuário autorizado que acompanha a denúncia.

## Consulta do histórico

Conforme os requisitos RF-008 e RF-016, o usuário autenticado deverá consultar as denúncias registradas por sua conta e as informações disponíveis sobre o andamento.

Essa consulta deverá continuar disponível quando a denúncia tiver sido registrada com proteção de identidade ativa.

## Registro das atualizações

Conforme os requisitos RF-013 e RF-020, cada atualização deverá registrar:

- Denúncia relacionada.
- Data da atualização.
- Descrição do andamento.
- Colaborador responsável pelo registro.
- Status correspondente, quando houver alteração.

O histórico deverá preservar os registros anteriores para permitir compreender a evolução da ocorrência.

## Permissões para atualização

Conforme a RNE-007, somente colaboradores autorizados da organização responsável e administradores com permissão poderão registrar atualizações ou alterar o status, respeitando suas atribuições.

A consulta das atualizações deverá respeitar as permissões definidas para o usuário e para a organização responsável.

## Requisitos relacionados

RF-007, RF-008, RF-013, RF-016, RF-020 e RNE-007.

## Verificação documental

A documentação deve distinguir o status atual da denúncia dos registros históricos de atualização e manter coerência com o modelo de dados. Nenhum teste de software é declarado por esta alteração documental.
