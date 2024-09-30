# Mineração de Dados - Wagner Meira - Laboratório Speed

## 24/09/2024 - 17h12

- É uma boa de se fazer junto com aprendizado de máquina.

Ementa: Processo de Descoberta de Conhecimento em Bancos de Dados. Coleta e engenharia de Dados ...

A disciplina é baseada num livro X, mas pra aprender realmente tem que ler o livro que não precisa comprar.

<DataMiningbook.info>
ISBN 978-1108473989

Se não estudar o livro, termina com um conhecimento muito superficial, que é o que o tempo permite.

O livro tem 800 páginas... 😨

Vídeos, slides e outros materiais estão no Boodle

Tem também no YouTube

Ele quer que haja um ambiente mais interativo.

Plataforma Lemonade (ele não usa muito mais)

No primeiro ano de Chat GPT, tinha-se a ideia de que ele conseguiria fazer tudo, mas isso não procede. Uma atividade que ele fez  foi deixar que todos os alunos respondessem com o GPT e depois criticassem a resposta.

Aprender a lidar com a volatilidade  das LLMs

"A pessoa pra ser reprovada tem que fazer um esforço brutal nessa disciplina. O objetivo é criar um ambiente legal de discussão"

26/09/24: Atributos, Capítulos 1 ao 4

O curso está baseado em 5 eixos. Atividades geralmente em dupla

Metaturma - Portal Minhas Turmas UFMG

### Slide 1

#### What is the best?

- Artificial Intelligence
- Machine Learning
- Data Mining
- Business Intelligence
- Data Analyst
- Data Science
- Big Data

#### Imagens

Tem diversas áreas muito interconectadas.

"Qual que é a essência?"
"O profissional de TI não tem que sair embarcando em tudo"
"Qual LLM é melhor?"

- JV: Letras como forma de análise das respostas e algum método para julgar a qualidade

#### Dimensions

- Data
  - A quantidade de dados ruins é impressionante
- Models and techniques
- PRocesses and Methodologies
- Technology
- People and organizations
- Ethical and societal issues
  - "Essa é a discussão do dia"
  - Esses algoritmos se tornaram algo de interesse público

Antes os alunos de mineração de dados implementavam tudo do 0, hoje isso não faz mais tanto sentido.

Biobanking: DNA + histórico clínico
95% do que está no biobanking é ariano caucasiano.

Dilema das redes: função objetivo é maximizar atenção, não o bem estar do usuário.

#### Impact on society?

"Carro autônomo é interessantíssimo, porque nunca vai dar certo"

#### Complexities

- Data
- Behavior
- Domain
- Social
- Environment
- Learning
- Deliverable

É difícil prever a integração

Desidentificar vs anonimizar

Se anonimizei duas bases de dados, mas interliguei ambas, pode ser que o indivíduo volte a ser identificável.

#### Vários slides que ele pulou

#### Data

- Tabular
  - Categorical
  - Numerical
- Text
- Graphs
- Sound
- Image
- Video

De grafos pra baixo é onde mais tem conteúdo e menos tem algoritmo.

"Me mostra o GPT analisar um vídeo, um gráfico"

#### Mais alguns slides que ele pulou

#### Data Mining

- Concept
  - Automatic extraction of knowledge or patterns that are interesting (novel, useful, implicit, etc.) from alrge volumes of data.
- TAsks
  - Data engineering
  - Characterization
  - Prediction

Dados vs informação vs conhecimento

Área: Gerenciamento do conhecimento. Ninguém sabe ao certo como nós (com o cérebro) gerenciamos o nosso conhecimento.

Patterns são os conhecimentos formatados.

Tornaram os resultados mais programáveis, mas com isso perdeu-se no determinismo.

##### Data Mining Models

- Concept

O modelo é uma abstração. A pergunta da validade do modelo está sempre presente.

"Será que a alucinação não é uma feature do modelo?"

###### Frequent Patterns

- Task
  - Quais as mais frequentes?
- Application Scenario
  - Market-basket scenario

###### Clustering

- Task
  - Como agrupar entidades similares?
- Application Scenarios
  - Custom categorization (?)

###### Classification

- Task
  - Definir em que classe conhecida uma determinada amostra deve estar
- Application Scenario
  - Credit Scoring

##### Data Mining Paradigms

Scikitlearning: cada algoritmo é mais adequado para um agrupamento de dados

Cada algorítmo tem um "princípio ativo"

- Paradigms
  - Combinatorial
  - Probabilistic
  - Algebraic
  - Graph-based
  - Connectionist

Se você entende o algortimo e entende os parâmetros, você entende as confusões.

###### Combinatorial

- Frequent itemset mining
- k-Means
- DBScan
- Decision Tree

###### Probabilístico

- Domain
- Task
- Strategies
  - Direta ou iterativa

- Expectation-Maximization
- DenClue
- Naive Bayes
  - Rodar esse sem ter uma boa independência, pode dar problema

###### Algébrico

- Domain
- Task
- Strategies
  - Direta ou iterativa

- PCA e SVN(?)

Isso se torna um problema de otimização

###### Graph-based

Mesmos dados mas modelado de forma diferente e resolvido de forma diferente.

###### Connectionist

- Domain
- Task
- Challenges
  - Design and calibration
  - Availability of enought training data
  - Interpretability of the results

Extrapolation ability. Ele interpola bem, mas não extrapola bem.

#### Summary

- Temos 4 tarefas: fica mias rico e legal se trouxermos os problemas de domnínio.
- Podemos submeter só uma página "o que, por que e como?","Vou pegar o dado e não sei onde e fazer não sei oq"
- Businesses understanding <=> Data Understanding -> Data Preparation <=> Modelling -> Evaluation -> Deployment & Business Understanding

- Habilidades e competências
  - Objetivo 1: Teórico: ligar os paradigmas
  - Objetivo 2: Ver as técnicas funcionando na realidade

### Dúvida

- Ele falou sobre a matrícula ser confirmada. O que isso significa?
