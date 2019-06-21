## Versionamento de edições
|Data      |        Autor            |           Descrição           |Versão|
|----------|-------------------------|-------------------------------|------|
|13/06/2019| Pedro Rodrigues Pereira | Adição da pagina e introdução | 1.0  |
|18/06/2019| Matheus Blanco | Adição de Elos | 2.0  |
|18/06/2019| Matheus Blanco | Adição de Elos | 3.0  |
|19/06/2019| Matheus Blanco | Adição de Elos | 4.0  |


### Introdução

Rastreável é uma característica de sistemas nos quais há uma interligação entre os dados obtidos e as informações geradas. No caso da engenharia de requisitos podemos considerar como rastreabilidade como a caracaterização de relação entre os requisitos e suas fontes ou artefatos criados durante todo o ciclo de vida do software. Essa característa está atrelada intrinsicamente a utilização de uma baseline de requisitos para uma melhor transparência dos requisitos elicitados.

Com a rastreabilidade é possível ver todo o processo evolutivo referente aos requisitos e suas conseguências.
Com isso temos a pré-rastreabilidade como uma projeção de possíveis surgimentos de requisitos e também temos a pós rastreabilidade que será tratada nesse tópico por meio da utilização de algumas técnicas inerentes a ela.

### Metodologia

Para a realização dessa tarefa, em um primeiro momento, fora refatorada a baseline e posteriormente o backlog do produto. Após esse processo de refatoração se tornou possível linkar os requisitos em relação a sua origem, levando em consideração todas as suas ocorrências.


***

### Tabela Backward-from

<div class="ritz grid-container" dir="ltr">
  <table class="waffle" cellspacing="0" cellpadding="0">
    <tbody>
         <tr style='height:22px;'>
            <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s1" dir="ltr">RichPicture</td>
        <td class="s1" dir="ltr">Questionário</td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R001</td>
        <td class="s3" dir="ltr">Responsividade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
          <td class="s3" dir="ltr">R002</td>
        <td class="s3" dir="ltr">Portabilidade mobile ios</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s3" dir="ltr">Ponto de vista do leitor<br>(Gabriel)<br><br>Import Story<br>(Pedro)</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
            <td class="s3" dir="ltr">R003</td>
        <td class="s3" dir="ltr">Portabilidade mobile android</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s3" dir="ltr">Ponto de vista do leitor<br>(Gabriel)<br><br>Import Story<br>(Pedro)</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R004</td>
        <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R005</td>
        <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R006</td>
        <td class="s3" dir="ltr">Política de privacidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R007</td>
        <td class="s3" dir="ltr">Identidade Visual</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R008</td>
        <td class="s3" dir="ltr">Alta disponibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Com que frequência você importa textos de outras plataformas para o
          Medium?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
            <td class="s3" dir="ltr">R009</td>
        <td class="s3" dir="ltr">Controle de Conteúdo</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à
          você?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s4" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R010</td>
        <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>New Story<br>(Pedro)</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Sobre quais tipos de assunto você escreve?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R011</td>
        <td class="s3" dir="ltr">Manutenibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R012</td>
        <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à
          você?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R013</td>
        <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R014</td>
        <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R015</td>
        <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
         <td class="s3" dir="ltr">R016</td>
        <td class="s3" dir="ltr">Ver status</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R017</td>
        <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>New Story<br>(Pedro)</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Sobre quais tipos de assunto você escreve?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R018</td>
        <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R019</td>
        <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R020</td>
        <td class="s3" dir="ltr">Visualizar stories publicadas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à
          você?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R021</td>
        <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>Import Story<br>(Pedro)</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Com que frequência você importa textos de outras plataformas para o
          Medium?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R022</td>
        <td class="s3" dir="ltr">Editar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R023</td>
        <td class="s3" dir="ltr">Deletar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
           <td class="s3" dir="ltr">R024</td>
        <td class="s3" dir="ltr">Aplaudir um texto lido</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você aplaude (&#39;claps&#39;) as
          publicações?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R025</td>
        <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">Ponto de vista do leitor<br>(Guilherme)<br><br>Ponto de vista do leitor<br>(Gabriel)
        </td>
        <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você compartilha as publicações?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R026</td>
        <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você comenta nas publicações?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R027</td>
        <td class="s3" dir="ltr">Escutar podcasts</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr">Ponto de vista do leitor<br>(Gabriel)</td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R028</td>
        <td class="s3" dir="ltr">Seguir escritores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R029</td>
        <td class="s3" dir="ltr">Seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R030</td>
        <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R031</td>
        <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Qual os assuntos pelo quais você se interessa ao acessar o
          MEDIUM?&quot;</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R032</td>
        <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R033</td>
        <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R034</td>
        <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s3" dir="ltr">R035</td>
        <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R036</td>
        <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R037</td>
        <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você comenta nas publicações?&quot;</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
                <td class="s3" dir="ltr">R038</td>
        <td class="s3" dir="ltr">Reportar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s3" dir="ltr">R039</td>
        <td class="s3" dir="ltr">Reportar usuário</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R040</td>
        <td class="s3" dir="ltr">Editar informações de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s3" dir="ltr">R041</td>
        <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R43" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">44</div>
        </th>
        <td class="s3" dir="ltr">R042</td>
        <td class="s3" dir="ltr">Visualizar autores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R44" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">45</div>
        </th>
        <td class="s3" dir="ltr">R043</td>
        <td class="s3" dir="ltr">Visualizar seguidores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R45" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">46</div>
        </th>
        <td class="s3" dir="ltr">R044</td>
        <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Com qual frequência você aplaude (&#39;claps&#39;) as
          publicações?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R46" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">47</div>
        </th>
        <td class="s3" dir="ltr">R045</td>
        <td class="s3" dir="ltr">Visualizar próprio perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R47" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">48</div>
        </th>
        <td class="s3" dir="ltr">R046</td>
        <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Com que frequência você utiliza as métricas feitas pelo Medium?&quot;
        </td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R48" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">49</div>
        </th>
        <td class="s3" dir="ltr">R047</td>
        <td class="s3" dir="ltr">Visualizar marcações feitas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R49" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">50</div>
        </th>
        <td class="s3" dir="ltr">R048</td>
        <td class="s3" dir="ltr">Criar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R50" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">51</div>
        </th>
        <td class="s3" dir="ltr">R049</td>
        <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R51" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">52</div>
        </th>
        <td class="s3" dir="ltr">R050</td>
        <td class="s6">Editar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R52" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">53</div>
        </th>
        <td class="s3" dir="ltr">R051</td>
        <td class="s6">Deletar Publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R53" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">54</div>
        </th>
        <td class="s3" dir="ltr">R052</td>
        <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Qual os assuntos pelo quais você se interessa ao acessar o
          MEDIUM?&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R54" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">55</div>
        </th>
        <td class="s3" dir="ltr">R053</td>
        <td class="s3" dir="ltr">Deixar de seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R55" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">56</div>
        </th>
        <td class="s3" dir="ltr">R054</td>
        <td class="s3" dir="ltr">Deixar de seguir publicações</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R56" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">57</div>
        </th>
        <td class="s3" dir="ltr">R055</td>
        <td class="s3">Aivar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R57" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">58</div>
        </th>
        <td class="s3" dir="ltr">R056</td>
        <td class="s3">Automatizar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:53px;'>
        <th id="0R58" style="height: 53px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 53px;">59</div>
        </th>
        <td class="s3">R057</td>
        <td class="s3">Editar email padrão</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R59" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">60</div>
        </th>
        <td class="s3">R058</td>
        <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R60" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">61</div>
        </th>
        <td class="s3">R059</td>
        <td class="s3">Desativar sugestão de artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R61" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">62</div>
        </th>
        <td class="s3">R060</td>
        <td class="s3">Ativar/desativar boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R62" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">63</div>
        </th>
        <td class="s3">R061</td>
        <td class="s3">Selecionar tema do boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:81px;'>
        <th id="0R63" style="height: 81px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 81px;">64</div>
        </th>
        <td class="s3">R062</td>
        <td class="s3">Ativar/desativar recomendações de stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3" dir="ltr"></td>
        <td class="s6" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:92px;'>
        <th id="0R64" style="height: 92px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 92px;">65</div>
        </th>
        <td class="s3">R063</td>
        <td class="s3">Ativar/desativar notificação por e-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R65" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">66</div>
        </th>
        <td class="s3">R064</td>
        <td class="s3">Ativar/desativar notificação social</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R66" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">67</div>
        </th>
        <td class="s3">R065</td>
        <td class="s3">Selecionar privacidade de menções</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R67" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">68</div>
        </th>
        <td class="s3">R066</td>
        <td class="s3">Desativar menções de usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R68" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">69</div>
        </th>
        <td class="s3">R067</td>
        <td class="s3">Conectar com redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R69" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">70</div>
        </th>
        <td class="s3">R068</td>
        <td class="s3">Conectar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R70" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">71</div>
        </th>
        <td class="s3">R069</td>
        <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:59px;'>
        <th id="0R71" style="height: 59px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 59px;">72</div>
        </th>
        <td class="s3">R070</td>
        <td class="s3">Editar nome de usuário para menção</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:50px;'>
        <th id="0R72" style="height: 50px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 50px;">73</div>
        </th>
        <td class="s3">R071</td>
        <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R73" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">74</div>
        </th>
        <td class="s3">R072</td>
        <td class="s3">Gerenciar usuários bloqueados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:49px;'>
        <th id="0R74" style="height: 49px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 49px;">75</div>
        </th>
        <td class="s3">R073</td>
        <td class="s3">Fazer download de meus dados do Medium</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:83px;'>
        <th id="0R75" style="height: 83px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 83px;">76</div>
        </th>
        <td class="s3">R074</td>
        <td class="s3">Deslogar de outras sessões </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:93px;'>
        <th id="0R76" style="height: 93px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 93px;">77</div>
        </th>
        <td class="s3">R075</td>
        <td class="s3">Desativar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:88px;'>
        <th id="0R77" style="height: 88px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 88px;">78</div>
        </th>
        <td class="s3">R076</td>
        <td class="s3">Deletar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:55px;'>
        <th id="0R78" style="height: 55px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 55px;">79</div>
        </th>
        <td class="s3">R077</td>
        <td class="s3">Visualizar tutorial das áreas da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:54px;'>
        <th id="0R79" style="height: 54px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 54px;">80</div>
        </th>
        <td class="s3">R078</td>
        <td class="s3">Acessar glossário MEDIUM</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:65px;'>
        <th id="0R80" style="height: 65px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 65px;">81</div>
        </th>
        <td class="s3">R079</td>
        <td class="s3">Responder questionário de satisfação da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:56px;'>
        <th id="0R81" style="height: 56px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 56px;">82</div>
        </th>
        <td class="s3">R080</td>
        <td class="s3">Pesquisar tópico de ajuda</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:69px;'>
        <th id="0R82" style="height: 69px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 69px;">83</div>
        </th>
        <td class="s3">R081</td>
        <td class="s3">Escolher plano de assinatura membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:52px;'>
        <th id="0R83" style="height: 52px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 52px;">84</div>
        </th>
        <td class="s3">R082</td>
        <td class="s3">Inserir forma de pagamento do medium membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:37px;'>
        <th id="0R84" style="height: 37px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 37px;">85</div>
        </th>
        <td class="s3">R083</td>
        <td class="s3">Login via redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:35px;'>
        <th id="0R85" style="height: 35px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 35px;">86</div>
        </th>
        <td class="s3">R084</td>
        <td class="s3">Login via Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:39px;'>
        <th id="0R86" style="height: 39px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 39px;">87</div>
        </th>
        <td class="s3">R085</td>
        <td class="s3">Login via E-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:35px;'>
        <th id="0R87" style="height: 35px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 35px;">88</div>
        </th>
        <td class="s3">R086</td>
        <td class="s3">Cadastrar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:38px;'>
        <th id="0R88" style="height: 38px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 38px;">89</div>
        </th>
        <td class="s3">R087</td>
        <td class="s3">Cadastrar com Facebook</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s6"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R89" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">90</div>
        </th>
        <td class="s3">R088</td>
        <td class="s3">Segurança</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R90" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">91</div>
        </th>
        <td class="s3">R089</td>
        <td class="s3">Desempenho</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3" dir="ltr"></td>
        <td class="s3"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R91" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">92</div>
        </th>
        <td class="s7" dir="ltr"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R92" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">93</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s9">StoryTelling e StoryBoard</td>
        <td class="s9">Brainstorming</td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R93" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">94</div>
        </th>
        <td class="s3" dir="ltr">R001</td>
        <td class="s3" dir="ltr">Responsividade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">StoryBoard Customização de interesses</td>
        <td class="s6">Brainstorming &quot;William: carregamento eficiente de artigos&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R94" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">95</div>
        </th>
        <td class="s3" dir="ltr">R002</td>
        <td class="s3" dir="ltr">Portabilidade mobile ios</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">StoryBoard Customização de interesses</td>
        <td class="s6">Brainstorming 2 &quot; Matheus: A aplicação está disponível em plataformas : web e mobile
          (ios/android)&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R95" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">96</div>
        </th>
        <td class="s3" dir="ltr">R003</td>
        <td class="s3" dir="ltr">Portabilidade mobile android</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">StoryBoard Customização de interesses</td>
        <td class="s6">Brainstorming 2 &quot; Matheus: A aplicação está disponível em plataformas : web e mobile
          (ios/android)&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R96" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">97</div>
        </th>
        <td class="s3" dir="ltr">R004</td>
        <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryBoard Tutorial e seguir escritor</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R97" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">98</div>
        </th>
        <td class="s3" dir="ltr">R005</td>
        <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">Brainstorming 4 &quot;matheus: ter um registro dos seus textos em seu blog&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R98" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">99</div>
        </th>
        <td class="s3" dir="ltr">R006</td>
        <td class="s3" dir="ltr">Política de privacidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">StoryBoard Login e cadastro</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R99" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">100</div>
        </th>
        <td class="s3" dir="ltr">R007</td>
        <td class="s3" dir="ltr">Identidade Visual</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">Brainstorming 2 &quot; Matheus: o design intuitivo e minimalista torna a experiência mais
          produtiva&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R100" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">101</div>
        </th>
        <td class="s3" dir="ltr">R008</td>
        <td class="s3" dir="ltr">Alta disponibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R101" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">102</div>
        </th>
        <td class="s3" dir="ltr">R009</td>
        <td class="s3" dir="ltr">Controle de Conteúdo</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">StoryBoard Customização de interesses</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R102" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">103</div>
        </th>
        <td class="s3" dir="ltr">R010</td>
        <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R103" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">104</div>
        </th>
        <td class="s3" dir="ltr">R011</td>
        <td class="s3" dir="ltr">Manutenibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R104" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">105</div>
        </th>
        <td class="s3" dir="ltr">R012</td>
        <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">Brainstorming 3 &quot;Matheus: os usuários podem ver os textos publicados na página de um
          escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R105" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">106</div>
        </th>
        <td class="s3" dir="ltr">R013</td>
        <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R106" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">107</div>
        </th>
        <td class="s3" dir="ltr">R014</td>
        <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R107" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">108</div>
        </th>
        <td class="s3" dir="ltr">R015</td>
        <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R108" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">109</div>
        </th>
        <td class="s3" dir="ltr">R016</td>
        <td class="s3" dir="ltr">Ver status</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">Brainstorming 4 &quot; Matheus: ver quem deu clap em suas publicações&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R109" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">110</div>
        </th>
        <td class="s3" dir="ltr">R017</td>
        <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R110" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">111</div>
        </th>
        <td class="s3" dir="ltr">R018</td>
        <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R111" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">112</div>
        </th>
        <td class="s3" dir="ltr">R019</td>
        <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R112" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">113</div>
        </th>
        <td class="s3" dir="ltr">R020</td>
        <td class="s3" dir="ltr">Visualizar stories publicadas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryBoard Tutorial e seguir escritor</td>
        <td class="s6">Brainstorming 3 &quot;Matheus: os usuários podem ver os textos publicados na página de um
          escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R113" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">114</div>
        </th>
        <td class="s3" dir="ltr">R021</td>
        <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R114" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">115</div>
        </th>
        <td class="s3" dir="ltr">R022</td>
        <td class="s3" dir="ltr">Editar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R115" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">116</div>
        </th>
        <td class="s3" dir="ltr">R023</td>
        <td class="s3" dir="ltr">Deletar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R116" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">117</div>
        </th>
        <td class="s3" dir="ltr">R024</td>
        <td class="s3" dir="ltr">Aplaudir um texto lido</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryBoard Tutorial e seguir escritor</td>
        <td class="s6">Brainstorming 3 &quot;matheus: o leitor poder gostar do texto&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R117" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">118</div>
        </th>
        <td class="s3" dir="ltr">R025</td>
        <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryTelling - Escritor, New Story</td>
        <td class="s6">Brainstorming 3 &quot;matheus: compartilhar o texto&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R118" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">119</div>
        </th>
        <td class="s3" dir="ltr">R026</td>
        <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">Brainstorming 4 &quot;Pedro: ver comentários de seus textos e responder os comentários de seus
          textos&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R119" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">120</div>
        </th>
        <td class="s3" dir="ltr">R027</td>
        <td class="s3" dir="ltr">Escutar podcasts</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryBoard Tutorial e seguir escritor</td>
        <td class="s6">Brainstorming 3 &quot;Gabriel: escutar podcasts&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R120" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">121</div>
        </th>
        <td class="s3" dir="ltr">R028</td>
        <td class="s3" dir="ltr">Seguir escritores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryBoard Tutorial e seguir escritor</td>
        <td class="s6">Brainstorming 3 &quot;Matheus: seguir o escritor&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R121" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">122</div>
        </th>
        <td class="s3" dir="ltr">R029</td>
        <td class="s3" dir="ltr">Seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6"> </td>
        <td class="s6">Brainstorming 3: &quot;Gabriel: Seguir outros usuários&quot;</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R122" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">123</div>
        </th>
        <td class="s3" dir="ltr">R030</td>
        <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Brainstorming 3: &quot;William: O leitor recebe as notificações de publicações de seus escritores
          favoritados</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R123" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">124</div>
        </th>
        <td class="s3" dir="ltr">R031</td>
        <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Brainstorming 3: &quot;Gabriel: Selecionar tema de artigos&quot;</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R124" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">125</div>
        </th>
        <td class="s3" dir="ltr">R032</td>
        <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Brainstorming 3: &quot;Matheus: os usuários podem ver os textos publicados na página de um
          escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R125" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">126</div>
        </th>
        <td class="s3" dir="ltr">R033</td>
        <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R126" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">127</div>
        </th>
        <td class="s3" dir="ltr">R034</td>
        <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R127" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">128</div>
        </th>
        <td class="s3" dir="ltr">R035</td>
        <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Brainstorming 2: &quot;William: visualizar os perfis de outros usuários&quot;</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R128" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">129</div>
        </th>
        <td class="s3" dir="ltr">R036</td>
        <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Brainstorming 3: &quot;Matheus: o leitor poder gostar do texto&quot;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R129" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">130</div>
        </th>
        <td class="s3" dir="ltr">R037</td>
        <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Brainstorming 4: &quot;Pedro: ver comentários de seus textos e responder os comentários de seus
          textos&quot;</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R130" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">131</div>
        </th>
        <td class="s3" dir="ltr">R038</td>
        <td class="s3" dir="ltr">Reportar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Editar Perfil</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R131" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">132</div>
        </th>
        <td class="s3" dir="ltr">R039</td>
        <td class="s3" dir="ltr">Reportar usuário</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Editar Perfil</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R132" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">133</div>
        </th>
        <td class="s3" dir="ltr">R040</td>
        <td class="s3" dir="ltr">Editar informações de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Editar Perfil: &quot;Ao lado do seu nome nesta página de perfil, existia um botão
          chamado “Edit profile” e logo Carlos clicou sobre esse botão.&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R133" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">134</div>
        </th>
        <td class="s3" dir="ltr">R041</td>
        <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Editar Perfil: &quot;Após ter editado tudo o que desejava, Carlos clicou no botão
          chamado “Save” e foi redirecionado para a página que apresentava os seus dados cadastrais, agora
          editados.&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R134" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">135</div>
        </th>
        <td class="s3" dir="ltr">R042</td>
        <td class="s3" dir="ltr">Visualizar autores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryBoard - Tutorial e seguir escritor: &quot;Realmente. E ainda consigo seguir o perfil de
          escritores dos tutoriais estando logado&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R135" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">136</div>
        </th>
        <td class="s3" dir="ltr">R043</td>
        <td class="s3" dir="ltr">Visualizar seguidores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Escritor New Story: &quot;Medium, como é chamado o site, é uma plataforma pensada
          na troca de conhecimentos por seus usuários, a partir de textos técnicos, assuntos atuais, sociais,
          tecnológicos, psicológicos e até mesmo pesquisas&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R136" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">137</div>
        </th>
        <td class="s3" dir="ltr">R044</td>
        <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Escritor New Story: &quot;Entretanto, ela estava satisfeita com os resultados,
          pois havia recebido um bom número de “claps”&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R137" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">138</div>
        </th>
        <td class="s3" dir="ltr">R045</td>
        <td class="s3" dir="ltr">Visualizar próprio perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Editar Perfil: &quot;Entre essas opções estava escrita a opção “Profile”, então
          Carlos clicou sobre essa opção e ao mesmo instante ele foi redirecionado para uma página que apresentava todos
          os seus dados cadastrais.&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R138" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">139</div>
        </th>
        <td class="s3" dir="ltr">R046</td>
        <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Editar Perfil: &quot;Ao começar a ganhar visibilidade em suas publicações, Carlos
          passou a receber comentários pedindo informações sobre a sua formação acadêmica, assim como o seu nome
          completo&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R139" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">140</div>
        </th>
        <td class="s3" dir="ltr">R047</td>
        <td class="s3" dir="ltr">Visualizar marcações feitas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">StoryBoard - Bookmarking: &quot;Nossa! O artigo é muito grande, acho que vou salvar para ler mais
          tarde&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R140" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">141</div>
        </th>
        <td class="s3" dir="ltr">R048</td>
        <td class="s3" dir="ltr">Criar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Escritor New Story: &quot;Natália percebeu que havia mais de uma maneira de se
          publicar um texto.&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R141" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">142</div>
        </th>
        <td class="s3" dir="ltr">R049</td>
        <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Escritor New Story: &quot;salvar o link do rascunho e customizar o link de sua
          publicação&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R142" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">143</div>
        </th>
        <td class="s3" dir="ltr">R050</td>
        <td class="s6">Editar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R143" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">144</div>
        </th>
        <td class="s3" dir="ltr">R051</td>
        <td class="s6">Deletar Publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R144" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">145</div>
        </th>
        <td class="s3" dir="ltr">R052</td>
        <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R145" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">146</div>
        </th>
        <td class="s3" dir="ltr">R053</td>
        <td class="s3" dir="ltr">Deixar de seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R146" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">147</div>
        </th>
        <td class="s3" dir="ltr">R054</td>
        <td class="s3" dir="ltr">Deixar de seguir publicações</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R147" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">148</div>
        </th>
        <td class="s3" dir="ltr">R055</td>
        <td class="s3">Aivar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Configurações</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R148" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">149</div>
        </th>
        <td class="s3" dir="ltr">R056</td>
        <td class="s3">Automatizar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Storytelling - Configurações</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R149" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">150</div>
        </th>
        <td class="s3">R057</td>
        <td class="s3">Editar email padrão</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s6">Brainstorming 2:<br>&quot;William&quot;,editar seu próprio perfil<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R150" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">151</div>
        </th>
        <td class="s3">R058</td>
        <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R151" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">152</div>
        </th>
        <td class="s3">R059</td>
        <td class="s3">Desativar sugestão de artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R152" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">153</div>
        </th>
        <td class="s3">R060</td>
        <td class="s3">Ativar/desativar boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R153" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">154</div>
        </th>
        <td class="s3">R061</td>
        <td class="s3">Selecionar tema do boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R154" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">155</div>
        </th>
        <td class="s3">R062</td>
        <td class="s3">Ativar/desativar recomendações de stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s6">Brainstorming 3: &quot;Gabriel&quot;,selecionar tema de artigo; &quot;Matheus&quot;,Escolher os
          textos na homepage<br><br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R155" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">156</div>
        </th>
        <td class="s3">R063</td>
        <td class="s3">Ativar/desativar notificação por e-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s6">Brainstorming 3: &quot;William&quot;,O leitor recebe as notificações de publicações de seus
          escritores favoritados<br></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R156" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">157</div>
        </th>
        <td class="s3">R064</td>
        <td class="s3">Ativar/desativar notificação social</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R157" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">158</div>
        </th>
        <td class="s3">R065</td>
        <td class="s3">Selecionar privacidade de menções</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R158" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">159</div>
        </th>
        <td class="s3">R066</td>
        <td class="s3">Desativar menções de usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R159" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">160</div>
        </th>
        <td class="s3">R067</td>
        <td class="s3">Conectar com redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R160" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">161</div>
        </th>
        <td class="s3">R068</td>
        <td class="s3">Conectar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R161" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">162</div>
        </th>
        <td class="s3">R069</td>
        <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R162" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">163</div>
        </th>
        <td class="s3">R070</td>
        <td class="s3">Editar nome de usuário para menção</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R163" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">164</div>
        </th>
        <td class="s3">R071</td>
        <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R164" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">165</div>
        </th>
        <td class="s3">R072</td>
        <td class="s3">Gerenciar usuários bloqueados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R165" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">166</div>
        </th>
        <td class="s3">R073</td>
        <td class="s3">Fazer download de meus dados do Medium</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R166" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">167</div>
        </th>
        <td class="s3">R074</td>
        <td class="s3">Deslogar de outras sessões </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R167" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">168</div>
        </th>
        <td class="s3">R075</td>
        <td class="s3">Desativar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R168" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">169</div>
        </th>
        <td class="s3">R076</td>
        <td class="s3">Deletar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R169" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">170</div>
        </th>
        <td class="s3">R077</td>
        <td class="s3">Visualizar tutorial das áreas da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R170" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">171</div>
        </th>
        <td class="s3">R078</td>
        <td class="s3">Acessar glossário MEDIUM</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R171" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">172</div>
        </th>
        <td class="s3">R079</td>
        <td class="s3">Responder questionário de satisfação da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R172" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">173</div>
        </th>
        <td class="s3">R080</td>
        <td class="s3">Pesquisar tópico de ajuda</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Usuário, Configurando a aplicação<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R173" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">174</div>
        </th>
        <td class="s3">R081</td>
        <td class="s3">Escolher plano de assinatura membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R174" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">175</div>
        </th>
        <td class="s3">R082</td>
        <td class="s3">Inserir forma de pagamento do medium membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R175" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">176</div>
        </th>
        <td class="s3">R083</td>
        <td class="s3">Login via redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Login e Cadastro<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R176" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">177</div>
        </th>
        <td class="s3">R084</td>
        <td class="s3">Login via Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Login e Cadastro<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R177" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">178</div>
        </th>
        <td class="s3">R085</td>
        <td class="s3">Login via E-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Login e Cadastro<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R178" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">179</div>
        </th>
        <td class="s3">R086</td>
        <td class="s3">Cadastrar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Login e Cadastro<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R179" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">180</div>
        </th>
        <td class="s3">R087</td>
        <td class="s3">Cadastrar com Facebook</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Login e Cadastro<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R180" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">181</div>
        </th>
        <td class="s3">R088</td>
        <td class="s3">Segurança</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R181" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">182</div>
        </th>
        <td class="s3">R089</td>
        <td class="s3">Desempenho</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R182" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">183</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R183" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">184</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s9">Instrospecção</td>
        <td class="s9">Cenários</td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R184" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">185</div>
        </th>
        <td class="s3" dir="ltr">R001</td>
        <td class="s3" dir="ltr">Responsividade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R185" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">186</div>
        </th>
        <td class="s3" dir="ltr">R002</td>
        <td class="s3" dir="ltr">Portabilidade mobile ios</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R186" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">187</div>
        </th>
        <td class="s3" dir="ltr">R003</td>
        <td class="s3" dir="ltr">Portabilidade mobile android</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R187" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">188</div>
        </th>
        <td class="s3" dir="ltr">R004</td>
        <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">Pesquisa por artigo</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R188" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">189</div>
        </th>
        <td class="s3" dir="ltr">R005</td>
        <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">Leitura de texto</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R189" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">190</div>
        </th>
        <td class="s3" dir="ltr">R006</td>
        <td class="s3" dir="ltr">Política de privacidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R190" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">191</div>
        </th>
        <td class="s3" dir="ltr">R007</td>
        <td class="s3" dir="ltr">Identidade Visual</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R191" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">192</div>
        </th>
        <td class="s3" dir="ltr">R008</td>
        <td class="s3" dir="ltr">Alta disponibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s10"></td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R192" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">193</div>
        </th>
        <td class="s3" dir="ltr">R009</td>
        <td class="s3" dir="ltr">Controle de Conteúdo</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">Relato de introspecção 6: Customização de Interesses</td>
        <td class="s6">Customizar interesses</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R193" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">194</div>
        </th>
        <td class="s3" dir="ltr">R010</td>
        <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R194" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">195</div>
        </th>
        <td class="s3" dir="ltr">R011</td>
        <td class="s3" dir="ltr">Manutenibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R195" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">196</div>
        </th>
        <td class="s3" dir="ltr">R012</td>
        <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">Leitura de texto</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R196" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">197</div>
        </th>
        <td class="s3" dir="ltr">R013</td>
        <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R197" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">198</div>
        </th>
        <td class="s3" dir="ltr">R014</td>
        <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R198" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">199</div>
        </th>
        <td class="s3" dir="ltr">R015</td>
        <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R199" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">200</div>
        </th>
        <td class="s3" dir="ltr">R016</td>
        <td class="s3" dir="ltr">Ver status</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R200" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">201</div>
        </th>
        <td class="s3" dir="ltr">R017</td>
        <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R201" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">202</div>
        </th>
        <td class="s3" dir="ltr">R018</td>
        <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R202" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">203</div>
        </th>
        <td class="s3" dir="ltr">R019</td>
        <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R203" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">204</div>
        </th>
        <td class="s3" dir="ltr">R020</td>
        <td class="s3" dir="ltr">Visualizar stories publicadas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R204" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">205</div>
        </th>
        <td class="s3" dir="ltr">R021</td>
        <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Importar um storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R205" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">206</div>
        </th>
        <td class="s3" dir="ltr">R022</td>
        <td class="s3" dir="ltr">Editar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R206" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">207</div>
        </th>
        <td class="s3" dir="ltr">R023</td>
        <td class="s3" dir="ltr">Deletar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6">Criar um novo Storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R207" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">208</div>
        </th>
        <td class="s3" dir="ltr">R024</td>
        <td class="s3" dir="ltr">Aplaudir um texto lido</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">Dar Claps</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R208" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">209</div>
        </th>
        <td class="s3" dir="ltr">R025</td>
        <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s6"> Compartilhar publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R209" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">210</div>
        </th>
        <td class="s3" dir="ltr">R026</td>
        <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">Comentar publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R210" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">211</div>
        </th>
        <td class="s3" dir="ltr">R027</td>
        <td class="s3" dir="ltr">Escutar podcasts</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">Leitura de texto</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R211" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">212</div>
        </th>
        <td class="s3" dir="ltr">R028</td>
        <td class="s3" dir="ltr">Seguir escritores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s6">Seguir usuário</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R212" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">213</div>
        </th>
        <td class="s3" dir="ltr">R029</td>
        <td class="s3" dir="ltr">Seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Seguir usuário</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R213" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">214</div>
        </th>
        <td class="s3" dir="ltr">R030</td>
        <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Configurar notificações</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R214" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">215</div>
        </th>
        <td class="s3" dir="ltr">R031</td>
        <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Pesquisa por artigo</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R215" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">216</div>
        </th>
        <td class="s3" dir="ltr">R032</td>
        <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R216" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">217</div>
        </th>
        <td class="s3" dir="ltr">R033</td>
        <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta
          uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto
          em que cada artigo salvo foi fechado;&quot;</td>
        <td class="s6">Criar um novo Bookmark</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R217" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">218</div>
        </th>
        <td class="s3" dir="ltr">R034</td>
        <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta
          uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto
          em que cada artigo salvo foi fechado;&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R218" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">219</div>
        </th>
        <td class="s3" dir="ltr">R035</td>
        <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Seguir usuário</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R219" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">220</div>
        </th>
        <td class="s3" dir="ltr">R036</td>
        <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta
          uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto
          em que cada artigo salvo foi fechado;&quot;</td>
        <td class="s6">Criar um novo Bookmark</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R220" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">221</div>
        </th>
        <td class="s3" dir="ltr">R037</td>
        <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Comentar publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R221" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">222</div>
        </th>
        <td class="s3" dir="ltr">R038</td>
        <td class="s3" dir="ltr">Reportar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R222" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">223</div>
        </th>
        <td class="s3" dir="ltr">R039</td>
        <td class="s3" dir="ltr">Reportar usuário</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R223" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">224</div>
        </th>
        <td class="s3" dir="ltr">R040</td>
        <td class="s3" dir="ltr">Editar informações de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Editar perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R224" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">225</div>
        </th>
        <td class="s3" dir="ltr">R041</td>
        <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Editar perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R225" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">226</div>
        </th>
        <td class="s3" dir="ltr">R042</td>
        <td class="s3" dir="ltr">Visualizar autores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Deixar de seguir usuário</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R226" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">227</div>
        </th>
        <td class="s3" dir="ltr">R043</td>
        <td class="s3" dir="ltr">Visualizar seguidores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R227" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">228</div>
        </th>
        <td class="s3" dir="ltr">R044</td>
        <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Dar clap</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R228" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">229</div>
        </th>
        <td class="s3" dir="ltr">R045</td>
        <td class="s3" dir="ltr">Visualizar próprio perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Editar perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R229" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">230</div>
        </th>
        <td class="s3" dir="ltr">R046</td>
        <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R230" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">231</div>
        </th>
        <td class="s3" dir="ltr">R047</td>
        <td class="s3" dir="ltr">Visualizar marcações feitas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Criar um novo Bookmark</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R231" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">232</div>
        </th>
        <td class="s3" dir="ltr">R048</td>
        <td class="s3" dir="ltr">Criar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Criar um storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R232" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">233</div>
        </th>
        <td class="s3" dir="ltr">R049</td>
        <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Criar um storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R233" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">234</div>
        </th>
        <td class="s3" dir="ltr">R050</td>
        <td class="s6">Editar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Criar um storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R234" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">235</div>
        </th>
        <td class="s3" dir="ltr">R051</td>
        <td class="s6">Deletar Publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Criar um storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R235" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">236</div>
        </th>
        <td class="s3" dir="ltr">R052</td>
        <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de instrospecção 6: &quot;Deve mostrar escritores sugeridos para os interesses do
          leitor.&quot;</td>
        <td class="s6">Customizar interesses</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R236" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">237</div>
        </th>
        <td class="s3" dir="ltr">R053</td>
        <td class="s3" dir="ltr">Deixar de seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de instrospecção 6: &quot;Deve ser capaz de deixar de seguir Blogs e escritores.&quot;
        </td>
        <td class="s6">Deixar de seguir usuário</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R237" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">238</div>
        </th>
        <td class="s3" dir="ltr">R054</td>
        <td class="s3" dir="ltr">Deixar de seguir publicações</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 3: &quot;Poder tornar o texto público ou privado para apenas um número
          definido de leitores;&quot;</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R238" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">239</div>
        </th>
        <td class="s3" dir="ltr">R055</td>
        <td class="s3">Aivar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R239" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">240</div>
        </th>
        <td class="s3" dir="ltr">R056</td>
        <td class="s3">Automatizar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R240" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">241</div>
        </th>
        <td class="s3">R057</td>
        <td class="s3">Editar email padrão</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">C04: Editar perfil</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R241" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">242</div>
        </th>
        <td class="s3">R058</td>
        <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">C10:Configurar notificações de e-mail<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R242" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">243</div>
        </th>
        <td class="s3">R059</td>
        <td class="s3">Desativar sugestão de artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">C10:Configurar notificações de e-mail<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R243" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">244</div>
        </th>
        <td class="s3">R060</td>
        <td class="s3">Ativar/desativar boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação:
          Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
        <td class="s6">C10:Configurar notificações de e-mail<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R244" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">245</div>
        </th>
        <td class="s3">R061</td>
        <td class="s3">Selecionar tema do boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação:
          Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
        <td class="s6">C10:Configurar notificações de e-mail<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R245" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">246</div>
        </th>
        <td class="s3">R062</td>
        <td class="s3">Ativar/desativar recomendações de stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">C10:Configurar notificações de e-mail<br></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R246" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">247</div>
        </th>
        <td class="s3">R063</td>
        <td class="s3">Ativar/desativar notificação por e-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação:
          Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R247" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">248</div>
        </th>
        <td class="s3">R064</td>
        <td class="s3">Ativar/desativar notificação social</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R248" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">249</div>
        </th>
        <td class="s3">R065</td>
        <td class="s3">Selecionar privacidade de menções</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R249" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">250</div>
        </th>
        <td class="s3">R066</td>
        <td class="s3">Desativar menções de usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R250" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">251</div>
        </th>
        <td class="s3">R067</td>
        <td class="s3">Conectar com redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R251" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">252</div>
        </th>
        <td class="s3">R068</td>
        <td class="s3">Conectar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R252" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">253</div>
        </th>
        <td class="s3">R069</td>
        <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R253" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">254</div>
        </th>
        <td class="s3">R070</td>
        <td class="s3">Editar nome de usuário para menção</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R254" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">255</div>
        </th>
        <td class="s3">R071</td>
        <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R255" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">256</div>
        </th>
        <td class="s3">R072</td>
        <td class="s3">Gerenciar usuários bloqueados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R256" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">257</div>
        </th>
        <td class="s3">R073</td>
        <td class="s3">Fazer download de meus dados do Medium</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R257" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">258</div>
        </th>
        <td class="s3">R074</td>
        <td class="s3">Deslogar de outras sessões </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R258" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">259</div>
        </th>
        <td class="s3">R075</td>
        <td class="s3">Desativar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R259" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">260</div>
        </th>
        <td class="s3">R076</td>
        <td class="s3">Deletar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R260" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">261</div>
        </th>
        <td class="s3">R077</td>
        <td class="s3">Visualizar tutorial das áreas da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R261" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">262</div>
        </th>
        <td class="s3">R078</td>
        <td class="s3">Acessar glossário MEDIUM</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R262" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">263</div>
        </th>
        <td class="s3">R079</td>
        <td class="s3">Responder questionário de satisfação da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R263" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">264</div>
        </th>
        <td class="s3">R080</td>
        <td class="s3">Pesquisar tópico de ajuda</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R264" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">265</div>
        </th>
        <td class="s3">R081</td>
        <td class="s3">Escolher plano de assinatura membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">C05: Premium</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R265" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">266</div>
        </th>
        <td class="s3">R082</td>
        <td class="s3">Inserir forma de pagamento do medium membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">C05: Premium</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R266" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">267</div>
        </th>
        <td class="s3">R083</td>
        <td class="s3">Login via redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 2:Usuário não logado;i , ii e iii</td>
        <td class="s6">C07:login</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R267" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">268</div>
        </th>
        <td class="s3">R084</td>
        <td class="s3">Login via Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 2:Usuário não logado;i , ii e iii</td>
        <td class="s6">C07:login</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R268" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">269</div>
        </th>
        <td class="s3">R085</td>
        <td class="s3">Login via E-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 2:Usuário não logado;i , ii e iii</td>
        <td class="s6">C07:login</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R269" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">270</div>
        </th>
        <td class="s3">R086</td>
        <td class="s3">Cadastrar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 2:Usuário não cadastrado, i e ii</td>
        <td class="s6">C06:Cadastro</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R270" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">271</div>
        </th>
        <td class="s3">R087</td>
        <td class="s3">Cadastrar com Facebook</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Relato de introspecção 2:Usuário não cadastrado, i e ii</td>
        <td class="s6">C06:Cadastro</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R271" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">272</div>
        </th>
        <td class="s3">R088</td>
        <td class="s3">Segurança</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s10"></td>
        <td class="s6">C06 e C07</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R272" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">273</div>
        </th>
        <td class="s3">R089</td>
        <td class="s3">Desempenho</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R273" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">274</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R274" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">275</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s9">Léxicos</td>
        <td class="s9">Casos de uso</td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R275" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">276</div>
        </th>
        <td class="s3" dir="ltr">R001</td>
        <td class="s3" dir="ltr">Responsividade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R276" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">277</div>
        </th>
        <td class="s3" dir="ltr">R002</td>
        <td class="s3" dir="ltr">Portabilidade mobile ios</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R277" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">278</div>
        </th>
        <td class="s3" dir="ltr">R003</td>
        <td class="s3" dir="ltr">Portabilidade mobile android</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R278" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">279</div>
        </th>
        <td class="s3" dir="ltr">R004</td>
        <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R279" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">280</div>
        </th>
        <td class="s3" dir="ltr">R005</td>
        <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R280" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">281</div>
        </th>
        <td class="s3" dir="ltr">R006</td>
        <td class="s3" dir="ltr">Política de privacidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">Léxico About</td>
        <td class="s6">UC Configurar perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R281" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">282</div>
        </th>
        <td class="s3" dir="ltr">R007</td>
        <td class="s3" dir="ltr">Identidade Visual</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R282" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">283</div>
        </th>
        <td class="s3" dir="ltr">R008</td>
        <td class="s3" dir="ltr">Alta disponibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R283" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">284</div>
        </th>
        <td class="s3" dir="ltr">R009</td>
        <td class="s3" dir="ltr">Controle de Conteúdo</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">Léxico Content</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R284" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">285</div>
        </th>
        <td class="s3" dir="ltr">R010</td>
        <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Series</td>
        <td class="s6">UC Series</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R285" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">286</div>
        </th>
        <td class="s3" dir="ltr">R011</td>
        <td class="s3" dir="ltr">Manutenibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s10"></td>
        <td class="s6">-</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R286" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">287</div>
        </th>
        <td class="s3" dir="ltr">R012</td>
        <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Series</td>
        <td class="s6">UC Series</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R287" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">288</div>
        </th>
        <td class="s3" dir="ltr">R013</td>
        <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Series</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R288" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">289</div>
        </th>
        <td class="s3" dir="ltr">R014</td>
        <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Series</td>
        <td class="s6">UC Series</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R289" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">290</div>
        </th>
        <td class="s3" dir="ltr">R015</td>
        <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Series</td>
        <td class="s6">UC Series</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R290" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">291</div>
        </th>
        <td class="s3" dir="ltr">R016</td>
        <td class="s3" dir="ltr">Ver status</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Status</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R291" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">292</div>
        </th>
        <td class="s3" dir="ltr">R017</td>
        <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R292" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">293</div>
        </th>
        <td class="s3" dir="ltr">R018</td>
        <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R293" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">294</div>
        </th>
        <td class="s3" dir="ltr">R019</td>
        <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R294" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">295</div>
        </th>
        <td class="s3" dir="ltr">R020</td>
        <td class="s3" dir="ltr">Visualizar stories publicadas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R295" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">296</div>
        </th>
        <td class="s3" dir="ltr">R021</td>
        <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R296" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">297</div>
        </th>
        <td class="s3" dir="ltr">R022</td>
        <td class="s3" dir="ltr">Editar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R297" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">298</div>
        </th>
        <td class="s3" dir="ltr">R023</td>
        <td class="s3" dir="ltr">Deletar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R298" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">299</div>
        </th>
        <td class="s3" dir="ltr">R024</td>
        <td class="s3" dir="ltr">Aplaudir um texto lido</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Clap</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R299" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">300</div>
        </th>
        <td class="s3" dir="ltr">R025</td>
        <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Share</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R300" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">301</div>
        </th>
        <td class="s3" dir="ltr">R026</td>
        <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxcio Response</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R301" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">302</div>
        </th>
        <td class="s3" dir="ltr">R027</td>
        <td class="s3" dir="ltr">Escutar podcasts</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R302" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">303</div>
        </th>
        <td class="s3" dir="ltr">R028</td>
        <td class="s3" dir="ltr">Seguir escritores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Storie</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R303" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">304</div>
        </th>
        <td class="s3" dir="ltr">R029</td>
        <td class="s3" dir="ltr">Seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Following</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R304" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">305</div>
        </th>
        <td class="s3" dir="ltr">R030</td>
        <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Digest e Léxico Newsletter</td>
        <td class="s6">UC Configurar perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R305" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">306</div>
        </th>
        <td class="s3" dir="ltr">R031</td>
        <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Search e Léxico Tag</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R306" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">307</div>
        </th>
        <td class="s3" dir="ltr">R032</td>
        <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Following</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R307" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">308</div>
        </th>
        <td class="s3" dir="ltr">R033</td>
        <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Bookmark</td>
        <td class="s6">UC Bookmark</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R308" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">309</div>
        </th>
        <td class="s3" dir="ltr">R034</td>
        <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">UC Bookmark</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R309" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">310</div>
        </th>
        <td class="s3" dir="ltr">R035</td>
        <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Profile</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R310" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">311</div>
        </th>
        <td class="s3" dir="ltr">R036</td>
        <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Bookmark</td>
        <td class="s6">UC Bookmark</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R311" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">312</div>
        </th>
        <td class="s3" dir="ltr">R037</td>
        <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Response</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R312" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">313</div>
        </th>
        <td class="s3" dir="ltr">R038</td>
        <td class="s3" dir="ltr">Reportar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">UC Configurar perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R313" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">314</div>
        </th>
        <td class="s3" dir="ltr">R039</td>
        <td class="s3" dir="ltr">Reportar usuário</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">UC Configurar perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R314" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">315</div>
        </th>
        <td class="s3" dir="ltr">R040</td>
        <td class="s3" dir="ltr">Editar informações de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Edit e Léxico Profile</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R315" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">316</div>
        </th>
        <td class="s3" dir="ltr">R041</td>
        <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Edit e Léxico Profile</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R316" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">317</div>
        </th>
        <td class="s3" dir="ltr">R042</td>
        <td class="s3" dir="ltr">Visualizar autores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Following</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R317" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">318</div>
        </th>
        <td class="s3" dir="ltr">R043</td>
        <td class="s3" dir="ltr">Visualizar seguidores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Followers</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R318" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">319</div>
        </th>
        <td class="s3" dir="ltr">R044</td>
        <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Clap</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R319" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">320</div>
        </th>
        <td class="s3" dir="ltr">R045</td>
        <td class="s3" dir="ltr">Visualizar próprio perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Profile</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R320" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">321</div>
        </th>
        <td class="s3" dir="ltr">R046</td>
        <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R321" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">322</div>
        </th>
        <td class="s3" dir="ltr">R047</td>
        <td class="s3" dir="ltr">Visualizar marcações feitas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Bookmark</td>
        <td class="s6">UC Bookmark</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R322" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">323</div>
        </th>
        <td class="s3" dir="ltr">R048</td>
        <td class="s3" dir="ltr">Criar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Stories</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R323" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">324</div>
        </th>
        <td class="s3" dir="ltr">R049</td>
        <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Stories</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R324" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">325</div>
        </th>
        <td class="s3" dir="ltr">R050</td>
        <td class="s6">Editar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Stories</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R325" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">326</div>
        </th>
        <td class="s3" dir="ltr">R051</td>
        <td class="s6">Deletar Publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Stories</td>
        <td class="s6">UC stories</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R326" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">327</div>
        </th>
        <td class="s3" dir="ltr">R052</td>
        <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">UC Cadastro</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R327" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">328</div>
        </th>
        <td class="s3" dir="ltr">R053</td>
        <td class="s3" dir="ltr">Deixar de seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Following</td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R328" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">329</div>
        </th>
        <td class="s3" dir="ltr">R054</td>
        <td class="s3" dir="ltr">Deixar de seguir publicações</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">UC Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R329" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">330</div>
        </th>
        <td class="s3" dir="ltr">R055</td>
        <td class="s3">Aivar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Night Mode</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R330" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">331</div>
        </th>
        <td class="s3" dir="ltr">R056</td>
        <td class="s3">Automatizar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">Léxico Night Mode</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R331" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">332</div>
        </th>
        <td class="s3">R057</td>
        <td class="s3">Editar email padrão</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R332" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">333</div>
        </th>
        <td class="s3">R058</td>
        <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R333" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">334</div>
        </th>
        <td class="s3">R059</td>
        <td class="s3">Desativar sugestão de artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R334" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">335</div>
        </th>
        <td class="s3">R060</td>
        <td class="s3">Ativar/desativar boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R335" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">336</div>
        </th>
        <td class="s3">R061</td>
        <td class="s3">Selecionar tema do boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R336" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">337</div>
        </th>
        <td class="s3">R062</td>
        <td class="s3">Ativar/desativar recomendações de stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R337" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">338</div>
        </th>
        <td class="s3">R063</td>
        <td class="s3">Ativar/desativar notificação por e-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R338" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">339</div>
        </th>
        <td class="s3">R064</td>
        <td class="s3">Ativar/desativar notificação social</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R339" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">340</div>
        </th>
        <td class="s3">R065</td>
        <td class="s3">Selecionar privacidade de menções</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R340" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">341</div>
        </th>
        <td class="s3">R066</td>
        <td class="s3">Desativar menções de usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R341" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">342</div>
        </th>
        <td class="s3">R067</td>
        <td class="s3">Conectar com redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R342" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">343</div>
        </th>
        <td class="s3">R068</td>
        <td class="s3">Conectar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R343" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">344</div>
        </th>
        <td class="s3">R069</td>
        <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R344" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">345</div>
        </th>
        <td class="s3">R070</td>
        <td class="s3">Editar nome de usuário para menção</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R345" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">346</div>
        </th>
        <td class="s3">R071</td>
        <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R346" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">347</div>
        </th>
        <td class="s3">R072</td>
        <td class="s3">Gerenciar usuários bloqueados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R347" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">348</div>
        </th>
        <td class="s3">R073</td>
        <td class="s3">Fazer download de meus dados do Medium</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R348" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">349</div>
        </th>
        <td class="s3">R074</td>
        <td class="s3">Deslogar de outras sessões </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R349" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">350</div>
        </th>
        <td class="s3">R075</td>
        <td class="s3">Desativar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R350" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">351</div>
        </th>
        <td class="s3">R076</td>
        <td class="s3">Deletar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R351" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">352</div>
        </th>
        <td class="s3">R077</td>
        <td class="s3">Visualizar tutorial das áreas da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R352" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">353</div>
        </th>
        <td class="s3">R078</td>
        <td class="s3">Acessar glossário MEDIUM</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R353" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">354</div>
        </th>
        <td class="s3">R079</td>
        <td class="s3">Responder questionário de satisfação da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R354" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">355</div>
        </th>
        <td class="s3">R080</td>
        <td class="s3">Pesquisar tópico de ajuda</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Área comum</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R355" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">356</div>
        </th>
        <td class="s3">R081</td>
        <td class="s3">Escolher plano de assinatura membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Acesso ao Medium Membership<br></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R356" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">357</div>
        </th>
        <td class="s3">R082</td>
        <td class="s3">Inserir forma de pagamento do medium membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Acesso ao Medium Membership<br></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R357" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">358</div>
        </th>
        <td class="s3">R083</td>
        <td class="s3">Login via redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Login</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R358" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">359</div>
        </th>
        <td class="s3">R084</td>
        <td class="s3">Login via Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Login</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R359" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">360</div>
        </th>
        <td class="s3">R085</td>
        <td class="s3">Login via E-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Login</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R360" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">361</div>
        </th>
        <td class="s3">R086</td>
        <td class="s3">Cadastrar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Cadastro de usuário<br></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R361" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">362</div>
        </th>
        <td class="s3">R087</td>
        <td class="s3">Cadastrar com Facebook</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">Cadastro de usuário<br></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R362" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">363</div>
        </th>
        <td class="s3">R088</td>
        <td class="s3">Segurança</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R363" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">364</div>
        </th>
        <td class="s3">R089</td>
        <td class="s3">Desempenho</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R364" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">365</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R365" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">366</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s9">Especificação suplementar</td>
        <td class="s9">Product Backlog</td>
        <td class="s9"></td>
        <td class="s9"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R366" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">367</div>
        </th>
        <td class="s3" dir="ltr">R001</td>
        <td class="s3" dir="ltr">Responsividade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 048 - Usuário: Desejo visualizar as páginas da plataforma em questão de forma responsiva</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R367" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">368</div>
        </th>
        <td class="s3" dir="ltr">R002</td>
        <td class="s3" dir="ltr">Portabilidade mobile ios</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 049 - Usuário: Poder acessar a aplicação via dispositivo IOS</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R368" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">369</div>
        </th>
        <td class="s3" dir="ltr">R003</td>
        <td class="s3" dir="ltr">Portabilidade mobile android</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 050 - Usuário: Poder acessar a aplicação via dispositivo Android</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R369" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">370</div>
        </th>
        <td class="s3" dir="ltr">R004</td>
        <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC03-Pesquisar artigo</td>
        <td class="s6">US 047 - Usuário: Pesquisar por nome de artigo</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R370" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">371</div>
        </th>
        <td class="s3" dir="ltr">R005</td>
        <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R371" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">372</div>
        </th>
        <td class="s3" dir="ltr">R006</td>
        <td class="s3" dir="ltr">Política de privacidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">UC17-Pagar via cartão de crédito</td>
        <td class="s6">US 020 - Usuário: Selecionar privacidade de menções</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R372" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">373</div>
        </th>
        <td class="s3" dir="ltr">R007</td>
        <td class="s3" dir="ltr">Identidade Visual</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R373" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">374</div>
        </th>
        <td class="s3" dir="ltr">R008</td>
        <td class="s3" dir="ltr">Alta disponibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">UC28-Visualizar Stories</td>
        <td class="s6">US 071 - Usuário: Visualizar storie</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R374" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">375</div>
        </th>
        <td class="s3" dir="ltr">R009</td>
        <td class="s3" dir="ltr">Controle de Conteúdo</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">UC05-Ler artigo</td>
        <td class="s6">US 009 - Usuário: selecionar/remover tópicos de interesse</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R375" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">376</div>
        </th>
        <td class="s3" dir="ltr">R010</td>
        <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC23 - Criar series</td>
        <td class="s6">US 059 - Usuário Escritor: Criar uma nova Serie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R376" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">377</div>
        </th>
        <td class="s3" dir="ltr">R011</td>
        <td class="s3" dir="ltr">Manutenibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s10"></td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R377" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">378</div>
        </th>
        <td class="s3" dir="ltr">R012</td>
        <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC20-Visualizar Series</td>
        <td class="s6">US 071 - Usuário: Visualizar storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R378" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">379</div>
        </th>
        <td class="s3" dir="ltr">R013</td>
        <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC23 - Criar series</td>
        <td class="s6">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R379" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">380</div>
        </th>
        <td class="s3" dir="ltr">R014</td>
        <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC23 - Criar series</td>
        <td class="s6">US 060 - Usuário Escritor: Editar uma Serie existente</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R380" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">381</div>
        </th>
        <td class="s3" dir="ltr">R015</td>
        <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC36-Excluir Publicação</td>
        <td class="s6">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R381" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">382</div>
        </th>
        <td class="s3" dir="ltr">R016</td>
        <td class="s3" dir="ltr">Ver status</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC20-Visualizar Series</td>
        <td class="s6">US 034 - Usuário: visualizar seguidores</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R382" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">383</div>
        </th>
        <td class="s3" dir="ltr">R017</td>
        <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC32-Escrever uma nova Story.</td>
        <td class="s6">US 063 - Usuário Escritor: Escrever &#39;new storie&#39;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R383" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">384</div>
        </th>
        <td class="s3" dir="ltr">R018</td>
        <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC32-Escrever uma nova Story.</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R384" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">385</div>
        </th>
        <td class="s3" dir="ltr">R019</td>
        <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC32-Escrever uma nova Story.</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R385" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">386</div>
        </th>
        <td class="s3" dir="ltr">R020</td>
        <td class="s3" dir="ltr">Visualizar stories publicadas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC28-Visualizar Stories</td>
        <td class="s6">US 071 - Usuário: Visualizar storie</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R386" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">387</div>
        </th>
        <td class="s3" dir="ltr">R021</td>
        <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC31-Importar uma Story</td>
        <td class="s6">US 064 - Usuário Escritor: Importar &#39;storie&#39;</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R387" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">388</div>
        </th>
        <td class="s3" dir="ltr">R022</td>
        <td class="s3" dir="ltr">Editar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC35-Editar Publicação</td>
        <td class="s6">US 060 - Usuário Escritor: Editar uma Serie existente</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R388" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">389</div>
        </th>
        <td class="s3" dir="ltr">R023</td>
        <td class="s3" dir="ltr">Deletar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC36-Excluir Publicação</td>
        <td class="s6">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R389" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">390</div>
        </th>
        <td class="s3" dir="ltr">R024</td>
        <td class="s3" dir="ltr">Aplaudir um texto lido</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 065 - Usuário: Aplaudir um texto lido</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R390" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">391</div>
        </th>
        <td class="s3" dir="ltr">R025</td>
        <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 066 - Usuário: Compartilhar texto lido no Facebook ou Instagram</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R391" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">392</div>
        </th>
        <td class="s3" dir="ltr">R026</td>
        <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 067 - Usuário: Comentar no corpo do texto</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R392" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">393</div>
        </th>
        <td class="s3" dir="ltr">R027</td>
        <td class="s3" dir="ltr">Escutar podcasts</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC04-Escutar podcast</td>
        <td class="s6">US 069 - Usuário: Escutar publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R393" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">394</div>
        </th>
        <td class="s3" dir="ltr">R028</td>
        <td class="s3" dir="ltr">Seguir escritores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 025 - Usuário: Seguir escritores</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R394" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">395</div>
        </th>
        <td class="s3" dir="ltr">R029</td>
        <td class="s3" dir="ltr">Seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 025 - Usuário: Seguir usuários</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R395" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">396</div>
        </th>
        <td class="s3" dir="ltr">R030</td>
        <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US 019 - Usuário: Ativar/desativar notificação por e-mail </td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R396" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">397</div>
        </th>
        <td class="s3" dir="ltr">R031</td>
        <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC03 - Pesquisar artigo</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R397" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">398</div>
        </th>
        <td class="s3" dir="ltr">R032</td>
        <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC30 - Visualizar Publicações</td>
        <td class="s6">US 027 - Usuário: Visualizar textos publicados de um escritor em específico</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R398" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">399</div>
        </th>
        <td class="s3" dir="ltr">R033</td>
        <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 030 - Usuário: Favoritar Publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R399" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">400</div>
        </th>
        <td class="s3" dir="ltr">R034</td>
        <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 030 - Usuário: Favoritar Publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R400" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">401</div>
        </th>
        <td class="s3" dir="ltr">R035</td>
        <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC03 - Pesquisar artigo</td>
        <td class="s6">US 029 - Usuário: Visualizar perfis de outros usuários</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R401" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">402</div>
        </th>
        <td class="s3" dir="ltr">R036</td>
        <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 030 - Usuário: Favoritar Publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R402" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">403</div>
        </th>
        <td class="s3" dir="ltr">R037</td>
        <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC30 - Visualizar Publicações</td>
        <td class="s6">US 031 - Usuário: Visualizar comentários da publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R403" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">404</div>
        </th>
        <td class="s3" dir="ltr">R038</td>
        <td class="s3" dir="ltr">Reportar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US 032 - Usuário: Reportar publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R404" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">405</div>
        </th>
        <td class="s3" dir="ltr">R039</td>
        <td class="s3" dir="ltr">Reportar usuário</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US 033 - Bloquear usuário</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R405" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">406</div>
        </th>
        <td class="s3" dir="ltr">R040</td>
        <td class="s3" dir="ltr">Editar informações de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC09 - Editar perfil</td>
        <td class="s6">US 043 - Usuário: Editar informações de perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R406" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">407</div>
        </th>
        <td class="s3" dir="ltr">R041</td>
        <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC09 - Editar perfil</td>
        <td class="s6">US 043 - Usuário: Editar informações de perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R407" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">408</div>
        </th>
        <td class="s3" dir="ltr">R042</td>
        <td class="s3" dir="ltr">Visualizar autores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R408" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">409</div>
        </th>
        <td class="s3" dir="ltr">R043</td>
        <td class="s3" dir="ltr">Visualizar seguidores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 032 - Usuário: Visualizar seguidores</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R409" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">410</div>
        </th>
        <td class="s3" dir="ltr">R044</td>
        <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC30 - Visualizar Publicações</td>
        <td class="s6">US 057 - Usuário: Visualizar claps em suas publicações</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R410" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">411</div>
        </th>
        <td class="s3" dir="ltr">R045</td>
        <td class="s3" dir="ltr">Visualizar próprio perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC09 - Editar perfil</td>
        <td class="s6">US 044 - Usuário: Visualizar próprio perfil</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R411" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">412</div>
        </th>
        <td class="s3" dir="ltr">R046</td>
        <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US 048 - Usuário: Ver estatísticas de uma série</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R412" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">413</div>
        </th>
        <td class="s3" dir="ltr">R047</td>
        <td class="s3" dir="ltr">Visualizar marcações feitas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R413" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">414</div>
        </th>
        <td class="s3" dir="ltr">R048</td>
        <td class="s3" dir="ltr">Criar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC32 - Escrever uma nova Story</td>
        <td class="s6">US 058 - Usuário: Criar publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R414" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">415</div>
        </th>
        <td class="s3" dir="ltr">R049</td>
        <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC29 - Visualizar Drafts</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R415" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">416</div>
        </th>
        <td class="s3" dir="ltr">R050</td>
        <td class="s6">Editar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC35 - Editar Publicação</td>
        <td class="s6">US 059 - Usuário: Editar publicação</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R416" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">417</div>
        </th>
        <td class="s3" dir="ltr">R051</td>
        <td class="s6">Deletar Publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC36 - Excluir Publicação</td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R417" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">418</div>
        </th>
        <td class="s3" dir="ltr">R052</td>
        <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC01 - Área comum</td>
        <td class="s6">US 008 - Usuário: Selecionar alguns tópicos de meu interesse</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R418" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">419</div>
        </th>
        <td class="s3" dir="ltr">R053</td>
        <td class="s3" dir="ltr">Deixar de seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R419" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">420</div>
        </th>
        <td class="s3" dir="ltr">R054</td>
        <td class="s3" dir="ltr">Deixar de seguir publicações</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">-</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R420" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">421</div>
        </th>
        <td class="s3" dir="ltr">R055</td>
        <td class="s3">Aivar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US010 - Ativar modo noturno </td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R421" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">422</div>
        </th>
        <td class="s3" dir="ltr">R056</td>
        <td class="s3">Automatizar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">US011-Automatizar modo noturno </td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R422" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">423</div>
        </th>
        <td class="s3">R057</td>
        <td class="s3">Editar email padrão</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US012-Editar email padrão </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R423" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">424</div>
        </th>
        <td class="s3">R058</td>
        <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US013-Selecionar período de sugestão de artigos </td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R424" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">425</div>
        </th>
        <td class="s3">R059</td>
        <td class="s3">Desativar sugestão de artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US014-Desativar sugestão de artigos </td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R425" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">426</div>
        </th>
        <td class="s3">R060</td>
        <td class="s3">Ativar/desativar boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US015-Ativar/desativar boletim informativo </td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R426" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">427</div>
        </th>
        <td class="s3">R061</td>
        <td class="s3">Selecionar tema do boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US016-Selecionar tema do boletim informativo </td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R427" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">428</div>
        </th>
        <td class="s3">R062</td>
        <td class="s3">Ativar/desativar recomendações de stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US017-Ativar as recomendações de stories </td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R428" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">429</div>
        </th>
        <td class="s3">R063</td>
        <td class="s3">Ativar/desativar notificação por e-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US018-Ativar as notificação por e-mail </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R429" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">430</div>
        </th>
        <td class="s3">R064</td>
        <td class="s3">Ativar/desativar notificação social</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R430" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">431</div>
        </th>
        <td class="s3">R065</td>
        <td class="s3">Selecionar privacidade de menções</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US019-Gerenciar a privacidade de menções </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R431" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">432</div>
        </th>
        <td class="s3">R066</td>
        <td class="s3">Desativar menções de usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US020-Desativar menções a mim </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R432" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">433</div>
        </th>
        <td class="s3">R067</td>
        <td class="s3">Conectar com redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US006-Conectar com redes sociais </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R433" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">434</div>
        </th>
        <td class="s3">R068</td>
        <td class="s3">Conectar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US007-Conectar com Google </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R434" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">435</div>
        </th>
        <td class="s3">R069</td>
        <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US021-Mostrar links para minhas redes sociais </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R435" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">436</div>
        </th>
        <td class="s3">R070</td>
        <td class="s3">Editar nome de usuário para menção</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R436" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">437</div>
        </th>
        <td class="s3">R071</td>
        <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R437" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">438</div>
        </th>
        <td class="s3">R072</td>
        <td class="s3">Gerenciar usuários bloqueados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R438" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">439</div>
        </th>
        <td class="s3">R073</td>
        <td class="s3">Fazer download de meus dados do Medium</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R439" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">440</div>
        </th>
        <td class="s3">R074</td>
        <td class="s3">Deslogar de outras sessões </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US034-Deslogar de outras sessões </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R440" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">441</div>
        </th>
        <td class="s3">R075</td>
        <td class="s3">Desativar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US022-Desativar minha conta </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R441" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">442</div>
        </th>
        <td class="s3">R076</td>
        <td class="s3">Deletar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US023- Deletar minha conta </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R442" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">443</div>
        </th>
        <td class="s3">R077</td>
        <td class="s3">Visualizar tutorial das áreas da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R443" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">444</div>
        </th>
        <td class="s3">R078</td>
        <td class="s3">Acessar glossário MEDIUM</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US001-Acessar glossário MEDIUM </td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R444" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">445</div>
        </th>
        <td class="s3">R079</td>
        <td class="s3">Responder questionário de satisfação da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US002-Responder questionário de satisfação da aplicação </td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R445" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">446</div>
        </th>
        <td class="s3">R080</td>
        <td class="s3">Pesquisar tópico de ajuda</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC10-Configurar preferências<br><br></td>
        <td class="s6">US003-Pesquisar tópico de ajuda </td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R446" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">447</div>
        </th>
        <td class="s3">R081</td>
        <td class="s3">Escolher plano de assinatura membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC12-Selecionar plano<br><br></td>
        <td class="s6">US038-visualizar os planos de assinatura disponíveis </td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R447" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">448</div>
        </th>
        <td class="s3">R082</td>
        <td class="s3">Inserir forma de pagamento do medium membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC15-Selecionar Método de pagamento<br><br></td>
        <td class="s6">US039-visualizar as formas de pagamento existentes </td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R448" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">449</div>
        </th>
        <td class="s3">R083</td>
        <td class="s3">Login via redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC02-Efetuar Login<br><br></td>
        <td class="s6">US035-Realizar login via redes sociais </td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R449" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">450</div>
        </th>
        <td class="s3">R084</td>
        <td class="s3">Login via Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC02-Efetuar Login<br><br></td>
        <td class="s6">US036-Realizar login via Google </td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R450" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">451</div>
        </th>
        <td class="s3">R085</td>
        <td class="s3">Login via E-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC02-Efetuar Login<br><br></td>
        <td class="s6">US037-Realizar login via E-mail </td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R451" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">452</div>
        </th>
        <td class="s3">R086</td>
        <td class="s3">Cadastrar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC01-Efetuar Cadastro<br><br></td>
        <td class="s6">US004-Realizar cadastro com Google </td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R452" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">453</div>
        </th>
        <td class="s3">R087</td>
        <td class="s3">Cadastrar com Facebook</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">UC01-Efetuar Cadastro<br><br></td>
        <td class="s6">US005-Realizar cadastro com Facebook </td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R453" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">454</div>
        </th>
        <td class="s3">R088</td>
        <td class="s3">Segurança</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R454" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">455</div>
        </th>
        <td class="s3">R089</td>
        <td class="s3">Desempenho</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R455" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">456</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R456" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">457</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s9">NFR</td>
        <td class="s9">I*</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R457" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">458</div>
        </th>
        <td class="s3" dir="ltr">R001</td>
        <td class="s3" dir="ltr">Responsividade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">NFR Iteroperabilidade</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R458" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">459</div>
        </th>
        <td class="s3" dir="ltr">R002</td>
        <td class="s3" dir="ltr">Portabilidade mobile ios</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">NFR Iteroperabilidade<br><br>NFR Usabilidade</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R459" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">460</div>
        </th>
        <td class="s3" dir="ltr">R003</td>
        <td class="s3" dir="ltr">Portabilidade mobile android</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">NFR Iteroperabilidade<br><br>NFR Usabilidade</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R460" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">461</div>
        </th>
        <td class="s3" dir="ltr">R004</td>
        <td class="s3" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R461" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">462</div>
        </th>
        <td class="s3" dir="ltr">R005</td>
        <td class="s3" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R462" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">463</div>
        </th>
        <td class="s3" dir="ltr">R006</td>
        <td class="s3" dir="ltr">Política de privacidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">NFR Controle de Qualidade</td>
        <td class="s6">i* Configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R463" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">464</div>
        </th>
        <td class="s3" dir="ltr">R007</td>
        <td class="s3" dir="ltr">Identidade Visual</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">NFR Usabilidade</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R464" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">465</div>
        </th>
        <td class="s3" dir="ltr">R008</td>
        <td class="s3" dir="ltr">Alta disponibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">NFR Confiabilidade</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R465" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">466</div>
        </th>
        <td class="s3" dir="ltr">R009</td>
        <td class="s3" dir="ltr">Controle de Conteúdo</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">NFR Controle de Qualidade</td>
        <td class="s6">I* Customização de interesses</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R466" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">467</div>
        </th>
        <td class="s3" dir="ltr">R010</td>
        <td class="s3" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R467" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">468</div>
        </th>
        <td class="s3" dir="ltr">R011</td>
        <td class="s3" dir="ltr">Manutenibilidade</td>
        <td class="s3" dir="ltr">Não funcional</td>
        <td class="s6">NFR Manutenibilidade</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R468" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">469</div>
        </th>
        <td class="s3" dir="ltr">R012</td>
        <td class="s3" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R469" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">470</div>
        </th>
        <td class="s3" dir="ltr">R013</td>
        <td class="s3" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R470" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">471</div>
        </th>
        <td class="s3" dir="ltr">R014</td>
        <td class="s3" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R471" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">472</div>
        </th>
        <td class="s3" dir="ltr">R015</td>
        <td class="s3" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R472" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">473</div>
        </th>
        <td class="s3" dir="ltr">R016</td>
        <td class="s3" dir="ltr">Ver status</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R473" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">474</div>
        </th>
        <td class="s3" dir="ltr">R017</td>
        <td class="s3" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R474" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">475</div>
        </th>
        <td class="s3" dir="ltr">R018</td>
        <td class="s3" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R475" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">476</div>
        </th>
        <td class="s3" dir="ltr">R019</td>
        <td class="s3" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R476" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">477</div>
        </th>
        <td class="s3" dir="ltr">R020</td>
        <td class="s3" dir="ltr">Visualizar stories publicadas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R477" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">478</div>
        </th>
        <td class="s3" dir="ltr">R021</td>
        <td class="s3" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R478" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">479</div>
        </th>
        <td class="s3" dir="ltr">R022</td>
        <td class="s3" dir="ltr">Editar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R479" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">480</div>
        </th>
        <td class="s3" dir="ltr">R023</td>
        <td class="s3" dir="ltr">Deletar story</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R480" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">481</div>
        </th>
        <td class="s3" dir="ltr">R024</td>
        <td class="s3" dir="ltr">Aplaudir um texto lido</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R481" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">482</div>
        </th>
        <td class="s3" dir="ltr">R025</td>
        <td class="s3" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R482" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">483</div>
        </th>
        <td class="s3" dir="ltr">R026</td>
        <td class="s3" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R483" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">484</div>
        </th>
        <td class="s3" dir="ltr">R027</td>
        <td class="s3" dir="ltr">Escutar podcasts</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R484" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">485</div>
        </th>
        <td class="s3" dir="ltr">R028</td>
        <td class="s3" dir="ltr">Seguir escritores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R485" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">486</div>
        </th>
        <td class="s3" dir="ltr">R029</td>
        <td class="s3" dir="ltr">Seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R486" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">487</div>
        </th>
        <td class="s3" dir="ltr">R030</td>
        <td class="s3" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Controle de Qualidade</td>
        <td class="s6">i* Configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R487" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">488</div>
        </th>
        <td class="s3" dir="ltr">R031</td>
        <td class="s3" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R488" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">489</div>
        </th>
        <td class="s3" dir="ltr">R032</td>
        <td class="s3" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R489" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">490</div>
        </th>
        <td class="s3" dir="ltr">R033</td>
        <td class="s3" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R490" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">491</div>
        </th>
        <td class="s3" dir="ltr">R034</td>
        <td class="s3" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R491" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">492</div>
        </th>
        <td class="s3" dir="ltr">R035</td>
        <td class="s3" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R492" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">493</div>
        </th>
        <td class="s3" dir="ltr">R036</td>
        <td class="s3" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R493" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">494</div>
        </th>
        <td class="s3" dir="ltr">R037</td>
        <td class="s3" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">i* Stories</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R494" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">495</div>
        </th>
        <td class="s3" dir="ltr">R038</td>
        <td class="s3" dir="ltr">Reportar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Segurança</td>
        <td class="s6">i* Configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R495" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">496</div>
        </th>
        <td class="s3" dir="ltr">R039</td>
        <td class="s3" dir="ltr">Reportar usuário</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Segurança</td>
        <td class="s6">i* Configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R496" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">497</div>
        </th>
        <td class="s3" dir="ltr">R040</td>
        <td class="s3" dir="ltr">Editar informações de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Segurança</td>
        <td class="s6">i* Perfil</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R497" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">498</div>
        </th>
        <td class="s3" dir="ltr">R041</td>
        <td class="s3" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Segurança</td>
        <td class="s6">i* Perfil</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R498" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">499</div>
        </th>
        <td class="s3" dir="ltr">R042</td>
        <td class="s3" dir="ltr">Visualizar autores seguidos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R499" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">500</div>
        </th>
        <td class="s3" dir="ltr">R043</td>
        <td class="s3" dir="ltr">Visualizar seguidores</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R500" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">501</div>
        </th>
        <td class="s3" dir="ltr">R044</td>
        <td class="s3" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Controle de Qualidade</td>
        <td class="s6">i* Stories</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R501" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">502</div>
        </th>
        <td class="s3" dir="ltr">R045</td>
        <td class="s3" dir="ltr">Visualizar próprio perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Segurança</td>
        <td class="s6">i* Perfil</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R502" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">503</div>
        </th>
        <td class="s3" dir="ltr">R046</td>
        <td class="s3" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R503" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">504</div>
        </th>
        <td class="s3" dir="ltr">R047</td>
        <td class="s3" dir="ltr">Visualizar marcações feitas</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R504" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">505</div>
        </th>
        <td class="s3" dir="ltr">R048</td>
        <td class="s3" dir="ltr">Criar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R505" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">506</div>
        </th>
        <td class="s3" dir="ltr">R049</td>
        <td class="s3" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R506" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">507</div>
        </th>
        <td class="s3" dir="ltr">R050</td>
        <td class="s6">Editar publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R507" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">508</div>
        </th>
        <td class="s3" dir="ltr">R051</td>
        <td class="s6">Deletar Publicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">I* Publicações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R508" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">509</div>
        </th>
        <td class="s3" dir="ltr">R052</td>
        <td class="s3" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Controle de Qualidade</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R509" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">510</div>
        </th>
        <td class="s3" dir="ltr">R053</td>
        <td class="s3" dir="ltr">Deixar de seguir usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">-</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R510" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">511</div>
        </th>
        <td class="s3" dir="ltr">R054</td>
        <td class="s3" dir="ltr">Deixar de seguir publicações</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Controle de Qualidade</td>
        <td class="s6">i* Pesquisar conteúdo</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R511" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">512</div>
        </th>
        <td class="s3" dir="ltr">R055</td>
        <td class="s3">Aivar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Usabilidade</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R512" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">513</div>
        </th>
        <td class="s3" dir="ltr">R056</td>
        <td class="s3">Automatizar modo noturno</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR Usabilidade</td>
        <td class="s6">-</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R513" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">514</div>
        </th>
        <td class="s3">R057</td>
        <td class="s3">Editar email padrão</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R514" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">515</div>
        </th>
        <td class="s3">R058</td>
        <td class="s3" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR :Controle de Qualidade<br></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R515" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">516</div>
        </th>
        <td class="s3">R059</td>
        <td class="s3">Desativar sugestão de artigos</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR :Controle de Qualidade<br></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R516" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">517</div>
        </th>
        <td class="s3">R060</td>
        <td class="s3">Ativar/desativar boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR :Controle de Qualidade<br></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R517" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">518</div>
        </th>
        <td class="s3">R061</td>
        <td class="s3">Selecionar tema do boletim informativo</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR :Controle de Qualidade<br></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R518" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">519</div>
        </th>
        <td class="s3">R062</td>
        <td class="s3">Ativar/desativar recomendações de stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR :Controle de Qualidade<br></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R519" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">520</div>
        </th>
        <td class="s3">R063</td>
        <td class="s3">Ativar/desativar notificação por e-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R520" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">521</div>
        </th>
        <td class="s3">R064</td>
        <td class="s3">Ativar/desativar notificação social</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R521" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">522</div>
        </th>
        <td class="s3">R065</td>
        <td class="s3">Selecionar privacidade de menções</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R522" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">523</div>
        </th>
        <td class="s3">R066</td>
        <td class="s3">Desativar menções de usuários</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R523" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">524</div>
        </th>
        <td class="s3">R067</td>
        <td class="s3">Conectar com redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R524" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">525</div>
        </th>
        <td class="s3">R068</td>
        <td class="s3">Conectar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R525" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">526</div>
        </th>
        <td class="s3">R069</td>
        <td class="s3">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R526" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">527</div>
        </th>
        <td class="s3">R070</td>
        <td class="s3">Editar nome de usuário para menção</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R527" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">528</div>
        </th>
        <td class="s3">R071</td>
        <td class="s3">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R528" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">529</div>
        </th>
        <td class="s3">R072</td>
        <td class="s3">Gerenciar usuários bloqueados</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R529" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">530</div>
        </th>
        <td class="s3">R073</td>
        <td class="s3">Fazer download de meus dados do Medium</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R530" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">531</div>
        </th>
        <td class="s3">R074</td>
        <td class="s3">Deslogar de outras sessões </td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R531" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">532</div>
        </th>
        <td class="s3">R075</td>
        <td class="s3">Desativar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R532" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">533</div>
        </th>
        <td class="s3">R076</td>
        <td class="s3">Deletar conta</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6">I* SD configurações</td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R533" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">534</div>
        </th>
        <td class="s3">R077</td>
        <td class="s3">Visualizar tutorial das áreas da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R534" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">535</div>
        </th>
        <td class="s3">R078</td>
        <td class="s3">Acessar glossário MEDIUM</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R535" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">536</div>
        </th>
        <td class="s3">R079</td>
        <td class="s3">Responder questionário de satisfação da aplicação</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R536" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">537</div>
        </th>
        <td class="s3">R080</td>
        <td class="s3">Pesquisar tópico de ajuda</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s6"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R537" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">538</div>
        </th>
        <td class="s3">R081</td>
        <td class="s3">Escolher plano de assinatura membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R538" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">539</div>
        </th>
        <td class="s3">R082</td>
        <td class="s3">Inserir forma de pagamento do medium membership</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s10"></td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R539" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">540</div>
        </th>
        <td class="s3">R083</td>
        <td class="s3">Login via redes sociais</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR: Segurança</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R540" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">541</div>
        </th>
        <td class="s3">R084</td>
        <td class="s3">Login via Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR: Segurança</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R541" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">542</div>
        </th>
        <td class="s3">R085</td>
        <td class="s3">Login via E-mail</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR: Segurança</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R542" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">543</div>
        </th>
        <td class="s3">R086</td>
        <td class="s3">Cadastrar com Google</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR: Segurança</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R543" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">544</div>
        </th>
        <td class="s3">R087</td>
        <td class="s3">Cadastrar com Facebook</td>
        <td class="s3" dir="ltr">Funcional</td>
        <td class="s6">NFR: Segurança</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R544" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">545</div>
        </th>
        <td class="s3">R088</td>
        <td class="s3">Segurança</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s6">NFR: Segurança</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr
      <tr style='height:20px;'>
        <th id="0R545" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">546</div>
        </th>
        <td class="s3">R089</td>
        <td class="s3">Desempenho</td>
        <td class="s3" dir="ltr">Não Funcional</td>
        <td class="s6">NFR: Desempenho</td>
        <td class="s10"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
        <td class="s8"></td>
      </tr>
    </tbody>
  </table>
</div>


### Tabela Backward-From V2.0


</style>
<div class="ritz grid-container" dir="ltr">
  <table class="waffle" cellspacing="0" cellpadding="0">
    <thead>
      <tr>
        <th class="row-header freezebar-origin-ltr"></th>
        <th id="0C0" style="width:38px" class="column-headers-background">A</th>
        <th id="0C1" style="width:146px" class="column-headers-background">B</th>
        <th id="0C2" style="width:100px" class="column-headers-background">C</th>
        <th id="0C3" style="width:38px" class="column-headers-background">D</th>
        <th id="0C4" style="width:154px" class="column-headers-background">E</th>
        <th id="0C5" style="width:154px" class="column-headers-background">F</th>
        <th id="0C6" style="width:188px" class="column-headers-background">G</th>
        <th id="0C7" style="width:195px" class="column-headers-background">H</th>
        <th id="0C8" style="width:205px" class="column-headers-background">I</th>
        <th id="0C9" style="width:104px" class="column-headers-background">J</th>
        <th id="0C10" style="width:97px" class="column-headers-background">K</th>
        <th id="0C11" style="width:119px" class="column-headers-background">L</th>
        <th id="0C12" style="width:108px" class="column-headers-background">M</th>
        <th id="0C13" style="width:191px" class="column-headers-background">N</th>
        <th id="0C14" style="width:152px" class="column-headers-background">O</th>
        <th id="0C15" style="width:103px" class="column-headers-background">P</th>
      </tr>
    </thead>
    <tbody>
      <tr style='height:20px;'>
        <th id="0R0" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">1</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
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
            <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s1" dir="ltr">Elo</td>
        <td class="s1" dir="ltr">RichPicture</td>
        <td class="s1" dir="ltr">Questionário</td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
        <td class="s1" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R001</td>
        <td class="s2" dir="ltr">Responsividade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
          <td class="s2" dir="ltr">R002</td>
        <td class="s2" dir="ltr">Portabilidade mobile ios</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr">Ponto de vista do leitor<br>(Gabriel)<br><br>Import Story<br>(Pedro)</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
            <td class="s2" dir="ltr">R003</td>
        <td class="s2" dir="ltr">Portabilidade mobile android</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr">Ponto de vista do leitor<br>(Gabriel)<br><br>Import Story<br>(Pedro)</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R004</td>
        <td class="s2" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF1</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R6" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">7</div>
        </th>
        <td class="s2" dir="ltr">R005</td>
        <td class="s2" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF2</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R006</td>
        <td class="s2" dir="ltr">Política de privacidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R007</td>
        <td class="s2" dir="ltr">Identidade Visual</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R008</td>
        <td class="s2" dir="ltr">Alta disponibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Com que frequência você importa textos de outras plataformas para o
          Medium?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
            <td class="s2" dir="ltr">R009</td>
        <td class="s2" dir="ltr">Controle de Conteúdo</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à
          você?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s2" dir="ltr">R010</td>
        <td class="s2" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF3</td>
        <td class="s2" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>New Story<br>(Pedro)</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Sobre quais tipos de assunto você escreve?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R011</td>
        <td class="s2" dir="ltr">Manutenibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s3"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R012</td>
        <td class="s2" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF4</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à
          você?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s2" dir="ltr">R013</td>
        <td class="s2" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF5</td>
        <td class="s2" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R014</td>
        <td class="s2" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF6</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R015</td>
        <td class="s2" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF7</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
         <td class="s2" dir="ltr">R016</td>
        <td class="s2" dir="ltr">Ver status</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF8</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s2" dir="ltr">R017</td>
        <td class="s2" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF9</td>
        <td class="s2" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>New Story<br>(Pedro)</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Sobre quais tipos de assunto você escreve?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R018</td>
        <td class="s2" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF10</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R019</td>
        <td class="s2" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF11</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R020</td>
        <td class="s2" dir="ltr">Visualizar stories publicadas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF12</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à
          você?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s2" dir="ltr">R021</td>
        <td class="s2" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF13</td>
        <td class="s2" dir="ltr">Ponto de vista do escritor<br>(Matheus Blanco)<br><br>Import Story<br>(Pedro)</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Com que frequência você importa textos de outras plataformas para o
          Medium?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R022</td>
        <td class="s2" dir="ltr">Editar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF14</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R023</td>
        <td class="s2" dir="ltr">Deletar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF15</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
           <td class="s2" dir="ltr">R024</td>
        <td class="s2" dir="ltr">Aplaudir um texto lido</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF16</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Com qual frequência você aplaude (&#39;claps&#39;) as
          publicações?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s2" dir="ltr">R025</td>
        <td class="s2" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF17</td>
        <td class="s2" dir="ltr">Ponto de vista do leitor<br>(Guilherme)<br><br>Ponto de vista do leitor<br>(Gabriel)
        </td>
        <td class="s2" dir="ltr">Pergunta: &quot;Com qual frequência você compartilha as publicações?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R026</td>
        <td class="s2" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF18</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr">Pergunta: &quot;Com qual frequência você comenta nas publicações?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R027</td>
        <td class="s2" dir="ltr">Escutar podcasts</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF19</td>
        <td class="s2" dir="ltr">Ponto de vista do leitor<br>(Gabriel)</td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R028</td>
        <td class="s2" dir="ltr">Seguir escritores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF20</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R029</td>
        <td class="s2" dir="ltr">Seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF21</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R030</td>
        <td class="s2" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF22</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R031</td>
        <td class="s2" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF23</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Qual os assuntos pelo quais você se interessa ao acessar o
          MEDIUM?&quot;</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R032</td>
        <td class="s2" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF24</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R033</td>
        <td class="s2" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF25</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R034</td>
        <td class="s2" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF26</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
             <td class="s2" dir="ltr">R035</td>
        <td class="s2" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF27</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R036</td>
        <td class="s2" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF28</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s2" dir="ltr">R037</td>
        <td class="s2" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF29</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Com qual frequência você comenta nas publicações?&quot;</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
                <td class="s2" dir="ltr">R038</td>
        <td class="s2" dir="ltr">Reportar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF30</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
               <td class="s2" dir="ltr">R039</td>
        <td class="s2" dir="ltr">Reportar usuário</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF31</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s2" dir="ltr">R040</td>
        <td class="s2" dir="ltr">Editar informações de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF32</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
              <td class="s2" dir="ltr">R041</td>
        <td class="s2" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF33</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R43" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">44</div>
        </th>
        <td class="s2" dir="ltr">R042</td>
        <td class="s2" dir="ltr">Visualizar autores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF34</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R44" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">45</div>
        </th>
        <td class="s2" dir="ltr">R043</td>
        <td class="s2" dir="ltr">Visualizar seguidores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF35</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R45" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">46</div>
        </th>
        <td class="s2" dir="ltr">R044</td>
        <td class="s2" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF36</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Com qual frequência você aplaude (&#39;claps&#39;) as
          publicações?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R46" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">47</div>
        </th>
        <td class="s2" dir="ltr">R045</td>
        <td class="s2" dir="ltr">Visualizar próprio perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF37</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R47" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">48</div>
        </th>
        <td class="s2" dir="ltr">R046</td>
        <td class="s2" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF38</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Com que frequência você utiliza as métricas feitas pelo Medium?&quot;
        </td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R48" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">49</div>
        </th>
        <td class="s2" dir="ltr">R047</td>
        <td class="s2" dir="ltr">Visualizar marcações feitas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF39</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R49" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">50</div>
        </th>
        <td class="s2" dir="ltr">R048</td>
        <td class="s2" dir="ltr">Criar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF40</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R50" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">51</div>
        </th>
        <td class="s2" dir="ltr">R049</td>
        <td class="s2" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF41</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R51" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">52</div>
        </th>
        <td class="s2" dir="ltr">R050</td>
        <td class="s2" dir="ltr">Editar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF42</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R52" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">53</div>
        </th>
        <td class="s2" dir="ltr">R051</td>
        <td class="s2" dir="ltr">Deletar Publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF43</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classifica o editor de textos padrão do Médium?&quot;</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R53" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">54</div>
        </th>
        <td class="s2" dir="ltr">R052</td>
        <td class="s2" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF44</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Qual os assuntos pelo quais você se interessa ao acessar o
          MEDIUM?&quot;</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R54" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">55</div>
        </th>
        <td class="s2" dir="ltr">R053</td>
        <td class="s2" dir="ltr">Deixar de seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF45</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R55" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">56</div>
        </th>
        <td class="s2" dir="ltr">R054</td>
        <td class="s2" dir="ltr">Deixar de seguir publicações</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF46</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">-</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R56" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">57</div>
        </th>
        <td class="s2" dir="ltr">R055</td>
        <td class="s2">Aivar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF47</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R57" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">58</div>
        </th>
        <td class="s2" dir="ltr">R056</td>
        <td class="s2">Automatizar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF48</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: &quot;Como você classificaria a interface do MEDIUM?&quot;</td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:53px;'>
        <th id="0R58" style="height: 53px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 53px;">59</div>
        </th>
        <td class="s2">R057</td>
        <td class="s2">Editar email padrão</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF49</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R59" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">60</div>
        </th>
        <td class="s2">R058</td>
        <td class="s2" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF50</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R60" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">61</div>
        </th>
        <td class="s2">R059</td>
        <td class="s2">Desativar sugestão de artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF51</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R61" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">62</div>
        </th>
        <td class="s2">R060</td>
        <td class="s2">Ativar/desativar boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF52</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R62" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">63</div>
        </th>
        <td class="s2">R061</td>
        <td class="s2">Selecionar tema do boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF53</td>
        <td class="s2"></td>
        <td class="s2" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:81px;'>
        <th id="0R63" style="height: 81px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 81px;">64</div>
        </th>
        <td class="s2">R062</td>
        <td class="s2">Ativar/desativar recomendações de stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF54</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3" dir="ltr">Pergunta: Qual o seu nível de satisfação com o conteúdo recomendado pelo MEDIUM à você?
        </td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:92px;'>
        <th id="0R64" style="height: 92px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 92px;">65</div>
        </th>
        <td class="s2">R063</td>
        <td class="s2">Ativar/desativar notificação por e-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF55</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R65" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">66</div>
        </th>
        <td class="s2">R064</td>
        <td class="s2">Ativar/desativar notificação social</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF56</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R66" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">67</div>
        </th>
        <td class="s2">R065</td>
        <td class="s2">Selecionar privacidade de menções</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF57</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R67" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">68</div>
        </th>
        <td class="s2">R066</td>
        <td class="s2">Desativar menções de usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF58</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R68" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">69</div>
        </th>
        <td class="s2">R067</td>
        <td class="s2">Conectar com redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF59</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R69" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">70</div>
        </th>
        <td class="s2">R068</td>
        <td class="s2">Conectar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF60</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R70" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">71</div>
        </th>
        <td class="s2">R069</td>
        <td class="s2">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF61</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:59px;'>
        <th id="0R71" style="height: 59px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 59px;">72</div>
        </th>
        <td class="s2">R070</td>
        <td class="s2">Editar nome de usuário para menção</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF62</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:50px;'>
        <th id="0R72" style="height: 50px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 50px;">73</div>
        </th>
        <td class="s2">R071</td>
        <td class="s2">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF63</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R73" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">74</div>
        </th>
        <td class="s2">R072</td>
        <td class="s2">Gerenciar usuários bloqueados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF64</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:49px;'>
        <th id="0R74" style="height: 49px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 49px;">75</div>
        </th>
        <td class="s2">R073</td>
        <td class="s2">Fazer download de meus dados do Medium</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF65</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:83px;'>
        <th id="0R75" style="height: 83px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 83px;">76</div>
        </th>
        <td class="s2">R074</td>
        <td class="s2">Deslogar de outras sessões </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF66</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:93px;'>
        <th id="0R76" style="height: 93px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 93px;">77</div>
        </th>
        <td class="s2">R075</td>
        <td class="s2">Desativar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF67</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:88px;'>
        <th id="0R77" style="height: 88px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 88px;">78</div>
        </th>
        <td class="s2">R076</td>
        <td class="s2">Deletar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF68</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:55px;'>
        <th id="0R78" style="height: 55px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 55px;">79</div>
        </th>
        <td class="s2">R077</td>
        <td class="s2">Visualizar tutorial das áreas da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF69</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:54px;'>
        <th id="0R79" style="height: 54px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 54px;">80</div>
        </th>
        <td class="s2">R078</td>
        <td class="s2">Acessar glossário MEDIUM</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF70</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:65px;'>
        <th id="0R80" style="height: 65px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 65px;">81</div>
        </th>
        <td class="s2">R079</td>
        <td class="s2">Responder questionário de satisfação da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF71</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:56px;'>
        <th id="0R81" style="height: 56px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 56px;">82</div>
        </th>
        <td class="s2">R080</td>
        <td class="s2">Pesquisar tópico de ajuda</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF72</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
      </tr>
      <tr style='height:69px;'>
        <th id="0R82" style="height: 69px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 69px;">83</div>
        </th>
        <td class="s2">R081</td>
        <td class="s2">Escolher plano de assinatura membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF73</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:52px;'>
        <th id="0R83" style="height: 52px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 52px;">84</div>
        </th>
        <td class="s2">R082</td>
        <td class="s2">Inserir forma de pagamento do medium membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF74</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:37px;'>
        <th id="0R84" style="height: 37px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 37px;">85</div>
        </th>
        <td class="s2">R083</td>
        <td class="s2">Login via redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF75</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:35px;'>
        <th id="0R85" style="height: 35px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 35px;">86</div>
        </th>
        <td class="s2">R084</td>
        <td class="s2">Login via Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF76</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:39px;'>
        <th id="0R86" style="height: 39px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 39px;">87</div>
        </th>
        <td class="s2">R085</td>
        <td class="s2">Login via E-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF77</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:35px;'>
        <th id="0R87" style="height: 35px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 35px;">88</div>
        </th>
        <td class="s2">R086</td>
        <td class="s2">Cadastrar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF78</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:38px;'>
        <th id="0R88" style="height: 38px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 38px;">89</div>
        </th>
        <td class="s2">R087</td>
        <td class="s2">Cadastrar com Facebook</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF79</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R89" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">90</div>
        </th>
        <td class="s2">R088</td>
        <td class="s2">Segurança</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3">EF80</td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R90" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">91</div>
        </th>
        <td class="s2">R089</td>
        <td class="s2">Desempenho</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2"></td>
        <td class="s2" dir="ltr"></td>
        <td class="s2"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R91" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">92</div>
        </th>
        <td class="s4" dir="ltr"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R92" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">93</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s1" dir="ltr">Elo</td>
        <td class="s6">StoryTelling e StoryBoard</td>
        <td class="s6">Brainstorming</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R93" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">94</div>
        </th>
        <td class="s2" dir="ltr">R001</td>
        <td class="s2" dir="ltr">Responsividade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">StoryBoard Customização de interesses</td>
        <td class="s3">Brainstorming &quot;William: carregamento eficiente de artigos&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R94" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">95</div>
        </th>
        <td class="s2" dir="ltr">R002</td>
        <td class="s2" dir="ltr">Portabilidade mobile ios</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">StoryBoard Customização de interesses</td>
        <td class="s3">Brainstorming 2 &quot; Matheus: A aplicação está disponível em plataformas : web e mobile
          (ios/android)&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R95" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">96</div>
        </th>
        <td class="s2" dir="ltr">R003</td>
        <td class="s2" dir="ltr">Portabilidade mobile android</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">StoryBoard Customização de interesses</td>
        <td class="s3">Brainstorming 2 &quot; Matheus: A aplicação está disponível em plataformas : web e mobile
          (ios/android)&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R96" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">97</div>
        </th>
        <td class="s2" dir="ltr">R004</td>
        <td class="s2" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF1</td>
        <td class="s3">StoryBoard Tutorial e seguir escritor</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R97" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">98</div>
        </th>
        <td class="s2" dir="ltr">R005</td>
        <td class="s2" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF2</td>
        <td class="s3">-</td>
        <td class="s3">Brainstorming 4 &quot;matheus: ter um registro dos seus textos em seu blog&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R98" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">99</div>
        </th>
        <td class="s2" dir="ltr">R006</td>
        <td class="s2" dir="ltr">Política de privacidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">StoryBoard Login e cadastro</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R99" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">100</div>
        </th>
        <td class="s2" dir="ltr">R007</td>
        <td class="s2" dir="ltr">Identidade Visual</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">Brainstorming 2 &quot; Matheus: o design intuitivo e minimalista torna a experiência mais
          produtiva&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R100" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">101</div>
        </th>
        <td class="s2" dir="ltr">R008</td>
        <td class="s2" dir="ltr">Alta disponibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R101" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">102</div>
        </th>
        <td class="s2" dir="ltr">R009</td>
        <td class="s2" dir="ltr">Controle de Conteúdo</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">StoryBoard Customização de interesses</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R102" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">103</div>
        </th>
        <td class="s2" dir="ltr">R010</td>
        <td class="s2" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF3</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R103" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">104</div>
        </th>
        <td class="s2" dir="ltr">R011</td>
        <td class="s2" dir="ltr">Manutenibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s3"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R104" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">105</div>
        </th>
        <td class="s2" dir="ltr">R012</td>
        <td class="s2" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF4</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">Brainstorming 3 &quot;Matheus: os usuários podem ver os textos publicados na página de um
          escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R105" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">106</div>
        </th>
        <td class="s2" dir="ltr">R013</td>
        <td class="s2" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF5</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R106" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">107</div>
        </th>
        <td class="s2" dir="ltr">R014</td>
        <td class="s2" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF6</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R107" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">108</div>
        </th>
        <td class="s2" dir="ltr">R015</td>
        <td class="s2" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF7</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R108" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">109</div>
        </th>
        <td class="s2" dir="ltr">R016</td>
        <td class="s2" dir="ltr">Ver status</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF8</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">Brainstorming 4 &quot; Matheus: ver quem deu clap em suas publicações&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R109" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">110</div>
        </th>
        <td class="s2" dir="ltr">R017</td>
        <td class="s2" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF9</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R110" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">111</div>
        </th>
        <td class="s2" dir="ltr">R018</td>
        <td class="s2" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF10</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R111" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">112</div>
        </th>
        <td class="s2" dir="ltr">R019</td>
        <td class="s2" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF11</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R112" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">113</div>
        </th>
        <td class="s2" dir="ltr">R020</td>
        <td class="s2" dir="ltr">Visualizar stories publicadas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF12</td>
        <td class="s3">StoryBoard Tutorial e seguir escritor</td>
        <td class="s3">Brainstorming 3 &quot;Matheus: os usuários podem ver os textos publicados na página de um
          escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R113" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">114</div>
        </th>
        <td class="s2" dir="ltr">R021</td>
        <td class="s2" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF13</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">Brainstorming 4 &quot; Matheus: possibilidade de escrever no blog ou fora do blog&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R114" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">115</div>
        </th>
        <td class="s2" dir="ltr">R022</td>
        <td class="s2" dir="ltr">Editar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF14</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R115" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">116</div>
        </th>
        <td class="s2" dir="ltr">R023</td>
        <td class="s2" dir="ltr">Deletar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF15</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R116" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">117</div>
        </th>
        <td class="s2" dir="ltr">R024</td>
        <td class="s2" dir="ltr">Aplaudir um texto lido</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF16</td>
        <td class="s3">StoryBoard Tutorial e seguir escritor</td>
        <td class="s3">Brainstorming 3 &quot;matheus: o leitor poder gostar do texto&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R117" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">118</div>
        </th>
        <td class="s2" dir="ltr">R025</td>
        <td class="s2" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF17</td>
        <td class="s3">StoryTelling - Escritor, New Story</td>
        <td class="s3">Brainstorming 3 &quot;matheus: compartilhar o texto&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R118" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">119</div>
        </th>
        <td class="s2" dir="ltr">R026</td>
        <td class="s2" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF18</td>
        <td class="s3">-</td>
        <td class="s3">Brainstorming 4 &quot;Pedro: ver comentários de seus textos e responder os comentários de seus
          textos&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R119" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">120</div>
        </th>
        <td class="s2" dir="ltr">R027</td>
        <td class="s2" dir="ltr">Escutar podcasts</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF19</td>
        <td class="s3">StoryBoard Tutorial e seguir escritor</td>
        <td class="s3">Brainstorming 3 &quot;Gabriel: escutar podcasts&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R120" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">121</div>
        </th>
        <td class="s2" dir="ltr">R028</td>
        <td class="s2" dir="ltr">Seguir escritores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF20</td>
        <td class="s3">StoryBoard Tutorial e seguir escritor</td>
        <td class="s3">Brainstorming 3 &quot;Matheus: seguir o escritor&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R121" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">122</div>
        </th>
        <td class="s2" dir="ltr">R029</td>
        <td class="s2" dir="ltr">Seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF21</td>
        <td class="s3"> </td>
        <td class="s3">Brainstorming 3: &quot;Gabriel: Seguir outros usuários&quot;</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R122" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">123</div>
        </th>
        <td class="s2" dir="ltr">R030</td>
        <td class="s2" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF22</td>
        <td class="s7"></td>
        <td class="s3">Brainstorming 3: &quot;William: O leitor recebe as notificações de publicações de seus escritores
          favoritados</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R123" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">124</div>
        </th>
        <td class="s2" dir="ltr">R031</td>
        <td class="s2" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF23</td>
        <td class="s7"></td>
        <td class="s3">Brainstorming 3: &quot;Gabriel: Selecionar tema de artigos&quot;</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R124" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">125</div>
        </th>
        <td class="s2" dir="ltr">R032</td>
        <td class="s2" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF24</td>
        <td class="s7"></td>
        <td class="s3">Brainstorming 3: &quot;Matheus: os usuários podem ver os textos publicados na página de um
          escritor, com foco nas publicações com as quais ele interagiu&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R125" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">126</div>
        </th>
        <td class="s2" dir="ltr">R033</td>
        <td class="s2" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF25</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R126" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">127</div>
        </th>
        <td class="s2" dir="ltr">R034</td>
        <td class="s2" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF26</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R127" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">128</div>
        </th>
        <td class="s2" dir="ltr">R035</td>
        <td class="s2" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF27</td>
        <td class="s7"></td>
        <td class="s3">Brainstorming 2: &quot;William: visualizar os perfis de outros usuários&quot;</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R128" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">129</div>
        </th>
        <td class="s2" dir="ltr">R036</td>
        <td class="s2" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF28</td>
        <td class="s7"></td>
        <td class="s3">Brainstorming 3: &quot;Matheus: o leitor poder gostar do texto&quot;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R129" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">130</div>
        </th>
        <td class="s2" dir="ltr">R037</td>
        <td class="s2" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF29</td>
        <td class="s7"></td>
        <td class="s3">Brainstorming 4: &quot;Pedro: ver comentários de seus textos e responder os comentários de seus
          textos&quot;</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R130" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">131</div>
        </th>
        <td class="s2" dir="ltr">R038</td>
        <td class="s2" dir="ltr">Reportar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF30</td>
        <td class="s3">Storytelling - Editar Perfil</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R131" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">132</div>
        </th>
        <td class="s2" dir="ltr">R039</td>
        <td class="s2" dir="ltr">Reportar usuário</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF31</td>
        <td class="s3">Storytelling - Editar Perfil</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R132" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">133</div>
        </th>
        <td class="s2" dir="ltr">R040</td>
        <td class="s2" dir="ltr">Editar informações de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF32</td>
        <td class="s3">Storytelling - Editar Perfil: &quot;Ao lado do seu nome nesta página de perfil, existia um botão
          chamado “Edit profile” e logo Carlos clicou sobre esse botão.&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R133" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">134</div>
        </th>
        <td class="s2" dir="ltr">R041</td>
        <td class="s2" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF33</td>
        <td class="s3">Storytelling - Editar Perfil: &quot;Após ter editado tudo o que desejava, Carlos clicou no botão
          chamado “Save” e foi redirecionado para a página que apresentava os seus dados cadastrais, agora
          editados.&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R134" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">135</div>
        </th>
        <td class="s2" dir="ltr">R042</td>
        <td class="s2" dir="ltr">Visualizar autores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF34</td>
        <td class="s3">StoryBoard - Tutorial e seguir escritor: &quot;Realmente. E ainda consigo seguir o perfil de
          escritores dos tutoriais estando logado&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R135" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">136</div>
        </th>
        <td class="s2" dir="ltr">R043</td>
        <td class="s2" dir="ltr">Visualizar seguidores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF35</td>
        <td class="s3">Storytelling - Escritor New Story: &quot;Medium, como é chamado o site, é uma plataforma pensada
          na troca de conhecimentos por seus usuários, a partir de textos técnicos, assuntos atuais, sociais,
          tecnológicos, psicológicos e até mesmo pesquisas&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R136" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">137</div>
        </th>
        <td class="s2" dir="ltr">R044</td>
        <td class="s2" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF36</td>
        <td class="s3">Storytelling - Escritor New Story: &quot;Entretanto, ela estava satisfeita com os resultados,
          pois havia recebido um bom número de “claps”&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R137" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">138</div>
        </th>
        <td class="s2" dir="ltr">R045</td>
        <td class="s2" dir="ltr">Visualizar próprio perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF37</td>
        <td class="s3">Storytelling - Editar Perfil: &quot;Entre essas opções estava escrita a opção “Profile”, então
          Carlos clicou sobre essa opção e ao mesmo instante ele foi redirecionado para uma página que apresentava todos
          os seus dados cadastrais.&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R138" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">139</div>
        </th>
        <td class="s2" dir="ltr">R046</td>
        <td class="s2" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF38</td>
        <td class="s3">Storytelling - Editar Perfil: &quot;Ao começar a ganhar visibilidade em suas publicações, Carlos
          passou a receber comentários pedindo informações sobre a sua formação acadêmica, assim como o seu nome
          completo&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R139" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">140</div>
        </th>
        <td class="s2" dir="ltr">R047</td>
        <td class="s2" dir="ltr">Visualizar marcações feitas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF39</td>
        <td class="s3">StoryBoard - Bookmarking: &quot;Nossa! O artigo é muito grande, acho que vou salvar para ler mais
          tarde&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R140" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">141</div>
        </th>
        <td class="s2" dir="ltr">R048</td>
        <td class="s2" dir="ltr">Criar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF40</td>
        <td class="s3">Storytelling - Escritor New Story: &quot;Natália percebeu que havia mais de uma maneira de se
          publicar um texto.&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R141" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">142</div>
        </th>
        <td class="s2" dir="ltr">R049</td>
        <td class="s2" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF41</td>
        <td class="s3">Storytelling - Escritor New Story: &quot;salvar o link do rascunho e customizar o link de sua
          publicação&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R142" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">143</div>
        </th>
        <td class="s2" dir="ltr">R050</td>
        <td class="s2" dir="ltr">Editar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF42</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R143" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">144</div>
        </th>
        <td class="s2" dir="ltr">R051</td>
        <td class="s2" dir="ltr">Deletar Publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF43</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R144" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">145</div>
        </th>
        <td class="s2" dir="ltr">R052</td>
        <td class="s2" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF44</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R145" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">146</div>
        </th>
        <td class="s2" dir="ltr">R053</td>
        <td class="s2" dir="ltr">Deixar de seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF45</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R146" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">147</div>
        </th>
        <td class="s2" dir="ltr">R054</td>
        <td class="s2" dir="ltr">Deixar de seguir publicações</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF46</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R147" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">148</div>
        </th>
        <td class="s2" dir="ltr">R055</td>
        <td class="s2">Aivar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF47</td>
        <td class="s3">Storytelling - Configurações</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R148" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">149</div>
        </th>
        <td class="s2" dir="ltr">R056</td>
        <td class="s2">Automatizar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF48</td>
        <td class="s3">Storytelling - Configurações</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R149" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">150</div>
        </th>
        <td class="s2">R057</td>
        <td class="s2">Editar email padrão</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF49</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s3">Brainstorming 2:<br>&quot;William&quot;,editar seu próprio perfil<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R150" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">151</div>
        </th>
        <td class="s2">R058</td>
        <td class="s2" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF50</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R151" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">152</div>
        </th>
        <td class="s2">R059</td>
        <td class="s2">Desativar sugestão de artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF51</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R152" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">153</div>
        </th>
        <td class="s2">R060</td>
        <td class="s2">Ativar/desativar boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF52</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R153" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">154</div>
        </th>
        <td class="s2">R061</td>
        <td class="s2">Selecionar tema do boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF53</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R154" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">155</div>
        </th>
        <td class="s2">R062</td>
        <td class="s2">Ativar/desativar recomendações de stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF54</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s3">Brainstorming 3: &quot;Gabriel&quot;,selecionar tema de artigo; &quot;Matheus&quot;,Escolher os
          textos na homepage<br><br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R155" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">156</div>
        </th>
        <td class="s2">R063</td>
        <td class="s2">Ativar/desativar notificação por e-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF55</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s3">Brainstorming 3: &quot;William&quot;,O leitor recebe as notificações de publicações de seus
          escritores favoritados<br></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R156" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">157</div>
        </th>
        <td class="s2">R064</td>
        <td class="s2">Ativar/desativar notificação social</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF56</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R157" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">158</div>
        </th>
        <td class="s2">R065</td>
        <td class="s2">Selecionar privacidade de menções</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF57</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R158" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">159</div>
        </th>
        <td class="s2">R066</td>
        <td class="s2">Desativar menções de usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF58</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R159" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">160</div>
        </th>
        <td class="s2">R067</td>
        <td class="s2">Conectar com redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF59</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R160" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">161</div>
        </th>
        <td class="s2">R068</td>
        <td class="s2">Conectar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF60</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R161" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">162</div>
        </th>
        <td class="s2">R069</td>
        <td class="s2">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF61</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R162" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">163</div>
        </th>
        <td class="s2">R070</td>
        <td class="s2">Editar nome de usuário para menção</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF62</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R163" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">164</div>
        </th>
        <td class="s2">R071</td>
        <td class="s2">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF63</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R164" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">165</div>
        </th>
        <td class="s2">R072</td>
        <td class="s2">Gerenciar usuários bloqueados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF64</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R165" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">166</div>
        </th>
        <td class="s2">R073</td>
        <td class="s2">Fazer download de meus dados do Medium</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF65</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R166" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">167</div>
        </th>
        <td class="s2">R074</td>
        <td class="s2">Deslogar de outras sessões </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF66</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R167" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">168</div>
        </th>
        <td class="s2">R075</td>
        <td class="s2">Desativar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF67</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R168" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">169</div>
        </th>
        <td class="s2">R076</td>
        <td class="s2">Deletar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF68</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R169" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">170</div>
        </th>
        <td class="s2">R077</td>
        <td class="s2">Visualizar tutorial das áreas da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF69</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R170" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">171</div>
        </th>
        <td class="s2">R078</td>
        <td class="s2">Acessar glossário MEDIUM</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF70</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R171" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">172</div>
        </th>
        <td class="s2">R079</td>
        <td class="s2">Responder questionário de satisfação da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF71</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R172" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">173</div>
        </th>
        <td class="s2">R080</td>
        <td class="s2">Pesquisar tópico de ajuda</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF72</td>
        <td class="s3">Usuário, Configurando a aplicação<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R173" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">174</div>
        </th>
        <td class="s2">R081</td>
        <td class="s2">Escolher plano de assinatura membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF73</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R174" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">175</div>
        </th>
        <td class="s2">R082</td>
        <td class="s2">Inserir forma de pagamento do medium membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF74</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R175" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">176</div>
        </th>
        <td class="s2">R083</td>
        <td class="s2">Login via redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF75</td>
        <td class="s3">Login e Cadastro<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R176" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">177</div>
        </th>
        <td class="s2">R084</td>
        <td class="s2">Login via Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF76</td>
        <td class="s3">Login e Cadastro<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R177" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">178</div>
        </th>
        <td class="s2">R085</td>
        <td class="s2">Login via E-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF77</td>
        <td class="s3">Login e Cadastro<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R178" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">179</div>
        </th>
        <td class="s2">R086</td>
        <td class="s2">Cadastrar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF78</td>
        <td class="s3">Login e Cadastro<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R179" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">180</div>
        </th>
        <td class="s2">R087</td>
        <td class="s2">Cadastrar com Facebook</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF79</td>
        <td class="s3">Login e Cadastro<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R180" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">181</div>
        </th>
        <td class="s2">R088</td>
        <td class="s2">Segurança</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3">EF80</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R181" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">182</div>
        </th>
        <td class="s2">R089</td>
        <td class="s2">Desempenho</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R182" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">183</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R183" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">184</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s1" dir="ltr">Elo</td>
        <td class="s6">Instrospecção</td>
        <td class="s6">Cenários</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R184" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">185</div>
        </th>
        <td class="s2" dir="ltr">R001</td>
        <td class="s2" dir="ltr">Responsividade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R185" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">186</div>
        </th>
        <td class="s2" dir="ltr">R002</td>
        <td class="s2" dir="ltr">Portabilidade mobile ios</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R186" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">187</div>
        </th>
        <td class="s2" dir="ltr">R003</td>
        <td class="s2" dir="ltr">Portabilidade mobile android</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R187" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">188</div>
        </th>
        <td class="s2" dir="ltr">R004</td>
        <td class="s2" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF1</td>
        <td class="s3">-</td>
        <td class="s3">Pesquisa por artigo</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R188" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">189</div>
        </th>
        <td class="s2" dir="ltr">R005</td>
        <td class="s2" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF2</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">Leitura de texto</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R189" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">190</div>
        </th>
        <td class="s2" dir="ltr">R006</td>
        <td class="s2" dir="ltr">Política de privacidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R190" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">191</div>
        </th>
        <td class="s2" dir="ltr">R007</td>
        <td class="s2" dir="ltr">Identidade Visual</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R191" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">192</div>
        </th>
        <td class="s2" dir="ltr">R008</td>
        <td class="s2" dir="ltr">Alta disponibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s7"></td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R192" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">193</div>
        </th>
        <td class="s2" dir="ltr">R009</td>
        <td class="s2" dir="ltr">Controle de Conteúdo</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">Relato de introspecção 6: Customização de Interesses</td>
        <td class="s3">Customizar interesses</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R193" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">194</div>
        </th>
        <td class="s2" dir="ltr">R010</td>
        <td class="s2" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF3</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R194" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">195</div>
        </th>
        <td class="s2" dir="ltr">R011</td>
        <td class="s2" dir="ltr">Manutenibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s3"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R195" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">196</div>
        </th>
        <td class="s2" dir="ltr">R012</td>
        <td class="s2" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF4</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">Leitura de texto</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R196" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">197</div>
        </th>
        <td class="s2" dir="ltr">R013</td>
        <td class="s2" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF5</td>
        <td class="s3">-</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R197" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">198</div>
        </th>
        <td class="s2" dir="ltr">R014</td>
        <td class="s2" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF6</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R198" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">199</div>
        </th>
        <td class="s2" dir="ltr">R015</td>
        <td class="s2" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF7</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R199" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">200</div>
        </th>
        <td class="s2" dir="ltr">R016</td>
        <td class="s2" dir="ltr">Ver status</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF8</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R200" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">201</div>
        </th>
        <td class="s2" dir="ltr">R017</td>
        <td class="s2" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF9</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R201" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">202</div>
        </th>
        <td class="s2" dir="ltr">R018</td>
        <td class="s2" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF10</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R202" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">203</div>
        </th>
        <td class="s2" dir="ltr">R019</td>
        <td class="s2" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF11</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R203" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">204</div>
        </th>
        <td class="s2" dir="ltr">R020</td>
        <td class="s2" dir="ltr">Visualizar stories publicadas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF12</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R204" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">205</div>
        </th>
        <td class="s2" dir="ltr">R021</td>
        <td class="s2" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF13</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Importar um storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R205" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">206</div>
        </th>
        <td class="s2" dir="ltr">R022</td>
        <td class="s2" dir="ltr">Editar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF14</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R206" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">207</div>
        </th>
        <td class="s2" dir="ltr">R023</td>
        <td class="s2" dir="ltr">Deletar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF15</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3">Criar um novo Storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R207" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">208</div>
        </th>
        <td class="s2" dir="ltr">R024</td>
        <td class="s2" dir="ltr">Aplaudir um texto lido</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF16</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">Dar Claps</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R208" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">209</div>
        </th>
        <td class="s2" dir="ltr">R025</td>
        <td class="s2" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF17</td>
        <td class="s3">Relato de introspecção 3: Usuário no processo de criação de uma nova Story</td>
        <td class="s3"> Compartilhar publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R209" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">210</div>
        </th>
        <td class="s2" dir="ltr">R026</td>
        <td class="s2" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF18</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">Comentar publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R210" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">211</div>
        </th>
        <td class="s2" dir="ltr">R027</td>
        <td class="s2" dir="ltr">Escutar podcasts</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF19</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">Leitura de texto</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R211" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">212</div>
        </th>
        <td class="s2" dir="ltr">R028</td>
        <td class="s2" dir="ltr">Seguir escritores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF20</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação</td>
        <td class="s3">Seguir usuário</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R212" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">213</div>
        </th>
        <td class="s2" dir="ltr">R029</td>
        <td class="s2" dir="ltr">Seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF21</td>
        <td class="s7"></td>
        <td class="s3">Seguir usuário</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R213" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">214</div>
        </th>
        <td class="s2" dir="ltr">R030</td>
        <td class="s2" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF22</td>
        <td class="s7"></td>
        <td class="s3">Configurar notificações</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R214" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">215</div>
        </th>
        <td class="s2" dir="ltr">R031</td>
        <td class="s2" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF23</td>
        <td class="s7"></td>
        <td class="s3">Pesquisa por artigo</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R215" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">216</div>
        </th>
        <td class="s2" dir="ltr">R032</td>
        <td class="s2" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF24</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R216" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">217</div>
        </th>
        <td class="s2" dir="ltr">R033</td>
        <td class="s2" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF25</td>
        <td class="s3">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta
          uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto
          em que cada artigo salvo foi fechado;&quot;</td>
        <td class="s3">Criar um novo Bookmark</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R217" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">218</div>
        </th>
        <td class="s2" dir="ltr">R034</td>
        <td class="s2" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF26</td>
        <td class="s3">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta
          uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto
          em que cada artigo salvo foi fechado;&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R218" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">219</div>
        </th>
        <td class="s2" dir="ltr">R035</td>
        <td class="s2" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF27</td>
        <td class="s7"></td>
        <td class="s3">Seguir usuário</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R219" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">220</div>
        </th>
        <td class="s2" dir="ltr">R036</td>
        <td class="s2" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF28</td>
        <td class="s3">Relato de Introspecção 4: &quot;ii. Listagem de artigos salvos: para um usuário logado, apresenta
          uma lista de todos os arquivos salvos por ele para uma fácil recuperação do artigo e também registra o ponto
          em que cada artigo salvo foi fechado;&quot;</td>
        <td class="s3">Criar um novo Bookmark</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R220" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">221</div>
        </th>
        <td class="s2" dir="ltr">R037</td>
        <td class="s2" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF29</td>
        <td class="s7"></td>
        <td class="s3">Comentar publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R221" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">222</div>
        </th>
        <td class="s2" dir="ltr">R038</td>
        <td class="s2" dir="ltr">Reportar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF30</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R222" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">223</div>
        </th>
        <td class="s2" dir="ltr">R039</td>
        <td class="s2" dir="ltr">Reportar usuário</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF31</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R223" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">224</div>
        </th>
        <td class="s2" dir="ltr">R040</td>
        <td class="s2" dir="ltr">Editar informações de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF32</td>
        <td class="s7"></td>
        <td class="s3">Editar perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R224" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">225</div>
        </th>
        <td class="s2" dir="ltr">R041</td>
        <td class="s2" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF33</td>
        <td class="s7"></td>
        <td class="s3">Editar perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R225" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">226</div>
        </th>
        <td class="s2" dir="ltr">R042</td>
        <td class="s2" dir="ltr">Visualizar autores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF34</td>
        <td class="s7"></td>
        <td class="s3">Deixar de seguir usuário</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R226" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">227</div>
        </th>
        <td class="s2" dir="ltr">R043</td>
        <td class="s2" dir="ltr">Visualizar seguidores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF35</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R227" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">228</div>
        </th>
        <td class="s2" dir="ltr">R044</td>
        <td class="s2" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF36</td>
        <td class="s7"></td>
        <td class="s3">Dar clap</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R228" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">229</div>
        </th>
        <td class="s2" dir="ltr">R045</td>
        <td class="s2" dir="ltr">Visualizar próprio perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF37</td>
        <td class="s7"></td>
        <td class="s3">Editar perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R229" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">230</div>
        </th>
        <td class="s2" dir="ltr">R046</td>
        <td class="s2" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF38</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R230" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">231</div>
        </th>
        <td class="s2" dir="ltr">R047</td>
        <td class="s2" dir="ltr">Visualizar marcações feitas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF39</td>
        <td class="s7"></td>
        <td class="s3">Criar um novo Bookmark</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R231" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">232</div>
        </th>
        <td class="s2" dir="ltr">R048</td>
        <td class="s2" dir="ltr">Criar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF40</td>
        <td class="s7"></td>
        <td class="s3">Criar um storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R232" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">233</div>
        </th>
        <td class="s2" dir="ltr">R049</td>
        <td class="s2" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF41</td>
        <td class="s7"></td>
        <td class="s3">Criar um storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R233" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">234</div>
        </th>
        <td class="s2" dir="ltr">R050</td>
        <td class="s2" dir="ltr">Editar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF42</td>
        <td class="s7"></td>
        <td class="s3">Criar um storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R234" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">235</div>
        </th>
        <td class="s2" dir="ltr">R051</td>
        <td class="s2" dir="ltr">Deletar Publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF43</td>
        <td class="s7"></td>
        <td class="s3">Criar um storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R235" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">236</div>
        </th>
        <td class="s2" dir="ltr">R052</td>
        <td class="s2" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF44</td>
        <td class="s3">Relato de instrospecção 6: &quot;Deve mostrar escritores sugeridos para os interesses do
          leitor.&quot;</td>
        <td class="s3">Customizar interesses</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R236" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">237</div>
        </th>
        <td class="s2" dir="ltr">R053</td>
        <td class="s2" dir="ltr">Deixar de seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF45</td>
        <td class="s3">Relato de instrospecção 6: &quot;Deve ser capaz de deixar de seguir Blogs e escritores.&quot;
        </td>
        <td class="s3">Deixar de seguir usuário</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R237" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">238</div>
        </th>
        <td class="s2" dir="ltr">R054</td>
        <td class="s2" dir="ltr">Deixar de seguir publicações</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF46</td>
        <td class="s3">Relato de introspecção 3: &quot;Poder tornar o texto público ou privado para apenas um número
          definido de leitores;&quot;</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R238" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">239</div>
        </th>
        <td class="s2" dir="ltr">R055</td>
        <td class="s2">Aivar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF47</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R239" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">240</div>
        </th>
        <td class="s2" dir="ltr">R056</td>
        <td class="s2">Automatizar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF48</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R240" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">241</div>
        </th>
        <td class="s2">R057</td>
        <td class="s2">Editar email padrão</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF49</td>
        <td class="s7"></td>
        <td class="s3">C04: Editar perfil</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R241" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">242</div>
        </th>
        <td class="s2">R058</td>
        <td class="s2" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF50</td>
        <td class="s7"></td>
        <td class="s3">C10:Configurar notificações de e-mail<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R242" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">243</div>
        </th>
        <td class="s2">R059</td>
        <td class="s2">Desativar sugestão de artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF51</td>
        <td class="s7"></td>
        <td class="s3">C10:Configurar notificações de e-mail<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R243" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">244</div>
        </th>
        <td class="s2">R060</td>
        <td class="s2">Ativar/desativar boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF52</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação:
          Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
        <td class="s3">C10:Configurar notificações de e-mail<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R244" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">245</div>
        </th>
        <td class="s2">R061</td>
        <td class="s2">Selecionar tema do boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF53</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação:
          Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
        <td class="s3">C10:Configurar notificações de e-mail<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R245" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">246</div>
        </th>
        <td class="s2">R062</td>
        <td class="s2">Ativar/desativar recomendações de stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF54</td>
        <td class="s7"></td>
        <td class="s3">C10:Configurar notificações de e-mail<br></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R246" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">247</div>
        </th>
        <td class="s2">R063</td>
        <td class="s2">Ativar/desativar notificação por e-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF55</td>
        <td class="s3">Relato de introspecção 1: Comportamento do usuário na Página inicial da aplicação:
          Vi.Possibilitar que o usuário possa receber notificações do sistema;<br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R247" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">248</div>
        </th>
        <td class="s2">R064</td>
        <td class="s2">Ativar/desativar notificação social</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF56</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R248" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">249</div>
        </th>
        <td class="s2">R065</td>
        <td class="s2">Selecionar privacidade de menções</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF57</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R249" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">250</div>
        </th>
        <td class="s2">R066</td>
        <td class="s2">Desativar menções de usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF58</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R250" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">251</div>
        </th>
        <td class="s2">R067</td>
        <td class="s2">Conectar com redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF59</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R251" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">252</div>
        </th>
        <td class="s2">R068</td>
        <td class="s2">Conectar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF60</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R252" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">253</div>
        </th>
        <td class="s2">R069</td>
        <td class="s2">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF61</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R253" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">254</div>
        </th>
        <td class="s2">R070</td>
        <td class="s2">Editar nome de usuário para menção</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF62</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R254" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">255</div>
        </th>
        <td class="s2">R071</td>
        <td class="s2">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF63</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R255" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">256</div>
        </th>
        <td class="s2">R072</td>
        <td class="s2">Gerenciar usuários bloqueados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF64</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R256" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">257</div>
        </th>
        <td class="s2">R073</td>
        <td class="s2">Fazer download de meus dados do Medium</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF65</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R257" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">258</div>
        </th>
        <td class="s2">R074</td>
        <td class="s2">Deslogar de outras sessões </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF66</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R258" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">259</div>
        </th>
        <td class="s2">R075</td>
        <td class="s2">Desativar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF67</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R259" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">260</div>
        </th>
        <td class="s2">R076</td>
        <td class="s2">Deletar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF68</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R260" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">261</div>
        </th>
        <td class="s2">R077</td>
        <td class="s2">Visualizar tutorial das áreas da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF69</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R261" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">262</div>
        </th>
        <td class="s2">R078</td>
        <td class="s2">Acessar glossário MEDIUM</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF70</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R262" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">263</div>
        </th>
        <td class="s2">R079</td>
        <td class="s2">Responder questionário de satisfação da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF71</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R263" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">264</div>
        </th>
        <td class="s2">R080</td>
        <td class="s2">Pesquisar tópico de ajuda</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF72</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R264" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">265</div>
        </th>
        <td class="s2">R081</td>
        <td class="s2">Escolher plano de assinatura membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF73</td>
        <td class="s7"></td>
        <td class="s3">C05: Premium</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R265" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">266</div>
        </th>
        <td class="s2">R082</td>
        <td class="s2">Inserir forma de pagamento do medium membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF74</td>
        <td class="s7"></td>
        <td class="s3">C05: Premium</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R266" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">267</div>
        </th>
        <td class="s2">R083</td>
        <td class="s2">Login via redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF75</td>
        <td class="s3">Relato de introspecção 2:Usuário não logado;i , ii e iii</td>
        <td class="s3">C07:login</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R267" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">268</div>
        </th>
        <td class="s2">R084</td>
        <td class="s2">Login via Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF76</td>
        <td class="s3">Relato de introspecção 2:Usuário não logado;i , ii e iii</td>
        <td class="s3">C07:login</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R268" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">269</div>
        </th>
        <td class="s2">R085</td>
        <td class="s2">Login via E-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF77</td>
        <td class="s3">Relato de introspecção 2:Usuário não logado;i , ii e iii</td>
        <td class="s3">C07:login</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R269" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">270</div>
        </th>
        <td class="s2">R086</td>
        <td class="s2">Cadastrar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF78</td>
        <td class="s3">Relato de introspecção 2:Usuário não cadastrado, i e ii</td>
        <td class="s3">C06:Cadastro</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R270" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">271</div>
        </th>
        <td class="s2">R087</td>
        <td class="s2">Cadastrar com Facebook</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF79</td>
        <td class="s3">Relato de introspecção 2:Usuário não cadastrado, i e ii</td>
        <td class="s3">C06:Cadastro</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R271" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">272</div>
        </th>
        <td class="s2">R088</td>
        <td class="s2">Segurança</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3">EF80</td>
        <td class="s7"></td>
        <td class="s3">C06 e C07</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R272" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">273</div>
        </th>
        <td class="s2">R089</td>
        <td class="s2">Desempenho</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R273" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">274</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R274" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">275</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s1" dir="ltr">Elo</td>
        <td class="s6">Léxicos</td>
        <td class="s6">Casos de uso</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R275" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">276</div>
        </th>
        <td class="s2" dir="ltr">R001</td>
        <td class="s2" dir="ltr">Responsividade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R276" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">277</div>
        </th>
        <td class="s2" dir="ltr">R002</td>
        <td class="s2" dir="ltr">Portabilidade mobile ios</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R277" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">278</div>
        </th>
        <td class="s2" dir="ltr">R003</td>
        <td class="s2" dir="ltr">Portabilidade mobile android</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R278" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">279</div>
        </th>
        <td class="s2" dir="ltr">R004</td>
        <td class="s2" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF1</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R279" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">280</div>
        </th>
        <td class="s2" dir="ltr">R005</td>
        <td class="s2" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF2</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R280" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">281</div>
        </th>
        <td class="s2" dir="ltr">R006</td>
        <td class="s2" dir="ltr">Política de privacidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">Léxico About</td>
        <td class="s3">UC Configurar perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R281" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">282</div>
        </th>
        <td class="s2" dir="ltr">R007</td>
        <td class="s2" dir="ltr">Identidade Visual</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R282" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">283</div>
        </th>
        <td class="s2" dir="ltr">R008</td>
        <td class="s2" dir="ltr">Alta disponibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R283" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">284</div>
        </th>
        <td class="s2" dir="ltr">R009</td>
        <td class="s2" dir="ltr">Controle de Conteúdo</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">Léxico Content</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R284" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">285</div>
        </th>
        <td class="s2" dir="ltr">R010</td>
        <td class="s2" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF3</td>
        <td class="s3">Léxico Series</td>
        <td class="s3">UC Series</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R285" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">286</div>
        </th>
        <td class="s2" dir="ltr">R011</td>
        <td class="s2" dir="ltr">Manutenibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3">-</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R286" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">287</div>
        </th>
        <td class="s2" dir="ltr">R012</td>
        <td class="s2" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF4</td>
        <td class="s3">Léxico Series</td>
        <td class="s3">UC Series</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R287" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">288</div>
        </th>
        <td class="s2" dir="ltr">R013</td>
        <td class="s2" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF5</td>
        <td class="s3">Léxico Series</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R288" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">289</div>
        </th>
        <td class="s2" dir="ltr">R014</td>
        <td class="s2" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF6</td>
        <td class="s3">Léxico Series</td>
        <td class="s3">UC Series</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R289" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">290</div>
        </th>
        <td class="s2" dir="ltr">R015</td>
        <td class="s2" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF7</td>
        <td class="s3">Léxico Series</td>
        <td class="s3">UC Series</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R290" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">291</div>
        </th>
        <td class="s2" dir="ltr">R016</td>
        <td class="s2" dir="ltr">Ver status</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF8</td>
        <td class="s3">Léxico Status</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R291" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">292</div>
        </th>
        <td class="s2" dir="ltr">R017</td>
        <td class="s2" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF9</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R292" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">293</div>
        </th>
        <td class="s2" dir="ltr">R018</td>
        <td class="s2" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF10</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R293" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">294</div>
        </th>
        <td class="s2" dir="ltr">R019</td>
        <td class="s2" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF11</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R294" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">295</div>
        </th>
        <td class="s2" dir="ltr">R020</td>
        <td class="s2" dir="ltr">Visualizar stories publicadas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF12</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R295" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">296</div>
        </th>
        <td class="s2" dir="ltr">R021</td>
        <td class="s2" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF13</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R296" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">297</div>
        </th>
        <td class="s2" dir="ltr">R022</td>
        <td class="s2" dir="ltr">Editar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF14</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R297" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">298</div>
        </th>
        <td class="s2" dir="ltr">R023</td>
        <td class="s2" dir="ltr">Deletar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF15</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R298" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">299</div>
        </th>
        <td class="s2" dir="ltr">R024</td>
        <td class="s2" dir="ltr">Aplaudir um texto lido</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF16</td>
        <td class="s3">Léxico Clap</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R299" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">300</div>
        </th>
        <td class="s2" dir="ltr">R025</td>
        <td class="s2" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF17</td>
        <td class="s3">Léxico Share</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R300" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">301</div>
        </th>
        <td class="s2" dir="ltr">R026</td>
        <td class="s2" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF18</td>
        <td class="s3">Léxcio Response</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R301" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">302</div>
        </th>
        <td class="s2" dir="ltr">R027</td>
        <td class="s2" dir="ltr">Escutar podcasts</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF19</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R302" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">303</div>
        </th>
        <td class="s2" dir="ltr">R028</td>
        <td class="s2" dir="ltr">Seguir escritores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF20</td>
        <td class="s3">Léxico Storie</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R303" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">304</div>
        </th>
        <td class="s2" dir="ltr">R029</td>
        <td class="s2" dir="ltr">Seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF21</td>
        <td class="s3">Léxico Following</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R304" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">305</div>
        </th>
        <td class="s2" dir="ltr">R030</td>
        <td class="s2" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF22</td>
        <td class="s3">Léxico Digest e Léxico Newsletter</td>
        <td class="s3">UC Configurar perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R305" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">306</div>
        </th>
        <td class="s2" dir="ltr">R031</td>
        <td class="s2" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF23</td>
        <td class="s3">Léxico Search e Léxico Tag</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R306" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">307</div>
        </th>
        <td class="s2" dir="ltr">R032</td>
        <td class="s2" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF24</td>
        <td class="s3">Léxico Following</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R307" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">308</div>
        </th>
        <td class="s2" dir="ltr">R033</td>
        <td class="s2" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF25</td>
        <td class="s3">Léxico Bookmark</td>
        <td class="s3">UC Bookmark</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R308" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">309</div>
        </th>
        <td class="s2" dir="ltr">R034</td>
        <td class="s2" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF26</td>
        <td class="s7"></td>
        <td class="s3">UC Bookmark</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R309" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">310</div>
        </th>
        <td class="s2" dir="ltr">R035</td>
        <td class="s2" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF27</td>
        <td class="s3">Léxico Profile</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R310" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">311</div>
        </th>
        <td class="s2" dir="ltr">R036</td>
        <td class="s2" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF28</td>
        <td class="s3">Léxico Bookmark</td>
        <td class="s3">UC Bookmark</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R311" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">312</div>
        </th>
        <td class="s2" dir="ltr">R037</td>
        <td class="s2" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF29</td>
        <td class="s3">Léxico Response</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R312" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">313</div>
        </th>
        <td class="s2" dir="ltr">R038</td>
        <td class="s2" dir="ltr">Reportar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF30</td>
        <td class="s7"></td>
        <td class="s3">UC Configurar perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R313" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">314</div>
        </th>
        <td class="s2" dir="ltr">R039</td>
        <td class="s2" dir="ltr">Reportar usuário</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF31</td>
        <td class="s7"></td>
        <td class="s3">UC Configurar perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R314" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">315</div>
        </th>
        <td class="s2" dir="ltr">R040</td>
        <td class="s2" dir="ltr">Editar informações de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF32</td>
        <td class="s3">Léxico Edit e Léxico Profile</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R315" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">316</div>
        </th>
        <td class="s2" dir="ltr">R041</td>
        <td class="s2" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF33</td>
        <td class="s3">Léxico Edit e Léxico Profile</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R316" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">317</div>
        </th>
        <td class="s2" dir="ltr">R042</td>
        <td class="s2" dir="ltr">Visualizar autores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF34</td>
        <td class="s3">Léxico Following</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R317" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">318</div>
        </th>
        <td class="s2" dir="ltr">R043</td>
        <td class="s2" dir="ltr">Visualizar seguidores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF35</td>
        <td class="s3">Léxico Followers</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R318" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">319</div>
        </th>
        <td class="s2" dir="ltr">R044</td>
        <td class="s2" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF36</td>
        <td class="s3">Léxico Clap</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R319" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">320</div>
        </th>
        <td class="s2" dir="ltr">R045</td>
        <td class="s2" dir="ltr">Visualizar próprio perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF37</td>
        <td class="s3">Léxico Profile</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R320" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">321</div>
        </th>
        <td class="s2" dir="ltr">R046</td>
        <td class="s2" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF38</td>
        <td class="s7"></td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R321" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">322</div>
        </th>
        <td class="s2" dir="ltr">R047</td>
        <td class="s2" dir="ltr">Visualizar marcações feitas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF39</td>
        <td class="s3">Léxico Bookmark</td>
        <td class="s3">UC Bookmark</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R322" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">323</div>
        </th>
        <td class="s2" dir="ltr">R048</td>
        <td class="s2" dir="ltr">Criar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF40</td>
        <td class="s3">Léxico Stories</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R323" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">324</div>
        </th>
        <td class="s2" dir="ltr">R049</td>
        <td class="s2" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF41</td>
        <td class="s3">Léxico Stories</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R324" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">325</div>
        </th>
        <td class="s2" dir="ltr">R050</td>
        <td class="s2" dir="ltr">Editar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF42</td>
        <td class="s3">Léxico Stories</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R325" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">326</div>
        </th>
        <td class="s2" dir="ltr">R051</td>
        <td class="s2" dir="ltr">Deletar Publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF43</td>
        <td class="s3">Léxico Stories</td>
        <td class="s3">UC stories</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R326" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">327</div>
        </th>
        <td class="s2" dir="ltr">R052</td>
        <td class="s2" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF44</td>
        <td class="s7"></td>
        <td class="s3">UC Cadastro</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R327" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">328</div>
        </th>
        <td class="s2" dir="ltr">R053</td>
        <td class="s2" dir="ltr">Deixar de seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF45</td>
        <td class="s3">Léxico Following</td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R328" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">329</div>
        </th>
        <td class="s2" dir="ltr">R054</td>
        <td class="s2" dir="ltr">Deixar de seguir publicações</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF46</td>
        <td class="s7"></td>
        <td class="s3">UC Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R329" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">330</div>
        </th>
        <td class="s2" dir="ltr">R055</td>
        <td class="s2">Aivar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF47</td>
        <td class="s3">Léxico Night Mode</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R330" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">331</div>
        </th>
        <td class="s2" dir="ltr">R056</td>
        <td class="s2">Automatizar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF48</td>
        <td class="s3">Léxico Night Mode</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R331" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">332</div>
        </th>
        <td class="s2">R057</td>
        <td class="s2">Editar email padrão</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF49</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R332" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">333</div>
        </th>
        <td class="s2">R058</td>
        <td class="s2" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF50</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R333" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">334</div>
        </th>
        <td class="s2">R059</td>
        <td class="s2">Desativar sugestão de artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF51</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R334" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">335</div>
        </th>
        <td class="s2">R060</td>
        <td class="s2">Ativar/desativar boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF52</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R335" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">336</div>
        </th>
        <td class="s2">R061</td>
        <td class="s2">Selecionar tema do boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF53</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R336" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">337</div>
        </th>
        <td class="s2">R062</td>
        <td class="s2">Ativar/desativar recomendações de stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF54</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R337" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">338</div>
        </th>
        <td class="s2">R063</td>
        <td class="s2">Ativar/desativar notificação por e-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF55</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R338" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">339</div>
        </th>
        <td class="s2">R064</td>
        <td class="s2">Ativar/desativar notificação social</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF56</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R339" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">340</div>
        </th>
        <td class="s2">R065</td>
        <td class="s2">Selecionar privacidade de menções</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF57</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R340" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">341</div>
        </th>
        <td class="s2">R066</td>
        <td class="s2">Desativar menções de usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF58</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R341" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">342</div>
        </th>
        <td class="s2">R067</td>
        <td class="s2">Conectar com redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF59</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R342" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">343</div>
        </th>
        <td class="s2">R068</td>
        <td class="s2">Conectar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF60</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R343" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">344</div>
        </th>
        <td class="s2">R069</td>
        <td class="s2">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF61</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R344" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">345</div>
        </th>
        <td class="s2">R070</td>
        <td class="s2">Editar nome de usuário para menção</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF62</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R345" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">346</div>
        </th>
        <td class="s2">R071</td>
        <td class="s2">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF63</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R346" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">347</div>
        </th>
        <td class="s2">R072</td>
        <td class="s2">Gerenciar usuários bloqueados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF64</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R347" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">348</div>
        </th>
        <td class="s2">R073</td>
        <td class="s2">Fazer download de meus dados do Medium</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF65</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R348" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">349</div>
        </th>
        <td class="s2">R074</td>
        <td class="s2">Deslogar de outras sessões </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF66</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R349" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">350</div>
        </th>
        <td class="s2">R075</td>
        <td class="s2">Desativar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF67</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R350" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">351</div>
        </th>
        <td class="s2">R076</td>
        <td class="s2">Deletar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF68</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R351" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">352</div>
        </th>
        <td class="s2">R077</td>
        <td class="s2">Visualizar tutorial das áreas da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF69</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R352" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">353</div>
        </th>
        <td class="s2">R078</td>
        <td class="s2">Acessar glossário MEDIUM</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF70</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R353" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">354</div>
        </th>
        <td class="s2">R079</td>
        <td class="s2">Responder questionário de satisfação da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF71</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R354" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">355</div>
        </th>
        <td class="s2">R080</td>
        <td class="s2">Pesquisar tópico de ajuda</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF72</td>
        <td class="s7"></td>
        <td class="s3">Área comum</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R355" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">356</div>
        </th>
        <td class="s2">R081</td>
        <td class="s2">Escolher plano de assinatura membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF73</td>
        <td class="s7"></td>
        <td class="s3">Acesso ao Medium Membership<br></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R356" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">357</div>
        </th>
        <td class="s2">R082</td>
        <td class="s2">Inserir forma de pagamento do medium membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF74</td>
        <td class="s7"></td>
        <td class="s3">Acesso ao Medium Membership<br></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R357" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">358</div>
        </th>
        <td class="s2">R083</td>
        <td class="s2">Login via redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF75</td>
        <td class="s7"></td>
        <td class="s3">Login</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R358" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">359</div>
        </th>
        <td class="s2">R084</td>
        <td class="s2">Login via Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF76</td>
        <td class="s7"></td>
        <td class="s3">Login</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R359" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">360</div>
        </th>
        <td class="s2">R085</td>
        <td class="s2">Login via E-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF77</td>
        <td class="s7"></td>
        <td class="s3">Login</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R360" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">361</div>
        </th>
        <td class="s2">R086</td>
        <td class="s2">Cadastrar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF78</td>
        <td class="s7"></td>
        <td class="s3">Cadastro de usuário<br></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R361" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">362</div>
        </th>
        <td class="s2">R087</td>
        <td class="s2">Cadastrar com Facebook</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF79</td>
        <td class="s7"></td>
        <td class="s3">Cadastro de usuário<br></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R362" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">363</div>
        </th>
        <td class="s2">R088</td>
        <td class="s2">Segurança</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3">EF80</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R363" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">364</div>
        </th>
        <td class="s2">R089</td>
        <td class="s2">Desempenho</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R364" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">365</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R365" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">366</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s1" dir="ltr">Elo</td>
        <td class="s6">Especificação suplementar</td>
        <td class="s6">Product Backlog</td>
        <td class="s6"></td>
        <td class="s6"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R366" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">367</div>
        </th>
        <td class="s2" dir="ltr">R001</td>
        <td class="s2" dir="ltr">Responsividade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">US 048 - Usuário: Desejo visualizar as páginas da plataforma em questão de forma responsiva</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R367" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">368</div>
        </th>
        <td class="s2" dir="ltr">R002</td>
        <td class="s2" dir="ltr">Portabilidade mobile ios</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">US 049 - Usuário: Poder acessar a aplicação via dispositivo IOS</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R368" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">369</div>
        </th>
        <td class="s2" dir="ltr">R003</td>
        <td class="s2" dir="ltr">Portabilidade mobile android</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">US 050 - Usuário: Poder acessar a aplicação via dispositivo Android</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R369" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">370</div>
        </th>
        <td class="s2" dir="ltr">R004</td>
        <td class="s2" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF1</td>
        <td class="s3">UC03-Pesquisar artigo</td>
        <td class="s3">US 047 - Usuário: Pesquisar por nome de artigo</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R370" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">371</div>
        </th>
        <td class="s2" dir="ltr">R005</td>
        <td class="s2" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF2</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R371" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">372</div>
        </th>
        <td class="s2" dir="ltr">R006</td>
        <td class="s2" dir="ltr">Política de privacidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">UC17-Pagar via cartão de crédito</td>
        <td class="s3">US 020 - Usuário: Selecionar privacidade de menções</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R372" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">373</div>
        </th>
        <td class="s2" dir="ltr">R007</td>
        <td class="s2" dir="ltr">Identidade Visual</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R373" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">374</div>
        </th>
        <td class="s2" dir="ltr">R008</td>
        <td class="s2" dir="ltr">Alta disponibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">UC28-Visualizar Stories</td>
        <td class="s3">US 071 - Usuário: Visualizar storie</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R374" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">375</div>
        </th>
        <td class="s2" dir="ltr">R009</td>
        <td class="s2" dir="ltr">Controle de Conteúdo</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">UC05-Ler artigo</td>
        <td class="s3">US 009 - Usuário: selecionar/remover tópicos de interesse</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R375" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">376</div>
        </th>
        <td class="s2" dir="ltr">R010</td>
        <td class="s2" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF3</td>
        <td class="s3">UC23 - Criar series</td>
        <td class="s3">US 059 - Usuário Escritor: Criar uma nova Serie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R376" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">377</div>
        </th>
        <td class="s2" dir="ltr">R011</td>
        <td class="s2" dir="ltr">Manutenibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R377" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">378</div>
        </th>
        <td class="s2" dir="ltr">R012</td>
        <td class="s2" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF4</td>
        <td class="s3">UC20-Visualizar Series</td>
        <td class="s3">US 071 - Usuário: Visualizar storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R378" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">379</div>
        </th>
        <td class="s2" dir="ltr">R013</td>
        <td class="s2" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF5</td>
        <td class="s3">UC23 - Criar series</td>
        <td class="s3">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R379" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">380</div>
        </th>
        <td class="s2" dir="ltr">R014</td>
        <td class="s2" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF6</td>
        <td class="s3">UC23 - Criar series</td>
        <td class="s3">US 060 - Usuário Escritor: Editar uma Serie existente</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R380" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">381</div>
        </th>
        <td class="s2" dir="ltr">R015</td>
        <td class="s2" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF7</td>
        <td class="s3">UC36-Excluir Publicação</td>
        <td class="s3">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R381" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">382</div>
        </th>
        <td class="s2" dir="ltr">R016</td>
        <td class="s2" dir="ltr">Ver status</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF8</td>
        <td class="s3">UC20-Visualizar Series</td>
        <td class="s3">US 034 - Usuário: visualizar seguidores</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R382" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">383</div>
        </th>
        <td class="s2" dir="ltr">R017</td>
        <td class="s2" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF9</td>
        <td class="s3">UC32-Escrever uma nova Story.</td>
        <td class="s3">US 063 - Usuário Escritor: Escrever &#39;new storie&#39;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R383" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">384</div>
        </th>
        <td class="s2" dir="ltr">R018</td>
        <td class="s2" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF10</td>
        <td class="s3">UC32-Escrever uma nova Story.</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R384" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">385</div>
        </th>
        <td class="s2" dir="ltr">R019</td>
        <td class="s2" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF11</td>
        <td class="s3">UC32-Escrever uma nova Story.</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R385" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">386</div>
        </th>
        <td class="s2" dir="ltr">R020</td>
        <td class="s2" dir="ltr">Visualizar stories publicadas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF12</td>
        <td class="s3">UC28-Visualizar Stories</td>
        <td class="s3">US 071 - Usuário: Visualizar storie</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R386" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">387</div>
        </th>
        <td class="s2" dir="ltr">R021</td>
        <td class="s2" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF13</td>
        <td class="s3">UC31-Importar uma Story</td>
        <td class="s3">US 064 - Usuário Escritor: Importar &#39;storie&#39;</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R387" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">388</div>
        </th>
        <td class="s2" dir="ltr">R022</td>
        <td class="s2" dir="ltr">Editar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF14</td>
        <td class="s3">UC35-Editar Publicação</td>
        <td class="s3">US 060 - Usuário Escritor: Editar uma Serie existente</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R388" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">389</div>
        </th>
        <td class="s2" dir="ltr">R023</td>
        <td class="s2" dir="ltr">Deletar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF15</td>
        <td class="s3">UC36-Excluir Publicação</td>
        <td class="s3">US 061 - Usuário Escritor: Deletar uma Serie existente</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R389" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">390</div>
        </th>
        <td class="s2" dir="ltr">R024</td>
        <td class="s2" dir="ltr">Aplaudir um texto lido</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF16</td>
        <td class="s3">-</td>
        <td class="s3">US 065 - Usuário: Aplaudir um texto lido</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R390" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">391</div>
        </th>
        <td class="s2" dir="ltr">R025</td>
        <td class="s2" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF17</td>
        <td class="s3">-</td>
        <td class="s3">US 066 - Usuário: Compartilhar texto lido no Facebook ou Instagram</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R391" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">392</div>
        </th>
        <td class="s2" dir="ltr">R026</td>
        <td class="s2" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF18</td>
        <td class="s3">-</td>
        <td class="s3">US 067 - Usuário: Comentar no corpo do texto</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R392" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">393</div>
        </th>
        <td class="s2" dir="ltr">R027</td>
        <td class="s2" dir="ltr">Escutar podcasts</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF19</td>
        <td class="s3">UC04-Escutar podcast</td>
        <td class="s3">US 069 - Usuário: Escutar publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R393" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">394</div>
        </th>
        <td class="s2" dir="ltr">R028</td>
        <td class="s2" dir="ltr">Seguir escritores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF20</td>
        <td class="s3">-</td>
        <td class="s3">US 025 - Usuário: Seguir escritores</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R394" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">395</div>
        </th>
        <td class="s2" dir="ltr">R029</td>
        <td class="s2" dir="ltr">Seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF21</td>
        <td class="s3">-</td>
        <td class="s3">US 025 - Usuário: Seguir usuários</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R395" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">396</div>
        </th>
        <td class="s2" dir="ltr">R030</td>
        <td class="s2" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF22</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">US 019 - Usuário: Ativar/desativar notificação por e-mail </td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R396" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">397</div>
        </th>
        <td class="s2" dir="ltr">R031</td>
        <td class="s2" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF23</td>
        <td class="s3">UC03 - Pesquisar artigo</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R397" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">398</div>
        </th>
        <td class="s2" dir="ltr">R032</td>
        <td class="s2" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF24</td>
        <td class="s3">UC30 - Visualizar Publicações</td>
        <td class="s3">US 027 - Usuário: Visualizar textos publicados de um escritor em específico</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R398" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">399</div>
        </th>
        <td class="s2" dir="ltr">R033</td>
        <td class="s2" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF25</td>
        <td class="s3">-</td>
        <td class="s3">US 030 - Usuário: Favoritar Publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R399" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">400</div>
        </th>
        <td class="s2" dir="ltr">R034</td>
        <td class="s2" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF26</td>
        <td class="s3">-</td>
        <td class="s3">US 030 - Usuário: Favoritar Publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R400" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">401</div>
        </th>
        <td class="s2" dir="ltr">R035</td>
        <td class="s2" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF27</td>
        <td class="s3">UC03 - Pesquisar artigo</td>
        <td class="s3">US 029 - Usuário: Visualizar perfis de outros usuários</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R401" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">402</div>
        </th>
        <td class="s2" dir="ltr">R036</td>
        <td class="s2" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF28</td>
        <td class="s3">-</td>
        <td class="s3">US 030 - Usuário: Favoritar Publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R402" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">403</div>
        </th>
        <td class="s2" dir="ltr">R037</td>
        <td class="s2" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF29</td>
        <td class="s3">UC30 - Visualizar Publicações</td>
        <td class="s3">US 031 - Usuário: Visualizar comentários da publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R403" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">404</div>
        </th>
        <td class="s2" dir="ltr">R038</td>
        <td class="s2" dir="ltr">Reportar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF30</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">US 032 - Usuário: Reportar publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R404" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">405</div>
        </th>
        <td class="s2" dir="ltr">R039</td>
        <td class="s2" dir="ltr">Reportar usuário</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF31</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">US 033 - Bloquear usuário</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R405" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">406</div>
        </th>
        <td class="s2" dir="ltr">R040</td>
        <td class="s2" dir="ltr">Editar informações de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF32</td>
        <td class="s3">UC09 - Editar perfil</td>
        <td class="s3">US 043 - Usuário: Editar informações de perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R406" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">407</div>
        </th>
        <td class="s2" dir="ltr">R041</td>
        <td class="s2" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF33</td>
        <td class="s3">UC09 - Editar perfil</td>
        <td class="s3">US 043 - Usuário: Editar informações de perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R407" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">408</div>
        </th>
        <td class="s2" dir="ltr">R042</td>
        <td class="s2" dir="ltr">Visualizar autores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF34</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R408" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">409</div>
        </th>
        <td class="s2" dir="ltr">R043</td>
        <td class="s2" dir="ltr">Visualizar seguidores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF35</td>
        <td class="s3">-</td>
        <td class="s3">US 032 - Usuário: Visualizar seguidores</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R409" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">410</div>
        </th>
        <td class="s2" dir="ltr">R044</td>
        <td class="s2" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF36</td>
        <td class="s3">UC30 - Visualizar Publicações</td>
        <td class="s3">US 057 - Usuário: Visualizar claps em suas publicações</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R410" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">411</div>
        </th>
        <td class="s2" dir="ltr">R045</td>
        <td class="s2" dir="ltr">Visualizar próprio perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF37</td>
        <td class="s3">UC09 - Editar perfil</td>
        <td class="s3">US 044 - Usuário: Visualizar próprio perfil</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R411" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">412</div>
        </th>
        <td class="s2" dir="ltr">R046</td>
        <td class="s2" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF38</td>
        <td class="s3">-</td>
        <td class="s3">US 048 - Usuário: Ver estatísticas de uma série</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R412" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">413</div>
        </th>
        <td class="s2" dir="ltr">R047</td>
        <td class="s2" dir="ltr">Visualizar marcações feitas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF39</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R413" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">414</div>
        </th>
        <td class="s2" dir="ltr">R048</td>
        <td class="s2" dir="ltr">Criar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF40</td>
        <td class="s3">UC32 - Escrever uma nova Story</td>
        <td class="s3">US 058 - Usuário: Criar publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R414" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">415</div>
        </th>
        <td class="s2" dir="ltr">R049</td>
        <td class="s2" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF41</td>
        <td class="s3">UC29 - Visualizar Drafts</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R415" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">416</div>
        </th>
        <td class="s2" dir="ltr">R050</td>
        <td class="s2" dir="ltr">Editar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF42</td>
        <td class="s3">UC35 - Editar Publicação</td>
        <td class="s3">US 059 - Usuário: Editar publicação</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R416" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">417</div>
        </th>
        <td class="s2" dir="ltr">R051</td>
        <td class="s2" dir="ltr">Deletar Publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF43</td>
        <td class="s3">UC36 - Excluir Publicação</td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R417" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">418</div>
        </th>
        <td class="s2" dir="ltr">R052</td>
        <td class="s2" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF44</td>
        <td class="s3">UC01 - Área comum</td>
        <td class="s3">US 008 - Usuário: Selecionar alguns tópicos de meu interesse</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R418" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">419</div>
        </th>
        <td class="s2" dir="ltr">R053</td>
        <td class="s2" dir="ltr">Deixar de seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF45</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R419" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">420</div>
        </th>
        <td class="s2" dir="ltr">R054</td>
        <td class="s2" dir="ltr">Deixar de seguir publicações</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF46</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">-</td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R420" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">421</div>
        </th>
        <td class="s2" dir="ltr">R055</td>
        <td class="s2">Aivar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF47</td>
        <td class="s3">-</td>
        <td class="s3">010 - Ativar modo noturno </td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R421" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">422</div>
        </th>
        <td class="s2" dir="ltr">R056</td>
        <td class="s2">Automatizar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF48</td>
        <td class="s3">-</td>
        <td class="s3">011-Automatizar modo noturno </td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R422" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">423</div>
        </th>
        <td class="s2">R057</td>
        <td class="s2">Editar email padrão</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF49</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">012-Editar email padrão </td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R423" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">424</div>
        </th>
        <td class="s2">R058</td>
        <td class="s2" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF50</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">013-Selecionar período de sugestão de artigos </td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R424" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">425</div>
        </th>
        <td class="s2">R059</td>
        <td class="s2">Desativar sugestão de artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF51</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">014-Desativar sugestão de artigos </td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R425" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">426</div>
        </th>
        <td class="s2">R060</td>
        <td class="s2">Ativar/desativar boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF52</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">015-Ativar/desativar boletim informativo </td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R426" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">427</div>
        </th>
        <td class="s2">R061</td>
        <td class="s2">Selecionar tema do boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF53</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">016-Selecionar tema do boletim informativo </td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R427" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">428</div>
        </th>
        <td class="s2">R062</td>
        <td class="s2">Ativar/desativar recomendações de stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF54</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">017-Ativar as recomendações de stories </td>
        <td class="s3"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R428" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">429</div>
        </th>
        <td class="s2">R063</td>
        <td class="s2">Ativar/desativar notificação por e-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF55</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">018-Ativar as notificação por e-mail </td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R429" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">430</div>
        </th>
        <td class="s2">R064</td>
        <td class="s2">Ativar/desativar notificação social</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF56</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R430" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">431</div>
        </th>
        <td class="s2">R065</td>
        <td class="s2">Selecionar privacidade de menções</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF57</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">019-Gerenciar a privacidade de menções </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R431" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">432</div>
        </th>
        <td class="s2">R066</td>
        <td class="s2">Desativar menções de usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF58</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">020-Desativar menções a mim </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R432" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">433</div>
        </th>
        <td class="s2">R067</td>
        <td class="s2">Conectar com redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF59</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">006-Conectar com redes sociais </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R433" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">434</div>
        </th>
        <td class="s2">R068</td>
        <td class="s2">Conectar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF60</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">007-Conectar com Google </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R434" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">435</div>
        </th>
        <td class="s2">R069</td>
        <td class="s2">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF61</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">021-Mostrar links para minhas redes sociais </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R435" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">436</div>
        </th>
        <td class="s2">R070</td>
        <td class="s2">Editar nome de usuário para menção</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF62</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R436" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">437</div>
        </th>
        <td class="s2">R071</td>
        <td class="s2">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF63</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R437" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">438</div>
        </th>
        <td class="s2">R072</td>
        <td class="s2">Gerenciar usuários bloqueados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF64</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R438" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">439</div>
        </th>
        <td class="s2">R073</td>
        <td class="s2">Fazer download de meus dados do Medium</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF65</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R439" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">440</div>
        </th>
        <td class="s2">R074</td>
        <td class="s2">Deslogar de outras sessões </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF66</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">034-Deslogar de outras sessões </td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R440" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">441</div>
        </th>
        <td class="s2">R075</td>
        <td class="s2">Desativar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF67</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">022-Desativar minha conta </td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R441" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">442</div>
        </th>
        <td class="s2">R076</td>
        <td class="s2">Deletar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF68</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">023- Deletar minha conta </td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R442" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">443</div>
        </th>
        <td class="s2">R077</td>
        <td class="s2">Visualizar tutorial das áreas da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF69</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R443" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">444</div>
        </th>
        <td class="s2">R078</td>
        <td class="s2">Acessar glossário MEDIUM</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF70</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">001-Acessar glossário MEDIUM </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R444" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">445</div>
        </th>
        <td class="s2">R079</td>
        <td class="s2">Responder questionário de satisfação da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF71</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">002-Responder questionário de satisfação da aplicação </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R445" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">446</div>
        </th>
        <td class="s2">R080</td>
        <td class="s2">Pesquisar tópico de ajuda</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF72</td>
        <td class="s3">UC10-Configurar preferências<br><br></td>
        <td class="s3">003-Pesquisar tópico de ajuda </td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R446" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">447</div>
        </th>
        <td class="s2">R081</td>
        <td class="s2">Escolher plano de assinatura membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF73</td>
        <td class="s3">UC12-Selecionar plano<br><br></td>
        <td class="s3">038-visualizar os planos de assinatura disponíveis </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R447" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">448</div>
        </th>
        <td class="s2">R082</td>
        <td class="s2">Inserir forma de pagamento do medium membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF74</td>
        <td class="s3">UC15-Selecionar Método de pagamento<br><br></td>
        <td class="s3">039-visualizar as formas de pagamento existentes </td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R448" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">449</div>
        </th>
        <td class="s2">R083</td>
        <td class="s2">Login via redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF75</td>
        <td class="s3">UC02-Efetuar Login<br><br></td>
        <td class="s3">035-Realizar login via redes sociais </td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R449" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">450</div>
        </th>
        <td class="s2">R084</td>
        <td class="s2">Login via Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF76</td>
        <td class="s3">UC02-Efetuar Login<br><br></td>
        <td class="s3">036-Realizar login via Google </td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R450" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">451</div>
        </th>
        <td class="s2">R085</td>
        <td class="s2">Login via E-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF77</td>
        <td class="s3">UC02-Efetuar Login<br><br></td>
        <td class="s3">037-Realizar login via E-mail </td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R451" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">452</div>
        </th>
        <td class="s2">R086</td>
        <td class="s2">Cadastrar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF78</td>
        <td class="s3">UC01-Efetuar Cadastro<br><br></td>
        <td class="s3">004-Realizar cadastro com Google </td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R452" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">453</div>
        </th>
        <td class="s2">R087</td>
        <td class="s2">Cadastrar com Facebook</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF79</td>
        <td class="s3">UC01-Efetuar Cadastro<br><br></td>
        <td class="s3">005-Realizar cadastro com Facebook </td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R453" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">454</div>
        </th>
        <td class="s2">R088</td>
        <td class="s2">Segurança</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3">EF80</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R454" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">455</div>
        </th>
        <td class="s2">R089</td>
        <td class="s2">Desempenho</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R455" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">456</div>
        </th>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s0"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R456" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">457</div>
        </th>
        <td class="s1" dir="ltr">ID</td>
        <td class="s1" dir="ltr">Requisito</td>
        <td class="s1" dir="ltr">Tipo</td>
        <td class="s1" dir="ltr">Elo</td>
        <td class="s6">NFR</td>
        <td class="s6">I*</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R457" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">458</div>
        </th>
        <td class="s2" dir="ltr">R001</td>
        <td class="s2" dir="ltr">Responsividade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">NFR Iteroperabilidade</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R458" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">459</div>
        </th>
        <td class="s2" dir="ltr">R002</td>
        <td class="s2" dir="ltr">Portabilidade mobile ios</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">NFR Iteroperabilidade<br><br>NFR Usabilidade</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R459" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">460</div>
        </th>
        <td class="s2" dir="ltr">R003</td>
        <td class="s2" dir="ltr">Portabilidade mobile android</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">NFR Iteroperabilidade<br><br>NFR Usabilidade</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R460" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">461</div>
        </th>
        <td class="s2" dir="ltr">R004</td>
        <td class="s2" dir="ltr">Pesquisar artigos por nome</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF1</td>
        <td class="s3">-</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R461" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">462</div>
        </th>
        <td class="s2" dir="ltr">R005</td>
        <td class="s2" dir="ltr">Visualizar data de publicação dos artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s2" dir="ltr">EF2</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R462" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">463</div>
        </th>
        <td class="s2" dir="ltr">R006</td>
        <td class="s2" dir="ltr">Política de privacidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">NFR Controle de Qualidade</td>
        <td class="s3">i* Configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R463" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">464</div>
        </th>
        <td class="s2" dir="ltr">R007</td>
        <td class="s2" dir="ltr">Identidade Visual</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">NFR Usabilidade</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R464" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">465</div>
        </th>
        <td class="s2" dir="ltr">R008</td>
        <td class="s2" dir="ltr">Alta disponibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">NFR Confiabilidade</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R465" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">466</div>
        </th>
        <td class="s2" dir="ltr">R009</td>
        <td class="s2" dir="ltr">Controle de Conteúdo</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s2" dir="ltr"></td>
        <td class="s3">NFR Controle de Qualidade</td>
        <td class="s3">I* Customização de interesses</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R466" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">467</div>
        </th>
        <td class="s2" dir="ltr">R010</td>
        <td class="s2" dir="ltr">Criar nova &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF3</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R467" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">468</div>
        </th>
        <td class="s2" dir="ltr">R011</td>
        <td class="s2" dir="ltr">Manutenibilidade</td>
        <td class="s2" dir="ltr">Não funcional</td>
        <td class="s3"></td>
        <td class="s3">NFR Manutenibilidade</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R468" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">469</div>
        </th>
        <td class="s2" dir="ltr">R012</td>
        <td class="s2" dir="ltr">Visualizar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF4</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R469" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">470</div>
        </th>
        <td class="s2" dir="ltr">R013</td>
        <td class="s2" dir="ltr">Salvar &#39;serie&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF5</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R470" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">471</div>
        </th>
        <td class="s2" dir="ltr">R014</td>
        <td class="s2" dir="ltr">Editar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF6</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R471" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">472</div>
        </th>
        <td class="s2" dir="ltr">R015</td>
        <td class="s2" dir="ltr">Deletar &#39;serie&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF7</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R472" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">473</div>
        </th>
        <td class="s2" dir="ltr">R016</td>
        <td class="s2" dir="ltr">Ver status</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF8</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R473" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">474</div>
        </th>
        <td class="s2" dir="ltr">R017</td>
        <td class="s2" dir="ltr">Escrever &#39;new story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF9</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R474" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">475</div>
        </th>
        <td class="s2" dir="ltr">R018</td>
        <td class="s2" dir="ltr">Salvar &#39;story&#39; como rascunho</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF10</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R475" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">476</div>
        </th>
        <td class="s2" dir="ltr">R019</td>
        <td class="s2" dir="ltr">visualizar rascunhos das &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF11</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R476" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">477</div>
        </th>
        <td class="s2" dir="ltr">R020</td>
        <td class="s2" dir="ltr">Visualizar stories publicadas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF12</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R477" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">478</div>
        </th>
        <td class="s2" dir="ltr">R021</td>
        <td class="s2" dir="ltr">Importar &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF13</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R478" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">479</div>
        </th>
        <td class="s2" dir="ltr">R022</td>
        <td class="s2" dir="ltr">Editar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF14</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R479" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">480</div>
        </th>
        <td class="s2" dir="ltr">R023</td>
        <td class="s2" dir="ltr">Deletar story</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF15</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R480" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">481</div>
        </th>
        <td class="s2" dir="ltr">R024</td>
        <td class="s2" dir="ltr">Aplaudir um texto lido</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF16</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R481" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">482</div>
        </th>
        <td class="s2" dir="ltr">R025</td>
        <td class="s2" dir="ltr">Compartilhar texto lido nas redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF17</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R482" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">483</div>
        </th>
        <td class="s2" dir="ltr">R026</td>
        <td class="s2" dir="ltr">Comentar no corpo do texto da &#39;story&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF18</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R483" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">484</div>
        </th>
        <td class="s2" dir="ltr">R027</td>
        <td class="s2" dir="ltr">Escutar podcasts</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF19</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R484" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">485</div>
        </th>
        <td class="s2" dir="ltr">R028</td>
        <td class="s2" dir="ltr">Seguir escritores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF20</td>
        <td class="s3">-</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R485" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">486</div>
        </th>
        <td class="s2" dir="ltr">R029</td>
        <td class="s2" dir="ltr">Seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF21</td>
        <td class="s3">-</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R486" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">487</div>
        </th>
        <td class="s2" dir="ltr">R030</td>
        <td class="s2" dir="ltr">Receber notificações dos escritores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF22</td>
        <td class="s3">NFR Controle de Qualidade</td>
        <td class="s3">i* Configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R487" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">488</div>
        </th>
        <td class="s2" dir="ltr">R031</td>
        <td class="s2" dir="ltr">Selecionar tema de artigos para leitura</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF23</td>
        <td class="s3">-</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R488" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">489</div>
        </th>
        <td class="s2" dir="ltr">R032</td>
        <td class="s2" dir="ltr">Visualizar textos publicados por um escritor em seu perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF24</td>
        <td class="s3">-</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R489" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">490</div>
        </th>
        <td class="s2" dir="ltr">R033</td>
        <td class="s2" dir="ltr">Visualizar os artigos favoritados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF25</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R490" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">491</div>
        </th>
        <td class="s2" dir="ltr">R034</td>
        <td class="s2" dir="ltr">Visualizar os artigos curtidos (?)</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF26</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R491" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">492</div>
        </th>
        <td class="s2" dir="ltr">R035</td>
        <td class="s2" dir="ltr">Visualizar perfis de outros usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF27</td>
        <td class="s3">-</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R492" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">493</div>
        </th>
        <td class="s2" dir="ltr">R036</td>
        <td class="s2" dir="ltr">Favoritar publicação para leitura posterior</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF28</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R493" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">494</div>
        </th>
        <td class="s2" dir="ltr">R037</td>
        <td class="s2" dir="ltr">Visualizar comentários da publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF29</td>
        <td class="s3">-</td>
        <td class="s3">i* Stories</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R494" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">495</div>
        </th>
        <td class="s2" dir="ltr">R038</td>
        <td class="s2" dir="ltr">Reportar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF30</td>
        <td class="s3">NFR Segurança</td>
        <td class="s3">i* Configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R495" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">496</div>
        </th>
        <td class="s2" dir="ltr">R039</td>
        <td class="s2" dir="ltr">Reportar usuário</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF31</td>
        <td class="s3">NFR Segurança</td>
        <td class="s3">i* Configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R496" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">497</div>
        </th>
        <td class="s2" dir="ltr">R040</td>
        <td class="s2" dir="ltr">Editar informações de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF32</td>
        <td class="s3">NFR Segurança</td>
        <td class="s3">i* Perfil</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R497" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">498</div>
        </th>
        <td class="s2" dir="ltr">R041</td>
        <td class="s2" dir="ltr">Salvar/cancelar edição de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF33</td>
        <td class="s3">NFR Segurança</td>
        <td class="s3">i* Perfil</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R498" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">499</div>
        </th>
        <td class="s2" dir="ltr">R042</td>
        <td class="s2" dir="ltr">Visualizar autores seguidos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF34</td>
        <td class="s3">-</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R499" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">500</div>
        </th>
        <td class="s2" dir="ltr">R043</td>
        <td class="s2" dir="ltr">Visualizar seguidores</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF35</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R500" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">501</div>
        </th>
        <td class="s2" dir="ltr">R044</td>
        <td class="s2" dir="ltr">Visualizar &#39;clap&#39; em &#39;stories&#39;</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF36</td>
        <td class="s3">NFR Controle de Qualidade</td>
        <td class="s3">i* Stories</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R501" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">502</div>
        </th>
        <td class="s2" dir="ltr">R045</td>
        <td class="s2" dir="ltr">Visualizar próprio perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF37</td>
        <td class="s3">NFR Segurança</td>
        <td class="s3">i* Perfil</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R502" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">503</div>
        </th>
        <td class="s2" dir="ltr">R046</td>
        <td class="s2" dir="ltr">Visualizar estatísticas de leitura em gráfico</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF38</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R503" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">504</div>
        </th>
        <td class="s2" dir="ltr">R047</td>
        <td class="s2" dir="ltr">Visualizar marcações feitas</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF39</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R504" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">505</div>
        </th>
        <td class="s2" dir="ltr">R048</td>
        <td class="s2" dir="ltr">Criar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF40</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R505" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">506</div>
        </th>
        <td class="s2" dir="ltr">R049</td>
        <td class="s2" dir="ltr">Visualizar rascunho de publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF41</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R506" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">507</div>
        </th>
        <td class="s2" dir="ltr">R050</td>
        <td class="s2" dir="ltr">Editar publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF42</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R507" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">508</div>
        </th>
        <td class="s2" dir="ltr">R051</td>
        <td class="s2" dir="ltr">Deletar Publicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF43</td>
        <td class="s3">-</td>
        <td class="s3">I* Publicações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R508" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">509</div>
        </th>
        <td class="s2" dir="ltr">R052</td>
        <td class="s2" dir="ltr">Selecionar tópicos de interesse</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF44</td>
        <td class="s3">NFR Controle de Qualidade</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R509" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">510</div>
        </th>
        <td class="s2" dir="ltr">R053</td>
        <td class="s2" dir="ltr">Deixar de seguir usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF45</td>
        <td class="s3">-</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R510" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">511</div>
        </th>
        <td class="s2" dir="ltr">R054</td>
        <td class="s2" dir="ltr">Deixar de seguir publicações</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF46</td>
        <td class="s3">NFR Controle de Qualidade</td>
        <td class="s3">i* Pesquisar conteúdo</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R511" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">512</div>
        </th>
        <td class="s2" dir="ltr">R055</td>
        <td class="s2">Aivar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF47</td>
        <td class="s3">NFR Usabilidade</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R512" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">513</div>
        </th>
        <td class="s2" dir="ltr">R056</td>
        <td class="s2">Automatizar modo noturno</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF48</td>
        <td class="s3">NFR Usabilidade</td>
        <td class="s3">-</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R513" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">514</div>
        </th>
        <td class="s2">R057</td>
        <td class="s2">Editar email padrão</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF49</td>
        <td class="s7"></td>
        <td class="s3">I* SD configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R514" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">515</div>
        </th>
        <td class="s2">R058</td>
        <td class="s2" dir="ltr">Selecionar período de sugestão de artigos </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF50</td>
        <td class="s3">NFR :Controle de Qualidade<br></td>
        <td class="s3">I* SD configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R515" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">516</div>
        </th>
        <td class="s2">R059</td>
        <td class="s2">Desativar sugestão de artigos</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF51</td>
        <td class="s3">NFR :Controle de Qualidade<br></td>
        <td class="s3">I* SD configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R516" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">517</div>
        </th>
        <td class="s2">R060</td>
        <td class="s2">Ativar/desativar boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF52</td>
        <td class="s3">NFR :Controle de Qualidade<br></td>
        <td class="s3">I* SD configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R517" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">518</div>
        </th>
        <td class="s2">R061</td>
        <td class="s2">Selecionar tema do boletim informativo</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF53</td>
        <td class="s3">NFR :Controle de Qualidade<br></td>
        <td class="s3">I* SD configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R518" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">519</div>
        </th>
        <td class="s2">R062</td>
        <td class="s2">Ativar/desativar recomendações de stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF54</td>
        <td class="s3">NFR :Controle de Qualidade<br></td>
        <td class="s3">I* SD configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R519" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">520</div>
        </th>
        <td class="s2">R063</td>
        <td class="s2">Ativar/desativar notificação por e-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF55</td>
        <td class="s7"></td>
        <td class="s3">I* SD configurações</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R520" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">521</div>
        </th>
        <td class="s2">R064</td>
        <td class="s2">Ativar/desativar notificação social</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF56</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R521" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">522</div>
        </th>
        <td class="s2">R065</td>
        <td class="s2">Selecionar privacidade de menções</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF57</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R522" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">523</div>
        </th>
        <td class="s2">R066</td>
        <td class="s2">Desativar menções de usuários</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF58</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R523" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">524</div>
        </th>
        <td class="s2">R067</td>
        <td class="s2">Conectar com redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF59</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R524" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">525</div>
        </th>
        <td class="s2">R068</td>
        <td class="s2">Conectar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF60</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R525" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">526</div>
        </th>
        <td class="s2">R069</td>
        <td class="s2">Mostrar links para facebook e twitter na página de perfil</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF61</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R526" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">527</div>
        </th>
        <td class="s2">R070</td>
        <td class="s2">Editar nome de usuário para menção</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF62</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R527" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">528</div>
        </th>
        <td class="s2">R071</td>
        <td class="s2">Permitir/bloquear leitura de notas privadas em seus stories</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF63</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R528" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">529</div>
        </th>
        <td class="s2">R072</td>
        <td class="s2">Gerenciar usuários bloqueados</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF64</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R529" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">530</div>
        </th>
        <td class="s2">R073</td>
        <td class="s2">Fazer download de meus dados do Medium</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF65</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R530" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">531</div>
        </th>
        <td class="s2">R074</td>
        <td class="s2">Deslogar de outras sessões </td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF66</td>
        <td class="s7"></td>
        <td class="s3">[I* SD configurações]: (task) deslocar de outras sesssões</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R531" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">532</div>
        </th>
        <td class="s2">R075</td>
        <td class="s2">Desativar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF67</td>
        <td class="s7"></td>
        <td class="s3">[I* SD configurações]: (task) desativar/deletar conta</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R532" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">533</div>
        </th>
        <td class="s2">R076</td>
        <td class="s2">Deletar conta</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF68</td>
        <td class="s7"></td>
        <td class="s3">[I* SD configurações]: (task) desativar/deletar conta</td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R533" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">534</div>
        </th>
        <td class="s2">R077</td>
        <td class="s2">Visualizar tutorial das áreas da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF69</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R534" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">535</div>
        </th>
        <td class="s2">R078</td>
        <td class="s2">Acessar glossário MEDIUM</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF70</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R535" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">536</div>
        </th>
        <td class="s2">R079</td>
        <td class="s2">Responder questionário de satisfação da aplicação</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF71</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R536" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">537</div>
        </th>
        <td class="s2">R080</td>
        <td class="s2">Pesquisar tópico de ajuda</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF72</td>
        <td class="s7"></td>
        <td class="s3"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R537" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">538</div>
        </th>
        <td class="s2">R081</td>
        <td class="s2">Escolher plano de assinatura membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF73</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R538" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">539</div>
        </th>
        <td class="s2">R082</td>
        <td class="s2">Inserir forma de pagamento do medium membership</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF74</td>
        <td class="s7"></td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R539" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">540</div>
        </th>
        <td class="s2">R083</td>
        <td class="s2">Login via redes sociais</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF75</td>
        <td class="s3">NFR: Segurança</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R540" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">541</div>
        </th>
        <td class="s2">R084</td>
        <td class="s2">Login via Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF76</td>
        <td class="s3">NFR: Segurança</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R541" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">542</div>
        </th>
        <td class="s2">R085</td>
        <td class="s2">Login via E-mail</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF77</td>
        <td class="s3">NFR: Segurança</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R542" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">543</div>
        </th>
        <td class="s2">R086</td>
        <td class="s2">Cadastrar com Google</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF78</td>
        <td class="s3">NFR: Segurança</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R543" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">544</div>
        </th>
        <td class="s2">R087</td>
        <td class="s2">Cadastrar com Facebook</td>
        <td class="s2" dir="ltr">Funcional</td>
        <td class="s3">EF79</td>
        <td class="s3">NFR: Segurança</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R544" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">545</div>
        </th>
        <td class="s2">R088</td>
        <td class="s2">Segurança</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3">EF80</td>
        <td class="s3">NFR: Segurança</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
      <tr style='height:20px;'>
        <th id="0R545" style="height: 20px;" class="row-headers-background">
          <div class="row-header-wrapper" style="line-height: 20px;">546</div>
        </th>
        <td class="s2">R089</td>
        <td class="s2">Desempenho</td>
        <td class="s2" dir="ltr">Não Funcional</td>
        <td class="s3"></td>
        <td class="s3">NFR: Desempenho</td>
        <td class="s7"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
        <td class="s5"></td>
      </tr>
    </tbody>
  </table>
</div>

### Elos Funcionais

**Legenda:**
- Representação/Representa = R
- Alocação = A
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

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: StoryTelling - Escritor, New Story **R** US 063

**R**: Brainstorming 4 **R** UC32

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**R**: RichPicture "Ponto de vista do escritor/New Story" **R** StoryTelling - Escritor, New Story

**R**: US 063 **R** i* Publicações
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
- US 063 - Usuário Escritor: Escrever 'new storie' 
- I* Publicações

#### Elos

**R**: 

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: StoryTelling - Escritor, New Story **R** US 063

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**R**: US 063 **R** i* Publicações
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
- I* Publicações

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: Cenário Criar um novo stories **AE** Introspecção 3

**A**: Introspecção 3 **AE** i* Publicações

**R**: StoryTelling - Escritor, New Story **R** Introspecção 3

**A**: US 032 **AE** UC Stories
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

#### Elos

**R**: StoryBoard Tutorial **R** Introspecção 1

**R**: Brainstorming 3 **R** StoryBoard Tutorial

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**R**: Léxico Stories **R** UC stories

**A**: UC28 **AE** UC Stories

**R**: US 071 **R** UC28

**R**: US 071 **R** i* Publicações
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

#### Elos
**R**: StoryTelling - Escritor, New Story **R** US 064

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: UC35 **AE** UC Stories

**A**: UC35 **AE** i* Publicações

**R**: US 060 **R** i* Publicações

**R**: StoryTelling - Escritor, New Story **R** Introspecção 3
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

#### Elos

**R**: Léxico Stories **R** UC stories

**A**: Léxico Stories **AE** Cenário Criar um novo stories

**A**: UC36 **AE** UC Stories

**A**: UC36 **AE** i* Publicações

**R**: UC36 **R** US 061

**R**: US 061 **R** i* Publicações

**R**: Léxico Stories **R** Introspecção 3
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

#### Elos

**R**: Léxico Clap **R** US 065

**R**: lexico clap **R** Cenário Dar Claps

**R**: introspecção 1 **R** StoryBoard Tutorial

**A**: US 065 **AE** i* Publicações

**A**: Cenário Dar Claps **AE**  Brainstorming 3
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

#### Elos

**R**: Brainstorming 4 **R** Introspecção 1

**R**: Cenário Comentar Publicação **R** US 067

**A**: Léxico Response **AE** Cenário Comentar Publicação

**R**: US 067 **Rdo em** i* Publicações
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
- i* Stories
#### Elos
**R**: Brainstorming 4 **R** Cenário Comentar Publicação

**A**: Léxico Response **AE** Cenário Comentar Publicação

**A**: UC30 **AE** US 031

**R**:Cenário Comentar Publicação **R** i* Stories
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
- Cenário Editar perfil	
- Léxico Edit e Léxico Profile	
- UC Área comum	
- UC09 - Editar perfil	
- US 043 - Usuário: Editar informações de perfil	
- NFR Segurança	
- i* Perfil
#### Elos
**R**: StoryTelling Editar **R** Cenário Editar Perfil

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
- Cenário Editar perfil	-
- Léxico Edit e Léxico Profile	
- UC Área comum	UC09 - Editar perfil	
- US 043 - Usuário: Editar informações de perfil	
- NFR Segurança	
- i* Perfil
#### Elos
**R**: StoryTelling Editar **R** Cenário Editar Perfil

**A**: Léxico Edit e Profile **AE** Cenário Editar Perfil

**A**: i* Perfl **AE** NFR Segurança

**R**: US 043 **R** UC Área Comum
***

#### EF34

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- StoryBoard - Tutorial e seguir escritor: "Realmente. E ainda consigo seguir o perfil de escritores dos tutoriais estando logado"			
- Cenário Deixar de seguir usuário	
- Léxico Following		
- i* Pesquisar conteúdo
#### Elos
**R**: StoryBoard Tutorial **R** Cenário Deixar de Seguir usuário

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
- Cenário Dar clap	
- Léxico Clap		
- UC30 - Visualizar Publicações	
- US 057 - Usuário: Visualizar claps em suas publicações	
- NFR Controle de Qualidade	
- i* Stories
#### Elos
**R**: Cenário Dar Clap **R** Storytelling Escritor

**A**: Léxico clap **AE** Cenário Dar Clap

**A**: UC30 **AE** Storytelling Escritor

**A**: UC30 **AE** US 057

**R**: US 057 **R** NFR Controle de Qualidade

**R**: NFR Controle de Qualidade **R** i* Stories
***

#### EF37

#### Categoria
Desenvolvimento
#### Elementos Rastreáveis
- Storytelling - Editar Perfil: "Entre essas opções estava escrita a opção “Profile”, então Carlos clicou sobre essa opção e ao mesmo instante ele foi redirecionado para uma página que apresentava todos os seus dados cadastrais."			
- Cenário Editar perfil	
- Léxico Profile	
- UC Área comum	
- UC09 - Editar perfil	
- US 044 - Usuário: Visualizar próprio perfil	
- NFR Segurança	
- i* Perfil
#### Elos
**R**: Storytelling Editar Perfil **R** Cenário Editar Perfil

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

**Representação**: StoryTelling Escritor, New Story e UC Stories **REPRESENTA** Cenário Criar um novo storie

**Representação**: I* Publicações **REPRESENTA** Cenário criar novo Storie e UC cenários

**Alocação**: Pergunta "Como você classifica o editor de textos padrão do Médium?" **ALOCADA EM** UC Stories, Cenário - criar novo Storie


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

**Representação**: StoryTelling Escritor, New Story e UC Stories **REPRESENTA** Cenário Criar um novo storie

**Representação**: I* Publicações **REPRESENTA** Cenário criar novo Storie e US 059

**Representação**: UC Stories **REPRESENTA** US 059 - Editar publicação

**Alocação**: Pergunta "Como você classifica o editor de textos padrão do Médium?" **ALOCADA EM** UC Stories, Cenário - criar novo Storie

**Alocação**: UC Stories **ALOCADO EM** I* Publicações

**Alocação**: Léxico editar **ALOCADO EM** Cenário Criar um novo storie

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

**Representação**: I* Publicações **REPRESENTA** Cenário criar novo Storie

**Representação**: UC Stories **REPRESENTA** US UC - Excluir publicação

**Alocação**: UC Stories **ALOCADO EM** I* Publicações

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

#### Elo

**Representação** UC cadastro **REPRESENTA** US 008 - Usuário: Selecionar alguns tópicos de meu interesse

**Alocação**: Cenário customizar interesses, US 008 **ALOCADO EM**  NFR Controle de Conteúdo

**Alocação**: I* Pesquisar conteúdo **ALOCADO EM** Especificação: UC01 - Área comum
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

**Representação**: UC01 - Área Comum **REPRESENTA** Cenário deixar de seguir usuários

***Representação**:  **REPRESENTA** Cenário deixar de seguir usuários

**Alocação**: Léxico Seguidores **ALOCADO EM** Especificação: UC01 - Área comum, UC01- Área Comum
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

#### Elo

**Representação**: UC01 - Área comum  **REPRESENTA** Especificação:UC10-Configurar preferências

**Alocação**: Introspecção 3 **ALOCADO EM** NFR Controle de Conteúdo

**Alocação**: i* Pesquisar conteúdo  **ALOCADO EM** UC01 - Área Comum

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

**Representação**: UC01 - Área comum  **REPRESENTA** Especificação:UC10-Configurar preferências

**Alocação**: Léxico night mode **ALOCADO EM** Storytelling - Configurações,US010 - Ativar modo noturno

**Alocação** Storytelling - Configurações e US010 - Ativar modo noturno  **ALOCADO EM** NFR Usabilidade

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

**Representação**: UC01 - Área comum  **REPRESENTA** Especificação:UC10-Configurar preferências

**Alocação**: Léxico night mode **ALOCADO EM** Storytelling - Configurações,US011-Automatizar modo noturno

**Alocação** Storytelling - Configurações e US011-Automatizar modo noturno  **ALOCADO EM** NFR Usabilidade

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

**Representação**: I* SD configurações: (task) editar email **REPRESENTA** US012 - Editar email padrão

**Representação**: UC Área comum **REPRESENTA** C04 editar perfil

**Alocação** Storytelling - Configurações **ALOCADO EM** Especificação: UC10-Configurar preferências

**Alocação** US012-Editar email padrão  **ALOCADO EM** Storytelling - Configurações e Brainstorming 2

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

#### Elo

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**Representação**: Caso de uso : Área comum  **REPRESENTA** Léxico newsletter

**Alocação** I* SD configurações e US013-Selecionar período de sugestão de artigos  **ALOCADO EM** NFR Controle de qualidade

**Alocação** Léxico newsletter **ALOCADO EM** US013-Selecionar período de sugestão de artigos

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

#### Elo

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**Representação**: Caso de uso : Área comum  **REPRESENTA** Léxico newsletter

**Alocação** I* SD configurações e US014-Desativar sugestão de artigos **ALOCADO EM** NFR Controle de qualidade

**Alocação** Léxico newsletter **ALOCADO EM** US013-Selecionar período de sugestão de artigos

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**Representação**: Caso de uso : Área comum  **REPRESENTA** Léxico newsletter e introspecçaõ 1

**Alocação** I* SD configurações e US015-Ativar/desativar boletim informativo **ALOCADO EM** NFR Controle de qualidade

**Alocação** Léxico newsletter **ALOCADO EM** US013-Selecionar período de sugestão de artigos e Introspecção 1

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**Representação**: Caso de uso : Área comum  **REPRESENTA** Léxico newsletter e introspecçaõ 1

**Alocação** I* SD configurações e US016-Selecionar tema do boletim informativo **ALOCADO EM** NFR Controle de qualidade

**Alocação** Léxico newsletter **ALOCADO EM** US013-Selecionar período de sugestão de artigos e Introspecção 1

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

#### Elo

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**Alocação**: US017-Ativar as recomendações de stories e Cenário: C10:Configurar notificações de e-mail **ALOCADO EM** Brainstorming 3

**Alocação** I* SD configurações e 017-Ativar as recomendações de stories **ALOCADO EM** NFR Controle de qualidade

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**Alocação**: US018-Ativar as notificação por e-mail e Cenário: C10:Configurar notificações de e-mail **ALOCADO EM** Brainstorming 3

**Alocação**: Cenário: C10:Configurar notificações de e-mail  **ALOCADO EM** Introspecção 1:Comportamento do usuário na Página inicial da aplicação

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação e Cenário: C10:Configurar notificações de e-mail

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Cenário: C10:Configurar notificações de e-mail e Especificação: UC10-Configurar preferências

**Alocação**: Cenário: C10:Configurar notificações de e-mail  **ALOCADO EM** Especificação: UC10

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Léxico mention **ALOCADO EM** Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US019

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Léxico mention **ALOCADO EM** Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US020-Desativar menções a mim  

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Léxico conection **ALOCADO EM** Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US020-Desativar menções a mim  e US006-Conectar com redes sociais

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Léxico conection **ALOCADO EM** Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US020-Desativar menções a mim e US007-Conectar com Google
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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências e US019-Gerenciar a privacidade de menções e US020-Desativar menções a mim e US021-Mostrar links para minhas redes sociais **ALOCADO EM** UC Área Comum
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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

**Alocação**: Léxico editar **ALOCADO EM** UC Área Comum e Storybord- Usuário configurando a aplicação
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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

**Alocação**: Léxico seguidores **ALOCADO EM** UC Área Comum e Storybord- Usuário configurando a aplicação
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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum
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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

**Alocação** US034-Deslogar de outras sessões **ALOCADO EM** Especificação: UC10-Configurar preferências
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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

**Alocação**: Léxico conta **ALOCADO EM** UC Área Comum e I* SD configurações

**Alocação** US022-Desativar minha conta **ALOCADO EM** Especificação: UC10-Configurar preferências
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

**Representação**: I* SD configurações **REPRESENTA** Storybord - Usuário, Configurando a aplicação

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

**Alocação**: Léxico conta **ALOCADO EM** UC Área Comum e I* SD configurações

**Alocação** US023- Deletar minha conta **ALOCADO EM** Especificação: UC10-Configurar preferências
***

#### EF69

#### Categoria
Desenvolvimento 
#### Elementos Rastreáveis

- Storybord - Usuário, Configurando a aplicação
- Caso de uso : Área comum
- Especificação: UC10-Configurar preferências

#### Elo

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

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

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

**Alocação**: Storybord, UC Área comum **ALOCADO EM** Léxico Medium

**Alocação**: US001-Acessar glossário MEDIUM **ALOCADO EM** UC Área Comum

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

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

**Alocação**: Storybord, UC Área comum **ALOCADO EM** Léxico Medium

**Alocação**: US002-Responder questionário de satisfação da aplicação **ALOCADO EM** UC Área Comum

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

**Representação**: Storybord-Usuário, Configurando a aplicação **REPRESENTA** Especificação: UC10-Configurar preferências

**Alocação**: Especificação: UC10-Configurar preferências **ALOCADO EM** UC Área Comum

**Alocação**: Storybord, UC Área comum **ALOCADO EM** Léxico Medium

**Alocação**: US003-Pesquisar tópico de ajuda **ALOCADO EM** UC Área Comum

***