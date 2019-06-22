## Versionamento de edições
| Data           | autor                | Descrição                           |Versão|
|----------------|----------------------|-------------------------------------|------|
|  09/04/2019    | Luís Cláudio T. Lima |Adição de texto base e introspecções | 0.1  |
|  10/04/2019    | William Elias        |Adição do relato da introspecção de login v.2| 0.2|
|  10/04/2019    | Aline Laureano       |Adição do relato da introspecção do comportamento do usuário na Página Inicial da aplicação | 0.3 |
|  10/04/2019    | Aline Laureano       |Adição do relato da introspecção da utilização da página do Marcador | 0.4 |
|  10/04/2019    | Aline Laureano       |Adição do relato da introspecção da Exploraração de tópicos | 0.5 |
|  10/04/2019    | Matheus Salles Blanco       |Adição do relato da introspecção do Usuário no processo de criação de uma nova _Story_ | 0.6 |
|  10/04/2019    | Matheus Salles Blanco       |Adição de requisitos elicitados em cada técnica | 0.7 |
|  17/06/2019    | William Elias        |Adição dos resultados| 1.0|

### Introdução

Introspecção é uma técnica que consiste em entender quais propriedades o sistema deve possuir para que ele seja um sucesso. A introspecção deve ser usada como uma forma de imaginar o caminho que um usuário ou qualquer outro stakeholder fará no sistema. O engenheiro de requisitos deve imaginar o que ele gostaria, se tivesse que desempenhar uma determinada tarefa, com os equipamentos disponíveis e demais recursos.

### Resultados 

Foram desenvolvidas introspecções com os seguintes focos:

* Comportamento do usuário na página inicial da aplicação
* Comportamento do usuário ao se logar ou cadastrar na aplicação
* Comportamento do usuário n
* Comportamento do usuário na criação de uma nova 'storie'
* Comportamento do usuário na utilização da página de marcador
* Comportamento do usuário ao explorar tópicos
* Comportamento do usuário ao customizar seus interesses

***
### Introspecções Desenvolvidas
***
#### Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação

**Relator: Gabriel Filipe**

Abaixo estão citadas funcionalidades que devam estar presentes na página inicial do Medium:

* Design intuitivo;
* Página inicial com variedade de artigos;
* Página inicial com categorias de artigos expostas;
* Ter um botão de redirecionamento à categorias como: “Culture”;
* Ter um botão de redirecionamento à categorias como: “Tech “;
* Ter um botão de redirecionamento à categorias como: “Health”;
* Ter um botão de redirecionamento à central de ajuda ao usuário;
* Ter um botão de redirecionamento à categorias como: “Self”;
* Ter um botão de redirecionamento à categorias como: “ Startups”;
* Ter um botão de redirecionamento à categorias como: “ Politics”;
* Ter um botão de redirecionamento à categorias como: “Design”;
* Ter um botão de redirecionamento à categorias como:  “Human Parts”;
* Ter um botão de redirecionamento à categorias como: “Collections”;
* Ter um botão de redirecionamento à informações técnicas (código) do software;
* Ter um botão de redirecionamento à uma página dedicada aos criadores do Medium;
* Vizualizar tempo média de leitura de cada artigo;
* Ter um botão de redirecionamento à página de vagas de trabalho disponíveis no Medium;
* Ter um botão de redirecionamento ao termo de política e privacidade;
* Ter um botão “More” para outros assuntos diversos;
* Ter um botão de redirecionamento à “OneZero” para assuntos relacionados à tendências futurísticas;
* Ter um botão “Home” para voltar à página inicial;
* Ter um campo de busca para o usuário encontrar o que deseja;
* Dar ao usuário a possibilidade de dar “Upgrade” em sua conta;
* Possibilitar que o usuário possa acessar o seu perfil;
* Possibilitar que o usuário possa receber notificações do sistema;
* Ter um botão de redirecionamento à notificações;
* Possibilitar que o usuário possa salvar artigos em sua coleção para que leia futuramente;
* Possibilitar que o usuário possa ver a data de publicação do artigo;
* Possibilitar que o usuário solicite ver artigos com temas relacionados aos artigos expostos na página principal;

######[Relato de introspecção 1 - V2.0]

**Relator(es): Aline e Gabriel**

i. **Design intuitivo:** permite ao usuário navegar pela home page conseguindo entender o significado de todas as áreas mostradas no site.

ii. **Variedade de artigos:** apresenta ao usuário o acesso a uma variedade de artigos expostos na home page com a informação do tempo médio de leitura que cada artigo leva além de mostrar a data de publicação dos artigos mais a possibilidade de permitir que o usuário veja artigos com temas relacionados aos artigos expostos na página principal.
Sistema de Categorias: permite ao usuário não logado visualizar conteúdo relacionado a um tema específico como: “Culture”, “Tech”, “Health”, “Startups”, “Politcs”, “Design”, “Human Parts” e “Collections”.

iii. **Campo de buscas:** permite ao usuário encontrar o que ele deseja.

iv. **Botões de redirecionamento -** para que o usuário seja redirecionado para páginas como: página de vagas de trabalho disponíveis no Medium, página dedicada aos autores do Medium, página do termo de política de privacidade, botão “More” para acessar artigos de mais assuntos diversos, botão “OneZero” para o acesso à assuntos com tendências futuristas, botão “Home” que redireciona o Medium para a sua Homepage;

v. **Coleção de artigos:** caso o usuário esteja logado, permite que ele salve artigos em sua coleção;

vi. **Notificações:** permite que o usuário tenha acesso às notificações do sistema e que ele possa acessar essas notificações através de um botão;

**Requisitos Elicitados**

| ID | Requisitos Elicitados desta técnica |
| ------ | ----------------------------- |
|R005|Visualizar data de publicação dos artigos|
|R006|Política de privacidade|


***
#### Relato de introspecção 2: Comportamento do usuário no ato de se logar ou se cadastrar na aplicação.

**Relator: William Elias Alves**

**Login**

* Ter um botão ou área, facilmente identificável, para o login.
* Ter a disposição o login via integração com a conta da  Google.
* Ter a disposição o login via integração com a conta do  Facebook.
* Ter a disposição o login via integração com a conta da  Twitter.
* Ter a disposição o login via integração com a conta do linkedin.
* Ter a opção de manter conectado.
* Ter os campos para login via e-mail e senha.
* Ter os campos para login via nome de usuário e senha.
* Ao realizar um login com sucesso ser redirecionado à página principal da aplicação.
ter um campo de recuperar senha.
* Ao solicitar a recuperação de senha receber e-mail com link de recuperação de senha.
Se houver inconsistência nos dados de login.

**Cadastro:**

* Ter um botão ou área, facilmente identificável para o cadastro.
* Inserir o email, nome, sobrenome, senha e telefone para o cadastro.
* A senha deverá ter no mínimo 8 caracteres alfanuméricos.
* O nome de usuário não deve ser o mesmo do nome(comum).
* Ter a confirmação de cadastro com sucesso.
* Ter a resposta visual de dados inseridos inválidos.
* Ter a resposta visual quando os dados inseridos forem repetidos, quando for feita uma busca no banco de dados
* Inserir áreas de interesses, em relação às publicações disponíveis
* Ao realizar um cadastro com sucesso, ser redirecionado à página principal já logado

######[Relato de introspecção 2 - V2.0]
<a id="introspec2"></a>

**Relator: William Elias Alves**

**Usuário não cadastrado**: Usuário com acesso a área comum, no processo de criação de um novo cadastro.

i - Consegue facilmente encontrar a área de cadastro, sendo possível somente com o cadastro via integração com o Google ou Facebook;

ii - Ao realizar cadastro com sucesso, já logado, o usuário é redirecionado a uma página de escolha de seus interesses, em relação às publicações disponíveis no banco de dados .


**Usuário não logado**:  Usuário cadastrado na aplicação, no processo de logar com suas credenciais.

i - Consegue facilmente identificar a área de acesso ao login, conseguindo se conectar via integração de redes sociais (Facebook e Twitter), integração com sua conta do Google ou inserindo seu e-mail cadastrado;

ii - A disposição está a possibilidade de se manter conectado;

iii - Ao realizar um login com sucesso ser redirecionado à página principal da aplicação, essa página estará customizada com seus interesses escolhidos depois de se cadastrar na plataforma.

***

#### Relato de introspecção 3: Usuário no processo de criação de uma nova _Story_

**Relator: Matheus Blanco**

Ao meu entender, para que o Medium possa prover uma experiência efetiva para um escritor, necessita dos seguintes requisitos.

* Design intuitivo e fácil de se usar;
* Possibilidade de diferenciar um texto por categorias;
* Possibilidade do escritor criar uma série de textos;
* Possibilidade de criar um espaço próprio, dentro do site, para publicações;
* Possibilidade de receber feedbacks de um leitor;
* Sugestões de texto que interessem o escritor, de maneira a dar mais aprendizado ao mesmo;
* Possibilidade de importar um texto de sites externos ao medium;
* Poder tornar o texto público ou privado para apenas um número definido de leitores;
* Poder enviar e compartilhar seu texto sem a necessidade de um agente terceiro para fazê-lo;
* Utilização de tecnologias de bancos de dados adequadas para guardar as informações e texto;
* Arquitetura boa o suficiente para que o site possa publicar os textos com facilidade;
* Botão acessível para a criação de uma New Story;
* Design de escrita simples e prático de se usar;
* Possibilidade de adicionar imagens, gráficos, links, código no corpo do texto, de maneira a estarem diferenciáveis e de fácil visualização;
* Poder adicionar tags na descrição de seu texto, para que o mesmo seja agrupado com outros que tratem do mesmo * assunto de maneira a facilitar sua visibilidade;
* Possibilidade de customização de link, para que a identificação do texto por leitores próximos ao escritor seja facilitada;
* Possibilidade de se realizar a revisão e visualização da prévia da história;
* Possibilidade de ajustar e escolher um horário de publicação para a história.

####[Relato de introspecção 3 - V2.0]

**Relator: Matheus Blanco**

<a id="introspec3"></a>
**Criação de New Story:** Usuário logado, com o intuito de criar uma nova história para publicar.

i - Deve clicar no ícone de perfil no canto direito de sua tela para ver as opções existentes;

ii - Consegue facilmente achar a opção de New Story;

iii - Aparece uma tela limpa com campos para se escrever título e corpo do texto. A tela é de fácil utilização;

iv - O usuário então facilmente encontra o botão verde de publicação;

v - É mostrada uma tela com uma prévia da história, um campo para se adicionar tags e um botão que permitiria que curadores recomendar a história para os leitores do publicador.

vi - O usuário encontra outro botão verde com os dizeres "Publish now", e o aperta para publicar a história.

**Requisitos Elicitados**

| ID | Requisitos Elicitados desta técnica |
| ------ | ----------------------------- |
|R010| Criar nova 'série'|
|R012| Inserir  conteúdo|
|R013|Editar série|
|R014|Deletar série|
|R021|Importar 'story'
|R022|Editar story|
|R023|Deletar story|

***

#### Relato de introspecção 4: Utilização da página de Marcador

**Relator: Guilherme**

Abaixo estão citadas, ao meu entender, funcionalidades que devam estar presentes para salvar um artigo.

####Bookmark:

* Botão visível ao longo do corpo do texto
* Ícone auto-explicativo da função
* Diferenciação clara de uma rtigo salvo e um não salvo
* Feedback de sucesso da operação
* Listagem de artigos salvos na minha conta
* Fácil recuperação de um artigo salvo
* Registro do ponto em que o artigo salvo foi fechado

####[Relato de introspecção 4 - V2.0]

**Relator(es): Aline e Guilherme**

i. **Botão de Marcador ou Bookmark:** apresenta-se como um botão com um ícone auto-explicativo que se mantém visível ao longo do corpo do texto e permite a diferenciação clara entre artigos salvos e não salvos além de apresentar um feedback de cada operação realizada com esse botão;

ii. **Listagem de artigos salvos:** para um usuário logado, apresenta uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto em que cada artigo salvo foi fechado;

**Requisitos Elicitados**

| ID | Requisitos Elicitados desta técnica |
| ------ | ----------------------------- |
|R034|Ver os artigos favoritados|
|R035|Ver os artigos curtidos|

***
#### Relato de introspecção 5: Exploraração de  Tópicos

**Relator: Luís Cláudio**

Funcionalidades que devam estar presentes na página para que o Medium possa prover um experiência efetiva na exploração da variedade de tópicos e assuntos que o mesmo possui:

* Design intuitivo;
* Página que contenha a todas as categorias de artigos do site;
* Todas 	as categorias de artigos sendo cobertas pelos títulos:
    - Arts & Entertainment
    - Industry
    - Innovation & Tech
    - Life
    - Society

####[Relato de introspecção 5 - V2.0]

<a id="introspec5"></a>

**Relator(es): Aline e Luís**

i. **Design intuitivo -** apresenta-se como uma página que permite uma fácil navegação e que contenha todas as categorias do site - classificadas em títulos como: “Arts & Entertainment”, “Industry”, “Innovation & Tech”, “Life” e “Society”.

***
#### Relato de introspecção 6: Customização de Interesses

**Relator: Pedro Rodrigues**

* Deve ser capaz de seguir Blogs.
* Deve gerar uma zona de conforto de conteúdos ao leitor.
* Deve mostrar assuntos em tendência ultimamente.
* Deve mostrar uma lista dos Blogs e escritores já seguidos pelo leitor.
* Deve ser capaz de deixar de seguir Blogs e escritores.
* Deve ser capaz de seguir categorias.
* Deve ser capaz de seguir Blogs listados em categorias específicas.
* Deve mostrar escritores sugeridos para os interesses do leitor.