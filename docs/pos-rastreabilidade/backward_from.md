## Versionamento de edições
|Data      |        Autor            |           Descrição           |Versão|
|----------|-------------------------|-------------------------------|------|
|13/06/2019| Pedro Rodrigues Pereira | Adição da pagina e introdução | 1.0  |
|18/06/2019| Matheus Blanco | Adição de Elos | 2.0  |
|18/06/2019| Matheus Blanco | Adição de Elos | 3.0  |
|19/06/2019| Matheus Blanco | Adição de Elos | 4.0  |
|21/06/2019|Matheus Blanco|Retirada da tabela temporariamente|5.0|
|24/06/2019|Matheus Blanco |Reinserção das tabelas e refatoração de elos|6.0|


### Introdução

Rastreável é uma característica de sistemas nos quais há uma interligação entre os dados obtidos e as informações geradas. No caso da engenharia de requisitos podemos considerar como rastreabilidade como a caracaterização de relação entre os requisitos e suas fontes ou artefatos criados durante todo o ciclo de vida do software. Essa característa está atrelada intrinsicamente a utilização de uma baseline de requisitos para uma melhor transparência dos requisitos elicitados.

Com a rastreabilidade é possível ver todo o processo evolutivo referente aos requisitos e suas conseguências.
Com isso temos a pré-rastreabilidade como uma projeção de possíveis surgimentos de requisitos e também temos a pós rastreabilidade que será tratada nesse tópico por meio da utilização de algumas técnicas inerentes a ela.

### Metodologia

Para a realização dessa tarefa, em um primeiro momento, fora refatorada a baseline e posteriormente o backlog do produto. Após esse processo de refatoração se tornou possível linkar os requisitos em relação a sua origem, levando em consideração todas as suas ocorrências.


***


### Tabela Backward-from V1.0

[Link para a versão 1 da tabela](https://docs.google.com/spreadsheets/d/1gACKU5xShhvnuP6dCYfcKChXkiPm0cqoJu00qufwBwc/edit?usp=sharing)


### Tabela Backward-from V2.0


[Link para a versão 2 da tabela](https://docs.google.com/spreadsheets/d/1ZyY_F4PT7S0lJi5sz7PbEd6RYt24CnyTrytggcTJZsc/edit?usp=sharing)

### Tabela Backward-from V3.0

<div class="ritz grid-container" dir="ltr">
    <table class="waffle" cellspacing="0" cellpadding="0">
        <tbody>
            <tr style='height:20px;'>
                <th id="0R0" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
            </tr>
            <tr style='height:22px;'>
                <th id="0R1" style="height: 22px;" class="row-headers-background">
                </th>
                <td class="s1" dir="ltr">ID</td>
                <td class="s1" dir="ltr">Requisito</td>
                <td class="s1" dir="ltr">Tipo</td>
                <td class="s1" dir="ltr">Elo</td>
                <td class="s1" dir="ltr">RichPicture</td>
                <td class="s1" dir="ltr">Questionário</td>
                <td class="s1" dir="ltr">StoryTelling e StoryBoard</td>
                <td class="s2" dir="ltr">Brainstorming</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R2" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R001</td>
                <td class="s3" dir="ltr">Responsividade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
                <td class="s3" dir="ltr">StoryBoard Customização de interesses: &quot;...bem mais fácil de colocar os tópicos...&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 2 &quot;William: carregamento eficiente de artigos&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R3" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R002</td>
                <td class="s3" dir="ltr">Portabilidade mobile ios</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s3" dir="ltr">Ponto de vista do leitor<br>(Gabriel)<br><br>Import Story<br>(Pedro)</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
                <td class="s3" dir="ltr">StoryBoard Customização de interesses: &quot;Dá até pra abrir no celular,...&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 2 &quot; Matheus: A aplicação está disponível em plataformas : web e mobile (ios/android)&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R4" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R003</td>
                <td class="s3" dir="ltr">Portabilidade mobile android</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s3" dir="ltr">Ponto de vista do leitor<br>(Gabriel)<br><br>Import Story<br>(Pedro)</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
                <td class="s3" dir="ltr">StoryBoard Customização de interesses: &quot;Dá até pra abrir no celular,...&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 2 &quot; Matheus: A aplicação está disponível em plataformas : web e mobile (ios/android)&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R5" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R004</td>
                <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s3" dir="ltr">EF1</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
                <td class="s3" dir="ltr">StoryBoard Tutorial e seguir escritor: &quot;WOW!!! Tem uma comunidade de React aqui dentro (e com vários tutoriais)&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R6" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R005</td>
                <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s3" dir="ltr">EF2</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s5" dir="ltr">Brainstorming 4 &quot;matheus: ter um registro dos seus textos em seu blog&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R7" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R006</td>
                <td class="s3" dir="ltr">Política de privacidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryBoard Login e cadastro: &quot;Ainda não tenho conta, vou clicar na opção de criar nova conta&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R8" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R007</td>
                <td class="s3" dir="ltr">Identidade Visual</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;parecia mais um site de notícias, com um visal simples, poucas cores&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 2 &quot; Matheus: o design intuitivo e minimalista torna a experiência mais produtiva&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R9" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R008</td>
                <td class="s3" dir="ltr">Alta disponibilidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Com que frequência você importa textos de outras plataformas para o Medium?&quot;
                </td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R10" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R009</td>
                <td class="s3" dir="ltr">Controle de Conteúdo</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?&quot;
                </td>
                <td class="s3" dir="ltr">StoryBoard Customização de interesses: &quot;Ele também te recomenda coisas novas de acordo com seu histórico de leitura&quot;</td>
                <td class="s7" dir="ltr">Brainstorming 3: &quot;William: recomendações de artigos do interesse do leitor&quot;
                </td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R11" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R010</td>
                <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF3</td>
                <td class="s3" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>New Story<br>(Pedro)</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Sobre quais tipos de assunto você escreve?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;criar uma nova história&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;
                </td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R12" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R011</td>
                <td class="s3" dir="ltr">Manutenibilidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s8"></td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R13" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R012</td>
                <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF4</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?&quot;
                </td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;Natália começou a ler, cada vez mais se interessando pelo site&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 3 &quot;Matheus: os usuários podem ver os textos publicados na página de um escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R14" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R013</td>
                <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF5</td>
                <td class="s3" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;salvar o link do rascunho&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R15" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R014</td>
                <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF6</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;após mexer e remexer seu texto&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R16" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R015</td>
                <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF7</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R17" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R016</td>
                <td class="s3" dir="ltr">Ver status</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF8</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;teve menos visualizações e reações do que o esperado&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 4 &quot; Matheus: ver quem deu clap em suas publicações&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R18" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R017</td>
                <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF9</td>
                <td class="s3" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>New Story<br>(Pedro)</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Sobre quais tipos de assunto você escreve?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;criar uma nova história&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;
                </td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R19" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R018</td>
                <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF10</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;salvar o link do rascunho&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R20" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R019</td>
                <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF11</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;Antes de publicar sua primeira história, a qual estava pronta, a escritora novata decidiu compartilhar o texto em seu twitter, salvar o link do rascunho e customizar o link de sua publicação.&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R21" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R020</td>
                <td class="s3" dir="ltr">Visualizar stories publicadas</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF12</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?&quot;
                </td>
                <td class="s3" dir="ltr">StoryBoard Tutorial e seguir escritor: &quot;WOW!!! Tem uma comunidade de React aqui dentro (e com vários tutoriais)&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 3 &quot;Matheus: os usuários podem ver os textos publicados na página de um escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R22" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R021</td>
                <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF13</td>
                <td class="s3" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>Import Story<br>(Pedro)</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Com que frequência você importa textos de outras plataformas para o Medium?&quot;
                </td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;opção de importar uma história&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;
                </td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R23" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R022</td>
                <td class="s3" dir="ltr">Editar story</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF14</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;após mexer e remexer seu texto&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R24" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R023</td>
                <td class="s3" dir="ltr">Deletar story</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF15</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R25" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R024</td>
                <td class="s3" dir="ltr">Aplaudir um texto lido</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF16</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você aplaude (&#39;claps&#39;) as publicações?&quot;
                </td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;pois havia recebido um bom número de “claps”&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 3 &quot;matheus: o leitor poder gostar do texto&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R26" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R025</td>
                <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF17</td>
                <td class="s3" dir="ltr">Ponto de vista do leitor<br>(Guilherme)<br><br>Ponto de vista do leitor<br>(Gabriel)
                </td>
                <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você compartilha as publicações?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;compartilhar o texto em seu twitter&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 3 &quot;matheus: compartilhar o texto&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R27" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R026</td>
                <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF18</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você comenta nas publicações?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;algumas passagens importantes de seu texto haviam sido destacadas e comentadas&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 4 &quot;Pedro: ver comentários de seus textos e responder os comentários de seus textos&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R28" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R027</td>
                <td class="s3" dir="ltr">Escutar podcasts</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF19</td>
                <td class="s3" dir="ltr">Ponto de vista do leitor<br>(Gabriel)</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s5" dir="ltr">Brainstorming 3 &quot;Gabriel: escutar podcasts&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R29" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R028</td>
                <td class="s3" dir="ltr">Seguir escritores</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF20</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryBoard Tutorial e seguir escritor: &quot;E ainda consigo seguir o perfil dos escritores...&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 3 &quot;Matheus: seguir o escritor&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R30" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R029</td>
                <td class="s3" dir="ltr">Seguir usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF21</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryBoard Tutorial e seguir escritor: &quot;consigo seguir o perfil dos escritores&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 3: &quot;Gabriel: Seguir outros usuários&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R31" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R030</td>
                <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF22</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s5" dir="ltr">Brainstorming 3: &quot;William: O leitor recebe as notificações de publicações de seus escritores favoritados</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R32" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R031</td>
                <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF23</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Qual os assuntos pelo quais você se interessa ao acessar o MEDIUM?&quot;
                </td>
                <td class="s3" dir="ltr">StoryBoard Customização de interesses: &quot;, bem mais fácil de colocar os tópicos que você gosta&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 3: &quot;Gabriel: Selecionar tema de artigos&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R33" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R032</td>
                <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF24</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryBoard Tutorial e seguir escritor: &quot;achar vários artigos relacionados aos seus interesses no perfil dele&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 3: &quot;Matheus: os usuários podem ver os textos publicados na página de um escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R34" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R033</td>
                <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF25</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryBoard - Bookmarking: &quot;acho que vou salvar para ler mais tarde&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R35" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R034</td>
                <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF26</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R36" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R035</td>
                <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF27</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s5" dir="ltr">Brainstorming 2: &quot;William: visualizar os perfis de outros usuários&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R37" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R036</td>
                <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF28</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryBoard - Bookmarking: &quot;acho que vou salvar para ler mais tarde</td>
                <td class="s5" dir="ltr">Brainstorming 3: &quot;Matheus: o leitor poder gostar do texto&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R38" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R037</td>
                <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF29</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você comenta nas publicações?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;algumas passagens importantes de seu texto haviam sido destacadas e comentadas&quot;</td>
                <td class="s5" dir="ltr">Brainstorming 4: &quot;Pedro: ver comentários de seus textos e responder os comentários de seus textos&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R39" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R038</td>
                <td class="s3" dir="ltr">Reportar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF30</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Storytelling - Editar Perfil: &quot;lista de publicações e usuários bloqueados&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R40" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R039</td>
                <td class="s3" dir="ltr">Reportar usuário</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF31</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Storytelling - Editar Perfil: &quot;lista de publicações e usuários bloqueados&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R41" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R040</td>
                <td class="s3" dir="ltr">Editar informações de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF32</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Storytelling - Editar Perfil: &quot;Ao lado do seu nome nesta página de perfil, existia um botão chamado “Edit profile” e logo Carlos clicou sobre esse botão.&quot;</td>
                <td class="s7" dir="ltr">Brainstorming 2 &quot;William: editar seu próprio perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R42" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R041</td>
                <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF33</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Storytelling - Editar Perfil: &quot;Após ter editado tudo o que desejava, Carlos clicou no botão chamado “Save” e foi redirecionado para a página que apresentava os seus dados cadastrais, agora editados.&quot;
                </td>
                <td class="s7" dir="ltr">Brainstorming 2 &quot;William: editar seu próprio perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R43" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R042</td>
                <td class="s3" dir="ltr">Visualizar autores seguidos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF34</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryBoard - Tutorial e seguir escritor: &quot;Realmente. E ainda consigo seguir o perfil de escritores dos tutoriais estando logado&quot;</td>
                <td class="s7" dir="ltr">Brainstorming 3 &quot;Gabriel: seguir o escritor&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R44" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R043</td>
                <td class="s3" dir="ltr">Visualizar seguidores</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF35</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Storytelling - Escritor New Story: &quot;Medium, como é chamado o site, é uma plataforma pensada na troca de conhecimentos por seus usuários, a partir de textos técnicos, assuntos atuais, sociais, tecnológicos, psicológicos e até mesmo
                    pesquisas&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R45" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R044</td>
                <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF36</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você aplaude (&#39;claps&#39;) as publicações?&quot;
                </td>
                <td class="s3" dir="ltr">Storytelling - Escritor New Story: &quot;Entretanto, ela estava satisfeita com os resultados, pois havia recebido um bom número de “claps”&quot;</td>
                <td class="s7" dir="ltr">Brainstorming 3 &quot;matheus: ver quem deu clap em suas publicações&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R46" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R045</td>
                <td class="s3" dir="ltr">Visualizar próprio perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF37</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Storytelling - Editar Perfil: &quot;Entre essas opções estava escrita a opção “Profile”, então Carlos clicou sobre essa opção e ao mesmo instante ele foi redirecionado para uma página que apresentava todos os seus dados cadastrais.&quot;</td>
                <td class="s7" dir="ltr">Brainstorming 3 &quot;Matheus acessar o perfil de usuário&quot;</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R47" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R046</td>
                <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF38</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Com que frequência você utiliza as métricas feitas pelo Medium?&quot;
                </td>
                <td class="s3" dir="ltr">Storytelling - Editar Perfil: &quot;Ao começar a ganhar visibilidade em suas publicações, Carlos passou a receber comentários pedindo informações sobre a sua formação acadêmica, assim como o seu nome completo&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R48" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R047</td>
                <td class="s3" dir="ltr">Visualizar marcações feitas</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF39</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">StoryBoard - Bookmarking: &quot;Nossa! O artigo é muito grande, acho que vou salvar para ler mais tarde&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R49" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R048</td>
                <td class="s3" dir="ltr">Criar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF40</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
                <td class="s3" dir="ltr">Storytelling - Escritor New Story: &quot;Natália percebeu que havia mais de uma maneira de se publicar um texto.&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R50" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R049</td>
                <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF41</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
                <td class="s3" dir="ltr">Storytelling - Escritor New Story: &quot;salvar o link do rascunho e customizar o link de sua publicação&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R51" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R050</td>
                <td class="s3" dir="ltr">Editar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF42</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
                <td class="s3" dir="ltr">StoryTelling - Escritor, New Story: &quot;após mexer e remexer seu texto&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R52" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R051</td>
                <td class="s3" dir="ltr">Deletar Publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF43</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R53" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R052</td>
                <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF44</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Qual os assuntos pelo quais você se interessa ao acessar o MEDIUM?&quot;
                </td>
                <td class="s3" dir="ltr">StoryBoard Customização de interesses: &quot;, bem mais fácil de colocar os tópicos que você gosta&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R54" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R053</td>
                <td class="s3" dir="ltr">Deixar de seguir usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF45</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R55" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R054</td>
                <td class="s3" dir="ltr">Deixar de seguir publicações</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF46</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R56" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R055</td>
                <td class="s3">Aivar modo noturno</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF47</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
                <td class="s3" dir="ltr">Storytelling - Configurações: &quot;- Modo nortuno&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R57" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R056</td>
                <td class="s3">Automatizar modo noturno</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF48</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
                <td class="s3" dir="ltr">Storytelling - Configurações: &quot;- Modo nortuno&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:53px;'>
                <th id="0R58" style="height: 53px;" class="row-headers-background">
                </th>
                <td class="s3">R057</td>
                <td class="s3">Editar email padrão</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF49</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;possível alterar o e-mail cadastrado&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 2:<br>&quot;William&quot;,editar seu próprio perfil<br></td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R59" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R058</td>
                <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF50</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
                </td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;configurar o período em que ocorrem as sugestões de artigos&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R60" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R059</td>
                <td class="s3">Desativar sugestão de artigos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF51</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
                </td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;configurar o período em que ocorrem as sugestões de artigos&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R61" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R060</td>
                <td class="s3">Ativar/desativar boletim informativo</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF52</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
                </td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;gerenciar seus boletins informativos&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R62" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R061</td>
                <td class="s3">Selecionar tema do boletim informativo</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF53</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
                </td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;gerenciar seus boletins informativos&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:81px;'>
                <th id="0R63" style="height: 81px;" class="row-headers-background">
                </th>
                <td class="s3">R062</td>
                <td class="s3">Ativar/desativar recomendações de stories</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF54</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s8" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
                </td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;também configurar as recomendações de histórias&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 3: &quot;Gabriel&quot;,selecionar tema de artigo; &quot;Matheus&quot;,Escolher os textos na homepage<br><br></td>
            </tr>
            <tr style='height:92px;'>
                <th id="0R64" style="height: 92px;" class="row-headers-background">
                </th>
                <td class="s3">R063</td>
                <td class="s3">Ativar/desativar notificação por e-mail</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF55</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;notificações de publicações e entre outras&quot;
                </td>
                <td class="s5" dir="ltr">Brainstorming 3: &quot;William&quot;,O leitor recebe as notificações de publicações de seus escritores favoritados<br></td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R65" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R064</td>
                <td class="s3">Ativar/desativar notificação social</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF56</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;gerências de notificações vindas de outros usuários&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R66" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R065</td>
                <td class="s3">Selecionar privacidade de menções</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF57</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;- Segurança&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R67" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R066</td>
                <td class="s3">Desativar menções de usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF58</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;gerências de notificações vindas de outros usuários&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R68" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R067</td>
                <td class="s3">Conectar com redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF59</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;se conectar pelo facebook ou google&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R69" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R068</td>
                <td class="s3">Conectar com Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF60</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;se conectar pelo facebook ou google&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R70" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R069</td>
                <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF61</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;possibilidade de compartilhar via essas redes sociais&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:59px;'>
                <th id="0R71" style="height: 59px;" class="row-headers-background">
                </th>
                <td class="s3">R070</td>
                <td class="s3">Editar nome de usuário para menção</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF62</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação:&quot;Edição de nome de perfil&quot;<br></td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:50px;'>
                <th id="0R72" style="height: 50px;" class="row-headers-background">
                </th>
                <td class="s3">R071</td>
                <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF63</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;Privacidade&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R73" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R072</td>
                <td class="s3">Gerenciar usuários bloqueados</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF64</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;Usuários bloqueados&quot;<br></td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:49px;'>
                <th id="0R74" style="height: 49px;" class="row-headers-background">
                </th>
                <td class="s3">R073</td>
                <td class="s3">Fazer download de meus dados do Medium</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF65</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;a incrível opção de fazer o download de seus dados&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:83px;'>
                <th id="0R75" style="height: 83px;" class="row-headers-background">
                </th>
                <td class="s3">R074</td>
                <td class="s3">Deslogar de outras sessões </td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF66</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;podia se deslogar de outras sessões ativas, desativar ou deletar sua conta&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:93px;'>
                <th id="0R76" style="height: 93px;" class="row-headers-background">
                </th>
                <td class="s3">R075</td>
                <td class="s3">Desativar conta</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF67</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;podia se deslogar de outras sessões ativas, desativar ou deletar sua conta&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:88px;'>
                <th id="0R77" style="height: 88px;" class="row-headers-background">
                </th>
                <td class="s3">R076</td>
                <td class="s3">Deletar conta</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF68</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;podia se deslogar de outras sessões ativas, desativar ou deletar sua conta&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:55px;'>
                <th id="0R78" style="height: 55px;" class="row-headers-background">
                </th>
                <td class="s3">R077</td>
                <td class="s3">Visualizar tutorial das áreas da aplicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF69</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;Tutoriais da aplicação&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:54px;'>
                <th id="0R79" style="height: 54px;" class="row-headers-background">
                </th>
                <td class="s3">R078</td>
                <td class="s3">Acessar glossário MEDIUM</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF70</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;Glossários&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:65px;'>
                <th id="0R80" style="height: 65px;" class="row-headers-background">
                </th>
                <td class="s3">R079</td>
                <td class="s3">Responder questionário de satisfação da aplicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF71</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;Perguntas de satisfação&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:56px;'>
                <th id="0R81" style="height: 56px;" class="row-headers-background">
                </th>
                <td class="s3">R080</td>
                <td class="s3">Pesquisar tópico de ajuda</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF72</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Usuário, Configurando a aplicação: &quot;Ajuda&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:69px;'>
                <th id="0R82" style="height: 69px;" class="row-headers-background">
                </th>
                <td class="s3">R081</td>
                <td class="s3">Escolher plano de assinatura membership</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF73</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:52px;'>
                <th id="0R83" style="height: 52px;" class="row-headers-background">
                </th>
                <td class="s3">R082</td>
                <td class="s3">Inserir forma de pagamento do medium membership</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF74</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:159px;'>
                <th id="0R84" style="height: 159px;" class="row-headers-background">
                </th>
                <td class="s3">R083</td>
                <td class="s3">Login via redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF75</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Login e Cadastro: &quot;legal poder logar com facebook, google, twitter ou meu e-mail.&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:161px;'>
                <th id="0R85" style="height: 161px;" class="row-headers-background">
                </th>
                <td class="s3">R084</td>
                <td class="s3">Login via Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF76</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Login e Cadastro: &quot;legal poder logar com facebook, google, twitter ou meu e-mail.&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:211px;'>
                <th id="0R86" style="height: 211px;" class="row-headers-background">
                </th>
                <td class="s3">R085</td>
                <td class="s3">Login via E-mail</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF77</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Login e Cadastro: &quot;legal poder logar com facebook, google, twitter ou meu e-mail.&quot;
                </td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:151px;'>
                <th id="0R87" style="height: 151px;" class="row-headers-background">
                </th>
                <td class="s3">R086</td>
                <td class="s3">Cadastrar com Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF78</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Login e Cadastro: &quot;Opa, opção de cadastro com google ou facebook.&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:135px;'>
                <th id="0R88" style="height: 135px;" class="row-headers-background">
                </th>
                <td class="s3">R087</td>
                <td class="s3">Cadastrar com Facebook</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF79</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s3" dir="ltr">Login e Cadastro: &quot;Opa, opção de cadastro com google ou facebook.&quot;</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R89" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R088</td>
                <td class="s3">Segurança</td>
                <td class="s3" dir="ltr">Não Funcional</td>
                <td class="s8">EF80</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R90" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R089</td>
                <td class="s3">Desempenho</td>
                <td class="s3" dir="ltr">Não Funcional</td>
                <td class="s8"></td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s4" dir="ltr">-</td>
                <td class="s6" dir="ltr">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R91" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s9" dir="ltr"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R92" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s11" dir="ltr"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R93" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s1" dir="ltr">ID</td>
                <td class="s1" dir="ltr">Requisito</td>
                <td class="s1" dir="ltr">Tipo</td>
                <td class="s1" dir="ltr">Elo</td>
                <td class="s12">Instrospecção</td>
                <td class="s12">Cenários</td>
                <td class="s12">Léxicos</td>
                <td class="s13">Casos de uso</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R94" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R001</td>
                <td class="s3" dir="ltr">Responsividade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s8">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R95" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R002</td>
                <td class="s3" dir="ltr">Portabilidade mobile ios</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R96" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R003</td>
                <td class="s3" dir="ltr">Portabilidade mobile android</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R97" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R004</td>
                <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s3" dir="ltr">EF1</td>
                <td class="s14">-</td>
                <td class="s8">Pesquisa por artigo</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC: UC03</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R98" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R005</td>
                <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s3" dir="ltr">EF2</td>
                <td class="s8">Relato de introspecção 1: Possibilitar que o usuário possa ver a data de publicação do artigo
                </td>
                <td class="s8">Leitura de texto</td>
                <td class="s8">Léxico Storie</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R99" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R006</td>
                <td class="s3" dir="ltr">Política de privacidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s8">Relato de introspecção 1: página do termo de política de privacidade</td>
                <td class="s14">-</td>
                <td class="s8">Léxico About</td>
                <td class="s16">UC Configurar perfil: UC09</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R100" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R007</td>
                <td class="s3" dir="ltr">Identidade Visual</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s8">Relato de introspecção 1: permite ao usuário navegar pela home page conseguindo entender o significado de todas as áreas mostradas no site.</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s17">UC Área comum</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R101" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R008</td>
                <td class="s3" dir="ltr">Alta disponibilidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R102" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R009</td>
                <td class="s3" dir="ltr">Controle de Conteúdo</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s8">Relato de introspecção 6: deve gerar uma zona de conforto de conteúdos ao leitor.</td>
                <td class="s8">Customizar interesses</td>
                <td class="s8">Léxico Content</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R103" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R010</td>
                <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF3</td>
                <td class="s8">Relato de introspecção 3: Usuário logado, com o intuito de criar uma nova história para publicar
                </td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Series</td>
                <td class="s16">UC Series: UC-5 - Criar Séries</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R104" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R011</td>
                <td class="s3" dir="ltr">Manutenibilidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s8"></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R105" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R012</td>
                <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF4</td>
                <td class="s8">Relato de introspecção 1: apresenta ao usuário o acesso a uma variedade de artigos expostos na home page</td>
                <td class="s8">Leitura de texto</td>
                <td class="s8">Léxico Series</td>
                <td class="s16">UC Series: UC-4 - Visualizar Published</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R106" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R013</td>
                <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF5</td>
                <td class="s14">-</td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Series</td>
                <td class="s16">UC series - UC03 - visualizar drafts</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R107" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R014</td>
                <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF6</td>
                <td class="s8">Relato de introspecção 3: vi - O usuário pode então editar o rascunho criado, ou simplemesmente apagá-lo.
                </td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Series</td>
                <td class="s16">UC Series: UC08 - Editar rascunho</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R108" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R015</td>
                <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF7</td>
                <td class="s8">Relato de introspecção 3: vi - O usuário pode então editar o rascunho criado, ou simplemesmente apagá-lo.
                </td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Series</td>
                <td class="s17">UC Series</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R109" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R016</td>
                <td class="s3" dir="ltr">Ver status</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF8</td>
                <td class="s8">Relato de introspecção 1: Poder ver o status do usuário;</td>
                <td class="s14">-</td>
                <td class="s8">Léxico Status</td>
                <td class="s16">UC Área comum: UC09 - Editar perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R110" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R017</td>
                <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF9</td>
                <td class="s8">Relato de introspecção 3: Usuário logado, com o intuito de criar uma nova história para publicar
                </td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC stories: UC06 - Escrever Nova story</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R111" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R018</td>
                <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF10</td>
                <td class="s8">Relato de introspecção 3: vi - O usuário pode então editar o rascunho criado, ou simplemesmente apagá-lo.
                </td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC stories: UC03 - Visualizar drafts</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R112" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R019</td>
                <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF11</td>
                <td class="s8">Relato de introspecção 3: vi - O usuário pode então editar o rascunho criado, ou simplemesmente apagá-lo.
                </td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC stories: UC03 - Visualizar drafts</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R113" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R020</td>
                <td class="s3" dir="ltr">Visualizar stories publicadas</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF12</td>
                <td class="s8">Relato de introspecção 1: Página inicial com variedade de artigos</td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC stories: UC04 - Visualizar publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R114" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R021</td>
                <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF13</td>
                <td class="s8">Relato de introspecção 3: Possibilidade de importar um texto de sites externos ao medium;</td>
                <td class="s8">Importar um storie</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC stories: UC05 - Importar uma story</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R115" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R022</td>
                <td class="s3" dir="ltr">Editar story</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF14</td>
                <td class="s8">Relato de introspecção 3: vi - O usuário pode então editar o rascunho criado, ou simplemesmente apagá-lo.
                </td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC stories: UC07 - Editar draft</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R116" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R023</td>
                <td class="s3" dir="ltr">Deletar story</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF15</td>
                <td class="s8">Relato de introspecção 3: vi - O usuário pode então editar o rascunho criado, ou simplemesmente apagá-lo.
                </td>
                <td class="s8">Criar um novo Storie</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC stories: UC08 - Excluir draft</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R117" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R024</td>
                <td class="s3" dir="ltr">Aplaudir um texto lido</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF16</td>
                <td class="s8">Relato de introspecção 1: Possibilitar que um usuário aplauda um texto;</td>
                <td class="s8">Dar Claps</td>
                <td class="s8">Léxico Clap</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R118" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R025</td>
                <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF17</td>
                <td class="s8">Relato de introspecção 3: Poder enviar e compartilhar seu texto sem a necessidade de um agente terceiro para fazê-lo;</td>
                <td class="s8"> Compartilhar publicação</td>
                <td class="s8">Léxico Share</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R119" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R026</td>
                <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF18</td>
                <td class="s8">Relato de introspecção 1: * Possibilitar a escuta de podcasts;<br></td>
                <td class="s8">Comentar publicação</td>
                <td class="s8">Léxico Response</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R120" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R027</td>
                <td class="s3" dir="ltr">Escutar podcasts</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF19</td>
                <td class="s8">Relato de introspecção 1: * Possibilitar a adição de comentários a uma publicação.<br></td>
                <td class="s8">Leitura de texto</td>
                <td class="s8">Léxico Storie</td>
                <td class="s16">UC Área comum: UC04 - Escutar Podcasts</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R121" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R028</td>
                <td class="s3" dir="ltr">Seguir escritores</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF20</td>
                <td class="s8">Relato de introspecção 6: Deve ser capaz de deixar de seguir Blogs e escritores</td>
                <td class="s8">Seguir usuário</td>
                <td class="s8">Léxico Storie</td>
                <td class="s17">UC Área comum</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R122" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R029</td>
                <td class="s3" dir="ltr">Seguir usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF21</td>
                <td class="s8">Relato de introspecção 6: Deve ser capaz de deixar de seguir Blogs e escritores</td>
                <td class="s8">Seguir usuário</td>
                <td class="s8">Léxico Following</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R123" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R030</td>
                <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF22</td>
                <td class="s8">Relato de introspecção 6: Deve ser capaz de deixar de seguir Blogs e escritores</td>
                <td class="s8">Configurar notificações</td>
                <td class="s8">Léxico Digest e Léxico Newsletter</td>
                <td class="s16">UC Configurar perfil: UC03 e UC04</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R124" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R031</td>
                <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF23</td>
                <td class="s18">Introspecção 1: Possibilitar que o usuário solicite ver artigos com temas relacionados aos artigos expostos na página principal;</td>
                <td class="s8">Pesquisa por artigo</td>
                <td class="s8">Léxico Search e Léxico Tag</td>
                <td class="s16">UC Área comum: UC07 - Visualizar artigos por categoria</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R125" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R032</td>
                <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF24</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">Léxico Following</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R126" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R033</td>
                <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF25</td>
                <td class="s8">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto em que cada artigo salvo foi
                    fechado;&quot;
                </td>
                <td class="s8">Criar um novo Bookmark</td>
                <td class="s8">Léxico Bookmark</td>
                <td class="s16">UC Bookmark: UC03 - Recuperar textos marcados</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R127" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R034</td>
                <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF26</td>
                <td class="s8">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto em que cada artigo salvo foi
                    fechado;&quot;
                </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Bookmark: UC03 - Recuperar textos marcados</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R128" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R035</td>
                <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF27</td>
                <td class="s14">-</td>
                <td class="s8">Seguir usuário</td>
                <td class="s8">Léxico Profile</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R129" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R036</td>
                <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF28</td>
                <td class="s8">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto em que cada artigo salvo foi
                    fechado;&quot;
                </td>
                <td class="s8">Criar um novo Bookmark</td>
                <td class="s8">Léxico Bookmark</td>
                <td class="s16">UC Bookmark: UC06 - Marcar texto com bookmark</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R130" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R037</td>
                <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF29</td>
                <td class="s14">-</td>
                <td class="s8">Comentar publicação</td>
                <td class="s8">Léxico Response</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R131" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R038</td>
                <td class="s3" dir="ltr">Reportar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF30</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s17">UC Configurar perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R132" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R039</td>
                <td class="s3" dir="ltr">Reportar usuário</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF31</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Configurar perfil: UC10 - Alterar usuários bloqueados</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R133" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R040</td>
                <td class="s3" dir="ltr">Editar informações de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF32</td>
                <td class="s14">-</td>
                <td class="s8">Editar perfil</td>
                <td class="s8">Léxico Edit e Léxico Profile</td>
                <td class="s16">UC Área comum: UC09 - Editar perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R134" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R041</td>
                <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF33</td>
                <td class="s14">-</td>
                <td class="s8">Editar perfil</td>
                <td class="s8">Léxico Edit e Léxico Profile</td>
                <td class="s16">UC Área comum: UC09 - Editar perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R135" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R042</td>
                <td class="s3" dir="ltr">Visualizar autores seguidos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF34</td>
                <td class="s14">-</td>
                <td class="s8">Deixar de seguir usuário</td>
                <td class="s8">Léxico Following</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R136" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R043</td>
                <td class="s3" dir="ltr">Visualizar seguidores</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF35</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">Léxico Followers</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R137" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R044</td>
                <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF36</td>
                <td class="s14">-</td>
                <td class="s8">Dar clap</td>
                <td class="s8">Léxico Clap</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R138" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R045</td>
                <td class="s3" dir="ltr">Visualizar próprio perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF37</td>
                <td class="s14">-</td>
                <td class="s8">Editar perfil</td>
                <td class="s8">Léxico Profile</td>
                <td class="s16">UC Área comum: UC09 - Editar perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R139" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R046</td>
                <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF38</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R140" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R047</td>
                <td class="s3" dir="ltr">Visualizar marcações feitas</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF39</td>
                <td class="s14">-</td>
                <td class="s8">Criar um novo Bookmark</td>
                <td class="s8">Léxico Bookmark</td>
                <td class="s16">UC Bookmark: UC01 - Visualizar bookmarks</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R141" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R048</td>
                <td class="s3" dir="ltr">Criar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF40</td>
                <td class="s14">-</td>
                <td class="s8">Criar um storie</td>
                <td class="s8">Léxico Stories</td>
                <td class="s16">UC stories: UC06 - Escrever Nova story</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R142" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R049</td>
                <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF41</td>
                <td class="s14">-</td>
                <td class="s8">Criar um storie</td>
                <td class="s8">Léxico Stories</td>
                <td class="s16">UC stories: UC03 - Visualizar drafts</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R143" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R050</td>
                <td class="s3" dir="ltr">Editar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF42</td>
                <td class="s14">-</td>
                <td class="s8">Criar um storie</td>
                <td class="s8">Léxico Stories</td>
                <td class="s16">UC stories: UC09 - editar publicação</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R144" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R051</td>
                <td class="s3" dir="ltr">Deletar Publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF43</td>
                <td class="s14">-</td>
                <td class="s8">Criar um storie</td>
                <td class="s8">Léxico Stories</td>
                <td class="s19">UC stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R145" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R052</td>
                <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF44</td>
                <td class="s8">Relato de instrospecção 6: &quot;Deve mostrar escritores sugeridos para os interesses do leitor.&quot;
                </td>
                <td class="s8">Customizar interesses</td>
                <td class="s14">-</td>
                <td class="s16">UC Cadastro: UC04 - Selecionar tópicos de interesse</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R146" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R053</td>
                <td class="s3" dir="ltr">Deixar de seguir usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF45</td>
                <td class="s8">Relato de instrospecção 6: &quot;Deve ser capaz de deixar de seguir Blogs e escritores.&quot;
                </td>
                <td class="s8">Deixar de seguir usuário</td>
                <td class="s8">Léxico Following</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R147" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R054</td>
                <td class="s3" dir="ltr">Deixar de seguir publicações</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF46</td>
                <td class="s8">Relato de introspecção 3: &quot;Poder tornar o texto público ou privado para apenas um número definido de leitores;&quot;</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R148" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R055</td>
                <td class="s3">Aivar modo noturno</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF47</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">Léxico Night Mode</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R149" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R056</td>
                <td class="s3">Automatizar modo noturno</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF48</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">Léxico Night Mode</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R150" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R057</td>
                <td class="s3">Editar email padrão</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF49</td>
                <td class="s14">-</td>
                <td class="s8">C04: Editar perfil</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R151" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R058</td>
                <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF50</td>
                <td class="s14">-</td>
                <td class="s8">C10:Configurar notificações de e-mail<br></td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R152" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R059</td>
                <td class="s3">Desativar sugestão de artigos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF51</td>
                <td class="s14">-</td>
                <td class="s8">C10:Configurar notificações de e-mail<br></td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R153" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R060</td>
                <td class="s3">Ativar/desativar boletim informativo</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF52</td>
                <td class="s8">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação: Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
                <td class="s8">C10:Configurar notificações de e-mail<br></td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R154" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R061</td>
                <td class="s3">Selecionar tema do boletim informativo</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF53</td>
                <td class="s8">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação: Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
                <td class="s8">C10:Configurar notificações de e-mail<br></td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R155" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R062</td>
                <td class="s3">Ativar/desativar recomendações de stories</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF54</td>
                <td class="s14">-</td>
                <td class="s8">C10:Configurar notificações de e-mail<br></td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R156" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R063</td>
                <td class="s3">Ativar/desativar notificação por e-mail</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF55</td>
                <td class="s8">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação: Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R157" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R064</td>
                <td class="s3">Ativar/desativar notificação social</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF56</td>
                <td class="s14">-</td>
                <td class="s18">Configurar notificações de e-mail</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R158" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R065</td>
                <td class="s3">Selecionar privacidade de menções</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF57</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R159" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R066</td>
                <td class="s3">Desativar menções de usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF58</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R160" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R067</td>
                <td class="s3">Conectar com redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF59</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC01 - Efetuar cadastro</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R161" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R068</td>
                <td class="s3">Conectar com Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF60</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC01 - Efetuar cadastro</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R162" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R069</td>
                <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF61</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R163" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R070</td>
                <td class="s3">Editar nome de usuário para menção</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF62</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R164" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R071</td>
                <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF63</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R165" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R072</td>
                <td class="s3">Gerenciar usuários bloqueados</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF64</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R166" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R073</td>
                <td class="s3">Fazer download de meus dados do Medium</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF65</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R167" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R074</td>
                <td class="s3">Deslogar de outras sessões </td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF66</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R168" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R075</td>
                <td class="s3">Desativar conta</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF67</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R169" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R076</td>
                <td class="s3">Deletar conta</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF68</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s16">UC Área comum: UC10 - Configurar preferências</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R170" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R077</td>
                <td class="s3">Visualizar tutorial das áreas da aplicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF69</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s17">Área comum</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R171" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R078</td>
                <td class="s3">Acessar glossário MEDIUM</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF70</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s17">Área comum</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R172" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R079</td>
                <td class="s3">Responder questionário de satisfação da aplicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF71</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s17">Área comum</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R173" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R080</td>
                <td class="s3">Pesquisar tópico de ajuda</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF72</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s17">Área comum</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R174" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R081</td>
                <td class="s3">Escolher plano de assinatura membership</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF73</td>
                <td class="s14">-</td>
                <td class="s8">C05: Premium</td>
                <td class="s14">-</td>
                <td class="s16">Acesso ao Medium Membership: UC01 - Selecionar plano</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R175" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R082</td>
                <td class="s3">Inserir forma de pagamento do medium membership</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF74</td>
                <td class="s14">-</td>
                <td class="s8">C05: Premium</td>
                <td class="s14">-</td>
                <td class="s16">Acesso ao Medium Membership: UC04 - Selecionar método de pagamento</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R176" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R083</td>
                <td class="s3">Login via redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF75</td>
                <td class="s8">Relato de introspecção 2:Consegue facilmente identificar a área de acesso ao login, conseguindo se conectar via integração de redes sociais (Facebook e Twitter), integração com sua conta do Google ou inserindo seu e-mail cadastrado;</td>
                <td class="s8">C07:login</td>
                <td class="s14">-</td>
                <td class="s16">Login: UC02, UC04</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R177" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R084</td>
                <td class="s3">Login via Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF76</td>
                <td class="s8">Relato de introspecção 2:Consegue facilmente identificar a área de acesso ao login, conseguindo se conectar via integração de redes sociais (Facebook e Twitter), integração com sua conta do Google ou inserindo seu e-mail cadastrado;</td>
                <td class="s8">C07:login</td>
                <td class="s14">-</td>
                <td class="s16">Login: UC03 - Integrar via conta do Google</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R178" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R085</td>
                <td class="s3">Login via E-mail</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF77</td>
                <td class="s8">Relato de introspecção 2:Consegue facilmente identificar a área de acesso ao login, conseguindo se conectar via integração de redes sociais (Facebook e Twitter), integração com sua conta do Google ou inserindo seu e-mail cadastrado;</td>
                <td class="s8">C07:login</td>
                <td class="s14">-</td>
                <td class="s16">Login: UC05 - Login via e-mail</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R179" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R086</td>
                <td class="s3">Cadastrar com Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF78</td>
                <td class="s8">Relato de introspecção 2:Consegue facilmente encontrar a área de cadastro, sendo possível somente com o cadastro via integração com o Google ou Facebook;</td>
                <td class="s8">C06:Cadastro</td>
                <td class="s14">-</td>
                <td class="s16">Cadastro de usuário: UC02 - Integrar via Conta do Google</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R180" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R087</td>
                <td class="s3">Cadastrar com Facebook</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF79</td>
                <td class="s8">Relato de introspecção 2:Consegue facilmente encontrar a área de cadastro, sendo possível somente com o cadastro via integração com o Google ou Facebook;</td>
                <td class="s8">C06:Cadastro</td>
                <td class="s14">-</td>
                <td class="s16">Cadastro de usuário: UC03 - Abrir modal com informações de login</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R181" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R088</td>
                <td class="s3">Segurança</td>
                <td class="s3" dir="ltr">Não Funcional</td>
                <td class="s8">EF80</td>
                <td class="s14">-</td>
                <td class="s8">C06 - Cadastro e C07 - Login</td>
                <td class="s14">-</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R182" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R089</td>
                <td class="s3">Desempenho</td>
                <td class="s3" dir="ltr">Não Funcional</td>
                <td class="s8"></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s15">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R183" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
                <td class="s10"></td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R184" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
                <td class="s0"></td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R185" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s1" dir="ltr">ID</td>
                <td class="s1" dir="ltr">Requisito</td>
                <td class="s1" dir="ltr">Tipo</td>
                <td class="s1" dir="ltr">Elo</td>
                <td class="s12" dir="ltr">Especificação</td>
                <td class="s12">Product Backlog</td>
                <td class="s12">NFR</td>
                <td class="s12">I*</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R186" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R001</td>
                <td class="s3" dir="ltr">Responsividade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s14">-</td>
                <td class="s8">US 048 - Usuário: Desejo visualizar as páginas da plataforma em questão de forma responsiva</td>
                <td class="s8">NFR Iteroperabilidade: &quot;Responsividade&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R187" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R002</td>
                <td class="s3" dir="ltr">Portabilidade mobile ios</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s14">-</td>
                <td class="s8">US 049 - Usuário: Poder acessar a aplicação via dispositivo IOS</td>
                <td class="s8">NFR Iteroperabilidade: &quot;Portabilidade&quot;<br><br>NFR Usabilidade: &quot;Ter suporte mobile&quot;
                </td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R188" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R003</td>
                <td class="s3" dir="ltr">Portabilidade mobile android</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s14">-</td>
                <td class="s8">US 050 - Usuário: Poder acessar a aplicação via dispositivo Android</td>
                <td class="s8">NFR Iteroperabilidade: &quot;Portabilidade&quot;<br><br>NFR Usabilidade: &quot;Ter suporte mobile&quot;
                </td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R189" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R004</td>
                <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s3" dir="ltr">EF1</td>
                <td class="s8">UC03-Pesquisar artigo: 2-Usuário/Visitante insere o termo a ser pesquisado </td>
                <td class="s8">US 047 - Usuário: Pesquisar por nome de artigo</td>
                <td class="s14">-</td>
                <td class="s8">i* Pesquisar conteúdo: task - lupa de pesquisa seja visível</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R190" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R005</td>
                <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s3" dir="ltr">EF2</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R191" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R006</td>
                <td class="s3" dir="ltr">Política de privacidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s8">UC17-Pagar via cartão de crédito: No passo 1,2 e 3 pode haver inconsistência nos dados inseridos o que impossibilita a execução dos próximos passos</td>
                <td class="s8">US 020 - Usuário: Selecionar privacidade de menções</td>
                <td class="s8">NFR Controle de Qualidade: &quot;Política de postagens&quot;</td>
                <td class="s8">i* Configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R192" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R007</td>
                <td class="s3" dir="ltr">Identidade Visual</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">NFR Usabilidade: &quot;Identidade visual</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R193" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R008</td>
                <td class="s3" dir="ltr">Alta disponibilidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s8">UC28-Visualizar Stories:Usuário deve estar conectado à internet, ser cadastrado na plataforma Medium e estar com o login efetuado no Medium.<br></td>
                <td class="s8">US 071 - Usuário: Visualizar storie</td>
                <td class="s8">NFR Confiabilidade: &quot;Alta disponilidade&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R194" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R009</td>
                <td class="s3" dir="ltr">Controle de Conteúdo</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s3" dir="ltr"></td>
                <td class="s8">UC05-Ler artigo: Funcionalidade responsável por possibilitar a leitura de um artigona plataforma Medium.
                </td>
                <td class="s8">US 009 - Usuário: selecionar/remover tópicos de interesse</td>
                <td class="s8">NFR Controle de Qualidade</td>
                <td class="s8">I* Customização de interesses</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R195" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R010</td>
                <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF3</td>
                <td class="s8">UC23 - Criar series: 2-Usuário cria a serie, incluindo texto, imagens
                    <br></td>
                <td class="s8">US 059 - Usuário Escritor: Criar uma nova Serie</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R196" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R011</td>
                <td class="s3" dir="ltr">Manutenibilidade</td>
                <td class="s3" dir="ltr">Não funcional</td>
                <td class="s8"></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">NFR Manutenibilidade</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R197" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R012</td>
                <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF4</td>
                <td class="s8">UC20-Visualizar Series: Funcionalidade responsável por disponibilizar uma página que mostra as series criadas como rascunho ou publicadas.
                    <br></td>
                <td class="s8">US 071 - Usuário: Visualizar storie</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R198" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R013</td>
                <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF5</td>
                <td class="s8">UC23 - Criar series: Usuário poderá rascunhar e publicar a história criada
                    <br></td>
                <td class="s8">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R199" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R014</td>
                <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF6</td>
                <td class="s8">UC23 - Criar series: Usuário poderá rascunhar e publicar a história criada
                    <br></td>
                <td class="s8">US 060 - Usuário Escritor: Editar uma Serie existente</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R200" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R015</td>
                <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF7</td>
                <td class="s8">UC36-Excluir Publicação: Usuário terá a sua publicação excluída.
                    <br></td>
                <td class="s8">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R201" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R016</td>
                <td class="s3" dir="ltr">Ver status</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF8</td>
                <td class="s8">UC20-Visualizar Series: Funcionalidade responsável por disponibilizar uma página que mostra as series criadas como rascunho ou publicadas.
                    <br></td>
                <td class="s8">US 034 - Usuário: visualizar seguidores</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R202" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R017</td>
                <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF9</td>
                <td class="s8">UC32-Escrever uma nova Story: Funcionalidade responsável por permitir que um usuário crie uma nova story.<br></td>
                <td class="s8">US 063 - Usuário Escritor: Escrever &#39;new storie&#39;</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R203" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R018</td>
                <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF10</td>
                <td class="s8">UC32-Escrever uma nova Story: [FA01] UC29-Visualizar Drafts.</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R204" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R019</td>
                <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF11</td>
                <td class="s8">UC32-Escrever uma nova Story: [FA01] UC29-Visualizar Drafts.</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R205" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R020</td>
                <td class="s3" dir="ltr">Visualizar stories publicadas</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF12</td>
                <td class="s8">UC28-Visualizar Stories:Funcionalidade responsável por mostrar uma aŕea com todos os rascunhos e publicações de stories de um usuário.</td>
                <td class="s8">US 071 - Usuário: Visualizar storie</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories e i* Customização de interesses</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R206" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R021</td>
                <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF13</td>
                <td class="s8">UC31-Importar uma Story: Funcionalidade responsável por permitir que um usuário publique uma story já publicada em qualquer outro site.</td>
                <td class="s8">US 064 - Usuário Escritor: Importar &#39;storie&#39;</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R207" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R022</td>
                <td class="s3" dir="ltr">Editar story</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF14</td>
                <td class="s8">UC35-Editar Publicação: Funcionalidade responsável por permitir que um usuário edite uma publicação.
                    <br></td>
                <td class="s8">US 060 - Usuário Escritor: Editar uma Serie existente</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R208" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R023</td>
                <td class="s3" dir="ltr">Deletar story</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF15</td>
                <td class="s8">UC36-Excluir Publicação: Funcionalidade responsável por permitir que um usuário exclua uma publicação.
                    <br></td>
                <td class="s8">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R209" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R024</td>
                <td class="s3" dir="ltr">Aplaudir um texto lido</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF16</td>
                <td class="s14">-</td>
                <td class="s8">US 065 - Usuário: Aplaudir um texto lido</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R210" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R025</td>
                <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF17</td>
                <td class="s14">-</td>
                <td class="s8">US 066 - Usuário: Compartilhar texto lido no Facebook ou Instagram</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R211" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R026</td>
                <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF18</td>
                <td class="s14">-</td>
                <td class="s8">US 067 - Usuário: Comentar no corpo do texto</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R212" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R027</td>
                <td class="s3" dir="ltr">Escutar podcasts</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF19</td>
                <td class="s8">UC04-Escutar podcast: Funcionalidade responsável pela possibilidade de escutar um podcast.
                    <br></td>
                <td class="s8">US 069 - Usuário: Escutar publicação</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R213" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R028</td>
                <td class="s3" dir="ltr">Seguir escritores</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF20</td>
                <td class="s14">-</td>
                <td class="s8">US 025 - Usuário: Seguir escritores</td>
                <td class="s14">-</td>
                <td class="s8">i* Pesquisar conteúdo</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R214" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R029</td>
                <td class="s3" dir="ltr">Seguir usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF21</td>
                <td class="s14">-</td>
                <td class="s8">US 025 - Usuário: Seguir usuários</td>
                <td class="s14">-</td>
                <td class="s8">i* Pesquisar conteúdo</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R215" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R030</td>
                <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF22</td>
                <td class="s8">UC10-Configurar preferências: Funcionalidade responsável por exibir configurações da aplicação na plataforma web.
                    <br></td>
                <td class="s8">US 019 - Usuário: Ativar/desativar notificação por e-mail </td>
                <td class="s8">NFR Controle de Qualidade</td>
                <td class="s8">i* Configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R216" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R031</td>
                <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF23</td>
                <td class="s8">UC03 - Pesquisar artigo: Funcionalidade responsável por realizar pesquisa de artigos na plataforma Medium.
                    <br></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s18">i* Pesquisar conteúdo e i* Customização de interesses</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R217" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R032</td>
                <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF24</td>
                <td class="s8">UC30 - Visualizar Publicações: Funcionalidade responsável por mostrar todos as Publicações de um usuário.
                    <br></td>
                <td class="s8">US 027 - Usuário: Visualizar textos publicados de um escritor em específico</td>
                <td class="s14">-</td>
                <td class="s8">i* Pesquisar conteúdo</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R218" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R033</td>
                <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF25</td>
                <td class="s14">-</td>
                <td class="s8">US 030 - Usuário: Favoritar Publicação</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R219" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R034</td>
                <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF26</td>
                <td class="s14">-</td>
                <td class="s8">US 030 - Usuário: Favoritar Publicação</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R220" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R035</td>
                <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF27</td>
                <td class="s8">UC03 - Pesquisar artigo: 3-Usuário/Visitante recebe como resultado um ou mais artigos para leitura
                    <br></td>
                <td class="s8">US 029 - Usuário: Visualizar perfis de outros usuários</td>
                <td class="s14">-</td>
                <td class="s8">i* Pesquisar conteúdo</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R221" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R036</td>
                <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF28</td>
                <td class="s14">-</td>
                <td class="s8">US 030 - Usuário: Favoritar Publicação</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R222" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R037</td>
                <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF29</td>
                <td class="s8">UC30 - Visualizar Publicações: [FP01] Este fluxo se inicia quando o usuário deseja visualizar a área com todos as publicações feitas por ele:</td>
                <td class="s8">US 031 - Usuário: Visualizar comentários da publicação</td>
                <td class="s14">-</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R223" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R038</td>
                <td class="s3" dir="ltr">Reportar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF30</td>
                <td class="s8">UC10-Configurar preferências: Usuário modifica o que achar necessário</td>
                <td class="s8">US 032 - Usuário: Reportar publicação</td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s8">i* Configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R224" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R039</td>
                <td class="s3" dir="ltr">Reportar usuário</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF31</td>
                <td class="s8">UC10-Configurar preferências: Usuário modifica o que achar necessário</td>
                <td class="s8">US 033 - Bloquear usuário</td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s8">i* Configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R225" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R040</td>
                <td class="s3" dir="ltr">Editar informações de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF32</td>
                <td class="s8">UC09 - Editar perfil: Funcionalidade responsável por possibilitar a edição do perfil de usuário Medium.
                    <br></td>
                <td class="s8">US 043 - Usuário: Editar informações de perfil</td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s8">i* Perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R226" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R041</td>
                <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF33</td>
                <td class="s8">UC09 - Editar perfil: 7-Usuário clica em &#39;save&#39; - No passo 7 do fluxo principal, há a opção de cancelar edição
                    <br></td>
                <td class="s8">US 043 - Usuário: Editar informações de perfil</td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s8">i* Perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R227" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R042</td>
                <td class="s3" dir="ltr">Visualizar autores seguidos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF34</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">i* Pesquisar conteúdo</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R228" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R043</td>
                <td class="s3" dir="ltr">Visualizar seguidores</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF35</td>
                <td class="s14">-</td>
                <td class="s8">US 032 - Usuário: Visualizar seguidores</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R229" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R044</td>
                <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF36</td>
                <td class="s8">UC30 - Visualizar Publicações: 3-O sistema retorna para a visualização do usuário todos as publicações feitas pelo usuário.
                    <br></td>
                <td class="s8">US 057 - Usuário: Visualizar claps em suas publicações</td>
                <td class="s8">NFR Controle de Qualidade: &quot;Verificar comentários do usuário em posts&quot;</td>
                <td class="s18">I* Publicações e i* Stories</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R230" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R045</td>
                <td class="s3" dir="ltr">Visualizar próprio perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF37</td>
                <td class="s8">UC09 - Editar perfil: [FP01] Este fluxo se inicia quando o usuário clica em &#39;profile&#39;
                    <br></td>
                <td class="s8">US 044 - Usuário: Visualizar próprio perfil</td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s8">i* Perfil</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R231" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R046</td>
                <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF38</td>
                <td class="s14">-</td>
                <td class="s8">US 048 - Usuário: Ver estatísticas de uma série</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R232" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R047</td>
                <td class="s3" dir="ltr">Visualizar marcações feitas</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF39</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R233" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R048</td>
                <td class="s3" dir="ltr">Criar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF40</td>
                <td class="s8">UC32 - Escrever uma nova Story: 2-O usuário clica sobre a opção &quot;Write a story&quot; localizada ao lado da opção &quot;Import a story&quot;. </td>
                <td class="s8">US 058 - Usuário: Criar publicação</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R234" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R049</td>
                <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF41</td>
                <td class="s8">UC29 - Visualizar Drafts: Funcionalidade responsável por mostrar todos os Drafts de um usuário.
                    <br></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R235" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R050</td>
                <td class="s3" dir="ltr">Editar publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF42</td>
                <td class="s8">UC35 - Editar Publicação: Funcionalidade responsável por permitir que um usuário edite uma publicação.
                    <br></td>
                <td class="s8">US 059 - Usuário: Editar publicação</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R236" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R051</td>
                <td class="s3" dir="ltr">Deletar Publicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF43</td>
                <td class="s8">UC36 - Excluir Publicação: Funcionalidade responsável por permitir que um usuário exclua uma publicação.
                    <br></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">I* Publicações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R237" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R052</td>
                <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF44</td>
                <td class="s8">UC01 - Área comum: 3-Visitante escolhe tópicos de interesse <br></td>
                <td class="s8">US 008 - Usuário: Selecionar alguns tópicos de meu interesse</td>
                <td class="s8">NFR Controle de Qualidade: &quot;Sugestão de conteúdo&quot;</td>
                <td class="s18">i* Pesquisar conteúdo e i* Customização de interesses</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R238" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R053</td>
                <td class="s3" dir="ltr">Deixar de seguir usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF45</td>
                <td class="s8">UC10-Configurar preferências: 3-Usuário visualiza opções de configurações de e-mail, conexões, conta, membership e seguraça</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R239" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R054</td>
                <td class="s3" dir="ltr">Deixar de seguir publicações</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF46</td>
                <td class="s8">UC10-Configurar preferências: 3-Usuário visualiza opções de configurações de e-mail, conexões, conta, membership e seguraça</td>
                <td class="s14">-</td>
                <td class="s8">NFR Controle de Qualidade: &quot;Sugestão de conteúdo&quot;</td>
                <td class="s18">i* Pesquisar conteúdo e i* Customização de interesses</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R240" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R055</td>
                <td class="s3">Aivar modo noturno</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF47</td>
                <td class="s14">-</td>
                <td class="s8">010 - Ativar modo noturno </td>
                <td class="s8">NFR Usabilidade: &quot;Ser agradável ao usuário&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R241" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3" dir="ltr">R056</td>
                <td class="s3">Automatizar modo noturno</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF48</td>
                <td class="s14">-</td>
                <td class="s8">011-Automatizar modo noturno </td>
                <td class="s8">NFR Usabilidade: &quot;Ser agradável ao usuário&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R242" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R057</td>
                <td class="s3">Editar email padrão</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF49</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">012-Editar email padrão </td>
                <td class="s14">-</td>
                <td class="s8">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R243" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R058</td>
                <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF50</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">013-Selecionar período de sugestão de artigos </td>
                <td class="s8">NFR Controle de Qualidade: &quot;Sugestão de conteúdo&quot;</td>
                <td class="s18">I* SD configurações e i* Customização de interesses</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R244" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R059</td>
                <td class="s3">Desativar sugestão de artigos</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF51</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">014-Desativar sugestão de artigos </td>
                <td class="s8">NFR Controle de Qualidade: &quot;Sugestão de conteúdo&quot;</td>
                <td class="s18">I* SD configurações e i* Customização de interesses</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R245" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R060</td>
                <td class="s3">Ativar/desativar boletim informativo</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF52</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">015-Ativar/desativar boletim informativo </td>
                <td class="s8">NFR Controle de Qualidade: &quot;Sugestão de conteúdo&quot;</td>
                <td class="s8">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R246" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R061</td>
                <td class="s3">Selecionar tema do boletim informativo</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF53</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">016-Selecionar tema do boletim informativo </td>
                <td class="s8">NFR Controle de Qualidade: &quot;Sugestão de conteúdo&quot;</td>
                <td class="s8">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R247" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R062</td>
                <td class="s3">Ativar/desativar recomendações de stories</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF54</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">017-Ativar as recomendações de stories </td>
                <td class="s8">NFR Controle de Qualidade: &quot;Sugestão de conteúdo&quot;</td>
                <td class="s18">I* SD configurações e i* Customização de interesses</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R248" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R063</td>
                <td class="s3">Ativar/desativar notificação por e-mail</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF55</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">018-Ativar as notificação por e-mail </td>
                <td class="s14">-</td>
                <td class="s8">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R249" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R064</td>
                <td class="s3">Ativar/desativar notificação social</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF56</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s18">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R250" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R065</td>
                <td class="s3">Selecionar privacidade de menções</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF57</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">019-Gerenciar a privacidade de menções </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R251" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R066</td>
                <td class="s3">Desativar menções de usuários</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF58</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">020-Desativar menções a mim </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R252" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R067</td>
                <td class="s3">Conectar com redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF59</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">006-Conectar com redes sociais </td>
                <td class="s14">-</td>
                <td class="s18">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R253" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R068</td>
                <td class="s3">Conectar com Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF60</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">007-Conectar com Google </td>
                <td class="s14">-</td>
                <td class="s18">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R254" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R069</td>
                <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF61</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">021-Mostrar links para minhas redes sociais </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R255" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R070</td>
                <td class="s3">Editar nome de usuário para menção</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF62</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R256" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R071</td>
                <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF63</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R257" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R072</td>
                <td class="s3">Gerenciar usuários bloqueados</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF64</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s18">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R258" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R073</td>
                <td class="s3">Fazer download de meus dados do Medium</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF65</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s18">I* SD configurações</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R259" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R074</td>
                <td class="s3">Deslogar de outras sessões </td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF66</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">034-Deslogar de outras sessões </td>
                <td class="s14">-</td>
                <td class="s8">[I* SD configurações]: (task) deslocar de outras sesssões</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R260" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R075</td>
                <td class="s3">Desativar conta</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF67</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">022-Desativar minha conta </td>
                <td class="s14">-</td>
                <td class="s8">[I* SD configurações]: (task) desativar/deletar conta</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R261" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R076</td>
                <td class="s3">Deletar conta</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF68</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">023- Deletar minha conta </td>
                <td class="s14">-</td>
                <td class="s8">[I* SD configurações]: (task) desativar/deletar conta</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R262" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R077</td>
                <td class="s3">Visualizar tutorial das áreas da aplicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF69</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R263" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R078</td>
                <td class="s3">Acessar glossário MEDIUM</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF70</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">001-Acessar glossário MEDIUM </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R264" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R079</td>
                <td class="s3">Responder questionário de satisfação da aplicação</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF71</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">002-Responder questionário de satisfação da aplicação </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R265" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R080</td>
                <td class="s3">Pesquisar tópico de ajuda</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF72</td>
                <td class="s8">UC10-Configurar preferências: &quot;3-Usuário visualiza opções de configurações de e-mail, notificações, sugestão de artigos, boletim informativo, privacidade de menções, usuários bloqueados, conexões, conta (deslogar, desativar, deletar
                    links para redes sociais, download de informações), tutoriais, glossário, pesquisa de satisfação, ajudamembership e segurança&quot;</td>
                <td class="s8">003-Pesquisar tópico de ajuda </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R266" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R081</td>
                <td class="s3">Escolher plano de assinatura membership</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF73</td>
                <td class="s8">UC12-Selecionar plano: Funcionalidade responsável por possibilitar a seleção de planos.
                    <br></td>
                <td class="s8">038-visualizar os planos de assinatura disponíveis </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R267" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R082</td>
                <td class="s3">Inserir forma de pagamento do medium membership</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF74</td>
                <td class="s8">UC15-Selecionar Método de pagamento: Funcionalidade responsável por possibilitar a seleção do método de pagamento.
                    <br></td>
                <td class="s8">039-visualizar as formas de pagamento existentes </td>
                <td class="s14">-</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R268" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R083</td>
                <td class="s3">Login via redes sociais</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF75</td>
                <td class="s8">UC02-Efetuar Login: 2-Usuário escolhe entre as opções de integração via redes sociais
                    <br></td>
                <td class="s8">035-Realizar login via redes sociais </td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R269" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R084</td>
                <td class="s3">Login via Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF76</td>
                <td class="s8">UC02-Efetuar Login: 2-Usuário escolhe entre as opções de integração via redes sociais
                    <br></td>
                <td class="s8">036-Realizar login via Google </td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R270" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R085</td>
                <td class="s3">Login via E-mail</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF77</td>
                <td class="s8">UC02-Efetuar Login: No passo 2 do fluxo principal, há a opção de login via E-mail
                    <br></td>
                <td class="s8">037-Realizar login via E-mail </td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R271" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R086</td>
                <td class="s3">Cadastrar com Google</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF78</td>
                <td class="s8">UC01-Efetuar Cadastro: 3-Visitante escolhe entre as opções de integração via redes sociais
                    <br></td>
                <td class="s8">004-Realizar cadastro com Google </td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R272" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R087</td>
                <td class="s3">Cadastrar com Facebook</td>
                <td class="s3" dir="ltr">Funcional</td>
                <td class="s8">EF79</td>
                <td class="s8">UC01-Efetuar Cadastro: 3-Visitante escolhe entre as opções de integração via redes sociais
                    <br></td>
                <td class="s8">005-Realizar cadastro com Facebook </td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R273" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R088</td>
                <td class="s3">Segurança</td>
                <td class="s3" dir="ltr">Não Funcional</td>
                <td class="s8">EF80</td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">NFR Segurança: &quot;Criação de contas&quot;</td>
                <td class="s14">-</td>
            </tr>
            <tr style='height:20px;'>
                <th id="0R274" style="height: 20px;" class="row-headers-background">
                </th>
                <td class="s3">R089</td>
                <td class="s3">Desempenho</td>
                <td class="s3" dir="ltr">Não Funcional</td>
                <td class="s8"></td>
                <td class="s14">-</td>
                <td class="s14">-</td>
                <td class="s8">NFR: Desempenho</td>
                <td class="s14">-</td>
            </tr>
        </tbody>
    </table>
</div>

### Elos Funcionais

**Legenda:**
- R/R = R
- A = A
- Alocado e = AE

#### EF1
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
***

#### EF2
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

#### EF3
***

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
***

#### EF4
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
***

#### EF5
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

***

#### EF6

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
***

#### EF7

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
***

#### EF8
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
***

#### EF9
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
- I* Stories

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: StoryTelling - Escritor, New Story **R** US 063

**R**: Brainstorming 4 **R** UC32

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**R**: RichPicture "Ponto de vista do escritor/New Story" **R** StoryTelling - Escritor, New Story

**R**: US 063 **R** i* Publicações

**R**: UC Stories **R** i* Stories

**A**: US 063 **AE** i* Stories
***

#### EF10
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryTelling - Escritor, New Story	
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Storie	
- UC stories	
- UC32-Escrever uma nova Story.	
- UC29 - Visualizar Drafts
- I* Publicações
- I* Stories

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: StoryTelling - Escritor, New Story **R** US 063

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**R**: US 063 **R** i* Publicações

**R**: UC Stories **R** i* Stories

**A**: UC29 **AE** UC32
***

#### EF11

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryTelling - Escritor, New Story	
- Relato de introspecção 3: Usuário no processo de criação de uma nova Story
- Cenário Criar um novo Storie	
- Léxico Storie	
- UC stories	
- UC32-Escrever uma nova Story.
- - UC29 - Visualizar Drafts	
- I* Publicações

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**A**: Introspecção 3 **AE** i* Publicações

**R**: StoryTelling - Escritor, New Story **R** Introspecção 3

**A**: US 032 **AE** UC Stories

**A**: UC29 **AE** UC32

**R**: UC Stories **R** i* Stories

**A**: i* Stories **AE** i* Publicações

***

#### EF12

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
- I* Stories
- I* Customização de interesses
  
#### Elos

**R**: StoryBoard Tutorial **R** Introspecção 1

**R**: Brainstorming 3 **R** StoryBoard Tutorial

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: Léxico Stories **R** UC stories

**A**: UC28 **AE** UC Stories

**R**: US 071 **R** UC28

**R**: US 071 **R** i* Publicações

**R**: US071 **AE** i* Stories

**A**: Introspecção **AE** i* Customização de interesses

**A**: i* Stories **AE** i* Publicações
***

#### EF13

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
- US 064- Usuário Escritor: Importar 'storie'
- i* Publicações
- I* Stories

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Importar um storie

**R**: StoryTelling - Escritor, New Story **R** US 064

**R**: Brainstorming 4 **R** UC31

**A**: Cenário Importar um storie **AE** Introspecção 3

**R**: RichPicture "Ponto de vista do escritor/New Story" **R** StoryTelling - Escritor, New Story

**R**: US 064 **R** i* Publicações

**A**: i* Stories **AE** i* Publicações
***

#### EF14

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
- i* Stories

#### Elos
**R**: StoryTelling - Escritor, New Story **R** US 064

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: UC35 **AE** UC Stories

**A**: UC35 **AE** i* Publicações

**R**: US 060 **R** i* Publicações

**R**: StoryTelling - Escritor, New Story **R** Introspecção 3

**A**: i* Stories **AE** i* Publicações
***

#### EF15
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
- i* Stories

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: UC36 **AE** UC Stories

**A**: UC36 **AE** i* Publicações

**R**: UC36 **R** US 061

**R**: US 061 **R** i* Publicações

**R**: Léxico Stories **R** Introspecção 3

**A**: i* Stories **AE** i* Publicações

***

#### EF16

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
- I* Stories
  
#### Elos

**R**: Léxico Clap **R** US 065

**R**: lexico clap **R** Cenário Dar Claps

**R**: introspecção 1 **R** StoryBoard Tutorial

**A**: US 065 **AE** i* Publicações

**A**: Cenário Dar Claps **AE**  Brainstorming 3

**A**: i* Stories **AE** i* Publicações

***

#### EF17
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
***

#### EF18
#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 4 "Pedro: ver comentários de seus textos e responder os comentários de seus textos"	
- Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Cenário Comentar publicação	
- Léxico Response	
- US 067 - Usuário: Comentar no corpo do texto		
- I* Publicações
- I* Stories

#### Elos

**R**: Brainstorming 4 **R** Introspecção 1

**R**: Cenário Comentar Publicação **R** US 067

**A**: Léxico Response **AE** Cenário Comentar Publicação

**R**: US 067 **Rdo em** i* Publicações

**A**: i* Stories **AE** i* Publicações

***

#### EF19
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
***

#### EF20

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
***

#### EF21

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
***

#### EF22

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
***

#### EF23

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 3: "Gabriel: Selecionar tema de artigos"
- Relato de Introspecção 1		
- Cenário Pesquisa por artigo	
- Léxico Search e Léxico Tag	
- UC Área comum	
- UC03 - Pesquisar artigo	
- i* Pesquisar conteúdo
- i* Customização de interesses
#### Elos
**R**: Brainstorming 3 **R** Cenário Pesquisa por artigo

**A**: Léxico Search e Tag **AE** Cenário Pesquisa por artigo

**R**: UC Área comum **R** UC03

**R**: UC03 **R** i* Pesquisar Conteúdo

**R**: instrospecção  1 **R** i* Pesquisar conteúdo

**A**: i* Pesquisar Conteúdo **AE** i* Customização de interesses
***

#### EF24

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
***

#### EF25

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
***

#### EF26

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
***

#### EF27

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
***

#### EF28

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
***

#### EF29

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Brainstorming 4: "Pedro: ver comentários de seus textos e responder os comentários de seus textos"		
- Cenário Comentar publicação	
- Léxico Response		
- UC30 - Visualizar Publicações	
- US 031 - Usuário: Visualizar comentários da publicação	
- i* Publicações	
- i* Stories
- 
#### Elos
**R**: Brainstorming 4 **R** Cenário Comentar Publicação

**A**: Léxico Response **AE** Cenário Comentar Publicação

**A**: UC30 **AE** US 031

**R**:Cenário Comentar Publicação **R** i* Stories

**A**: i* Stories **AE** i* Publicações

***

#### EF30

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
***

#### EF31

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
***

#### EF32

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Editar Perfil: "Ao lado do seu nome nesta página de perfil, existia um botão chamado “Edit profile” e logo Carlos clicou sobre esse botão."		
- Brainstorming 2 "William: Editar seu próprio perfil"
- Cenário Editar perfil	
- Léxico Edit e Léxico Profile	
- UC Área comum	
- UC09 - Editar perfil	
- US 043 - Usuário: Editar informações de perfil	
- NFR Segurança	
- i* Perfil
#### Elos
**R**: StoryTelling Editar **R** Cenário Editar Perfil

**R** Storytelling Editar **R** Brainstorming 2

**A**: Cenário Editar Perfil **AE** Brainstorming 2

**A**: Léxico Edit e Profile **AE** Cenário Editar Perfil

**R**: US 043 **R** UC09

**A**: UC09 **AE** UC Área Comum

**A**: i* Perfl **AE** NFR Segurança
***

#### EF33

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Editar Perfil: "Após ter editado tudo o que desejava, Carlos clicou no botão chamado “Save” e foi redirecionado para a página que apresentava os seus dados cadastrais, agora editados."
- Brainstorming 2 "William: Editar seu próprio perfil"
- Cenário Editar perfil	-
- Léxico Edit e Léxico Profile	
- UC Área comum	UC09 - Editar perfil	
- US 043 - Usuário: Editar informações de perfil	
- NFR Segurança	
- i* Perfil
#### Elos
**R**: StoryTelling Editar **R** Cenário Editar Perfil

**R** Storytelling Editar **R** Brainstorming 2

**A**: Cenário Editar Perfil **AE** Brainstorming 2

**A**: Léxico Edit e Profile **AE** Cenário Editar Perfil

**A**: i* Perfl **AE** NFR Segurança

**R**: US 043 **R** UC Área Comum
***

#### EF34

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryBoard - Tutorial e seguir escritor: "Realmente. E ainda consigo seguir o perfil de escritores dos tutoriais estando logado"	
- Brainstorming 3 "Gabriel: seguir o escritor"		
- Cenário Deixar de seguir usuário	
- Léxico Following		
- i* Pesquisar conteúdo
#### Elos
**R**: StoryBoard Tutorial **R** Cenário Deixar de Seguir usuário

**A**: Brainstorming 3 **AE** Cenário Deixar de Seguir usuário

**A**: Léxico Following **AE** Cenário Deixar de Seguir usuário

**R**: StoryBoard Tutorial **R** i* Pesquisar Conteúdo

**A**: Léxico Following **AE** i* Pesquisar Conteúdo
***

#### EF35

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Escritor New Story: "Medium, como é chamado o site, é uma plataforma pensada na troca de conhecimentos por seus usuários, a partir de textos técnicos, assuntos atuais, sociais, tecnológicos, psicológicos e até mesmo pesquisas"	
- Léxico Followers	
- US 032 - Usuário: Visualizar seguidores

#### Elos
**A**: StoryTelling Escritor **AE** Léxico Followers


**R**: Léxico Followers **R** US 032

**R**: StoryTelling **R** US 032
***

#### EF36

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Escritor New Story: "Entretanto, ela estava satisfeita com os resultados, pois havia recebido um bom número de “claps”"			
- Brainstorming 3 "Matheus: ver quem deu clap em suas publicações"		
- Cenário Dar clap	
- Léxico Clap		
- UC30 - Visualizar Publicações	
- US 057 - Usuário: Visualizar claps em suas publicações	
- NFR Controle de Qualidade	
- i* Stories
- i* Publicações
#### Elos
**R**: Cenário Dar Clap **R** Storytelling Escritor

**A**: Brainstorming 3 **AE** Cenário Dar Clap

**A**: Léxico clap **AE** Cenário Dar Clap

**A**: UC30 **AE** Storytelling Escritor

**A**: UC30 **AE** US 057

**R**: US 057 **R** NFR Controle de Qualidade

**R**: NFR Controle de Qualidade **R** i* Stories

**A**: i* Stories **AE** i* Publicações

***

#### EF37

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Editar Perfil: "Entre essas opções estava escrita a opção “Profile”, então Carlos clicou sobre essa opção e ao mesmo instante ele foi redirecionado para uma página que apresentava todos os seus dados cadastrais."		
- Brainstorming 3 "Matheus: acessar o perfil de usuário"	
- Cenário Editar perfil	
- Léxico Profile	
- UC Área comum	
- UC09 - Editar perfil	
- US 044 - Usuário: Visualizar próprio perfil	
- NFR Segurança	
- i* Perfil
#### Elos
**R**: Storytelling Editar Perfil **R** Cenário Editar Perfil

**R**: Storytelling Editar Perfil **R** Brainstorming 3

**A**: Léxico Profile **AE** Cenário Editar Perfil

**R**: US 044 **R** UC Área comum

**A**: UC09 **AE** UC Área comum

**R**: i* Perfil **AE** NFR Segurança
***

#### EF38

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Editar Perfil: "Ao começar a ganhar visibilidade em suas publicações, Carlos passou a receber comentários pedindo informações sobre a sua formação acadêmica, assim como o seu nome completo"					
- US 048 - Usuário: Ver estatísticas de uma série
#### Elos
**R**: Storytelling - Editar Perfil **R** US 048
***

#### EF39

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryBoard - Bookmarking: "Nossa! O artigo é muito grande, acho que vou salvar para ler mais tarde"			
- Cenário Criar um novo Bookmark	
- Léxico Bookmark	
- UC Bookmark
#### Elos
**R**: StoryBoard - Bookmarking **R** UC Bookmark

**A**: Léxico Bookmark **R** Cenário Criar um novo Bookmark

**R**: Cenário Criar um novo Bookmark **R** UC Bookmark

**R**: StoryBoard - Bookmarking **R** Cenário Criar um novo Bookmark
***

#### EF40

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Escritor New Story: "Natália percebeu que havia mais de uma maneira de se publicar um texto."			
- Cenário Criar um storie	
- Léxico Stories	
- UC stories	
- UC32 - Escrever uma nova Story	
- US 058 - Usuário: Criar publicação		
- I* Publicações
#### Elos
**R**: Storytelling Escritor **R** Cenário Criar um Storie

**A**: Léxico Stories **AE** Cenário Criar um Storie

**R**: US 058 **R** UC32

**A**: UC32 **AE** UC Stories

**R** US 058 **R** UC Stories

**R** US 058 **R** i* Publicações
***

#### EF41

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Pergunta: "Como você classifica o editor de textos padrão do Médium?"
- StoryTelling: Escritor, New Story
- Cenário: Criar um novo Storie	
- UC: Stories
- Especificação: UC29 - visualizar drafts
- I* Publicações

#### Elo

**R**: StoryTelling Escritor, New Story e UC Stories **R** Cenário Criar um novo storie

**R**: I* Publicações **R** Cenário criar novo Storie e UC cenários

**A**: Pergunta "Como você classifica o editor de textos padrão do Médium?" **ALOCADA EM** UC Stories, Cenário - criar novo Storie


***

#### EF42

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Pergunta: "Como você classifica o editor de textos padrão do Médium?"
- Cenário: Criar um novo Storie	
- Léxico editar
- UC: Stories
- Especificação: UC35 - Editar Publicação
- US 059 - Usuário: Editar publicação
- I* Publicações

#### Elo

**R**: StoryTelling Escritor, New Story e UC Stories **R** Cenário Criar um novo storie

**R**: I* Publicações **R** Cenário criar novo Storie e US 059

**R**: UC Stories **R** US 059 - Editar publicação

**A**: Pergunta "Como você classifica o editor de textos padrão do Médium?" **ALOCADA EM** UC Stories, Cenário - criar novo Storie

**A**: UC Stories **AE** I* Publicações

**A**: Léxico editar **AE** Cenário Criar um novo storie

***

#### EF43

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Cenário: Criar um novo Storie	
- UC: Stories
- Especificação: UC36 - Excluir Publicação
- I* Publicações

#### Elo

**R**: I* Publicações **R** Cenário criar novo Storie

**R**: UC Stories **R** US UC - Excluir publicação

**A**: UC Stories **AE** I* Publicações

***

#### EF44

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Introspecção: Relato de instrospecção 6- "Deve mostrar escritores sugeridos para os interesses do leitor."
- Cenário: Customizar interesses
- UC: Cadastro
- Especificação: UC01 - Área comum
- US 008 - Usuário: Selecionar alguns tópicos de meu interesse
- NFR: Controle de Conteúdo
- I* Pesquisar conteúdo
- I* Customização de interesses

#### Elo

**R** UC cadastro **R** US 008 - Usuário: Selecionar alguns tópicos de meu interesse

**A**: Cenário customizar interesses, US 008 **AE**  NFR Controle de Conteúdo

**A**: I* Pesquisar conteúdo **AE** Especificação: UC01 - Área comum

**A**: I* Pesquisar conteúdo **AE** i* Customização de interesses
***

#### EF45

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Introspecção: Relato de instrospecção 6: "Deve ser capaz de deixar de seguir Blogs e escritores."
- Cenário: Deixar de seguir usuários
- Léxico: seguidores
- UC01 - Área comum
- Especificação:UC10-Configurar preferências

#### Elo

**R**: UC01 - Área Comum **R** Cenário deixar de seguir usuários

***R**:  **R** Cenário deixar de seguir usuários

**A**: Léxico Seguidores **AE** Especificação: UC01 - Área comum, UC01- Área Comum
***

#### EF46

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Introspecção: Relato de introspecção 3: "Poder tornar o texto público ou privado para apenas um número definido de leitores;"
- UC01 - Área comum
- Especificação:UC10-Configurar preferências
- NFR Controle de Conteúdo
- i* Pesquisar conteúdo
- i* Customização de interesses

#### Elo

**R**: UC01 - Área comum  **R** Especificação:UC10-Configurar preferências

**A**: Introspecção 3 **AE** NFR Controle de Conteúdo

**A**: i* Pesquisar conteúdo  **AE** UC01 - Área Comum

**A**: I* Pesquisar conteúdo **AE** i* Customização de interesses

***

#### EF47

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storytelling - Configurações
- Léxico night mode
- US010 - Ativar modo noturno 
- NFR Usabilidade

#### Elo

**R**: UC01 - Área comum  **R** Especificação:UC10-Configurar preferências

**A**: Léxico night mode **AE** Storytelling - Configurações,US010 - Ativar modo noturno

**A** Storytelling - Configurações e US010 - Ativar modo noturno  **AE** NFR Usabilidade

***

#### EF48

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storytelling - Configurações
- Léxico night mode
- US011-Automatizar modo noturno        
- NFR Usabilidade

#### Elo

**R**: UC01 - Área comum  **R** Especificação:UC10-Configurar preferências

**A**: Léxico night mode **AE** Storytelling - Configurações,US011-Automatizar modo noturno

**A** Storytelling - Configurações e US011-Automatizar modo noturno  **AE** NFR Usabilidade

***

#### EF49

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storytelling - Configurações
- Brainstorming 2: "William",editar seu próprio perfil
- Cenário: C04: Editar perfil
- Léxico editar
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US012-Editar email padrão 
- I* SD configurações: (task) editar email

#### Elo

**R**: I* SD configurações: (task) editar email **R** US012 - Editar email padrão

**R**: UC Área comum **R** C04 editar perfil

**A** Storytelling - Configurações **AE** Especificação: UC10-Configurar preferências

**A** US012-Editar email padrão  **AE** Storytelling - Configurações e Brainstorming 2

***

#### EF50

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Cenário: C10:Configurar notificações de e-mail
- Léxico newsletter
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US013-Selecionar período de sugestão de artigos
- NFR Controle de qualidade
- I* SD configurações
- i* Customização de interesses

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**R**: Storybord-Usuário, Configurando a aplicação **R** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**R**: Caso de uso : Área comum  **R** Léxico newsletter

**A** I* SD configurações e US013-Selecionar período de sugestão de artigos  **AE** NFR Controle de qualidade

**A** Léxico newsletter **AE** US013-Selecionar período de sugestão de artigos

**A**: i* Customização de interesses **AE** i* Configurações
***

#### EF51

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Cenário: C10:Configurar notificações de e-mail
- Léxico newsletter
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US014-Desativar sugestão de artigos
- NFR Controle de qualidade
- I* SD configurações
- I* Customização de interesses

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**R**: Storybord-Usuário, Configurando a aplicação **R** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**R**: Caso de uso : Área comum  **R** Léxico newsletter

**A** I* SD configurações e US014-Desativar sugestão de artigos **AE** NFR Controle de qualidade

**A** Léxico newsletter **AE** US013-Selecionar período de sugestão de artigos

**A**: i* Customização de interesses **AE** i* Configurações

***

#### EF52

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Cenário: C10:Configurar notificações de e-mail
- Léxico newsletter
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US015-Ativar/desativar boletim informativo 
- NFR Controle de qualidade
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**R**: Storybord-Usuário, Configurando a aplicação **R** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**R**: Caso de uso : Área comum  **R** Léxico newsletter e introspecçaõ 1

**A** I* SD configurações e US015-Ativar/desativar boletim informativo **AE** NFR Controle de qualidade

**A** Léxico newsletter **AE** US013-Selecionar período de sugestão de artigos e Introspecção 1

***

#### EF53

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Cenário: C10:Configurar notificações de e-mail
- Léxico newsletter
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US016-Selecionar tema do boletim informativo
- NFR Controle de qualidade
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**R**: Storybord-Usuário, Configurando a aplicação **R** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**R**: Caso de uso : Área comum  **R** Léxico newsletter e introspecçaõ 1

**A** I* SD configurações e US016-Selecionar tema do boletim informativo **AE** NFR Controle de qualidade

**A** Léxico newsletter **AE** US013-Selecionar período de sugestão de artigos e Introspecção 1

***

#### EF54

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Brainstorming 3
- Cenário: C10:Configurar notificações de e-mail
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US017-Ativar as recomendações de stories
- NFR Controle de qualidade
- I* SD configurações
- I* Customização de interesses

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**R**: Storybord-Usuário, Configurando a aplicação **R** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**A**: US017-Ativar as recomendações de stories e Cenário: C10:Configurar notificações de e-mail **AE** Brainstorming 3

**A** I* SD configurações e 017-Ativar as recomendações de stories **AE** NFR Controle de qualidade

**A**: i* Customização de interesses **AE** i* Configurações

***

#### EF55

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Brainstorming 3
- Introspecção 1: Comportamento do usuário na Página inicial da aplicação
- Cenário: C10:Configurar notificações de e-mail
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US018-Ativar as notificação por e-mail
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**R**: Storybord-Usuário, Configurando a aplicação **R** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**A**: US018-Ativar as notificação por e-mail e Cenário: C10:Configurar notificações de e-mail **AE** Brainstorming 3

**A**: Cenário: C10:Configurar notificações de e-mail  **AE** Introspecção 1:Comportamento do usuário na Página inicial da aplicação

***

#### EF56

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Cenário: C10:Configurar notificações de e-mail
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**R**: Storybord-Usuário, Configurando a aplicação **R** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**A**: Cenário: C10:Configurar notificações de e-mail  **AE** Especificação: UC10

***

#### EF57

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico mention
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US019-Gerenciar a privacidade de menções
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Léxico mention **AE** Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US019

***

#### EF58

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico mention
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US020-Desativar menções a mim
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Léxico mention **AE** Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US020-Desativar menções a mim  

***


#### EF59

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico conta e conection
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US006-Conectar com redes sociais
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Léxico conection **AE** Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US020-Desativar menções a mim  e US006-Conectar com redes sociais

***

#### EF60

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico conta e conection
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US007-Conectar com Google
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Léxico conection **AE** Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US020-Desativar menções a mim e US007-Conectar com Google
***

#### EF61

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US021-Mostrar links para minhas redes sociais
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US020-Desativar menções a mim e US021-Mostrar links para minhas redes sociais **AE** UC Área Comum
***

#### EF62

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico editar
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

**A**: Léxico editar **AE** UC Área Comum e Storybord- Usuário configurando a aplicação
***

#### EF63

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

***

#### EF64

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico seguidores
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

**A**: Léxico seguidores **AE** UC Área Comum e Storybord- Usuário configurando a aplicação
***

#### EF65

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum
***

#### EF66

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US034-Deslogar de outras sessões
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

**A** US034-Deslogar de outras sessões **AE** Especificação: UC10-Configurar preferências
***

#### EF67

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico conta
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US022-Desativar minha conta
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

**A**: Léxico conta **AE** UC Área Comum e I* SD configurações

**A** US022-Desativar minha conta **AE** Especificação: UC10-Configurar preferências
***

#### EF68

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico conta
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US023- Deletar minha conta
- I* SD configurações

#### Elo

**R**: I* SD configurações **R** Storybord - Usuário, Configurando a aplicação

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

**A**: Léxico conta **AE** UC Área Comum e I* SD configurações

**A** US023- Deletar minha conta **AE** Especificação: UC10-Configurar preferências
***

#### EF69

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências

#### Elo

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

***

#### EF70

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Léxico MEDIUM
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US001-Acessar glossário MEDIUM

#### Elo

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

**A**: Storybord, UC Área comum **AE** Léxico Medium

**A**: US001-Acessar glossário MEDIUM **AE** UC Área Comum

***

#### EF71

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US002-Responder questionário de satisfação da aplicação

#### Elo

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

**A**: Storybord, UC Área comum **AE** Léxico Medium

**A**: US002-Responder questionário de satisfação da aplicação **AE** UC Área Comum

***

#### EF72

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências
- US003-Pesquisar tópico de ajuda

#### Elo

**R**: Storybord-Usuário, Configurando a aplicação **R** Especificação: UC10-Configurar preferências

**A**: Especificação: UC10-Configurar preferências **AE** UC Área Comum

**A**: Storybord, UC Área comum **AE** Léxico Medium

**A**: US003-Pesquisar tópico de ajuda **AE** UC Área Comum

***



