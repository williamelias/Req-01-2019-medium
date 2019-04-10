## Versionamento de edições
| Data           | autor                | Descrição                           |Versão|
|----------------|----------------------|-------------------------------------|------|
|  09/04/2019    | Luís Cláudio T. Lima |Adição de texto base e introspecções | 0.1  |
|  10/04/2019    | William Elias        | Adição do relato da introspecção de login v.2| 0.2|


## Definição
Introspecção é uma técnica que cosiste em entender quais propriedades o sistema deve possuir para que seja um sucesso. O engenheiro de requisitos deve imaginar o que ele gostaria, se tivesse que desempenhar uma determinada tarefa, com os equipamentos disponíveis e demais recursos.

***
## Introspecções Desenvolvidas
***
### Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação

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

***
### Relato de introspecção 2: Comportamento do usuário no ato de se logar ou se cadastrar na aplicação.

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
***
**V2.0**

**Relator: William Elias Alves**

**Usuário não cadastrado**: Usuário com acesso a área comum, no processo de criação de um novo cadastro.

i - Consegue facilmente encontrar a área de cadastro, sendo possível somente com o cadastro via integração com o Google ou Facebook;
ii - Ao realizar cadastro com sucesso, já logado, o usuário é redirecionado a uma página de escolha de seus interesses, em relação às publicações disponíveis no banco de dados .


**Usuário não logado**:  Usuário cadastrado na aplicação, no processo de logar com suas credenciais.

i - Consegue facilmente identificar a área de acesso ao login, conseguindo se conectar via integração de redes sociais (Facebook e Twitter), integração com sua conta do Google ou inserindo seu e-mail cadastrado;
ii - A disposição está a possibilidade de se manter conectado;
iii - Ao realizar um login com sucesso ser redirecionado à página principal da aplicação, essa página estará customizada com seus interesses escolhidos depois de se cadastrar na plataforma.

***

### Relato de introspecção 3: Usuário no processo de criação de uma nova _Story_

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

***

### Relato de introspecção 4: Utilização da página de Marcador

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

***

### Relato de introspecção 5: Exploraração de  Tópicos

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

***

### Relato de introspecção 6: Customização de Interesses

**Relator: Pedro Rodrigues**

* Deve ser capaz de seguir Blogs. 
* Deve gerar uma zona de conforto de conteúdos ao leitor. 
* Deve mostrar assuntos em tendência ultimamente. 
* Deve mostrar uma lista dos Blogs e escritores já seguidos pelo leitor. 
* Deve ser capaz de deixar de seguir Blogs e escritores. 
* Deve ser capaz de seguir categorias. 
* Deve ser capaz de seguir Blogs listados em categorias específicas. 
* Deve mostrar escritores sugeridos para os interesses do leitor. 



