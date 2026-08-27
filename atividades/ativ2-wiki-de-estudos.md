<div align="center">

<h1>📚 Atividade Prática 02</h1>
<h2>Wiki de Estudos Web</h2>
<p><strong>Organize conhecimentos, crie caminhos de navegação e transforme sua página em um guia de estudos!</strong></p>
<p><code>HTML5</code> • <code>Listas</code> • <code>Links</code> • <code>Âncoras</code></p>

</div>

---

## 🎯 Sobre a atividade

Nesta atividade, você construirá uma **Wiki de Estudos Web**. O objetivo é praticar a organização semântica de textos, a criação de listas e o uso de hiperlinks para navegar entre conteúdos da própria página e sites externos.

Ao final, sua página deverá funcionar como um pequeno guia para quem deseja começar a estudar desenvolvimento Front-end.

## 🧭 Visão geral

| Item | Orientação |
| --- | --- |
| 📄 Produto | Página de guia de estudos |
| 🧱 Tecnologia | HTML5 |
| 🔗 Recursos principais | Links externos e âncoras internas |
| 📋 Organização | Listas ordenadas e não ordenadas |

> [!NOTE]
> Uma **âncora interna** permite sair de uma parte da página e ir diretamente para outra usando um atributo `id`.

## ✅ Requisitos obrigatórios

- [ ] Manter a estrutura base com `<html>`, `<head>` e `<body>`.
- [ ] Criar um título principal para a Wiki.
- [ ] Adicionar pelo menos **dois links externos** com `target="_blank"`.
- [ ] Criar um menu no topo com links para seções da própria página.
- [ ] Usar o atributo `id` nas seções que receberão os links internos.
- [ ] Criar uma lista ordenada com uma sequência de estudos.
- [ ] Criar uma lista não ordenada com links úteis.
- [ ] Adicionar um link para voltar ao início da página.

## 🏗️ Estrutura esperada

| Seção | Conteúdo solicitado | Tags esperadas |
| --- | --- | --- |
| 🧭 **Cabeçalho e menu** | Título da Wiki e links rápidos para as seções da página. | `<h1>`, `<a href="#id">` |
| 🪜 **Passo a passo de estudo** | Uma sequência organizada para aprender Front-end. | `<ol>`, `<li>`, `<strong>` |
| 🔗 **Links úteis** | Uma lista de documentações e materiais de consulta. | `<ul>`, `<li>`, `<a target="_blank">` |
| ⬆️ **Retorno ao topo** | Um link no final da página para voltar ao início. | `<a href="#topo">`, `<small>` |

## 🗺️ Exemplo de organização

```text
Wiki de Estudos Web
├── Menu de navegação
├── Passo a passo de estudo
├── Links úteis
└── Voltar ao início
```

## 🪜 Passo a passo sugerido

1. Crie o título principal e adicione `id="topo"`.
2. Defina as seções que farão parte da Wiki.
3. Crie o menu com links internos.
4. Monte a lista ordenada de estudos.
5. Adicione a lista de links externos.
6. Insira o link de retorno ao topo.
7. Abra a página no navegador e teste todos os links.
8. Corrija qualquer destino incorreto antes da entrega.

<details>
<summary><strong>💡 Dica do professor — clique para abrir</strong></summary>

Adicione `id="topo"` ao título principal:

```html
<h1 id="topo">Minha Wiki de Estudos</h1>
```

Depois, crie o link de retorno:

```html
<a href="#topo">Voltar ao início</a>
```

</details>

## 🔎 Checklist antes da entrega

- [ ] Todos os links externos abrem corretamente?
- [ ] Os links do menu levam às seções certas?
- [ ] O link “Voltar ao início” funciona?
- [ ] As listas estão organizadas com seus respectivos itens?
- [ ] A página está fácil de compreender e navegar?

---

<div align="center">

<h3>🧠 Uma boa Wiki não apenas guarda informações: ela ajuda o leitor a encontrá-las.</h3>

</div>
