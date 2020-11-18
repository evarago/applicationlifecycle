# Application Lifecycle Management - ALM

O ALM contempla um conjunto de ferramentas que integram e norteiam as etapas do ciclo de vida de uma aplicação: Concepção, construção, operação e evolução.

Aborda desde a idealização de um produto, definição das tecnologias a serem utilizadas na construção dos softwares até o acompanhamento de custos de manutenção evolutiva dos recursos de TI.

## Pessoas, Processos e Ferramentas são a composição que sustenta a gestão do ciclo de vida das aplicações:

### Pessoas 
Qualquer integrante da equipe que interage com qualquer uma das etapas do ciclo de vida da aplicação. Este grupo é o responsável pelo alinhamento estratégico da aplicação, pelo desenvolvimento do mesmo e pela aderência aos requisitos dos clientes.
### Processos 
Identificam o como fazer. Este pilar é composto por artefatos, boas práticas e documentações que norteiam as pessoas durante o desenvolvimento e/ou manutenção das aplicações.
### Ferramentas 
Este pilar engloba toda e qualquer meio que possibilite as pessoas realizarem os seus processos. Por exemplo: IDEs, linguagens de programação, computadores, etc.

## Fases que agrupam atividades distintas

### Definição
Nesta fase são identificadas as necessidades e motivações da empresa que justifiquem a execução do projeto.
### Construção
Nesta segunda etapa são executados os planos de ação elaborados na etapa anterior. É neste período do ciclo de vida que utilizamos a gestão de projetos para concretizar a aplicação mantendo-a dentro dos prazos e custos planejados.
### Operação
Aqui a aplicação já foi desenvolvida e será publicada para acesso pelo grande público. Neste segmento do processo, a equipe de infra-estrutura deve empenhar-se para que a aplicação mantenha-se funcional e sem gargalos.
### Fim
Aqui a empresa fica responsável por analisar criteriosamente a aplicação e definir a sua evolução através de patches e/ou a substituição completa por novas versões.

## Entradas e saídas esperadas em cada uma das fases do ALM e os seus respectivos responsáveis.

### Gerenciamento de Requisitos
Refere-se à pratica de documentar e manter a rastreabilidade dos requisitos ao longo do ciclo de vida da aplicação.
### Gerenciamento de Configuração de Software
Esta disciplina descreve a forma de gerenciar os diversos artefatos da aplicação (código-fonte, documentos, planilhas, apresentações, etc) e versioná-los.
### Montagem e Integração
Esta disciplina consiste na prática de unir todos os módulos e componentes da aplicação em um único pacote e testá-lo e distribuí-lo na infraestrutura de TI.
### Engenharia de Distribuição
A Engenharia de Distribuição trabalha em conjunto com o Gerenciamento de Configuração de Software para garantir que os artefatos estão versionados corretamente, estejam eles em ambiente de produção ou homologação.
### Gerenciamento de Defeitos
A disciplina consistem em coletar ocorrências da aplicação ou de qualquer parte do processo, analisar a(s) causa(s)-raiz(es) e evitar que os mesmos problemas voltem a acontecer no futuro.
### Testes Unitário, Integrado e de Regressão 
Como o próprio nome da disciplina diz, é neste momento que os testes devem ser realizados para garantir a integridade das operações da aplicação.
Análise de Código: Neste momento o código-fonte é validado quanto à aderência aos padrões e políticas propostos pela empresa. Aqui também são refatoradas as partes necessárias e aplicados padrões de projeto quando aplicáveis.
### Teste de Sistema 
Aqui a aplicação é testada quanto ao desempenho e a aderência aos requisitos dos clientes.

## Algumas ferramentas/Plataformas que facilitam a vida no contexto do ALM

### Gestão & Colaboração
#### Jira
Para que os times planejem e acompanhem o progresso do trabalho, registrem atividades e atendam solicitações.
#### Jira Software
Gestão Ágil para times que usam Scrum ou Kanban
#### Jira Service Desk
Funcionalidades específicas para os times de suporte e Service Desk.
#### Confluence
Suporte ao time através de um local para criar, colaborar, compartilhar e obter informações necessárias para executar o trabalho.

### Desenvolvimento e qualidade de código
#### Bitbucket
Gerenciar, revisar e compartilhar o código-fonte controlado pelo Git ou Mercurial com quantos repositórios forem necessários
#### Bamboo
Integração Contínua, deployment e gerenciamento de releases.
#### Clover
Testes de cobertura de código-fonte para Java e Groovy.
#### Crucicble
Encontrar defeitos e melhorar a qualidade do código-fonte através de revisão colaborativa (peer review)
