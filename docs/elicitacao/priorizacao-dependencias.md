## Versionamento de edições

| Data           | autor                | Descrição                           |Versão|
|----------------|----------------------|-------------------------------------|------|
|17/04/2019|William Elias |Adicionando tabela das dependências v.1|1.0|
|17/06/2019|William Elias |Adicionando introdução e metodologia|2.0|

### Introdução

Para que seja aplicada a técnica de priorização _First Things Firts_ (FTF) não se pode haver requisitos com dependências. Para que essa prerrogativa seja atendida, é necessário se criar uma planilha de dependências entre os requisitos com a finalidade de filtrar somente os requisitos que se encontram sem nenhum vínculo.

### Metodologia

Foram pegos os requitos da priorização de moscow e feita análise de cada relação com outro requisito, se o requisto possuir uma dependência é retirado.

***

#### Lista de dependências (Versão 1)

<table>
        <thead>
         <tr>
               <th></th>
               <th>Funcionalidade conforme a área</th>
               <th>Estado</th>
               <th>Justificativa</th>
         </tr>
        </thead>
       <tr>
              <th>ID</th>
              <th>Series</th>
              <th></th>
              <th></th>
          </tr>
       <tr>
              <td>R001</td>
              <td>Criar nova 'serie'</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R002</td>
              <td>Inserir título</td>
              <td>Não permanece</td>
              <td>Depende de 'Criar nova serie'</td>
          </tr>
       <tr>
              <td>R003</td>
              <td>inserir conteúdo</td>
              <td>Não permanece</td>
              <td>Depende de 'Criar nova serie'</td>
          </tr>
       <tr>
              <td>R004</td>
              <td>Inserir nova página de conteúdo</td>
              <td>Não permanece</td>
              <td>Depende de 'Criar nova serie'</td>
          </tr>
       <tr>
              <td>R005</td>
              <td>inserir imagem</td>
              <td>Não permanece</td>
              <td>Depende de 'Criar nova serie'</td>
          </tr>
       <tr>
              <td>R006</td>
              <td>Editar serie</td>
              <td>Não permanece</td>
              <td>Depende de 'Criar nova serie'</td>
          </tr>
       <tr>
              <td>R007</td>
              <td>Deletar serie</td>
              <td>Não permanece</td>
              <td>Depende de 'Criar nova serie'</td>
          </tr>
       <tr>
              <td>R008</td>
              <td>Ver status</td>
              <td>Não permanece</td>
              <td>Depende de 'Criar nova serie'</td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Stories</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R009</td>
              <td>Escrever 'new story'</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R010</td>
              <td>visualizar rascunhos</td>
              <td>Não Permanece</td>
              <td>Depende de 'Escrever new storie'</td>
          </tr>
       <tr>
              <td>R011</td>
              <td>Visualizar stories publicadas</td>
              <td>Não Permanece</td>
              <td>Depende de 'Escrever new storie'</td>
          </tr>
       <tr>
              <td>R012</td>
              <td>Importar 'story'</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R013</td>
              <td>Editar story</td>
              <td>Não Permanece</td>
              <td>Depende de 'Escrever new storie'</td>
          </tr>
       <tr>
              <td>R014</td>
              <td>Deletar story</td>
              <td>Não Permanece</td>
              <td>Depende de 'Escrever new storie'</td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Leitor/Ouvinte</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R015</td>
              <td>Aplaudir um texto lido</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R016</td>
              <td>Compartilhar texto lido no Facebook ou  Instagram</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R017</td>
              <td>Comentar no corpo do texto</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R018</td>
              <td>receber notificações de textos publicados por autores seguidos</td>
              <td>Não Permanece</td>
              <td>Depende de 'Seguir autores'</td>
          </tr>
       <tr>
              <td>R019</td>
              <td>Seguir autores</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R020</td>
              <td>Seguir usuários</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R021</td>
              <td>Escutar podcasts</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R022</td>
              <td>Visualizar textos publicados por um escritor em seu perfil</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R023</td>
              <td>Ter recomendações de leituras conforme histórico de leitura</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R024</td>
              <td>Ver os artigos favoritados</td>
              <td>Não Permanece</td>
              <td>Depende de 'favoritar publicação'</td>
          </tr>
       <tr>
              <td>R025</td>
              <td>Ver os artigos curtidos</td>
              <td>Não Permanece</td>
              <td>Depende de 'Aplaudir um texto'</td>
          </tr>
       <tr>
              <td>R026</td>
              <td>Visualizar perfis de outros usuários</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R027</td>
              <td>Favoritar publicação</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R028</td>
              <td>Visualizar comentários da publicação</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R029</td>
              <td>Reportar publicação</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R030</td>
              <td>Bloquear usuário</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R031</td>
              <td>Selecionar tema de artigos</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Perfil</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R032</td>
              <td>Editar perfil de usuário</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R033</td>
              <td>Salvar/cancelar edição</td>
              <td>Não Permanece</td>
              <td>Depende de 'editar perfil'</td>
          </tr>
       <tr>
              <td>R034</td>
              <td>Visualizar autores seguidos</td>
              <td>Não Permanece</td>
              <td>Depende de 'seguir escritor'</td>
          </tr>
       <tr>
              <td>R035</td>
              <td>Visualizar seguidores</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R036</td>
              <td>Visualizar 'claps'</td>
              <td>Permanece</td>
              <td>Depende de 'favoritar um texto lido'</td>
          </tr>
       <tr>
              <td>R037</td>
              <td>visualizar próprio perfil</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R038</td>
              <td>Visualizar claps em suas publicações</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R039</td>
              <td>Ver seus seguidores</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Stats</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R040</td>
              <td>Visualizar estatisticas em gráfico</td>
              <td>Não Permanece</td>
              <td>Depende de "Criar publicação"</td>
          </tr>
       <tr>
              <td>R041</td>
              <td>aprender mais sobre estatíticas</td>
              <td>Não Permanece</td>
              <td>Funcionalidade presente na página de ajuda</td>
          </tr>
       <tr>
              <td>ID</td>
              <td>Bookmarks</td>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R042</td>
              <td>Visualizar marcações</td>
              <td>Não Permanece</td>
              <td>Depende de "Adicionar texto aos favoritos"</td>
          </tr>
       <tr>
              <td>R043</td>
              <td>Ler artigos marcados</td>
              <td>Não Permanece</td>
              <td>Depende de "Adicionar texto aos favoritos"</td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Publications</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R044</td>
              <td>Visualizar autores seguidos</td>
              <td>Não Permanece</td>
              <td>Depende de "Seguir autores"</td>
          </tr>
       <tr>
              <td>R045</td>
              <td>Visualizar sugestões de leitura</td>
              <td>Não Permanece</td>
              <td>Depende de "Seguir autores"</td>
          </tr>
       <tr>
              <td>R046</td>
              <td>Criar publicação</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Customize your interests</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R047</td>
              <td>Visualizar pessoas que foram seguidas por você</td>
              <td>Não Permanece</td>
              <td>Depende de "seguir pessoa"</td>
          </tr>
       <tr>
              <td>R048</td>
              <td>Visualizar Publicações seguidas</td>
              <td>Não Permanece</td>
              <td>Depende de "Seguir autores"</td>
          </tr>
       <tr>
              <td>R049</td>
              <td>selecionar/remover tópicos de interesse</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R050</td>
              <td>Deixar de seguir usuários</td>
              <td>Não Permanece</td>
              <td>Depende de "seguir usuários"</td>
          </tr>
       <tr>
              <td>R051</td>
              <td>Deixar de seguir publicações</td>
              <td>Não Permanece</td>
              <td>Depende de "seguir autores"</td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Configurações</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R052</td>
              <td>Ativar/desativar notificação social</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R053</td>
              <td>Ativar/desativar modo noturno</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R054</td>
              <td>Automatizar modo noturno</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R055</td>
              <td>Editar email</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R056</td>
              <td>salvar/cancelar edição de e-mail</td>
              <td>Não Permanece</td>
              <td>Depende de 'Editar e-mail'</td>
          </tr>
       <tr>
              <td>R057</td>
              <td>Selecionar périodo de  sugestão de artigos</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R058</td>
              <td>Desativar sugestão de artigos</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R059</td>
              <td>Ativar/desativar boletim informativo</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R060</td>
              <td>Selecionar tema do boletim informativo</td>
              <td>Não Permanece</td>
              <td>Depende de 'Ativar/desativar boletim informativo'</td>
          </tr>
       <tr>
              <td>R061</td>
              <td>Ativar/desativar recomendações de stories</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R062</td>
              <td>Ativar/desativar notificação por e-mail</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R063</td>
              <td>Selecionar privacidade de menções</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R064</td>
              <td>Desativar menções</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R065</td>
              <td>Conectar com redes sociais (faceboo/twitter)</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R066</td>
              <td>Conectar com Google</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R067</td>
              <td>Mostrar links para facebook e twitter na página de perfil</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R068</td>
              <td>editar nome de usuário</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R069</td>
              <td>Permitir/bloquear leitura de notas privadas em seus stories</td>
              <td>Não Permanece</td>
              <td>Depende de 'criar storie'</td>
          </tr>
       <tr>
              <td>R070</td>
              <td>Visualizar usuários bloqueados</td>
              <td>Não Permanece</td>
              <td>Depende de 'bloquear usuários'</td>
          </tr>
       <tr>
              <td>R071</td>
              <td>Gerenciar usuários bloqueados</td>
              <td>Não Permanece</td>
              <td>Depende de 'Bloquear usuários'</td>
          </tr>
       <tr>
              <td>R072</td>
              <td>Fazer download de suas informações</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R073</td>
              <td>Deslogar de outras sessões</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R074</td>
              <td>Desativar sua conta</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R075</td>
              <td>Deletar sua conta</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R076</td>
              <td>Ativar/desativar notificação de novas funcionalidades da aplicação</td>
              <td>Não Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R077</td>
              <td>Gerenciar atualizações de seus escritores</td>
              <td>Não Permanece</td>
              <td>Depende de 'Seguir autores'</td>
          </tr>
       <tr>
              <td>R078</td>
              <td>Receber e-mail quando receber clap</td>
              <td>Não permanece</td>
              <td>Depende de 'criar storie'</td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Help Page</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R079</td>
              <td>Tutorial das áreas da aplicação</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R080</td>
              <td>Acessar glossário MEDIUM</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R081</td>
              <td>Responder questionário de satisfação</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R082</td>
              <td>Pesquisar tópico de ajuda</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Medium ChatBot</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R083</td>
              <td>Abrir sidebar que inicia interface do chatbot</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R084</td>
              <td>Fechar sidebar do chatbot</td>
              <td>Não Permanece</td>
              <td>Depende de 'Inserir dúvida no campo de texto'</td>
          </tr>
       <tr>
              <td>R085</td>
              <td>Enviar dúvida para o chatbot</td>
              <td>Permanece</td>
              <td>Depende de 'abrir sidebar do chatbot'</td>
          </tr>
       <tr>
              <td>R086</td>
              <td>Clicar em sugestões de dúvidas comuns</td>
              <td>Permanece</td>
              <td>Depende de 'abrir sidebar do chatbot'</td>
          </tr>
       <tr>
              <td>R087</td>
              <td>Acessar configurações do chatbot</td>
              <td>Não Permanece</td>
              <td>Depende de 'Ativar o som de recebimento de mensagens de resposta'</td>
          </tr>
       <tr>
              <td>R088</td>
              <td>Ativar/desativar o som de recebimento de mensagens de resposta</td>
              <td>Permanece</td>
              <td>Depende de 'abrir sidebar do chatbot'</td>
          </tr>
       <tr>
              <td>R089</td>
              <td>Enviar transcript do chatbot via e-mail</td>
              <td>Permanece</td>
              <td>Depende de 'abrir sidebar do chatbot'</td>
          </tr>
       <tr>
              <td>R090</td>
              <td>Baixar transcript pelo navegador</td>
              <td></td>
              <td>Depende de 'abrir sidebar do chatbot'</td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Medium Membership</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R091</td>
              <td>Escolher plano</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R092</td>
              <td>Inserir forma de pagamento</td>
              <td>Não Permanece</td>
              <td>Depende de 'Escolher plano'</td>
          </tr>
       <tr>
              <td>R093</td>
              <td>Retirar limites de histórias</td>
              <td>Não Permanece</td>
              <td>Depende de 'Inserir forma de pagamento'</td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Login/Cadastro</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R094</td>
              <td>Login via redes sociais (facebook ou twitter)</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R095</td>
              <td>Login via Google</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R096</td>
              <td>Login via E-mail</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R097</td>
              <td>Cadastrar com Google</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R098</td>
              <td>Cadastrar com Facebook</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <th>ID</th>
              <th>Aplicação(visão geral)</th>
              <td></td>
              <td></td>
          </tr>
       <tr>
              <td>R099</td>
              <td>Responsividade</td>
              <td>Não permanece</td>
              <td>Requisito não funcional</td>
          </tr>
       <tr>
              <td>R100</td>
              <td>Portabilidade mobile ios</td>
              <td>Não permanece</td>
              <td>Para implementações futuras</td>
          </tr>
       <tr>
              <td>R101</td>
              <td>Portabilidade mobile android</td>
              <td>Não permanece</td>
              <td>Para implementações futuras</td>
          </tr>
       <tr>
              <td>R102</td>
              <td>Pesquisar artigos por nome</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R103</td>
              <td>Visualizar data de publicação dos artigos</td>
              <td>Permanece</td>
              <td></td>
          </tr>
       <tr>
              <td>R104</td>
              <td>Política de privacidade</td>
              <td>Não permanece</td>
              <td>Requisito não funcional</td>
          </tr>
       <tr>
              <td>R105</td>
              <td>Paleta de cores monocromáticas no site</td>
              <td>Não permanece</td>
              <td>Para implementações futuras</td>
          </tr>
       <tr>
              <td>R106</td>
              <td>Acessar a área de membro</td>
              <td>Não permanece</td>
              <td>Para implementações futuras</td>
          </tr>
       <tr>
              <td>R107</td>
              <td>Visualizar artigos populares</td>
              <td>Permanece</td>
              <td></td>
          </tr>
   </table>
   