## Versionamento de edições
| Data           | autor                | Descrição                           |Versão|
|----------------|----------------------|-------------------------------------|------|
|09/04/2019|Pedro Rodrigues|Adiciona o Moscow|0.1|
|09/04/2019|Guilherme Marques|Adiciona a Lista de Dependência|0.2|
|09/04/2019|William Elias |Adicionando tabela FTF v.1|0.3|
|10/04/2019|William Elias |Modificando texto do requisito R004 |0.4|
|15/04/2019|Matheus Salles Blanco | Adicionando o Rastro na tabela de Lista de requisitos eliticitados | 0.5 |
|15/04/2019|Matheus Salles Blanco e Pedro Rodrigues| Adicionando o Rastro na tabela de Lista de requisitos eliticitados | 0.6 |
|17/04/2019|William Elias |Remoção da lista de requisitos, moscow e ftf para arquivos avulsos |0.7|

# Moscow
**Descrição:** Por meio da técnica de priorização de Moscow, podemos classificar os requisitos quanto a importância, assim facilitando a continuação do ciclo de desenvolvimento do software. Para classificar utilizamos as seguintes denotações: must, could, should e would.

ID | Funcionalidade conforme a área | Prioridade 
------- | ------- | -------
x | **Aplicação** | x
R001 | Responsividade | Must 
R002 | Portabilidade mobile ios | Could
R003 | Portabilidade mobile android | Could
R004 | Pesquisar artigos por nome | Should
R005 | Visualizar data de publicação dos artigos | Could
R006 | Política de privacidade | Must
R007 | Paleta de cores monocromáticas no site | Should
R008 | Acessar a área de membro | Must
R009 | Visualizar artigos populares | Must
x | **Séries** | x
R010 | Criar nova 'serie' | Must
R011 | Inserir título | Must
R012 | Inserir conteúdo | Must
R013 | Inserir nova página de conteúdo | Should
R014 | Inserir imagem | Should
R015 | Editar série | Should
R016 | Deletar série | Must
R017 | Ver status | Should
x | **Story** | x
R018 | Escrever 'new story' | Must
R019 | Visualizar rascunhos | Should
R020 | Visualizar stories publicadas | Must
R021 | Importar 'story' | Would
R022 | Editar story | Should
R023 | Deletar story | Must
x | **Leitor/Ouvinte** | x
R024 | Aplaudir um texto lido | Could
R025 | Compartilhar texto lido no Facebook ou Instagram | Could
R026 | Comentar no corpo do texto | Could
R027 | Receber notificações de textos publicados por autores seguidos | Should
R028 | Seguir escritores | Should
R029 | Seguir usuários | Should
R030 | Escutar podcasts | Should
R031 | Selecionar tema de artigos | Must
R032 | Visualizar textos publicados por um escritor em seu perfil | Should
R033 | Ter recomendações de leituras conforme histórico de leitura | Should
R034 | Ver os artigos favoritados | Should
R035 | Ver os artigos curtidos | Should
R036 | Visualizar perfis de outros usuários | Could
R037 | Favoritar publicação | Should
R038 | Visualizar comentários da publicação | Should
R039 | Reportar publicação | Should
R040 | Bloquear usuário | Should
x | **Perfil** | x
R041 | Editar perfil de usuário | Must
R042 | Salvar/cancelar edição | Should
R043 | Visualizar autores seguidos | Should
R044 | Visualizar seguidores | Should
R045 | Visualizar 'claps' | Could
R046 | Visualizar próprio perfil | Must
R047 | Visualizar claps em suas publicações | Would
R048 | Ver seus seguidores | Could
x | **Stats** | x
R049 | Visualizar estatisticas em gráfico | Would
R050 | Aprender mais sobre estatíticas | Would
x | **Bookmarks** | x
R051 | Visualizar marcações | Could
R052 | Ler artigos marcados | Should
x | **Publications** | x
R053 | Visualizar autores seguidos | Could 
R054 | Criar publicação | Must
R055 | Visualizar rascunhos | Should
x | **Customize your interests** | x
R056 | Visualizar pessoas que foram seguidas por você | Should
R057 | Visualizar Publicações seguidas | Should
R058 | Selecionar/remover tópicos de interesse | Could
R059 | Deixar de seguir usuários | Should
R060 | Deixar de seguir publicações | Must
x | **Configurações** | x
R061 | Ativar/desativar modo noturno | Would 
R062 | Automatizar modo noturno | Would
R063 | Enviar e-mail quando tiver o texto destacado | Would
R064 | Salvar/cancelar edição de e-mail | Must
R065 | Selecionar périodo de sugestão de artigos diária | Could
R066 | Desativar sugestão de artigos | Should
R067 | Ativar/desativar boletim informativo | Should 
R068 | Selecionar tema do informativo | Could
R069 | Ativar/desativar recomendações de stories | Could
R070 | Ativar/desativar notificação por e-mail | Must
R071 | Ativar/desativar notificação social | Must
R072 | Selecionar privacidade de menções | Should
R073 | Desativar menções | Should
R074 | Conectar com redes sociais (Facebook/Twitter) | Could
R075 | Conectar com Google | Could
R076 | Mostrar links para Facebook e Twitter na página de perfil | Could 
R077 | Editar nome de usuário | Could
R078 | Permitir/bloquear leitura de notas privadas em seus stories | Should
R079 | Visualizar usuários bloqueados | Could
R080 | Gerenciar usuários bloqueados | Could
R081 | Fazer download de suas informações | Could
R082 | Deslogar de outras sessões | Must
R083 | Desativar sua conta | Must
R084 | Deletar sua conta | Must
R085 | Ativar/desativar notificação de novas funcionalidades da aplicação | Must
R086 | Gerenciar atualizações de seus escritores | Could
R087 | Enviar e-mail quando receber clap | Would
x | **Help Page** | x
R088 | Tutorial das áreas da aplicação | Must
R089 | Acessar glossário MEDIUM | Should
R090 | Responder questionário de satisfação | Could
R091 | Pesquisar tópico de ajuda | Should
x | **Medium ChatBot** | x
R092 | Abrir sidebar do chatbot | Should
R093 | Fechar sidebar do chatbot | Should
R094 | Enviar dúvida para o chatbot | Must
R095 | Clicar em sugestões de dúvidas comuns | Should
R096 | Acessar configurações do chatbot | Should
R097 | Ativar/desativar o som de recebimento de mensagens de resposta | Must
R098 | Enviar transcript do chatbot via e-mail | Could
R099 | Baixar transcript pelo navegador | Should
x | **Medium Membership** | x
R100 | Escolher plano | Should
R101 | Inserir como forma de pagamento | Must
R102 | Retirar limites de histórias | Must
x | **Login/Cadastro** | x
R103 | Login via redes sociais (Facebook ou Twitter) | Could
R104 | Login via Google | Could
R105 | Login via E-mail | Should
R106 | Cadastrar com Google | Could
R107 | Cadastrar com Facebook |Could


