
# Documentação do Time Ágil — SpeakUp

## Papéis do time

O time responsável pela gestão ágil desta atividade é composto por Mateus Henrique Bueno de Carvalho e Leandro Anisio Barreto de Queiroz. A divisão prática de responsabilidades considera o tamanho reduzido do grupo e a natureza acadêmica do trabalho.

- **Product Owner — Mateus Henrique Bueno de Carvalho:** organiza e prioriza o backlog, considerando as necessidades dos cidadãos, os requisitos do SpeakUp, o valor das funcionalidades e as dependências entre tarefas.
- **Scrum Master — Leandro Anisio Barreto de Queiroz:** apoia a organização do fluxo de trabalho, acompanha o quadro Kanban, identifica impedimentos e contribui para a aplicação dos acordos de trabalho.
- **Execução e desenvolvimento dos artefatos — Mateus e Leandro:** ambos contribuem para a elaboração e revisão dos requisitos, da documentação, das issues, dos pull requests e dos demais artefatos de gestão do projeto.

Como esta entrega se concentra na gestão ágil e na documentação, a responsabilidade pela execução dos artefatos não significa que todas as funcionalidades do sistema já estejam implementadas.

## Definition of Ready

Uma issue estará pronta para entrar em DOING quando atender às seguintes condições verificáveis:

- O título identifica claramente a funcionalidade, o problema ou a tarefa.
- A descrição apresenta o objetivo e o contexto relacionado ao SpeakUp.
- A necessidade está relacionada a um requisito funcional, requisito não funcional ou regra de negócio identificável, quando aplicável.
- Os critérios de aceitação descrevem resultados verificáveis.
- A prioridade MoSCoW está definida no corpo da issue.
- As dependências conhecidas estão registradas.
- O escopo permite compreender o que precisa ser feito e como verificar o resultado.
- As informações necessárias para iniciar a atividade estão disponíveis.

Se alguma condição essencial estiver ausente, a issue permanece em TO-DO até ser esclarecida.

## Definition of Done

Uma issue poderá ser movida para DONE quando todos os itens aplicáveis abaixo forem atendidos:

- [ ] Os critérios de aceitação da issue foram atendidos.
- [ ] As alterações foram revisadas e estão coerentes com os requisitos e as regras de negócio do SpeakUp.
- [ ] A documentação e os artefatos relacionados foram atualizados, quando aplicável.
- [ ] As verificações pertinentes foram realizadas e seus resultados foram registrados. Quando não for possível testar, a limitação ou pendência foi documentada.
- [ ] As regras de proteção da identidade e de controle de acesso foram respeitadas, quando aplicáveis.

O mesmo checklist deve aparecer no template de pull request. Quando uma funcionalidade ainda não estiver implementada, a issue poderá ser concluída como atividade de especificação ou documentação somente se seus critérios de aceitação forem atendidos e as limitações estiverem explicitadas.

## Matriz de stakeholders

A análise considera os stakeholders relacionados ao SpeakUp e ao contexto acadêmico. Poder representa a capacidade de influenciar decisões ou impor requisitos; interesse representa o grau de envolvimento ou impacto relacionado ao projeto.

| Quadrante | Estratégia | Stakeholders |
|---|---|---|
| Alto poder e alto interesse | Gerenciar de perto | Responsável pelo produto, responsável pela facilitação do time e docente orientador ou avaliador do projeto |
| Alto poder e baixo interesse direto | Manter satisfeito | Coordenação do curso e ANPD, considerando seu papel institucional e regulatório |
| Baixo poder e alto interesse | Manter informado | Cidadãos denunciantes e colaboradores das organizações responsáveis pelo atendimento das ocorrências |
| Baixo poder e baixo interesse | Monitorar | Pessoas que não utilizam diretamente o sistema, mas podem acompanhar sua evolução acadêmica |

A estratégia de comunicação deve considerar que os cidadãos precisam de facilidade de registro e transparência no acompanhamento, enquanto os colaboradores das organizações precisam consultar somente as ocorrências autorizadas. A ANPD representa uma referência regulatória relevante para os requisitos de proteção de dados pessoais, sem que isso implique participação direta no desenvolvimento acadêmico.

## Plano de comunicação

| O que comunicar | Para quem | Canal | Frequência |
|---|---|---|---|
| Objetivos, prioridades e itens selecionados para o ciclo | Mateus e Leandro | GitHub Issues e GitHub Projects | No início de cada ciclo de trabalho |
| Andamento, bloqueios e próximas ações | Mateus e Leandro | Quadro Kanban e canal de comunicação acordado pelo grupo | Diariamente nos períodos de atividade |
| Alterações em documentação e artefatos | Integrantes do time | Pull requests do GitHub | A cada alteração submetida para revisão |
| Resultados e evidências das entregas acadêmicas | Docente orientador ou avaliador | Ambiente acadêmico e demonstração dos artefatos | A cada entrega ou quando solicitado |
| Mudanças relevantes no escopo e nos requisitos | Integrantes e docente, quando pertinente | Issues e documentação do repositório | Sempre que ocorrer uma mudança |
| Necessidades de usuários e expectativas sobre o acompanhamento das ocorrências | Cidadãos e demais usuários envolvidos em validações planejadas | Formulário de pesquisa ou avaliação do protótipo | Quando houver uma atividade de validação planejada |
| Requisitos de privacidade e controle de acesso | Integrantes responsáveis pela documentação e implementação futura | Issues e documentos do projeto | Durante a revisão dos requisitos e das mudanças relacionadas |

O Sprint Planning e a Retrospective são voltados ao time. A Daily Scrum, quando adotada como cerimônia, deve ser utilizada para inspecionar o progresso e ajustar o plano de trabalho. A Sprint Review pode incluir a apresentação dos resultados ao docente ou a outros stakeholders pertinentes.

As frequências acima representam o plano proposto para a atividade; não constituem evidência de reuniões ou validações que ainda não tenham ocorrido.

## Quadro e limite de WIP

O acompanhamento será realizado no GitHub Projects, com as colunas TO-DO, DOING e DONE.

- **TO-DO:** issues priorizadas que ainda não estão em execução.
- **DOING:** issues em execução.
- **DONE:** issues que atenderam aos critérios de conclusão definidos para a atividade.

O limite de WIP de DOING será de **2 issues simultâneas**. Como o time tem dois integrantes, esse limite permite, em princípio, uma atividade ativa por pessoa, sem incentivar a abertura de muitas tarefas ao mesmo tempo. Caso uma atividade dependa da outra ou exija colaboração, os integrantes poderão trabalhar juntos no mesmo item, respeitando o limite estabelecido.

O limite deverá ser declarado na configuração ou na documentação do quadro. As issues do backlog devem estar associadas ao projeto e ser movimentadas conforme o estado real do trabalho.

## Declaração de uso de IA

Foi utilizada inteligência artificial como apoio à organização e à elaboração inicial dos artefatos desta atividade.

- **Ferramenta:** ChatGPT, da OpenAI.
- **Finalidade:** apoiar a estruturação do README, dos templates de issues e pull requests e da documentação do time ágil, utilizando o enunciado da atividade e os materiais existentes do SpeakUp.
- **Revisão e adaptação:** Mateus revisou o contexto da atividade e esclareceu que somente ele e Leandro participam desta entrega. O conteúdo foi estruturado para refletir os requisitos, as regras de negócio e os stakeholders do SpeakUp, evitando declarar como implementadas funcionalidades que ainda estão previstas.
- **Revisão final:** os integrantes devem conferir as prioridades, os critérios de aceitação, a divisão prática das responsabilidades e a coerência entre os arquivos antes da entrega.

A IA foi utilizada como ferramenta de apoio à redação e à organização. As decisões finais e a validação dos artefatos são responsabilidade dos integrantes.
