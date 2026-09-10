<div align="center">

<h1>🗺️ Projeto 02</h1>
<h2>Do Projeto 01 a um Site com Várias Páginas</h2>
<p><strong>Transforme sua página temática em um site completo, organizado e fácil de explorar!</strong></p>
<p><code>HTML5</code> • <code>Várias páginas</code> • <code>Imagens locais</code> • <code>Semântica</code> • <code>Acessibilidade</code></p>

</div>

---

## 🎯 O desafio

No Projeto 01, sua equipe criou uma página para apresentar um tema. Agora esse projeto deverá evoluir para um **site com várias páginas conectadas**.

O visitante deverá perceber a mudança diretamente no navegador: haverá um menu, novas páginas, novos conteúdos e imagens armazenadas no próprio projeto.

Ao mesmo tempo, o código será reorganizado com tags semânticas para explicar a função de cada região do site.

> [!IMPORTANT]
> Este projeto continua sendo desenvolvido somente com HTML. O CSS será estudado e acrescentado em outro momento.

## 🧭 Visão geral

| Item | Orientação |
| --- | --- |
| 👥 Organização | Solo, Dupla ou trio |
| 🏠 Página inicial | `index.html` |
| 📄 Quantidade mínima | 4 páginas HTML |
| 🖼️ Imagens | Pelo menos 3 arquivos locais |
| 🧱 Tecnologia | Somente HTML |
| 📦 Repositório | `projeto-02-site-tematico` |
| ⌨️ Teste | Mouse e teclado |

## 🚀 Objetivos

Ao concluir o projeto, você deverá ser capaz de:

- transformar uma página isolada em um site com várias páginas;
- organizar arquivos HTML e imagens em pastas;
- criar links usando caminhos relativos;
- usar `../` para voltar uma pasta;
- inserir imagens locais com texto alternativo;
- organizar cada página com tags semânticas;
- manter um menu de navegação coerente;
- testar o site usando mouse e teclado;
- explicar uma decisão tomada durante o desenvolvimento.

## 👥 Papéis da equipe

| Papel | Responsabilidade |
| --- | --- |
| ⌨️ **Driver** | Opera o computador e realiza as alterações. |
| 🧭 **Navegador** | Acompanha o enunciado, confere os caminhos e orienta o próximo passo. |
| 🔎 **Revisor** | Abre todas as páginas, testa links e imagens e registra o que precisa ser corrigido. |

> [!NOTE]
> Nas duplas, o Navegador também assume a revisão. Os papéis devem ser trocados durante o projeto para que todos participem da construção e dos testes.

## 🏗️ O site que será construído

O site deverá ter uma página inicial e pelo menos três páginas adicionais.

### Páginas obrigatórias

| Página | Conteúdo esperado |
| --- | --- |
| 🏠 **Página inicial** | Apresentação do tema, imagem de destaque e caminhos para as demais páginas. |
| 🙋 **Sobre mim ou sobre a equipe** | Apresentação segura dos autores, interesses gerais, motivo da escolha do tema e o que aprenderam. |
| 📚 **Página de conteúdo** | Informações úteis relacionadas ao tema escolhido. |
| 🖼️ **Galeria ou segunda página de conteúdo** | Imagens locais com legendas ou outro conteúdo que complemente o site. |

### Sugestões para as páginas de conteúdo

| Tema | Possíveis páginas |
| --- | --- |
| 🎮 Jogo | personagens, guia para iniciantes, fases, itens, dicas ou galeria |
| 🎬 Filme, série ou animação | personagens, história sem spoilers, curiosidades ou recomendações |
| 📚 Livro | autor, personagens, contexto, resenha ou obras relacionadas |
| ⚽ Esporte | regras, equipamentos, posições, atletas ou competições |
| 🎨 Hobby | materiais, primeiros passos, técnicas ou projetos inspiradores |
| 🍲 Receita | ingredientes, preparo, variações ou cuidados na cozinha |
| 💻 Tecnologia | história, componentes, funcionamento, usos ou cuidados |
| 🌱 Comunidade e ambiente | problema, ações possíveis, exemplos ou campanha escolar |

> [!TIP]
> Cada página precisa ter uma função clara. Evite criar quatro páginas com o mesmo texto apenas para atingir a quantidade mínima.

## 🔒 Sobre mim sem expor dados pessoais

A página **Sobre mim** ou **Sobre a equipe** pode apresentar:

- primeiro nome, iniciais ou apelido autorizado;
- interesses gerais;
- papel desempenhado no projeto;
- motivo da escolha do tema;
- parte preferida do site;
- algo aprendido durante o desenvolvimento.

Não publique:

- nome completo;
- telefone ou endereço de e-mail pessoal;
- endereço residencial;
- localização em tempo real;
- senhas ou nomes de usuário privados;
- horários e rotinas pessoais;
- fotografia pessoal sem autorização.

> [!WARNING]
> A atividade avalia o site, não a exposição da vida pessoal. Use somente informações com as quais você se sinta confortável e que tenham sido autorizadas para o projeto escolar.

## 🗂️ Estrutura recomendada

```text
projeto-02-site-tematico/
├── index.html
├── imagens/
│   ├── destaque.jpg
│   ├── imagem-02.jpg
│   └── imagem-03.jpg
└── paginas/
    ├── sobre.html
    ├── conteudo.html
    └── galeria.html
```

Os nomes podem mudar de acordo com o tema, mas devem ser escritos com:

- letras minúsculas;
- palavras separadas por hífen;
- nenhum espaço;
- nenhum acento.

Exemplos: `sobre-a-equipe.html`, `guia-iniciante.html` e `personagens.html`.

## 🔗 Caminhos relativos

### Da página inicial para uma página da pasta

```html
<a href="paginas/sobre.html">Conheça os autores do site</a>
```

### De uma página interna para a página inicial

```html
<a href="../index.html">Voltar à página inicial</a>
```

### Da página inicial para uma imagem local

```html
<img
  src="imagens/destaque.jpg"
  alt="Descrição relacionada à função da imagem"
>
```

### De uma página interna para uma imagem local

```html
<img
  src="../imagens/imagem-02.jpg"
  alt="Descrição relacionada à função da imagem"
>
```

> [!TIP]
> Leia `../` como **“voltar uma pasta”**. Depois de voltar, o navegador procura a pasta `imagens`.

## 🧱 Estrutura semântica das páginas

Todas as páginas devem possuir:

```html
<body>
  <header>
    <!-- Apresentação desta página -->
  </header>

  <nav>
    <!-- Menu principal do site -->
  </nav>

  <main>
    <!-- Conteúdo principal e exclusivo desta página -->
  </main>

  <footer>
    <!-- Informações finais -->
  </footer>
</body>
```

### Como escolher outras tags

| Tag | Use quando... |
| --- | --- |
| `<section>` | houver um grupo de conteúdo com assunto e título próprios; |
| `<article>` | o conteúdo fizer sentido sozinho e puder ser reaproveitado; |
| `<aside>` | a informação for relacionada, mas complementar ao assunto principal. |

> [!IMPORTANT]
> A tag correta é `<section>`. Não existe uma tag estrutural chamada `<session>` em HTML.

## 🧭 Menu de navegação

Todas as páginas devem apresentar um menu com caminhos para:

- página inicial;
- página Sobre mim/equipe;
- primeira página de conteúdo;
- segunda página de conteúdo ou galeria.

O menu pode ser organizado com uma lista:

```html
<nav>
  <h2>Explore o site</h2>
  <ul>
    <li><a href="../index.html">Página inicial</a></li>
    <li><a href="sobre.html">Sobre a equipe</a></li>
    <li><a href="conteudo.html">Conteúdo principal</a></li>
    <li><a href="galeria.html">Galeria</a></li>
  </ul>
</nav>
```

> [!NOTE]
> Os caminhos mudam conforme a localização do arquivo. Não copie um menu sem conferir em qual pasta a página está.

## 🖼️ Imagens e recursos locais

- [ ] Todas as imagens estão dentro do repositório.
- [ ] Os nomes dos arquivos não possuem espaços nem acentos.
- [ ] Cada `src` aponta para um arquivo existente.
- [ ] Cada imagem possui `alt` adequado à sua função.
- [ ] Imagens com legenda utilizam `figure` e `figcaption`.
- [ ] A origem das imagens foi registrada.

Utilize preferencialmente:

- imagens de sites oficiais ou fan kits que autorizem esse uso;
- materiais indicados pelo professor.

Não utilize arquivos de origem desconhecida sem mencionar devidamente os créditos da fonte.

## ✅ Requisitos obrigatórios

### 🌐 Site e páginas

- [ ] O site possui `index.html` na pasta principal.
- [ ] Existem pelo menos quatro páginas HTML funcionais.
- [ ] Cada página apresenta conteúdo diferente e útil.
- [ ] Existe uma página Sobre mim ou Sobre a equipe.
- [ ] Existe um menu de navegação em todas as páginas.
- [ ] É possível retornar à página inicial a partir de qualquer página.

### 🧱 HTML e semântica

- [ ] Todas as páginas possuem `<!DOCTYPE html>`, `html`, `head` e `body`.
- [ ] O idioma está definido como `pt-BR`.
- [ ] Cada página possui um `title` relacionado ao seu conteúdo.
- [ ] Cada página possui somente um `h1`.
- [ ] Todas as páginas usam `header`, `nav`, `main` e `footer`.
- [ ] O site utiliza `section`, `article` e `aside` de acordo com suas funções.
- [ ] Os títulos formam uma hierarquia coerente.

### 🔗 Links e caminhos

- [ ] Os links do menu funcionam em todas as páginas.
- [ ] O site utiliza caminhos relativos entre arquivos.
- [ ] Pelo menos um caminho utiliza `../` corretamente.
- [ ] Os textos dos links informam o destino.
- [ ] Existe pelo menos um link para uma fonte externa confiável.

### 🖼️ Imagens

- [ ] Existem pelo menos três imagens locais.
- [ ] As imagens aparecem no navegador sem erros.
- [ ] Cada imagem possui texto alternativo coerente.
- [ ] Pelo menos uma imagem possui legenda com `figure` e `figcaption`.
- [ ] A origem dos recursos foi registrada no site ou no `README.md`.

### 🧪 Teste, Git e entrega

- [ ] Todas as páginas foram abertas no navegador.
- [ ] Outra equipe testou o menu e as imagens.
- [ ] O site foi percorrido usando `Tab`, `Shift + Tab` e `Enter`.
- [ ] O histórico possui pelo menos três commits com mensagens relacionadas ao trabalho realizado.
- [ ] Cada integrante consegue demonstrar ou explicar uma contribuição.

## 🪜 Etapas do projeto

### 🟦 Etapa 1 — Planejar e criar as páginas

1. Abrir o Projeto 01.
2. Definir quais serão as três novas páginas.
3. Desenhar um mapa simples do site.
4. Criar as pastas `paginas` e `imagens`, caso ainda não existam.
5. Criar os novos arquivos HTML.
6. Fazer um commit com a estrutura inicial.

### 🟧 Etapa 2 — Adicionar conteúdo e organizar o HTML

1. Produzir conteúdo diferente para cada página.
2. Adicionar as imagens locais.
3. Inserir `header`, `nav`, `main` e `footer`.
4. Organizar os conteúdos com `section`, `article` e `aside` quando fizer sentido.
5. Adicionar o mesmo conjunto de destinos ao menu de todas as páginas.
6. Fazer um commit com os conteúdos e a organização.

### 🟩 Etapa 3 — Testar, corrigir e apresentar

1. Abrir cada página no navegador.
2. Testar todos os links e imagens.
3. Repetir o teste usando somente o teclado.
4. Solicitar a revisão de outra equipe.
5. Corrigir os problemas encontrados.
6. Fazer o commit da versão final.
7. Apresentar uma decisão de cada integrante.

## 🔎 Revisão por outra equipe

| Verificação | Sim | Corrigir |
| --- | :---: | :---: |
| A página inicial abre corretamente. | ☐ | ☐ |
| O menu aparece em todas as páginas. | ☐ | ☐ |
| Todos os links chegam ao destino esperado. | ☐ | ☐ |
| É possível voltar à página inicial. | ☐ | ☐ |
| As imagens locais aparecem. | ☐ | ☐ |
| Os textos alternativos correspondem às imagens. | ☐ | ☐ |
| Cada página possui conteúdo próprio. | ☐ | ☐ |
| A função de `header`, `nav`, `main` e `footer` pode ser reconhecida no código. | ☐ | ☐ |
| `section`, `article` e `aside` foram usados com sentido. | ☐ | ☐ |
| O foco fica visível durante o teste com `Tab`. | ☐ | ☐ |
| A ordem dos links faz sentido pelo teclado. | ☐ | ☐ |

**Problema encontrado:** ________________________________________________

**Correção realizada:** _________________________________________________

## 📊 Rubrica — 10 pontos

| Critério | 0 pontos | 1 ponto | 2 pontos |
| --- | --- | --- | --- |
| Páginas e conteúdo | O site não apresenta páginas funcionais ou conteúdos reconhecíveis. | Parte das páginas funciona, mas há repetição ou conteúdo incompleto. | Existem pelo menos quatro páginas funcionais, diferentes e úteis. |
| Navegação e caminhos | Os links impedem a navegação pelo site. | A maior parte funciona, mas existem caminhos incorretos ou destinos confusos. | O menu funciona em todas as páginas e utiliza caminhos relativos, incluindo `../`. |
| Imagens locais e acessibilidade | As imagens não funcionam ou não possuem alternativa compreensível. | Parte das imagens funciona, mas há problemas de caminho, `alt`, legenda ou origem. | Pelo menos três imagens locais funcionam, possuem `alt` adequado e têm origem registrada. |
| Semântica e hierarquia | A estrutura não permite reconhecer a organização do conteúdo. | Parte das tags foi utilizada corretamente, mas existem escolhas ou títulos incoerentes. | As regiões e conteúdos utilizam semântica e hierarquia coerentes. |
| Teste e contribuição | Não há evidência de teste nem contribuição identificável. | O teste ou a contribuição individual foi demonstrado parcialmente. | A equipe testou, corrigiu e registrou o site; cada integrante demonstra uma contribuição. |

## ♿ Formas equivalentes de participação

Os critérios do produto são comuns à turma. A contribuição individual pode ser demonstrada por:

- criação ou edição de uma página;
- escolha e organização de imagens;
- montagem do mapa do site;
- escolha do destino de um link;
- organização de cartões ou blocos HTML;
- operação do navegador;
- teste com mouse ou teclado;
- explicação oral ou apontamento na tela.

O nível de apoio recebido deve ser registrado separadamente e não reduz automaticamente a avaliação.

## 📦 Entrega

> [!IMPORTANT]
> Entregue o endereço do repositório `projeto-02-site-tematico`. O arquivo `index.html` deve estar na pasta principal e todas as imagens necessárias devem estar dentro do próprio repositório.

Antes de finalizar, abra o site a partir do `index.html` e visite todas as páginas sem utilizar os arquivos abertos no VS Code como atalho.

## ⭐ Desafios adicionais

Terminou os requisitos obrigatórios? Experimente:

- [ ] criar uma quinta página útil;
- [ ] adicionar links internos para partes da mesma página;
- [ ] criar uma página de fontes e créditos;
- [ ] usar imagens diferentes para funções diferentes;
- [ ] melhorar os textos alternativos depois da revisão;
- [ ] desenhar um mapa do site mostrando como as páginas estão conectadas.

---

<div align="center">

<h3>✨ Uma página apresenta uma ideia. Um site permite explorá-la.</h3>
<p><strong>Planeje os caminhos, construa as páginas, teste tudo e ajude o visitante a não se perder.</strong></p>

</div>
