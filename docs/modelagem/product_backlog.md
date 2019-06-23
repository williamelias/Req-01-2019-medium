## Versionamento de edições
| Data           | autor                | Descrição                           |Versão|
|----------------|----------------------|-------------------------------------|------|
|   07/05/2019   | William Elias Alves  | Criação da página | 1.0  |
|   07/05/2019   | Matheus Blanco  | Adição de rastro relativo aos temas | 1.1  |
|   04/06/2019   | Gabriel Filipe Manso Araujo  | Adição de rastros | 1.2  |
|   05/06/2019   | Gabriel Filipe Manso Araujo  | Validação e melhoria das definições | 1.3  |
|   16/06/2019   | William Elias Alves  | inserção do backlog do produto versão 2 | 1.4  |
|   22/06/2019   | William Elias Alves  | inserção do backlog do produto versão 3 | 1.5  |
|   22/06/2019   | William Elias Alves  | inserção dos rastros da versão 3 | 1.6  |
|   22/06/2019   | William Elias Alves  | Atualizando valores tabela v3 | 2.0  |

---

### Definição

O Product Backlog, ou Backlog do Produto, é uma lista de funcionalidades desejadas de um produto, ou seja, os requisitos que um cliente espera receber ao final do projeto, descrito com sua própria linguagem. O ponto central do Scrum é a criação do Product Backlog, é nele que o projeto começa.

Diferente do modelo tradicional de gestão de projetos, onde precisamos fechar o escopo para poder começar a executar, no Scrum acredita-se que o início do projeto não é o melhor momento para isso. Afinal nesse ponto ainda não conhecemos suficiente o projeto e precisamos avançar um pouco mais em algumas hipóteses antes de ter tanta “certeza”.

O Backlog do Produto se mostra como uma parte essencial para especificação e clareamento dos requisitos já elicitados. É bastante importante por trazer uma visão mais transparente do software assim como de suas funcionalidades. Ele é facilmente entendido pelos stakeholders e é principalmente usada juntamente com metodologias ágeis.

### Objetivo

Por meio da estruturação dos requisitos e separação dos mesmos de acordo com temas, buscamos facilitar a visualização das funcionalidades da aplicação para o cliente e os desenvolvedores envolvidos. Além de ir um pouco mais além por meio da criação de histórias de usuário e agragação de pontuação e __MoSCoW__.


### Metodologia

Para a realização da confecção do backlog do produto v.3 foi necessário a utilização da [baseline](../../baseline) de requisitos juntamento com a priorização dos requisitos.
Após a priorização dos requisitos, eles foram divididos nos seguintes temas:

* [Ajuda](#Ajuda)
* [Cadastro](#Cadastro)
* [Conexões](#Conexoes)
* [Interação](#Interacao)
* [Login](#Login)
* [Membership](#Member)
* [Partner program](#Parter)
* [Perfil](#Perfil)
* [Serie](#Serie)
* [Storie](#Storie)
* [Publicação](#Publicacao)

Após a divisão dos temas os requisitos da [baseline](../../baseline) foram agrupos de acordo com o tema pertencente. Também está atrelado a cada requisito sua pontuação com base em *story points*, sua priorização em [Moscow](../../elicitacao/priorizacao-moscow) e o seu rastro, quando existente.


### Resultados

Foram especificados os requisitos com base no mapeamento prévio utilizando o First Things First (FTF) e esses foram pontuados por meio de uma reunião realizadas com os membros da equipe. No total foram determinadas 71 funcionalidades na primeira versão, entretanto na segunda versão esse número caiu para 59 e esse número se manteve para a [terceira versão](#t3).

***

### Backlog do produto

***

####[Versão 1](backlog_versoes/backlogv1.md)


**Divisão de tarefas**

Para essa primeira versão do backlog as terefas foram divididas da seguinte maneira:

|id	|Tema	|Nº de funcionalidades	|Responsável|
|---|-----|-----------|-----------|
|1	|Stories	|8	|Aline|
|2	|Series	|4	|william|
|3	|Perfil	|4	|Aline|
|4	|Cadastro	|2	|william|
|5	|Login 	|5	|Guilherme|
|6	|configuração	|12	|Pedro|
|7	|Interações 	|11|	|Blanco|
|8	|Conexões	|3	|william|
|9	|membership	|2	|william|
|10	|Conta	|2	|Luís|
|12	|partner program	|4|	Luís| 
|13|	não funcional	|6	|aline/wlliam|
|14|	Ajuda	|4	|william|


| Rastro de Tema | Origem |
| ------- | ------- |
| Geral | [Priorização First Things First](../elicitacao/priorizacao-ftf.md) / Brainstorming |
| Configuração | [Storytelling](../elicitacao/storytelling.md) - Configurar Aplicação |
| Editar perfil | [Storyboard](../elicitacao/storyboards.md) - Editar Perfil |
| Storie | [Storytelling](../elicitacao/storytelling.md) - Escrever 'New Storie' |
| Cadastro | [Storyboard](../elicitacao/storyboards.md) - Cadastro e Login |
| Login | [Storyboard](../elicitacao/storyboards.md) - Cadastro e Login |


***

####[Versão 2](backlog_versoes/backlogv2.md)

**Divisão de tarefas**

Para essa segunda versão do backlog as terefas foram divididas entre os seguintes membros responsáveis:

- William Elias Alves
- Mathes Blanco



| Rastro de Tema | Origem |
| ------- | ------- |
| Geral | [Priorização First Things First](../elicitacao/priorizacao-ftf.md) / Brainstorming |
| Configuração | [Storytelling](../elicitacao/storytelling.md) - Configurar Aplicação |
| Editar perfil | [Storyboard](../elicitacao/storyboards.md) - Editar Perfil |
| Storie | [Storytelling](../elicitacao/storytelling.md) - Escrever 'New Storie' |
| Cadastro | [Storyboard](../elicitacao/storyboards.md) - Cadastro e Login |
| Login | [Storyboard](../elicitacao/storyboards.md) - Cadastro e Login |

***
<a id="t3"></a>
#### Versão 3

**Divisão de tarefas**

Para essa terceira versão do backlog as terefas delegadas com base nos responsáveis das análise, sendo que o seguinte membro ficou responsável pela refatoração do backlog do produto.

**Responsável**: William Elias Alves
<br>
#### Tabela de Backlog do produto
<br>

<table>
    <tr style="color:black">
        <th >
            <p>Tema</p>
        </th>
        <th >
            <p>ID</p>
        </th>
        <th >
            <p>Eu, como</p>
        </th>
        <th >
            <p>Desejo</p>
        </th>
        <th >
            <p>Para que eu possa</p>
        </th>
        <th >
            <p>Pontos</p>
        </th>
        <th >
            <p>MoSCoW</p>
        </th>
        <th >
            <p>Rastro</p>
        </th>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="3" >
            <p id="Ajuda">Ajuda</p>
        </td>
        <td >
            <p>001</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Acessar o glossário MEDIUM</p>
        </td>
        <td >
            <p>visualizar a lista de palavras-chave da aplicação </p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../user_case#areacomum">Caso de Uso Área comum</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>002</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Responder o questionário de satisfação da aplicação </p>
        </td>
        <td >
            <p>contribuir para o feedback de alguns aspectos da aplicação Medium</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p>
            <a href="../user_case#areacomum">Área comum</a>
            </p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>003</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Pesquisar por tópico de ajuda</p>
        </td>
        <td >
            <p>Encontrar com uma maior facilidade conteúdos específicos para o meu auxílio</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../user_case#areacomum">Caso de Uso Área comum</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="2" >
            <p id="Cadastro">Cadastro</p>
        </td>
        <td >
            <p id="US004">004</p>
        </td>
        <td >
            <p>Visitante</p>
        </td>
        <td >
            <p>Realizar cadastro com Google</p>
        </td>
        <td >
            <p>Me tornar um usuário via integração com uma conta existente da Google</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../user_case#areacomum">Caso de Uso Área comum</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US005">005</p>
        </td>
        <td >
            <p>Visitante</p>
        </td>
        <td >
            <p>Realizar cadastro com Facebook</p>
        </td>
        <td >
            <p>Me tornar um usuário via integração com uma conta existente do Facebook</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../user_case#areacomum">Caso de Uso Área comum</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="18" >
            <p id="Conexoes">Conexões</p>
        </td>
        <td >
            <p id="US006">006</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Conectar com redes sociais</p>
        </td>
        <td >
            <p>Realizar uma integração com o Facebook ou Twitter, adicionando uma nova forma de login</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/brainstormings#brain2">-Brainstorming2</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>007</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Conectar com Google</p>
        </td>
        <td >
            <p>Realizar uma integração com uma conta da Google, adicionando uma nova forma de login</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/brainstormings#brain2">-Brainstorming2</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>008</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>selecionar alguns tópicos de meu interesse</p>
        </td>
        <td >
            <p>gerenciar conteúdos que me serão sugeridos para leitura</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td >
            <p><a href="../../elicitacao/brainstormings#brain2">-Brainstorming2</a><br/><a href="../../elicitacao/introspeccao#introspec5">-Introspecção 5</a><br/><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US009">009</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Ativar a notificação social</p>
        </td>
        <td >
            <p>Receber ou não notificações de medias sociais</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/brainstormings#brain2">-Brainstorming2</a>;<br/><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>010</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Ativar modo noturno</p>
        </td>
        <td >
            <p> gerenciar o modo de leitura noturno</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Would</p>
        </td>
        <td >
            <p> <a href="../../elicitacao/brainstormings#brain2">-Brainstorming2</a>;<br/><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>011</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Automatizar modo noturno</p>
        </td>
        <td >
            <p>Ativar de forma automatica o modo noturno de acordo com o horário</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Would</p>
        </td>
        <td >
            <p><a href="../../elicitacao/brainstormings#brain2">-Brainstorming2</a>;<br/><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>012</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Editar email padrão</p>
        </td>
        <td >
            <p>Realizar a troca do email cadastrado</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>013</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Selecionar período de  sugestão de artigos</p>
        </td>
        <td >
            <p>gerenciar a recorrência dos artigos sugeridos</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>014</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Desativar sugestão de artigos</p>
        </td>
        <td >
            <p>gerenciar períodos de inatividade na sugestão de artigos</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>015</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Ativar boletim informativo</p>
        </td>
        <td >
            <p>Visualizar ou não o boletim informativo em meu e-mail</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>016</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Selecionar tema do boletim informativo</p>
        </td>
        <td >
            <p>receber artigos novos de acordo com o tema escolhido</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td >
            <p><a href="../../elicitacao/brainstormings#brain2">-Brainstorming2</a>;<br/><a href="../../elicitacao/introspeccao#introspec5">-Introspecção 5</a><br/><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>017</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Ativar as recomendações de stories</p>
        </td>
        <td >
            <p>receber ou não sugestões de artigos populares</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td >
            <p><a href="../../elicitacao/brainstormings#brain2">-Brainstorming2</a>;<br/><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US018">018</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Ativar as notificação por e-mail</p>
        </td>
        <td >
            <p>receber ou não mensagens em meu e-mail cadastrado</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>019</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>gerenciar a privacidade de menções</p>
        </td>
        <td >
            <p>selecionar os níveis acesso referentes à citações</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>020</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Desativar menções a mim</p>
        </td>
        <td >
            <p>gerir minhas interações com outros usuários</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>021</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Mostrar links para minhas redes sociais</p>
        </td>
        <td >
            <p>compartilhar minhas leituras</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>022</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Desativar minha conta</p>
        </td>
        <td >
            <p>inativar temporariamente minhas ações dentro da aplicação</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>023</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Deletar minha conta</p>
        </td>
        <td >
            <p>excluir definitivamente meus dados da conta do medium</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="9" >
            <p id="Interacao">Interação</p>
        </td>
        <td >
            <p id="US024">024</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Seguir escritores</p>
        </td>
        <td >
            <p>Receber notificações de suas ações</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storyboards#tutorial">-StoryBord Tutorial e seguir escritor</a></p>
            <p><a href="../../elicitacao/brainstormings#brain3">-Brainstorming 3</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US025">025</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Seguir usuários</p>
        </td>
        <td >
            <p>Receber notificações de suas ações</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storyboards#tutorial">-StoryBord Tutorial e seguir escritor</a></p>
            <p><a href="../../elicitacao/brainstormings#brain3">-Brainstorming 3</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>026</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Visualizar textos publicados de um escritor em seu perfil</p>
        </td>
        <td >
            <p>Encontrar com uma maior facilidade conteúdos específicos para o meu auxílio</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US027">027</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Visualizar perfis de outros usuários</p>
        </td>
        <td >
            <p>Ver seus históricos de leitura, ou segui-los ou ou ainda encontrar novos assuntos de interesse</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>028</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Favoritar texto </p>
        </td>
        <td >
            <p>tê-lo para leitura posterior</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US029">029</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Visualizar comentários da publicação</p>
        </td>
        <td >
            <p>Me atentar às discussões relacionadas ao artigo ou dar minha opinião em relação ao assunto</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US030">030</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Reportar publicação </p>
        </td>
        <td >
            <p>Denunciar uma publicação considerei ofensiva/Contribuir positivamente para a saúde mental da comunidade em questão</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>031</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>reportar usuário</p>
        </td>
        <td >
            <p>Parar de receber notificações do mesmo/Cortar relações com o usuário</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td ><a href="../../elicitacao/storytelling#editprofile">Storytelling editar perfil</a> </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>032</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>visualizar seguidores</p>
        </td>
        <td >
            <p>Encontrar uma pessoa à qual estou procurando, mais facilmente/Ver meu status de popularidade na plataforma</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="4" >
            <p id="Login">Login</p>
        </td>
        <td >
            <p>034</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Deslogar de outras sessões </p>
        </td>
        <td >
            <p>Impedir que terceiros tenham acesso a minha conta</p>
        </td>
        <td >
            <p>13</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#storytuconfig">-Storytelling,Usuário configurando a aplicação</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US035">035</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Realizar login via redes sociais</p>
        </td>
        <td >
            <p>Me conectar a minha conta via integração(Facebook ou twitter)</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#login">- Storytelling e storybord: login e cadastro;</a><br></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US036">036</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Realizar login via Google</p>
        </td>
        <td >
            <p>Me conectar a minha conta via integração com o Google</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/introspeccao#introspec2">-Introspecção 2</a><br/><a href="../../elicitacao/storytelling#login">- Storytelling e storybord: login e cadastro;</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US037">037</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Realizar login via E-mail</p>
        </td>
        <td >
            <p>Me conectar a minha conta usando o email institucional ou pessoal</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/introspeccao#introspec2">-Introspecção 2</a><br/><a href="../../elicitacao/storytelling#login">- Storytelling e storybord: login e cadastro;</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="2" >
            <p id ="Member">Membership</p>
        </td>
        <td >
            <p>038</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>visualizar os planos de assinatura disponíveis</p>
        </td>
        <td >
            <p>selecionar o plano mais adequado ao meu orçamento</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>039</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>visualizar as formas de pagamento existentes</p>
        </td>
        <td >
            <p>inserir uma forma de pagamento que me satisfaça</p>
        </td>
        <td >
            <p>13</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="3" >
            <p id="Parter">Partner Program</p>
        </td>
        <td >
            <p>040</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>visualizar os termos de usuário</p>
        </td>
        <td >
            <p>concordar ou não com os termos de serviço do Medium Partner Program</p>
        </td>
        <td >
            <p>2</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>041</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>selecionar minha conta como de empresa </p>
        </td>
        <td >
            <p>inserir dados de conta empresarial</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>042</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>configurar meu cartão de débito</p>
        </td>
        <td >
            <p>ter um novo método de pagamento</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>must</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="2" >
            <p id="Perfil">Perfil</p>
        </td>
        <td >
            <p id="US043">043</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>editar informações de perfil</p>
        </td>
        <td >
            <p>alterar as informações do meu perfil de acordo com o meu querer</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#editprofile">Storytelling editar perfil</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US044">044</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Visualizar próprio perfil</p>
        </td>
        <td >
            <p>Ver todas as informações do meu perfil</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/storytelling#editprofile">Storytelling editar perfil</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="4" >
            <p id="Serie">Serie</p>
        </td>
        <td >
            <p id="US045">045</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Criar uma nova Serie</p>
        </td>
        <td >
            <p>Publicar conjuntos de textos sequenciais </p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td > <a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a><br><a href="../../elicitacao/storytelling#newstory">-Storytelling new story</a></td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>046</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Editar uma Serie existente</p>
        </td>
        <td >
            <p>Modificar aspectos da mesma de acordo com o meu querer</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td ><a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a> <br><a href="../../elicitacao/storytelling#newstory">-Storytelling new story</a></td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US047">047</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Deletar uma Serie existente</p>
        </td>
        <td >
            <p>Remover, por motivos pessoais, uma serie de minha lista de rascunhos ou publicadas</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td ><a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a> <br><a href="../../elicitacao/storytelling#newstory">-Storytelling new story</a></td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>048</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Ver estatísticas de uma série</p>
        </td>
        <td >
            <p>Me manter atualizado quanto a quantidade de leituras e claps  da mesma</p>
        </td>
        <td >
            <p>2</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="8" >
            <p id="Storie">Storie</p>
        </td>
        <td >
            <p id="US049">049</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Escrever 'new storie'</p>
        </td>
        <td >
            <p>Escrever e publicar novas histórias</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td >
            <p><a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a></p>
            <p><a href="../../elicitacao/storytelling#newstory">Storytelling new story</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US050">050</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Importar 'storie'</p>
        </td>
        <td >
            <p>Aproveitar uma história já publicada em algum site para editá-la e/ou publicá-la entre as minhas histórias do Medium</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td >
            <p><a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a></p>
            <p><a href="../../elicitacao/storytelling#newstory">Storytelling new story</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>051</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Aplaudir um texto lido</p>
        </td>
        <td >
            <p>Expressar que gostei de um texto que li</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>052</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Compartilhar texto lido nas redes sociais</p>
        </td>
        <td >
            <p>Divulgar o texto lido com mais pessoas de outras redes sociais</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td >
            <p><a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>053</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Comentar no corpo do texto da 'story'</p>
        </td>
        <td >
            <p>Adicionar anotações que eu achar relevantes sobre uma storie</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td >
            <p><a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a></p>
        </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>054</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Escutar podcast</p>
        </td>
        <td >
            <p>Receber notificações para acompanhar todas as novas stories de uma Publicação </p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p id="US055">055</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Visualizar storie</p>
        </td>
        <td >
            <p>Ler um texto na íntegra e realizar outras ações posteriores relacionadas ao mesmo</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td > <a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a></td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>056</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Visualizar claps em suas publicações</p>
        </td>
        <td >
            <p>Ver o quão positiva foi a recepção de minha publicação, para que possa melhorar para a próxima</p>
        </td>
        <td >
            <p>3</p>
        </td>
        <td >
            <p>Could</p>
        </td>
        <td > <a href="../../elicitacao/introspeccao#introspec3">-Introspecção 3</a></td>
        <td  > </td>
    </tr>
    <tr >
        <td rowspan="3" >
            <p id="Publicacao">Publicação </p>
        </td>
        <td >
            <p>057</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Criar publicação</p>
        </td>
        <td >
            <p>Ter um blog dentro da aplicação Medium</p>
        </td>
        <td >
            <p>13</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>058</p>
        </td>
        <td >
            <p>Usuário Escritor</p>
        </td>
        <td >
            <p>Editar publicação </p>
        </td>
        <td >
            <p>Alterar aspectos de meu blog conforme meu querer</p>
        </td>
        <td >
            <p>8</p>
        </td>
        <td >
            <p>Must</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>059</p>
        </td>
        <td >
            <p>Usuário</p>
        </td>
        <td >
            <p>Favoritar publicação para leitura posterior</p>
        </td>
        <td >
            <p>Ter um acesso rápido e fácil meus blogs favoritos</p>
        </td>
        <td >
            <p>5</p>
        </td>
        <td >
            <p>Should</p>
        </td>
        <td > </td>
        <td  > </td>
    </tr>
    <tr >
        <td >
            <p>Total</p>
        </td>
        <td > </td>
        <td >
            <p>2</p>
        </td>
        <td > </td>
        <td > </td>
        <td >
            <p>312</p>
        </td>
        <td > </td>
        <td  > </td>
        <td  > </td>
    </tr>
</table>


| Rastro de Tema | Origem |
| ------- | ------- |
| Geral | [Priorização First Things First](../elicitacao/priorizacao-ftf.md) / Brainstorming |
| Configuração | [Storytelling](../elicitacao/storytelling.md) - Configurar Aplicação |
| Editar perfil | [Storyboard](../elicitacao/storyboards.md) - Editar Perfil |
| Storie | [Storytelling](../elicitacao/storytelling.md) - Escrever 'New Storie' |
| Cadastro | [Storyboard](../elicitacao/storyboards.md) - Cadastro e Login |
| Login | [Storyboard](../elicitacao/storyboards.md) - Cadastro e Login |