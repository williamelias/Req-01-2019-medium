## Versionamento de edições
| Data           | autor                | Descrição                           |Versão|
|----------------|----------------------|-------------------------------------|------|
|   28/04/2019   | William Elias Alves  | Criação da página | 0.1  |
|   28/04/2019   | William Elias Alves  | Inserção das especificações| 0.2  |
|   08/06/2019   | Luís Cláudio T. Lima | Correção da numeração das UC's| 0.3  |
|   21/06/2019   | Luís Cláudio T. Lima | Refatoração de especificações | 0.4  |
|   22/06/2019   | Luís Cláudio T. Lima | Refatoração de mais especificações e adição de links para as versões em cada UC | 0.5 |
|   23/06/2019   | Luís Cláudio T. Lima | Refatoranção das especificações concluída | 0.6 |




### Definição

Com o auxílio do desenvolvimento de cenários, ficou possível obter uma visão mais clara a respeito da concepção de casos de uso. Os casos de uso facilitam na obtenção de uma visão geral a respeito de dada funcionalidade de uma aplicação e poderá ser usada beneficamente por desenvolvedores, pois ela contém aspectos relevantes referentes a relacionamentos entre entidades.

<span id ="versaoAntiga"></span>
***
### Especificações
<a href="#versaoRefatorada">ir para versão final(refatorada)</a>

***

#### Área comum(william elias alves)
<span id = "UC01_antigo"></span>
**UC01-Efetuar Cadastro**

<a href="#UC01_refatorado">ver UC01 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por realizar cadastro na aplicação.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Visitante deve estar conectado à internet|
|**Pós-condições**|Visitante se tornará Usuário<br/>Usuário estará logado na aplicação <br/>Usuário terá acesso às funcionalidades da aplicação|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja realizar o cadastro na    aplicação:**<br/> 1-Visitante clica em 'Sign in' <br/>2-Visitante clica em 'create one'<br/>3-Visitante escolhe entre as opções de integração via redes sociais <br>4-Visitante escolhe tópicos de interesse <br/>5-Visitante é redirecionada a página principal da aplicação já logado|
|**Fluxo alternativo**|** [FA01] Possibilidade de integração via E-mail:**<br/>No passo 3 do fluxo   principal, há a opção de login via E-mail|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 3 há a verificação de  conexão com a internet <br>** [FE02] Erro no serviço de integração de contas**<br/>No passo 3, a integração com as redes sociais deve retornar status 200 |

***

<span id = "UC02_antigo"></span>
**UC02-Efetuar Login**

<a href="#UC02_refatorado">ver UC02 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por realizar login na aplicação.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br/>Usuário deve ter um cadastro ativo|
|**Pós-condições**|Usuário estará logado na aplicação <br/>Usuário terá acesso às funcionalidades da aplicação|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja realizar o login na    aplicação:**<br/> 1-Usuário clica em 'Sign in' <br/>2-Usuário escolhe entre as opções de integração via redes sociais <br/>3-Usuário é redirecionada a página principal da aplicação já logado|
|**Fluxo alternativo**|** [FA01] Possibilidade de integração via E-mail:**<br/>No passo 2 do fluxo   principal, há a opção de login via E-mail|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet <br>** [FE02] Erro no serviço de integração de contas**<br/>No passo 2, a integração com as redes sociais deve retornar status 200 |

***

<span id = "UC03_antigo"></span>
**UC03-Pesquisar artigo**

<a href="#UC03_refatorado">ver UC03 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por realizar pesquisa de artigos na plataforma Medium.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante receberá um artigo para leitura
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário pesquisar um artigo na  aplicação**<br/> 1-Usuário/Visitante clica no ícone da lupa<br/>2-Usuário/Visitante insere o termo a ser pesquisado <br>3-Usuário/Visitante recebe como resultado um ou mais artigos para leitura|
|**Fluxo alternativo**|** [FA01] Selecionar podcast:**<br/>No passo 3 do fluxo principal, há a opção de selecionar um podcast a ser escutado|
|**Fluxo de exceção**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet <br>** [FE02] Nenhum resultado**<br/>No passo 3, pode haver um erro de digitação ou a não existência de artigos/podcasts para o termo inserido|

***

<span id = "UC04_antigo"></span>
**UC04-Escutar podcast**

<a href="#UC04_refatorado">ver UC04 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pela possibilidade de escutar um podcast.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante receberá/terá escutado um podcast
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário seleciona um podcast a ouvir**<br> 1-Usuário/Visitante clica no podcast escolhido<br/>2-Usuário/Visitante visualiza um reprodutor de mídia<br>3-Usuário/visitante clica em reproduzir|
|**Fluxo alternativo**|** [FA01] Voltar para página principal:**<br/>No passo 2 o usuário pode retornar a página principal da aplicação para selecionar outro podcast|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet <br>** [FE02] Reprodutor com problemas**<br/>No passo 3, pode haver um erro no reprodutor usado pela plataforma|

***

<span id = "UC05_antigo"></span>
**UC05-Ler artigo**

<a href="#UC05_refatorado">ver UC05 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por possibilitar a leitura de um artigo na plataforma Medium.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante terá lido um artigo 
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário selecionar um artigo para   leitura**<br/> 1-Usuário/Visitante clica no artigo escolhido<br/>2-Usuário/Visitante visualiza a página com conteúdo do artigo|
|**Fluxo de exceção**&nbsp;|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de conexão com a internet|

***
<span id = "UC06_antigo"></span>
**UC06-Visualizar artigos populares**

<a href="#UC06_refatorado">ver UC06 refatorado</a>


|||
|---|---|
|**Descrição**| Funcionalidade responsável exibir artigos populares.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante visualizará os artigos populares na barra lateral direita da página principal da aplicação|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário acessa a área principal da  aplicação**<br/> 1-Usuário/Visitante clica no ícone do Medium<br/>2-Usuário/Visitante visualiza os artigos populares na lateral direita do site|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet|

***
<span id = "UC07_antigo"></span>
**UC07-Visualizar artigos por categoria**

<a href="#UC07_refatorado">ver UC07 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pela exibição de artigos por categoria.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante receberá uma lista de artigos para leitura, dada uma categoria
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário Acessa a página principal da aplicação**<br/>1-Usuário/Visitante clica no ícone do Medium<br/>2-Usuário/Visitante visualiza a barra de categorias na área superior do site<br>3-Usuário/Visitante escolhe uma categoria<br>4-Usuário clica na categoria desejada<br>5-Usuário visualiza um lista de artigos|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet <br>** [FE02] Nenhum resultado**<br/>No passo 5, pode ser que não exista artigos/podcasts para o termo clicado|

***
<span id = "UC08_antigo"></span>
**UC08-Acessar área de ajuda**

<a href="#UC08_refatorado">ver UC08 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por exibir a área de ajuda da plataforma Medium.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante recebera várias instruções de utilização da plataforma
|**Fluxo principal**|** [FP01] Este fluxo se inicia em qualquer página do site**<br/> 1-Usuário/Visitante clica em 'Help'<br/>2-Usuário/Visitante Seleciona o tópico de ajuda desejado <br>3-Usuário/Visitante recebe instruções sobre dado assunto|
|**Fluxo alternativo**|** [FA01] Acessar pela foto do perfil:**<br/>O passo 1 pode ser substituido por acessar a página de ajuda por meio da foto do perfil de usuário|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet|

***
<span id = "UC09_antigo"></span>
**UC09-Editar Perfil**

<a href="#UC09_refatorado">ver UC09 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por possibilitar a edição do perfil de usuário Medium.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá editado seus informações básicas|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário clica em 'profile'**<br/> 1-Usuário clica em sua foto de usuário<br/>2-Usuário clica em 'profile'<br>3-Usuário clica em edit 'profile' <br> 4-Usuário altera seu nome no campo de texto<br>5-Usuário clica em sua foto de perfil  <br>6-Usuário seleciona uma foto para o perfil de seu dispositivo<br>7-Usuário clica em 'save'|
|**Fluxo alternativo**|** [FA01] Cancelar edição:**<br/>No passo 7 do fluxo principal, há a opção de cancelar edição|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet <br>** [FE02] Erro de leitura de imagem**<br/>No passo 6, pode haver um erro de na leitura ou corrompimento da imagem 'upada'|

<span id = "UC10_antigo"></span>
**UC10-Configurar preferências**

<a href="#UC10_refatorado">ver UC10 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por exibir configurações da aplicação na plataforma web.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá configurado alguns aspectos da aplicação
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário clica na foto de seu perfil**<br/> 1-Usuário clica em sua foto de perfil<br/>2-Usuário clica em 'settings'<br>3-Usuário visualiza opções de configurações de e-mail, conexões, conta, membership e seguraça<br>4-Usuário modifica o que achar necessário|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de conexão com a internet|

<span id = "UC11_antigo"></span>
**UC11-Tornar-se membership**

<a href="#UC11_refatorado">ver UC11 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por exibir a área de membership.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet|
|**Pós-condições**|Usuário se tornará membership|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário clica em 'upgrade'**<br/> 1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br>3-Usuário seleciona o plano desejado<br>4-Usuário seleciona a forma de pagamento<br>5-Usuário clica em 'Start my membership'|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet|


#### Acesso ao Medium Membership(william elias alves)

<span id = "UC12_antigo"></span>
**UC12-Selecionar plano**

<a href="#UC12_refatorado">ver UC12 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por possibilitar a seleção de planos.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá escolhido um plano de pagamento|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar um plano**<br/> 1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br>3-Usuário seleciona o plano desejado|
|**Fluxo de exceção**&nbsp;|** [FE01] Verificação de conexão à internet**<br/>No passo 3 há a verificação de  conexão com a internet|

***
<span id = "UC13_antigo"></span>
**UC13-Selecionar $5/Mês**

<a href="#UC13_refatorado">ver UC13 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por possibilitar a seleção do plano mensal.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet|
|**Pós-condições**|Usuário terá selecionado o plano mensal|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar um plano**<br/> 1-Usuário clica na área 'plain'<br>2-Usuário clica em plano mensal|
|**Fluxo alternativo**|** [FA01] **UC14-Selecionar $50/Ano** **|


***
<span id = "UC14_antigo"></span>
**UC14-Selecionar $50/Ano**

<a href="#UC14_refatorado">ver UC14 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por possibilitar a seleção do plano anual.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet|
|**Pós-condições**|Usuário terá selecionado o plano mensal|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar um plano**<br/> 1-Usuário clica na área 'plain'<br>2-Usuário clica em plano anual|
|**Fluxo alternativo**|** [FA01] **UC13-Selecionar $5/Mês** **|

***
<span id = "UC15_antigo"></span>
**UC15-Selecionar Método de pagamento**

<a href="#UC15_refatorado">ver UC15 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por possibilitar a seleção do método de pagamento.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet|
|**Pós-condições**|Usuário terá selecionado o método de pagamento|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar um método de pagamento**<br/> 1-Usuário clica na área 'payment'<br>2-Usuário clica em 'credit card'|
|**Fluxo alternativo**|** [FA01] **UC16-Pagar via PayPal**|

***
<span id = "UC16_antigo"></span>
**UC16-Pagar via PayPal**

<a href="#UC16_refatorado">ver UC16 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por possibilitar a seleção do método de pagamento como PayPal.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet|
|**Pós-condições**|Usuário terá selecionado o método de pagamento|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar o método de pagamento como Paypal**<br/>1-Usuário clica em 'payments' <br/>2-Usuário clica em PayPal<br>3-Usuário visualiza um modal de inserção de dados do PayPal<br>4-Usuário insere seus dados de login no PayPal|
|**Fluxo alternativo**|** [FA01] **UC17-Pagar via cartão de crédito**|
|**Fluxo de exceção**|** [FE01] Dados PaylPal inválidos**<br/>No passo 4 pode haver inconsistência nos dados inseridos o que impossibilita a execução dos próximos passos|

***
<span id = "UC17_antigo"></span>
**UC17-Pagar via cartão de crédito**

<a href="#UC17_refatorado">ver UC17 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável disponibilizar o método de pagamento como Cartão de crédito.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet|
|**Pós-condições**|Usuário terá escolhido o método de pagamento como cartão de crédito|
|**Fluxo principal**|** [FP01]O fluxo se inicia quando o usuário deseja selecionar o método de pagamento como Cartão de crédito**<br/>1-Usuário insere o número do cartão<br>2-Usuário insere a data de expiração do cartão<br>3-Usuário insere o código de segurança do cartão||
|**Fluxo alternativo**|** [FA01] UC16-Pagar via PayPal**|
|**Fluxo de exceção**&nbsp;&nbsp;&nbsp;&nbsp;|** [FE01] Dados do cartão de crédito inválidos**<br/>No passo 1,2 e 3 pode haver inconsistência nos dados inseridos o que impossibilita a execução dos próximos passos|

***

<span id = "UC18_antigo"></span>
**UC18-Acessar área de membro vip**

<a href="#UC18_refatorado">ver UC18 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável disponibilizar o método de pagamento como Cartão de crédito.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet|
|**Pós-condições**|Usuário visualizará a área de membership|
|**Fluxo principal**&nbsp;&nbsp;|** [FP01]O fluxo se inicia quando o usuário deseja acessar a área de membership**<br/>1-Usuário clica em 'access'|

***
#### Series (Matheus Blanco)

**Versão 1.0**

![Especificação Serie](../images/esp2_001.png)
![Especificação Serie](../images/esp2_002.png)

**Versão 2.0**

<span id = "UC19_antigo"></span>
**UC19-Acessar menu lateral**

<a href="#UC19_refatorado">ver UC19 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por disponibilizar um DropDown de opções para o usuário.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar logado|
|**Pós-condições**|Usuário visualizará as opções |
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja acessar o menu lateral**<br/>1-Usuário clica no ícone de perfil|

***
<span id = "UC20_antigo"></span>
**UC20-Visualizar Series**

<a href="#UC20_refatorado">ver UC20 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por disponibilizar uma página que mostra as series criadas como rascunho ou publicadas.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve possuir rascunhos e/ou series publicados|
|**Pós-condições**|Usuário poderá criar series, publicar rascunhos ou visualizar os publicados |
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário acessa a página de Series**<br/>1-Usuário clica no botão series no menu lateral; <br/>2-Usuário visualiza rascunhos criados.|
|**Fluxo alternativo**&nbsp;&nbsp;|**[FA01] UC22 - Visualizar published**; <br/>**[FA02] UC23 - Criar series**|

***
<span id = "UC21_antigo"></span>
**UC21-Visualizar Drafts**

<a href="#UC21_refatorado">ver UC21 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário acesse e reveja os rascunhos de series criados anteriormente.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve ter acessado a página de series e ter rascunhos salvos|
|**Pós-condições**|Usuário visualizará as opções |
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja abrir as series rascunhadas**<br/>1-Usuário seleciona uma serie criada <br/>2-Usuário lê a serie criada|
|**Fluxo alternativo**|**[FA01] UC26 - Editar rascunho**|

***
**UC22-Visualizar Published**

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário acesse e reveja as series publicadas anteriormente.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve ter acessado a página de series e series publicadas|
|**Pós-condições**|Usuário visualizará as opções de series publicadas |
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja abrir as series publicadas**<br/>1-Usuário seleciona uma serie publicada <br/>2-Usuário lê a serie criada|

***
<span id = "UC23_antigo"></span>
**UC23 - Criar Serie**

<a href="#UC23_refatorado">ver UC23 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário crie uma nova serie.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve ter acessado a página de series|
|**Pós-condições**|Usuário poderá rascunhar e publicar a história criada |
|**Fluxo principal**|** [FP01] O fluxo se inicia quando o usuário deseja criar uma nova serie**<br/>1-Usuário aperta o botão de Create Series**<br/>2-Usuário cria a serie, incluindo texto, imagens|
|**Fluxo alternativo**|**[FA01] UC25 - Publicar serie**<br/>**[FA02] UC24 - Enviar prévia para app de celular**|

***
<span id = "UC24_antigo"></span>
**UC24 - Enviar prévia para app de celular**

<a href="#UC24_refatorado">ver UC24 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário envie a prévia do rascunho para ser visualizada no aplicativo de celular.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve ter criado e salvo o rascunho de uma serie|
|**Pós-condições**|Usuário poderá visualizar a serie no celular|
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja mandar a serie para o aplicativo de celular**<br/>1-Usuário aperta o botão de Send preview to phone<br/>2-Usuário visualiza serie no celular|

***
<span id = "UC25_antigo"></span>
**UC25-Publicar Serie**

<a href="#UC25_refatorado">ver UC25 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário publique sua serie.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve ter criado e salvo o rascunho de uma serie|
|**Pós-condições**|Usuário poderá visualizar a serie publicada|
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja publicar a serie para que outros usuários a vejam**<br/>1-Usuário aperta o botão de publicar<br/>2-Usuário visualiza a serie publicada no computador|

***
<span id = "UC26_antigo"></span>
**UC26-Editar rascunho**

<a href="#UC26_refatorado">ver UC26 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário faça edições no rascunho criado.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve ter criado e salvo o rascunho de uma serie|
|**Pós-condições**|Usuário poderá melhorar o rascunho e posteriormente, publicá-lo|
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja editar o rascunho criado**<br/>1-Usuário visualiza a página com os rascunhos<br/>2-Usuário seleciona um rascunho a ser editado<br/>3-Usuário edita o rascunho<br/>4-Usuário pode sair da página recente para salvar o rascunho recém editado.|

***
#### UC Stories (Aline Laureano)

**UC27 - Acessar menu lateral do usuário**

|||
|---|---|
|**Descrição**| Funcionalidade responsável por mostrar todas as ações que somente um usuário com login efetuado pode fazer.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário visualizará as funcionalidades disponíveis para um usuário com o login efetuado.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja visualizar as funcionalidades disponíveis para um usuário com o login efetuado:**<br/> 1-Usuário clica na sua foto de perfil localizida no superior esquerdo da página. <br/>2-É mostrado ao usuário logado um menu lateral com as funcionalidades disponíveis para ele. <br/>|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***
<span id = "UC28_antigo"></span>
**UC28-Visualizar Stories**

<a href="#UC28_refatorado">ver UC28 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por mostrar uma aŕea com todos os rascunhos e publicações de stories de um usuário.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário visualizará a área de Stories.|
|**Fluxo principal**|** [FP01]O fluxo se inicia quando o usuário deseja visualizar a área com todas as suas publicações e rascunhos:**<br/>1-[UC27] Acessar menu lateral do usuário.<br>2-Usuário clica na opção "Stories". <br>3-O usuário visualizará a área de Stories.||
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***
<span id = "UC29_antigo"></span>
**UC29-Visualizar Drafts**

<a href="#UC29_refatorado">ver UC29 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por mostrar todos os Drafts de um usuário.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário visualizará os seus Drafts.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja visualizar a área com todos os Drafts feitos por ele:**<br/> 1-[US02] Usuário visualiza a área de Stories. <br/>2-O sistema retorna para a visualização do usuário todos os Drafts feitos pelo usuário. |
|**Fluxo alternativo**|[FA01] UC30-Visualizar Publicações.<br> [FA02] UC31- Importar uma Story.<br> [FA03] UC32-Escrever uma nova Story.<br>|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***

**UC30-Visualizar Publicações**

|||
|---|---|
|**Descrição**| Funcionalidade responsável por mostrar todos as Publicações de um usuário.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário visualizará as suas Publicações.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja visualizar a área com todos as publicações feitas por ele:**<br/> 1-[US02] Usuário visualiza a área de Stories. <br/>2-O usuário clica sobre a opção "Publishes" localizada ao lado da opção "Drafts". <br/>3-O sistema retorna para a visualização do usuário todos as publicações feitas pelo usuário. |
|**Fluxo alternativo**|[FA01] UC29-Visualizar Drafts.<br> [FA02] UC31- Importar uma Story.<br> [FA03] UC32-Escrever uma nova Story.<br>|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***
<span id = "UC31_antigo"></span>
**UC31-Importar uma Story.**

<a href="#UC31_refatorado">ver UC31 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário publique uma story já publicada em qualquer outro site.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário publicará uma story já publicada em qualquer outro site.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja publicar uma story já existente em qualquer outro site:**<br/> 1-[US02] Usuário visualiza a área de Stories. <br/>2-O usuário clica sobre a opção "Import a story" localizada ao lado da opção "Write a story". <br/>3-O sistema solicita o link da story que o usuário quer publicar. <br>4-O usuário insere o link e clica no botão "import". <br>5-O usuário edita a story importada. <br> 6-O usuário clica na opção "Ready to publish?". <br>7-O sistema redireciona o usuário para uma página com a prévia da publicação importada. <br>8-O usuário clica na opção "Publish now". <br>9-O sistema retorna uma mensagem de publicação realizada com sucesso.|
|**Fluxo alternativo**|[FA01] UC29-Visualizar Drafts.<br> [FA02] UC30-Visualizar publicações.<br> [FA03] UC32-Escrever uma nova Story.<br>|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***
<span id = "UC32_antigo"></span>
**UC32-Escrever uma nova Story.**

<a href="#UC32_refatorado">ver UC32 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário crie uma nova story.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá a sua nova story publicada.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja publicar uma nova story:**<br/> 1-[US02] Usuário visualiza a área de Stories. <br/>2-O usuário clica sobre a opção "Write a story" localizada ao lado da opção "Import a story". <br/>3-O sistema redireciona o usuário para uma página de criação da nova story. <br>4-O usuário insere o conteúdo da nova story e clica no botão "Ready to publish?".<br>5-O sistema redireciona o usuário para uma página com a prévia da nova publicação. <br>6-O usuário clica na opção "Publish now". <br>7-O sistema retorna uma mensagem de publicação realizada com sucesso.|
|**Fluxo alternativo**|[FA01] UC29-Visualizar Drafts.<br> [FA02] UC30-Visualizar publicações.<br> [FA03] UC31-Importar uma Story.<br>|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***
<span id = "UC33_antigo"></span>
**UC33-Editar Drafts**

<a href="#UC33_refatorado">ver UC33 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário edite um draft.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá o seu draft editado.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja editar um draft:**<br/> 1-[US02] Usuário visualiza a área de Stories. <br/>2-O usuário clica sobre uma seta apontada para baixo localizada ao lado da descrição do draft que ele quer editar. <br/>3-O usuário clica na opção "Edit draft" localizada em baixo da seta. <br/>4-O sistema redireciona o usuário para uma página de edição do draft. <br>5-O usuário insere as alterações no conteúdo do draft e sai da página de edição sem salvar o rascunho.<br>6-O sistema irá salvar as edições feitas no rascunho.|
|**Fluxo alternativo**|[FA01] UC34-Excluir Draft.|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***
<span id = "UC34_antigo"></span>
**UC34-Excluir Draft**

<a href="#UC34_refatorado">ver UC34 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário exclua um draft.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá o seu draft excluído.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja excluir um draft:**<br/> 1-[US02] Usuário visualiza a área de Stories. <br/>2-O usuário clica sobre uma seta apontada para baixo localizada ao lado da descrição do draft que ele quer excluir. <br>3-O usuário clica na opção "Delete draft" localizada em baixo da seta. <br/>4-O sistema redireciona o usuário para uma página para confirmar a exclusão do draft. <br>5-O usuário clica sobre o botão "Delete".<br>5-O sistema sistema redireciona o usuário para a página de visualização de drafts sem o draft excluído.|
|**Fluxo alternativo**|[FA01] UC33-s.|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***
<span id = "UC35_antigo"></span>
**UC35-Editar Publicação**

<a href="#UC35_refatorado">ver UC35 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário edite uma publicação.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá a sua publicação editada.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja editar uma publicação:**<br/> 1-[US04] Usuário visualiza a área de Publicações. <br/>2-O usuário clica sobre uma seta apontada para baixo localizada ao lado da descrição da publicação que ele quer editar. <br/>3-O usuário clica na opção "Edit story" localizada em baixo da seta. <br/>4-O sistema redireciona o usuário para uma página de edição da story. <br>5-O usuário insere as alterações no conteúdo da story e clica no botão "Save and publish".<br>6-O sistema redireciona o usuário para a página da story com as alterações feitas.|
|**Fluxo alternativo**|[FA01] UC36-Excluir Publicação.|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

***
<span id = "UC36_antigo"></span>
**UC36-Excluir Publicação**

<a href="#UC36_refatorado">ver UC36 refatorado</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário exclua uma publicação.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá a sua publicação excluída.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja excluir uma story:**<br/>  1-[US04] Usuário visualiza a área de Publicações.  <br/>2-O usuário clica sobre uma seta apontada para baixo localizada ao lado da descrição da publicação que ele quer excluir. <br>3-O usuário clica na opção "Delete story" localizada em baixo da seta. <br/>4-O sistema redireciona o usuário para uma página para confirmar a exclusão da story. <br>5-O usuário clica sobre o botão "Delete".<br>5-O sistema sistema redireciona o usuário para a página de visualização de publicações sem a story excluída.|
|**Fluxo alternativo**|[FA01] UC35-Editar Publicação.|
|**Fluxo de exceção**|** [FE01] Verificação de conexão à internet**|

<span id = "versaoRefatorada"></span>
***
#Especificações(versão final)
**Responsável: Luís Cláudio T. Lima**

<a href="#versaoAntiga">voltar à versão antiga</a>

***

#### Área comum(william elias alves)

<span id = "UC01_refatorado"></span>
**UC01-Efetuar Cadastro**

<a href="#UC01_antigo">voltar ao UC01 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por realizar cadastro na aplicação.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Visitante deve estar conectado à internet|
|**Pós-condições**|Visitante se tornará Usuário<br/>Usuário estará logado na aplicação <br/>Usuário terá acesso às funcionalidades da aplicação|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja realizar o cadastro na aplicação:**<br/> 1-Visitante clica em 'Get started' <br/>2-Visitante escolhe entre as opções de integração via redes sociais <br>3-Visitante escolhe tópicos de interesse <br/>4-Visitante é redirecionado a página principal da aplicação já logado|
|**Fluxo alternativo**|** [FA01] Possibilidade de cadastro clicando em "Sign in"**<br/> 1-Visitante clica em 'Sign in' <br/> 2-Visitante clica em 'create one' e segue a partir do passo 2 do [FP01]
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 3 ocorre um erro de conexão com a internet <br>** [FE02] Erro no serviço de integração de contas**<br/>No passo 3, a integração com as redes sociais deve retornar status 200 |

***

<span id = "UC02_refatorado"></span>
**UC02-Efetuar Login**

<a href="#UC02_antigo">voltar ao UC02 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por realizar login na aplicação.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br/>Usuário deve ter um cadastro ativo|
|**Pós-condições**|Usuário estará logado na aplicação <br/>Usuário terá acesso às funcionalidades da aplicação|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja realizar o login na    aplicação:**<br/> 1-Usuário clica em 'Sign in' <br/>2-Usuário escolhe entre as opções de integração via redes sociais <br/>3-Usuário é redirecionada a página principal da aplicação já logado|
|**Fluxo alternativo**|** [FA01] Possibilidade de integração via E-mail:**<br/>No passo 2 do fluxo   principal, há a opção de login via E-mail|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet <br>** [FE02] Erro no serviço de integração de contas**<br/>No passo 2, a integração com as redes sociais deve retornar status 200 |

***

<span id = "UC03_refatorado"></span>
**UC03-Pesquisar artigo**

<a href="#UC03_antigo">voltar ao UC03 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por realizar pesquisa de artigos na plataforma Medium.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante terá visualizado o(s) resultado(s) de sua pesquisa
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja pesquisar um artigo na  aplicação**<br/> 1-Usuário/Visitante clica no ícone da lupa<br/>2-Usuário/Visitante insere o termo a ser pesquisado <br>3-Usuário/Visitante visualiza o(s) resultado(s) de sua pesquisa.|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro  de  conexão com a internet|


***

<span id = "UC04_refatorado"></span>
**UC04-Escutar podcast**

<a href="#UC04_antigo">voltar ao UC04 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir escutar um podcast.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante receberá/terá escutado um podcast
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário seleciona um podcast a ouvir**<br> 1-Usuário/Visitante clica no podcast escolhido<br/>2-Usuário/Visitante visualiza um reprodutor de mídia<br>3-Usuário/visitante clica em reproduzir<br>4-Usuário/visitante escuta o podcast|
|**Fluxo alternativo**|** [FA01] Voltar para página principal:**<br/>No passo 2 o usuário pode retornar a página principal da aplicação para selecionar outro podcast|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet** <br/>[FE02] Reprodutor com problemas**<br/>No passo 3, pode haver um erro no reprodutor usado pela plataforma|

***

<span id = "UC05_refatorado"></span>
**UC05-Ler artigo**

<a href="#UC05_antigo">voltar ao UC05 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir a leitura de um artigo na plataforma Medium.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante terá lido um artigo 
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário selecionar um artigo para leitura**<br/> 1-Usuário/Visitante clica no artigo escolhido<br/>2-Usuário/Visitante visualiza a página com conteúdo do artigo|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC06_refatorado"></span>
**UC06-Visualizar artigos populares**

<a href="#UC06_antigo">voltar ao UC06 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável exibir artigos populares.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante visualizará os artigos populares na barra lateral direita da página principal da aplicação|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário acessa a área principal da  aplicação**<br/> 1-Usuário/Visitante clica no ícone do Medium<br/>2-Usuário/Visitante visualiza os artigos populares na lateral direita do site|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC07_refatorado"></span>
**UC07-Visualizar artigos por categoria**

<a href="#UC07_antigo">voltar ao UC07 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pela exibição de artigos por categoria.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante receberá uma lista de artigos para leitura, dada uma categoria
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário Acessa a página principal da aplicação**<br/>1-Usuário/Visitante clica no ícone do Medium<br/>2-Usuário/Visitante visualiza a barra de categorias na área superior do site<br>3-Usuário/Visitante escolhe uma categoria<br>4-Usuário clica na categoria desejada<br>5-Usuário visualiza um lista de artigos|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet <br>** [FE02] Nenhum resultado**<br/>No passo 5, pode ser que não exista artigos para o termo clicado|

***
<span id = "UC08_refatorado"></span>
**UC08-Acessar área de ajuda**

<a href="#UC08_antigo">voltar ao UC08 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por exibir a área de ajuda da plataforma Medium.|
|**Atores**|Visitante e Usuário|
|**Pré-condições**|Usuário/Visitante deve estar conectado à internet|
|**Pós-condições**|Usuário/Visitante recebera várias instruções de utilização da plataforma
|**Fluxo principal**|** [FP01] Este fluxo se inicia em qualquer página do site**<br/> 1-Usuário/Visitante clica em 'Help'<br/>2-Usuário/Visitante Seleciona o tópico de ajuda desejado <br>3-Usuário/Visitante recebe instruções sobre dado assunto|
|**Fluxo alternativo**|** [FA01] Acessar pela foto do perfil:**<br/>O passo 1 pode ser substituido por acessar a página de ajuda por meio da foto do perfil de usuário|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC09_refatorado"></span>
**UC09-Editar Perfil**

<a href="#UC09_antigo">voltar ao UC09 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pela edição de perfil do usuário Medium.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá editado suas informações básicas|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário clica em 'profile'**<br/> 1-Usuário clica em sua foto de usuário<br/>2-Usuário clica em 'profile'<br>3-Usuário clica em edit 'profile' <br> 4-Usuário altera seu nome no campo de texto<br>5-Usuário clica em sua foto de perfil  <br>6-Usuário seleciona uma foto para o perfil de seu dispositivo<br>7-Usuário clica em 'save'|
|**Fluxo de exceção** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|** [FE01] Verificação de conexão à internet**<br/>No passo 2 há a verificação de  conexão com a internet <br>** [FE02] Erro de leitura de imagem**<br/>No passo 6, pode haver um erro de leitura ou corrompimento do imagem 'upada' <br>** [FE03] Cancelamento de edição**<br>No passo 7 do fluxo principal, o usuário seleciona a opção cancelar impedindo a edição de perfil|

<span id = "UC10_refatorado"></span>
**UC10-Configurar preferências**

<a href="#UC10_antigo">voltar ao UC10 antigo</a>

|||
|---|---|
|**Descrição**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| Funcionalidade responsável pelas configurações de usuário e de preferências da aplicação na plataforma web.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá configurado aspectos da aplicação de acordo com sua preferência
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário clica na foto de seu perfil**<br/> 1-Usuário clica em sua foto de perfil<br/>2-Usuário clica em 'settings'<br>3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança<br>4-Usuário modifica o que achar necessário |
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

<span id = "UC11_refatorado"></span>
**UC11-Tornar-se membership**

<a href="#UC11_antigo">voltar ao UC11 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por tornar o usuário membership.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário se tornará membership|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário clica em 'upgrade'**<br/> 1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br>3-Usuário seleciona o plano desejado<br>4-Usuário seleciona a forma de pagamento<br>5-Usuário clica em 'Start my membership'|
|**Fluxo alternativo**|** [FA01] Este fluxo se inicia quando o usuário clica no ícone de perfil**<br/> 1-Usuário clica no ícone de perfil<br/>2-Usuário clica em 'Become a member'<br>3-Usuário segue a partir do passo 3 do [FP01]
|**Fluxo de exceção**&nbsp;&nbsp;|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|  


#### Acesso ao Medium Membership(william elias alves)

<span id = "UC12_refatorado"></span>
**UC12-Selecionar plano**

<a href="#UC12_antigo">voltar ao UC12 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pela seleção de planos de pagamento.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá escolhido um plano de pagamento|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar um plano**<br/> 1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br>3-Usuário seleciona o plano desejado|
|**Fluxo alternativo**|** [FA01] Este fluxo se inicia quando o usuário clica no ícone de perfil**<br/> 1-Usuário clica no ícone de perfil<br/>2-Usuário clica em 'Become a member'<br>3-Usuário seleciona o plano desejado
|**Fluxo de exceção**&nbsp;|** [FE01] Falha de conexão à internet**<br/>No passo 3 ocorre um erro de conexão com a internet|

***
<span id = "UC13_refatorado"></span>
**UC13-Selecionar $5/Mês**

<a href="#UC13_antigo">voltar ao UC13 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pela escolha do plano mensal.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá selecionado o plano mensal|
|**Fluxo principal**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar o plano mensal**<br/>1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br/> 3-Usuário vai na área 'PLAN' e seleciona "$5/month"|


***
<span id = "UC14_refatorado"></span>
**UC14-Selecionar $50/Ano**

<a href="#UC14_antigo">voltar ao UC14 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pela escolha do plano anual.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá selecionado o plano anual|
|**Fluxo principal**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar o plano anual**<br/>1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br/> 3-Usuário vai na área 'PLAN' e seleciona "$50/year (save $10)"|

***
<span id = "UC15_refatorado"></span>
**UC15-Selecionar Método de pagamento**

<a href="#UC15_antigo">voltar ao UC15 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pela escolha do método de pagamento.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá selecionado o método de pagamento|
|**Fluxo principal**&nbsp;&nbsp;&nbsp;|** [FP01] Este fluxo se inicia quando o usuário deseja selecionar um método de pagamento**<br/>1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br/> 3-Usuário vai na área 'PAYMENT' e seleciona o método de pagamento desejado|

***
<span id = "UC16_refatorado"></span>
**UC16-Pagar via PayPal**

<a href="#UC16_antigo">voltar ao UC16 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir o pagamento via PayPal.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá realizado o pagamento via PayPal|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja realizar o pagamento por meio do Paypal**<br/>1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br/> 3-Usuário vai na área 'PAYMENT' e clica em 'PayPal'<br>4-Usuário clica em 'PayPal Finalisar' e visualiza um modal de inserção de dados do PayPal<br>5-Usuário insere seus dados de login no PayPal<br>6-Usuário finaliza o pagamento|
|**Fluxo de exceção**|** [FE01] Dados PaylPal inválidos**<br/>No passo 5 pode haver inconsistência nos dados inseridos o que impossibilita a execução dos próximos passos|

***
<span id = "UC17_refatorado"></span>
**UC17-Pagar via cartão de crédito**

<a href="#UC17_antigo">voltar ao UC17 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir o pagamento via cartão de crédito.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá realizado o pagamento com cartão de crédito|
|**Fluxo principal**|** [FP01]O fluxo se inicia quando o usuário deseja realizar o pagamento por meio do cartão de crédito**<br/>1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br/> 3-Usuário vai na área 'PAYMENT' e clica em 'Credit card'<br>4-Usuário insere os dados de seu cartão de crédito<br>5-Usuário finaliza o pagamento| 
|**Fluxo de exceção**&nbsp;&nbsp;|** [FE01] Dados do cartão de crédito inválidos**<br/>No passo 4 pode haver inconsistência nos dados inseridos o que impossibilita a execução dos próximos passos|

***

<span id = "UC18_refatorado"></span>
**UC18-Acessar área de membro vip**

<a href="#UC18_antigo">voltar ao UC18 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável pelo acesso da área de membro vip.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário acessa a área de membership|
|**Fluxo principal**|** [FP01]O fluxo se inicia quando o usuário deseja acessar a área de membership**<br/>1-Usuário clica no ícone de 'upgrade'<br/>2-Usuário clica em 'get start'<br/> 3-Usuário seleciona os planos e insere seus dados no método de pagamento escolhido<br>4-Usuário clica em 'Start my membership'<br>5-Usuário tem acesso a área de membro vip|

***

#### Series (Matheus Blanco)

<span id = "UC19_refatorado"></span>
**UC19-Acessar menu lateral**

<a href="#UC19_antigo">voltar ao UC19 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por disponibilizar um DropDown de opções para o usuário.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar logado|
|**Pós-condições**|Usuário visualizará as opções |
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja acessar o menu lateral**<br/>1-Usuário clica no ícone de perfil|

***
<span id = "UC20_refatorado"></span>
**UC20-Visualizar Series Publicadas**

<a href="#UC20_antigo">voltar ao UC20 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por disponibilizar uma página que mostra as series publicadas do usuário.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado<br>Usuário deve possuir séries já publicadas|
|**Pós-condições**|Usuário terá visualizado suas séries já publicadas |
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja visualizar suas series criadas**<br/> 1-Usuário clica no ícone de perfil<br/>2-Usuário clica no botão series no menu lateral;<br/> 3-Usuário clica em 'Published' e visualiza uma lista de todas suas series publicadas|

***
<span id = "UC21_refatorado"></span>
**UC21-Visualizar Drafts de Series**

<a href="#UC21_antigo">voltar ao UC21 antigo</a>

|||
|---|---|
|**Descrição**|Funcionalidade responsável por permitir que o usuário acesse e reveja os rascunhos de series criados anteriormente.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado<br>Usuário deve possuir séries criadas como rascunho|
|**Pós-condições**|Usuário terá visualizado seus rascunhos de series|
|**Fluxo principal**&nbsp;&nbsp;&nbsp;|**[FP01] O fluxo se inicia quando o usuário deseja visualizar as series rascunhadas**<br/> 1-Usuário clica no ícone de perfil<br/>2-Usuário clica no botão series no menu lateral;<br/>3-Usuário clica em 'Drafts' e visualiza uma lista de todas as suas series rascunhadas|

***

<span id = "UC23_refatorado"></span>
**UC23 - Criar Serie**

<a href="#UC23_antigo">voltar ao UC23 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário crie uma nova serie.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá criado uma serie|
|**Fluxo principal**&nbsp;&nbsp;&nbsp;|** [FP01] O fluxo se inicia quando o usuário deseja criar uma nova serie** <br/> 1-Usuário clica no ícone de perfil<br/>2-Usuário clica no botão series no menu lateral;<br/> 3-Usuário aperta o botão Create series<br/>4-Usuário inclui textos e imagens na paginas<br/>5-Usuário clica em 'Publish' criando e publicando a serie|

***
<span id = "UC24_refatorado"></span>
**UC24 - Enviar prévia para app de celular**

<a href="#UC24_antigo">voltar ao UC24 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário envie a prévia do rascunho para ser visualizada no aplicativo de celular.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado|
|**Pós-condições**|Usuário terá enviado uma prévia de serie para o celular|
|**Fluxo principal**|**[FP01] O fluxo se inicia quando o usuário deseja mandar uma prévia de serie para o aplicativo de celular**<br/> 1-Usuário clica no ícone de perfil<br/>2-Usuário clica no botão series no menu lateral;<br/> 3-Usuário aperta o botão Create series<br/>4-Usuário inclui textos e imagens na pagina<br/>5-Usuário aperta o botão 'Send preview to phone' enviando uma previa para o app de celular|

***
<span id = "UC25_refatorado"></span>
**UC25-Publicar Serie**

<a href="#UC25_antigo">voltar ao UC25 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário publique sua serie.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado<br>O usuário deve ter rascunho(s) de serie(s) salva(s) no Medium|
|**Pós-condições**|Usuário terá publicado uma serie no Medium|
|**Fluxo principal**|** [FP01] O fluxo se inicia quando o usuário deseja publicar uma serie para que outros usuários a vejam**<br/> 1- [FP01] UC26 - Editar Draft de Series<br/>2-Usuário clica em 'Publish'|
|**Fluxo alternativo**|** [FA01] O fluxo se inicia quando o usuário deseja publicar uma serie mas ainda não possui rascunhos da mesma**<br/> [FP01] UC23 - Criar Serie|

***
<span id = "UC26_refatorado"></span>
**UC26-Editar Draft de Series**

<a href="#UC26_antigo">voltar ao UC26 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário faça edições nas series criadas como rascunho.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet<br>Usuário deve estar logado<br>Usuário deve ter criado e salvo o rascunho de uma serie|
|**Pós-condições**|Usuário terá editado um rascunho de serie criado anteriormente|
|**Fluxo principal**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|** [FP01] O fluxo se inicia quando o usuário deseja editar um rascunho já criado **<br/> 1-Usuário clica no ícone de perfil<br/>2-Usuário clica no botão series no menu lateral;<br/>3-Usuário clica em 'Drafts' e visualiza seus rascunhos<br/>4-Usuário clica na seta para baixo no canto direito do rascunho que deseja editar<br/>5-Usuário clica em 'Edit draft' podendo editar seu rascunho, que é salvo automaticamente|

***
#### UC Stories (Aline Laureano)

***
<span id = "UC28_refatorado"></span>
**UC28-Visualizar Stories Publicados**

<a href="#UC28_antigo">voltar ao UC28 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por disponibilizar uma página que mostra os stories publicados do usuário.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá visualizado seus stories publicados.|
|**Fluxo principal**|** [FP01]O fluxo se inicia quando o usuário deseja visualizar a área com todas os seus stories publicados **<br/>1-Usuário clica no ícone de perfil.<br>2-Usuário clica na opção "Stories" no menu lateral. <br>3-Usuário clica em 'Published' e visualiza uma lista de todos seus stories publicados|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**|<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC29_refatorado"></span>
**UC29-Visualizar Drafts de Stories**

<a href="#UC29_antigo">voltar ao UC29 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário acesse e reveja os rascunhos de stories criados anteriormente.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá visualizado seus rascunhos de stories|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja visualizar a área com todos os seus rascunhos de stories salvos:**<br/> 1-Usuário clica no ícone de perfil. <br/>2-Usuário clica no botão "Stories" no menu lateral. <br/>3-Usuário clica em 'Drafts' e visualiza uma lista de todos seus rascunhos de stories|
|**Fluxo de exceção**&nbsp;|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC31_refatorado"></span>
**UC31-Importar uma Story.**

<a href="#UC31_antigo">voltar ao UC31 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário publique uma story já publicada em qualquer outro site.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário publicará uma story já publicada em qualquer outro site.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja publicar uma story já existente em qualquer outro site:**<br/> 1-Usuário clica no ícone de perfil. <br/>2-Usuário clica no botão "Stories" no menu lateral.<br/>3-O usuário clica sobre a opção "Import a story" localizada ao lado da opção "Write a story". <br/>4-O sistema solicita o link da story que o usuário quer publicar. <br>5-O usuário insere o link e clica no botão "import". <br>6-O usuário edita a story importada. <br> 7-O usuário clica na opção "Ready to publish?". <br>8-O sistema redireciona o usuário para uma página com a prévia da publicação importada. <br>9-O usuário clica na opção "Publish now". <br>10-O sistema retorna uma mensagem dizendo que a publicação foi realizada com sucesso.|
|**Fluxo de exceção**&nbsp;|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC32_refatorado"></span>
**UC32-Escrever uma nova Story.**

<a href="#UC32_antigo">voltar ao UC32 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário crie uma nova story.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá a sua nova story publicada.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja publicar uma nova story:** <br/> 1-Usuário clica no ícone de perfil. <br/>2-Usuário clica no botão "Stories" no menu lateral. <br/>3-O usuário clica sobre a opção "Write a story" localizada ao lado da opção "Import a story". <br/>4-O sistema redireciona o usuário para uma página de criação da nova story. <br>5-O usuário insere o conteúdo da nova story e clica no botão "Ready to publish?".<br>6-O sistema redireciona o usuário para uma página com a prévia da nova publicação. <br>7-O usuário clica na opção "Publish now". <br>8-O sistema retorna uma mensagem dizendo que a publicação foi realizada com sucesso.|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|


***
<span id = "UC33_refatorado"></span>
**UC33-Editar Drafts de Stories.**

<a href="#UC33_antigo">voltar ao UC33 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que o usuário faça edições nos stories criados como rascunho.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá editado um rascunho de story.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja editar um rascunho de story:**<br/>1-Usuário clica no ícone de perfil. <br/>2-Usuário clica no botão "Stories" no menu lateral.  <br/>3-O usuário clica sobre uma seta apontada para baixo localizada ao lado da descrição do draft que ele quer editar. <br/>4-O usuário clica na opção "Edit draft" localizada em baixo da seta. <br/>5-O sistema redireciona o usuário para uma página de edição do draft. <br>6-O usuário insere as alterações no conteúdo do draft, que é salvo automaticamente.|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC34_refatorado"></span>
**UC34-Excluir Draft de Story**

<a href="#UC34_antigo">voltar ao UC34 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário exclua um draft.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá o seu rascunho de story excluído.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja excluir um draft:** <br/>1-Usuário clica no ícone de perfil. <br/>2-Usuário clica no botão "Stories" no menu lateral.<br/>3-O usuário clica sobre uma seta apontada para baixo localizada ao lado da descrição do draft que ele quer excluir. <br>4-O usuário clica na opção "Delete draft" localizada em baixo da seta. <br/>5-O sistema redireciona o usuário para uma página para confirmar a exclusão do draft. <br>6-O usuário clica sobre o botão "Delete".<br>7-O sistema sistema redireciona o usuário para a página de visualização de drafts sem o draft excluído.|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC35_refatorado"></span>
**UC35-Editar Publicação de Story.**

<a href="#UC35_antigo">voltar ao UC35 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário edite uma publicação de story.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá a sua publicação editada.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja editar uma publicação:**<br/> 1-Usuário clica no ícone de perfil. <br/>2-Usuário clica no botão "Stories" no menu lateral. <br/>3-Usuário clica em 'Published'<br/>4-O usuário clica sobre uma seta apontada para baixo localizada ao lado da descrição da publicação que ele quer editar. <br/>5-O usuário clica na opção "Edit story" localizada em baixo da seta. <br/>6-O sistema redireciona o usuário para uma página de edição da story. <br>7-O usuário insere as alterações no conteúdo da story e clica no botão "Save and publish".<br>8-O sistema redireciona o usuário para a página da story com as alterações feitas.|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***
<span id = "UC36_refatorado"></span>
**UC36-Excluir Publicação de Story**

<a href="#UC36_antigo">voltar ao UC36 antigo</a>

|||
|---|---|
|**Descrição**| Funcionalidade responsável por permitir que um usuário exclua a publicação de um story.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.|
|**Pós-condições**|Usuário terá a sua publicação excluída.|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja excluir uma story:**<br/>  1-Usuário clica no ícone de perfil. <br/>2-Usuário clica no botão "Stories" no menu lateral. <br/>3-Usuário clica em 'Published' <br/>4-O usuário clica sobre uma seta apontada para baixo localizada ao lado da descrição da publicação que ele quer excluir. <br>5-O usuário clica na opção "Delete story" localizada em baixo da seta. <br/>6-O sistema redireciona o usuário para uma página para confirmar a exclusão da story. <br>7-O usuário clica sobre o botão "Delete".<br>8-O sistema sistema redireciona o usuário para a página de visualização de publicações sem a story excluída.|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 2 ocorre um erro de conexão com a internet|

***

####Conta (Luís Cláudio T. Lima)

***

**UC37-Deletar Conta**

|||
|---|---|
|**Descrição**|Funcionalidade que permite ao usuário deletar sua conta permenentemente.|
|**Atores**|Usuário|
|**Pré-condições**|Usuário deve estar conectado a internet|Usuário deve estar logado|
|**Pós-condições**|Usuário terá excluído sua conta na aplicação Medium|
|**Fluxo principal**|** [FP01] Este fluxo se inicia quando o usuário deseja excluir permenentemente sua conta no medium:**<br/>  1-Usuário clica no ícone de perfil.<br/>2-Usuário clica em 'Settings'<br/>3-Usuário desce até o final da pagina e clica em 'Delete account'<br/>4-Usuário é direcionado para uma página de confirmação de exclusão da sua conta;<br/>5-Usuário digita seu username no campo indicado e clica em 'Confirm deletion'|
|**Fluxo de exceção**|** [FE01] Falha de conexão à internet**<br/>No passo 5 ocorre um erro de conexão com a internet impedindo a exclusão de sua conta.|