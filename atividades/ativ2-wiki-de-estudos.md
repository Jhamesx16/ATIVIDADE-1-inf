<h1>🚀 Atividade Prática 02: Criando uma Wiki de Estudos Web</h1>

<p>
  Nesta atividade, você construirá uma página de guia de estudos interativa. O objetivo é praticar a estruturação de textos semânticos, a criação de listas organizadas e a navegação por hiperlinks.
</p>

<h2>📋 Requisitos da Atividade</h2>

<ul>
  <li><b>Estrutura Semântica:</b> Manter as tags base do HTML5 (<code>&lt;html&gt;</code>, <code>&lt;head&gt;</code>, <code>&lt;body&gt;</code>).</li>
  <li><b>Navegação Externa:</b> Adicionar pelo menos 2 links para sites externos com <code>target="_blank"</code>.</li>
  <li><b>Navegação por Âncora:</b> Criar um menu no topo com link direto para seções da própria página (usando o atributo <code>id</code>).</li>
</ul>

<h2>🏗️ Guia de Conteúdo e Tags</h2>

<table>
  <thead>
    <tr>
      <th>Seção</th>
      <th>Conteúdo Solicitado</th>
      <th>Tags Esperadas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Cabeçalho e Menu</b></td>
      <td>Título da Wiki + Menu de links rápidos para as seções da página.</td>
      <td><code>&lt;h1&gt;</code>, <code>&lt;a href="#id"&gt;</code></td>
    </tr>
    <tr>
      <td><b>Passo a Passo de Estudo</b></td>
      <td>Uma lista ordenada com a sequência ideal para aprender Frontend.</td>
      <td><code>&lt;ol&gt;</code>, <code>&lt;li&gt;</code>, <code>&lt;strong&gt;</code></td>
    </tr>
    <tr>
      <td><b>Links Úteis</b></td>
      <td>Uma lista não ordenada com links para documentações (ex: MDN Web Docs, W3Schools).</td>
      <td><code>&lt;ul&gt;</code>, <code>&lt;li&gt;</code>, <code>&lt;a target="_blank"&gt;</code></td>
    </tr>
    <tr>
      <td><b>Rodapé / Retorno</b></td>
      <td>Um link no final da página para voltar ao topo ("Voltar ao Início").</td>
      <td><code>&lt;a href="#topo"&gt;</code>, <code>&lt;small&gt;</code></td>
    </tr>
  </tbody>
</table>

<br>

<details>
  <summary>💡 <b>Dica do Professor (Clique para abrir)</b></summary>
  <p>Para criar a âncora de retorno ao topo, adicione o atributo <code>id="topo"</code> na sua tag <code>&lt;h1&gt;</code> principal! No link do rodapé, utilize <code>&lt;a href="#topo"&gt;Voltar ao início&lt;/a&gt;</code>.</p>
</details>
