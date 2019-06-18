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
**Representação**: Cenário Pesquisa por artigo ***REPRESENTA*** UC Área comum

**Representação**: Léxico Storie ***REPRESENTA*** Cenário Pesquisa por artigo

**Representação**: UC03-Pesquisar artigo ***REPRESENTA*** UC Área comum
**Representação**: US 047 ***REPRESENTA*** UC03

**Alocação** : Pergunta: "Como você classificaria a interface do MEDIUM?" ***ALOCADO EM*** UC Área comum

**Alocação**: UC Área comum ***ALOCADO EM*** i* Pesquisar conteúdo

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
**Representação**: Brainstorming 4 ***REPRESENTA*** Introspecção 1

**Alocação**: Cenário Leitura de texto ***ALOCADO EM*** Léxico Storie

**Representação**: Léxico Stories ***REPRESENTA*** i* Publicações

**Alocação**: Brainstorming 4 ***REPRESENTA*** i* Publicações

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

**Representação**: Pergunta: "Sobre quais tipos de assunto você escreve?" ***REPRESENTA*** RichPicture "Ponto de vista do escritor" e "NewStory"

**Representação**: Brainstorming 4 ***REPRESENTA*** StoryTelling - Escritor, New Story

**Representação**: Introspecção 3 ***REPRESENTA*** StoryTelling - Escritor, New Story

**Representação**: Cenário Criar um novo Storie ***REPRESENTA*** Brainstorming 4

**Alocação**: Léxico Series ***ALOCADO EM*** UC Series

**Alocação**: 