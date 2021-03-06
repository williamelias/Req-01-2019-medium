## Versionamento de edições
| Data       | autor               | Descrição                        | Versão |
|------------|---------------------|----------------------------------|--------|
| 08/06/2019 | Luís Cláudio T. Lima| adição da introdução e critérios | 0.1    |
| 09/06/2019 | Luís Cláudio T. Lima| adição da tabela de avaliação das especificações | 0.2 |
| 10/06/2019 | Matheus Blanco | Adição de parágrafo de validação | 0.3 |
| 10/06/2019 | Luís Cláudio T. Lima | Atualizado definição e mudando padrão de verificação para "V"| 0.4 |

## Introdução

Para a realização da verificação, foi utilizado o método de inspeção de Fagan. Esse tipo de abordagem atua na verificação de artefatos de elicitação e sem uma estrutura própria, ou produzidos por Engenheiros de Software/Requisitos, o que o configura, nesse caso, como uma lista de requisitos.

Para a realização da análise das especificações pela técnica de ispeção, antes de mais nada, foi necessária a correção da numeração das especificações de casos de uso. Em seguida foram realizados os seguintes passos:

* **Criação de 9 critérios de aceitação;**
* **Verifição das especificações de 36 casos de uso;**

##Critérios de aceitação

Para que os UCs sejam verificados por meio de inspeção, é necessário, marcar com V para os critérios considerados corretos e deixar em branco aqueles com erros, incoerências ou passiveis de possível refatoração:
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

  8- Já existe uma representação em notação UML do UC em questão?

  9- Está claro quais são os rastros de origem do UC em questão?
~~~

###Tabela de avaliação das especificações

**Responsável:** Luís Cláudio T. Lima  

<table>
    <tr>
        <td>
            Especificações Casos de Uso
        </td>
        <td colspan="8">
            Critérios de verificação
        </td>
        <td> </td>
        <td> </td>
        <td> </td>
        <td> </td>
        <td> </td>
    </tr>
    <tr>
        <td>UC</td>
        <td>1</td>
        <td>2</td>
        <td>3</td>
        <td>4</td>
        <td>5</td>
        <td>6</td>
        <td>7</td>
        <td>8</td>
        <td>9</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>01</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>02</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>03</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>   
    <tr>
        <td>04</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>05</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>06</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>07</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>08</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>09</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>10</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>11</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>12</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>13</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>14</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>15</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>16</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>17</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>18</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>19</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>20</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>21</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>22</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>23</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>24</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>25</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>26</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>27</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>28</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>29</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>30</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>     
    <tr>
        <td>31</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>32</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>33</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr> 
    <tr>
        <td>34</td>
        <td></td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>35</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>36</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td>V</td>
        <td></td>
        <td></td>
        <td>V</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## Análise a partir de um segundo ponto de vista, feita por Matheus Blanco

Em relação às questões de orientação para verificação das especificações, concordo com todas no plano geral. Pelo fato de ter aconselhado o autor da verificação em questão em relação ao tipo de questões apresentadas, estamos alinhados sobre quais  critérios deveriam ser apresentados.

Em relação à individualidade das questões:

- Na questão 3 não consegui identificar corretamente a 'funcionalidade' no contexto de pré-condição;

- Questões 1, 2, 4, 7, 8 e 9 estou de acordo com o contexto;

- Em relação à questão 5, também estou de acordo, entretanto acredito que está muito parecida com a 6. Considerando que a questão 5 aborda o fluxo principal, o critério de saber se os objetivos foram atingidos é coerente com o contexto de especificações. Quanto à questões 6, ao contrário de perguntar se os objetivos são atingidos poderia perguntar se o fluxo alternativo é capaz de fornecer novas rotas que levariam de volta ao fluxo principal em algum momento;

- Além dessas, acredito que seria interessante uma ou duas perguntas a mais relativas à apresentação de fluxos de outras especificações, como etapas já anteriormente cumpridas.

Também estou satisfeito com os resultados das verificações das especificações da Wiki. Pelo fato de, no geral, estar de acordo com as perguntas apresentadas e após validar as verificações realizadas, encontro-me de acordo com os resultados alcançados.

Entretanto, sinto falta de pareceres em relação à concordância ou não de uma questão das especificações. Acredito que a existência de tal seria de tamanho engrandecimento e ajuda na validação e refatoração dos itens.