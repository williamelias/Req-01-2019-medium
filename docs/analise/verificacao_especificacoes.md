## Versionamento de edições
| Data       | autor               | Descrição                        | Versão |
|------------|---------------------|----------------------------------|--------|
| 08/06/2019 | Luís Cláudio T. Lima| adição da introdução e critérios | 0.1    |

### Verificação Especificações de Casos de Uso

Para a realização da verificação, foi utilizado o método de inspeção de Fagan. Esse tipo de abordagem atua na verificação de artefatos de elicitação e sem uma estrutura própria, ou produzidos por Engenheiros de Software/Requisitos, o que o configura, nesse caso, como uma lista de requisitos.

Para a realização da análise das especificações pela técnica de ispeção, antes de mais nada, foi necessária a correção da numeração das especificações de casos de uso. Em seguida foram realizados os seguintes passos:

* **Criação de 10 critérios de aceitação;**
* **Verifição das especificações de 36 casos de uso;**

###Critérios de aceitação
Para que os UCs sejam verificados por meio de inspeção, é necessário, para cada um, responder as perguntas com sim ou não:
~~~text
  1- A descrição está coerente, objetiva e de fácil entendimento?

  2- Os atores envolvidos estão bem definidos?

  3- As funcionalidades e pré-condições estão coerentes e bem estabelecidas?

  4- As pós-condições apresentam de fato os objetivos a serem alcançados?

  5- O fluxo principal apresentado atinje, de forma bem sucedida, o objetivo a ser alcançado
       pelas funcionalidades?

  6- O fluxo alternativo apresentado também atinge o objetivo a ser alcançado pelas 
     funcionalidades?

  7- O fluxo de excessão apresentado é um imprevisto inesperado que impede o objetivo a ser
     alcançado pelas funcionalidades ?

  8- O comportamento do sistema esta de acordo com critérios de requisitos funcionais ?

  9- O UC em questão já possui representação na notação UML?

  10- O UC em questão possui rastros de sua origem?
~~~

###Tabela de avaliação das especificações