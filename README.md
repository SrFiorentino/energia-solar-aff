# AFF Elétrica — Energia Solar Fotovoltaica

Projeto desenvolvido para a **Atividade 1** da disciplina de **Linguagem de Script para Web** do Instituto Federal do Triângulo Mineiro (IFTM — Campus Uberaba Parque Tecnológico).

## Sobre o Projeto
Site institucional e informativo sobre soluções em energia solar fotovoltaica com a identidade da **AFF Elétrica** (Uberaba-MG), apresentando tipos de módulos, arquiteturas de sistemas, orientações pré-instalação, dúvidas frequentes e formulário de solicitação de orçamento.

## Estrutura de Arquivos
```text
.
├── index.html
├── estilo.css
├── README.md
└── img/
    ├── mono.png
    ├── poli.png
    ├── offgrid.png
    └── inversores.png
```

## Recursos de HTML Semântico e Acessibilidade Aplicados
- **Estrutura semântica:** uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<figure>`, `<figcaption>` e `<footer>`.
- **Navegação acessível:** link *"Pular para o conteúdo principal"* visível ao foco por teclado (`Tab`) e atributos `aria-label` / `aria-labelledby`.
- **Tabela acessível:** uso de `<caption>`, `<thead>`, `<tbody>` e `<th scope="col|row">`.
- **Interatividade nativa sem JS:** seção de Dúvidas Frequentes construída com `<details>` e `<summary>`.
- **Formulário estruturado:** campos agrupados em `<fieldset>` e `<legend>`, com `<label for="...">` associados e validação nativa (`required`, `type`, `min`).

## Publicação (GitHub Pages)
Acesse o site publicado em: https://srfiorentino.github.io/energia-solar-aff/
