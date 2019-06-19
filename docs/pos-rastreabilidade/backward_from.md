## Versionamento de edições
|Data      |        Autor            |           Descrição           |Versão|
|----------|-------------------------|-------------------------------|------|
|13/06/2019| Pedro Rodrigues Pereira | Adição da pagina e introdução | 1.0  |

### Introdução

Rastreável é uma característica de sistemas nos quais há uma interligação entre os dados obtidos e as informações geradas. No caso da engenharia de requisitos podemos considerar como rastreabilidade como a caracaterização de relação entre os requisitos e suas fontes ou artefatos criados durante todo o ciclo de vida do software. Essa característa está atrelada intrinsicamente a utilização de uma baseline de requisitos para uma melhor transparência dos requisitos elicitados.

Com a rastreabilidade é possível ver todo o processo evolutivo referente aos requisitos e suas conseguências.
Com isso temos a pré-rastreabilidade como uma projeção de possíveis surgimentos de requisitos e também temos a pós rastreabilidade que será tratada nesse tópico por meio da utilização de algumas técnicas inerentes a ela.

### Metodologia

Para a realização dessa tarefa, em um primeiro momento, fora refatorada a baseline e posteriormente o backlog do produto. Após esse processo de refatoração se tornou possível linkar os requisitos em relação a sua origem, levando em consideração todas as suas ocorrências.

### Elos Funcionais

**Legenda:**
- Representação/Representa = R
- Alocação = A
- Alocado e = AE

### EF1
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Pergunta: "Como você classificaria a interface do MEDIUM?"
- StoryBoard Tutorial e seguir escritor
- Cenário Pesquisa por artigo
- Léxico Storie
- UC Área comum	
- UC03-Pesquisar artigo	
- US 047 - Usuário: Pesquisar por nome de artigo
- i* Pesquisar conteúdo

#### Elo
**R**: Cenário Pesquisa por artigo ***R*** UC Área comum

**R**: Léxico Storie ***R*** Cenário Pesquisa por artigo

**R**: UC03-Pesquisar artigo ***R*** UC Área comum
**R**: US 047 ***R*** UC03

**A** : Pergunta: "Como você classificaria a interface do MEDIUM?" ***AE*** UC Área comum

**A**: UC Área comum ***AE*** i* Pesquisar conteúdo

### EF2
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 4 "matheus: ter um registro dos seus textos em seu blog"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação	
-  Cenário Leitura de texto	
-  Léxico Storie
- i* Publicações

#### Elo
**R**: Brainstorming 4 ***R*** Introspecção 1

**A**: Cenário Leitura de texto ***AE*** Léxico Storie

**R**: Léxico Stories ***R*** i* Publicações

**A**: Brainstorming 4 ***A*** i* Publicações

### EF3

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- RichPicture "Ponto de vista do escritor" e "New Story"
- Pergunta: "Sobre quais tipos de assunto você escreve?"	
- StoryTelling - Escritor, New Story	
- Brainstorming 4 " Matheus: possibilidade de escrever no blog ou fora do blog"
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Series	
- UC Series	
- UC23 - Criar series	
- US 059 - Usuário Escritor: Criar uma nova Serie
- I* Publicações

#### Elo

**R**: Pergunta: "Sobre quais tipos de assunto você escreve?" ***R*** RichPicture "Ponto de vista do escritor" e "NewStory"

**R**: Brainstorming 4 ***R*** StoryTelling - Escritor, New Story

**R**: Introspecção 3 ***R*** StoryTelling - Escritor, New Story

**R**: Cenário Criar um novo Storie ***R*** Brainstorming 4

**A**: Léxico Series ***AE*** UC Series

**A**: UC23 ***AE*** US 059

### EF4
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Pergunta: "Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?"	
- StoryTelling - Escritor, New Story	
- Brainstorming 3 "Matheus: os usuários podem ver os textos publicados na página de um escritor, com foco nas publicações com as quais ele interagiu"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação	
- Cenário Leitura de texto	
- Léxico Series	
- UC Series	
- UC20-Visualizar Series	
- US 071 - Usuário: Visualizar storie
- I* Publicações

#### Elo

**R**: StoryTelling  Escritor, New Story **R** Brainstorming 3

**R**: Cenário Leitura de texto **R** Brainstorming 3

**R**: Léxico Series **R** UC Series

**A**: UC Series **AE** UC20

**A**: UC20 **AE** US 071 

**R**: StoryTelling Escritor, New Story **R** i* Publicações

### EF5
####Categoria
Desenvolvimento
####Elementos Rastreáveis
- RichPicture Ponto de vista do escritor
- StoryTelling - Escritor, New Story
- Cenário Criar um novo Storie	
- Léxico Series	
- UC stories	
- UC23 - Criar series	
- US 061 - Usuário Escritor: Deletar uma Serie existente 
- I* Publicações

#### Elos

**R**: Cenário Criar uma nova storie **R** UC stories

**A**: Léxico Series **AE** UC23

**A**: UC23 **AE** US 061

**R**: StoryTelling Escritor, New Story **R** i* Publicações

**R**: RichPicture Ponto de vista do escritor **R** StoryTelling Escritor, New Story


### EF6

#### Categoria
Desenvolvimento

#### Elementos Rastreáveis
- StoryTelling - Escritor, New Story
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story	
- Cenário Criar um novo Storie	
- Léxico Series	
- UC Series	
- UC23 - Criar series	
- US 060 - Usuário Escritor: Editar uma Serie existente
- I* Publicações

#### Elos
**R**:  Introspecção 3 ***R*** StoryTelling - Escritor, New Story

**R**: Léxico Series **R** UC Series

**A**: UC23 **AE** US 060

**A**: UC23 **AE** UC Series

**R**: StoryTelling Escritor, New Story **R** i* Publicações

**R**: Cenário Criar uma nova storie **R** Introspecção 3

### EF7

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Series	
- UC Series	
- UC36-Excluir Publicação	
- US 061 - Usuário Escritor: Deletar uma Serie existente
- I* Publicações

#### Elos

**R**: Cenário Criar uma nova storie **R** Introspecção 3

**A**: UC23 **AE** US 060

**R**: Introspecção 3 **R** UC36

**R**: Léxico Series **R** UC Series

**A**: Introspecção 3 **AE** i* Publicações

### EF8
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryTelling - Escritor, New Story	
- Brainstorming 4 " Matheus: ver quem deu clap em suas publicações"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Léxico Status	
- UC Área comum	
- UC20-Visualizar Series	
- US 034 - Usuário: visualizar seguidores
- I* Publicações

#### Elos

**A**: StoryTelling - Escritor, New Story **AE** Brainstorming 4

**A**: UC20 **AE** UC Área comum

**A**: Léxico Status **AE** UC Área comum

**A**: Introspecção 1 **AE** UC Área comum

**A**: US 034 **AE** UC Área comum

**R**: US 034 **R** i* Publicações

### EF9
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- RichPicture "Ponto de vista do escritor/New Story"
- StoryTelling - Escritor, New Story	
- Brainstorming 4 " Matheus: possibilidade de escrever no blog ou fora do blog"
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Storie	
- UC stories	
- UC32-Escrever uma nova Story.	
- US 063 - Usuário Escritor: Escrever 'new storie' 
- I* Publicações

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: StoryTelling - Escritor, New Story **R** US 063

**R**: Brainstorming 4 **R** UC32

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**R**: RichPicture "Ponto de vista do escritor/New Story" **R** StoryTelling - Escritor, New Story

**R**: US 063 **R** i* Publicações

### EF10
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryTelling - Escritor, New Story	
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Storie	
- UC stories	
- UC32-Escrever uma nova Story.	
- US 063 - Usuário Escritor: Escrever 'new storie' 
- I* Publicações

#### Elos

**R**: 

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: StoryTelling - Escritor, New Story **R** US 063

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**R**: US 063 **R** i* Publicações

### EF11

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryTelling - Escritor, New Story	
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Storie	
- UC stories	
- UC32-Escrever uma nova Story.	
- I* Publicações

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**A**: Introspecção 3 **AE** i* Publicações

**R**: StoryTelling - Escritor, New Story **R** Introspecção 3

**A**: US 032 **AE** UC Stories

### EF12

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryBoard Tutorial e seguir escritor	
- Brainstorming 3 "Matheus: os usuários podem ver os textos publicados na página de um escritor, com foco nas publicações com as quais ele interagiu"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação	- Cenário Criar um novo Storie	
- Léxico Storie	
- UC stories	
- UC28-Visualizar Stories	
- US 071 - Usuário: Visualizar storie 
- I* Publicações

#### Elos

**R**: StoryBoard Tutorial **R** Introspecção 1

**R**: Brainstorming 3 **R** StoryBoard Tutorial

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: Léxico Stories **R** UC stories

**A**: UC28 **AE** UC Stories

**R**: US 071 **R** UC28

**R**: US 071 **R** i* Publicações

### EF13

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- RichPicture "Ponto de vista do escritor/New Story"
- StoryTelling - Escritor, New Story	
- Brainstorming 4 " Matheus: possibilidade de escrever no blog ou fora do blog"
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Importar um storie	
- Léxico Storie	
- UC stories	
- UC31-Importar uma Story	
- US 064 - Usuário Escritor: Importar 'storie'
- i* Publicações

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Importar um storie

**R**: StoryTelling - Escritor, New Story **R** US 064

**R**: Brainstorming 4 **R** UC31

**A**: Cenário Importar um storie **AE** Introspecção 3

**R**: RichPicture "Ponto de vista do escritor/New Story" **R** StoryTelling - Escritor, New Story

**R**: US 064 **R** i* Publicações

### EF14

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryTelling - Escritor, New Story	
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Storie	
- UC stories	
- UC35-Editar Publicação
- US 060 - Usuário Escritor: Editar uma Serie existente
- i* Publicações

#### Elos
**R**: StoryTelling - Escritor, New Story **R** US 064

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: UC35 **AE** UC Stories

**A**: UC35 **AE** i* Publicações

**R**: US 060 **R** i* Publicações

**R**: StoryTelling - Escritor, New Story **R** Introspecção 3

### EF15
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Storie	
- UC stories	
- UC36-Excluir Publicação	
- US 061 - Usuário Escritor: Deletar uma Serie existente
- i* Publicações

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: UC36 **AE** UC Stories

**A**: UC36 **AE** i* Publicações

**R**: UC36 **R** US 061

**R**: US 061 **R** i* Publicações

**R**: Léxico Stories **R** Introspecção 3

### EF16

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryBoard Tutorial e seguir escritor	
- Brainstorming 3 "matheus: o leitor poder gostar do texto"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Cenário Dar Claps	
- Léxico Clap 
- US 065 - Usuário: Aplaudir um texto lido
- I* Publicações

#### Elos

**R**: Léxico Clap **R** US 065

**R**: lexico clap **R** Cenário Dar Claps

**R**: introspecção 1 **R** StoryBoard Tutorial

**A**: US 065 **AE** i* Publicações

**A**: Cenário Dar Claps **AE**  Brainstorming 3

### EF17
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- RichPicture "Ponto de vista do leitor"
- StoryTelling - Escritor, New Story	
- Brainstorming 3 "matheus: compartilhar o texto"	
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Compartilhar publicação	
- Léxico Share		
- US 066 - Usuário: Compartilhar texto lido no Facebook ou Instagram	
- I* Publicações

#### Elos

**R**: RichPicture "Ponto de vista do leitor" **R** StoryTelling Escritor

**A**: Lexico Share **AE** Cenário Compartilhar Publicação

**R**: RichPicture "Ponto de vista do leitor" **R** Introspecção 3

**A**: US 066 **AE** i* Publicações

### EF18
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 4 "Pedro: ver comentários de seus textos e responder os comentários de seus textos"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Cenário Comentar publicação	
- Léxico Response	
- US 067 - Usuário: Comentar no corpo do texto		
- I* Publicações

#### Elos

**R**: Brainstorming 4 **R** Introspecção 1

**R**: Cenário Comentar Publicação **R** US 067

**A**: Léxico Response **AE** Cenário Comentar Publicação

**R**: US 067 **Rdo em** i* Publicações

### EF19
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryBoard Tutorial e seguir escritor
- Brainstorming 3 "Gabriel: escutar podcasts"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Cenário Leitura de texto	
- Léxico Storie	
- UC Área comum	
- UC04-Escutar podcast	
- US 069 - Usuário: Escutar publicação

#### Elos

**R**: lexico storie **R** UC Área comum

**A**: lexico storie **AE** Cenário Leitura de texto

**R**: UC Área Comum **R** UC04

**R**: UC04 **R** US 069

**R**: Brainstorming 3 **R** introspecção 1

### EF20

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryBoard Tutorial e seguir escritor	
- Brainstorming 3 "Matheus: seguir o escritor"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Cenário Seguir usuário	
- Léxico Storie	
- UC Área comum		
- US 025 - Usuário: Seguir escritores		
- i* Pesquisar conteúdo

#### Elos:

**R**: Brainstorming 3 **R** introspecção 1

**R**: Brainstorming 3 **R** StoryBoard Tutorial

**A**: lexico storie **AE** Cenário Seguir Usuário

**R**: US 025 **R** UC Área Comum

### EF21

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 3: "Gabriel: Seguir outros usuários"		
- Cenário Seguir usuário	
- Léxico Following		
- US 025 - Usuário: Seguir usuários		
- i* Pesquisar conteúdo
#### Elos
**R**: Brainstorming 3 **R** Cenário Seguir Usuário

**A**: lexico Following **AE** Cenário Seguir Usuário

**R** US 025 **R** Brainstorming 3

**R** Brainstorming 3 **R** i* Pesquisar Conteúdos

### EF22

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 3: "William: O leitor recebe as notificações de publicações de seus escritores favoritados"		
- Cenário Configurar notificações	
- Léxico Digest e Léxico Newsletter	
- UC Configurar perfil	
- "UC10-Configurar preferências"	
- US 019 - Usuário: Ativar/desativar notificação por e-mail 	
- NFR Controle de Qualidade	
- i* Configurações
#### Elos
**R**: Brainstorming 3 **R** Léxico Digest e Newsletter

**A**: Léxico Digest e Newsletter **AE** Cenário Configurar notificação

**A**: NFR Controle de Qualidade **AE** i* Configurações

**R**: UC Configurar perfil **R** UC10

**R**: UC10 **R** US 019

### EF23

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 3: "Gabriel: Selecionar tema de artigos"		
- Cenário Pesquisa por artigo	
- Léxico Search e Léxico Tag	
- UC Área comum	
- UC03 - Pesquisar artigo	
- i* Pesquisar conteúdo
#### Elos
**R**: Brainstorming 3 **R** Cenário Pesquisa por artigo

**A**: Léxico Search e Tag **AE** Cenário Pesquisa por artigo

**R**: UC Área comum **R** UC03

**R**: UC03 **R** i* Pesquisar Conteúdo

### EF24

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 3: "Matheus: os usuários podem ver os textos publicados na página de um escritor, com foco nas publicações com as quais ele interagiu"			
- Léxico Following		
- UC30 - Visualizar Publicações	
- US 027 - Usuário: Visualizar textos publicados de um escritor em específico
- i* Pesquisar conteúdo
#### Elos
**R**: Brainstorming 3 **R** UC30

**A**: UC30 **AE** US 027

**A**: Léxico Following **AE** Brainstorming 3

**R**: US 027 **R** i* Pesquisar Conteúdo

### EF25

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Relato de Introspecção 4: "ii. Listagem de artigos salvos: para um usuário logado, apresenta uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto em que cada artigo salvo foi fechado;"	
- Cenário Criar um novo Bookmark	
- Léxico Bookmark	
- UC Bookmark		
- US 030 - Usuário: Favoritar Publicação
#### Elos
**R**: Introspecção 4 **R** UC Bookmark

**A**: Léxico Bookmark **AE** Cenário Criar um novo Bookmark

**R**: UC Bookmark **R** Introspecção 4

**A**: US 030 **AE** UC Bookmark

### EF26

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Relato de Introspecção 4: "ii. Listagem de artigos salvos: para um usuário logado, apresenta uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto em que cada artigo salvo foi fechado;"		
- UC Bookmark		
- US 030 - Usuário: Favoritar Publicação
#### Elos
**R**: Introspecção 4 **R** UC Bookmark

**A**: US 030 **AE** UC Bookmark

**R**: US 030 **R** Introspecção 4

### EF27

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 2: "William: visualizar os perfis de outros usuários"		
- Cenáro Seguir usuário	
- Léxico Profile	
- UC03 - Pesquisar artigo	
- US 029 - Usuário: Visualizar perfis de outros usuários		
- i* Pesquisar conteúdo
#### Elos
**R**: Brainstorming 2 **R** Cenário Seguir usuário

**A**: Léxico Profile **AE** Cenário Seguir usuário

**A**: UC03 **AE** US 029

**R**: Brainstorming 2 **R** i* Pesquisar Conteúdo

### EF28

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 3: "Matheus: o leitor poder gostar do texto"	
- Relato de Introspecção 4: "ii. Listagem de artigos salvos: para um usuário logado, apresenta uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto em que cada artigo salvo foi fechado;"	
- Cenário Criar um novo Bookmark	
- Léxico Bookmark	
- UC Bookmark		
- US 030 - Usuário: Favoritar Publicação
#### Elos
**R**: Brainstorming 3 **R** Introspecção 4

**A** Léxico Bookmark **AE** Cenário Criar um novo Bookmark

**R**: US 030 **AE** UC Bookmark

**R** Introspecção 4 **R** US 030

### EF29

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 4: "Pedro: ver comentários de seus textos e responder os comentários de seus textos"		
- Cenário Comentar publicação	
- Léxico Response		
- UC30 - Visualizar Publicações	
- US 031 - Usuário: Visualizar comentários da publicação		
- i* Stories
#### Elos
**R**: Brainstorming 4 **R** Cenário Comentar Publicação

**A**: Léxico Response **AE** Cenário Comentar Publicação

**A**: UC30 **AE** US 031

**R**:Cenário Comentar Publicação **R** i* Stories

### EF30

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Editar Perfil					
- UC Configurar perfil	
- "UC10-Configurar preferências"	
- US 032 - Usuário: Reportar publicação	NFR Segurança	
- i* Configurações
#### Elos
**R**: Storytelling - Editar perfil **R** UC Configurar perfil

**A**: UC10 **AE** UC Configurar Perfil

**R**: UC10 **R** US 032

**R**: UC Configurar Perfil **R** i* Configurações

### EF31

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Editar Perfil					
- UC Configurar perfil	
- "UC10-Configurar preferências"	
- US 033 - Bloquear usuário	
- NFR Segurança	
- i* Configurações
#### Elos
**R**: Storytelling Editar Perfil **R** UC Configurar perfil

**A**: UC Configurar Perfil **AE** UC10

**R** US 033 **R** NFR Segurança

**A**: i* Configurações **AE** NFR Segurança

### EF32

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos

### EF33

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos

### EF34

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos

### EF35

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos

### EF36

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos

### EF37

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos

### EF38

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos

### EF39

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos

### EF40

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis

#### Elos
