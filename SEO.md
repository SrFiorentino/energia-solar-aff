# Relatório de SEO — AFF Elétrica (Atividade 2)

Projeto desenvolvido para a **Atividade 2 (Meu Site Encontrável)** da disciplina de **Linguagem de Script para Web** — IFTM Campus Uberaba Parque Tecnológico.

- **Repositório:** https://github.com/SrFiorentino/energia-solar-aff
- **Site publicado:** https://srfiorentino.github.io/energia-solar-aff/
- **Página secundária:** https://srfiorentino.github.io/energia-solar-aff/sobre.html

---

## 1. Palavras-chave Definidas
1. `energia solar Uberaba`
2. `instalação de energia solar`
3. `placas solares fotovoltaicas`

---

## 2. Decisões e Otimizações Aplicadas

- **SEO On-page (`index.html` e `sobre.html`):** criação de `<title>` (50–60 caracteres) e `<meta name="description">` (120–160 caracteres) únicos em cada página, focados nas 3 palavras-chave definidas, além de `<link rel="canonical">` apontando para a URL oficial de cada página.
- **Open Graph e Favicon:** inclusão das tags `og:type`, `og:title`, `og:description`, `og:image` (imagem `img/og-capa.jpg` em `1200x630` px com URL absoluta), `og:url` e `og:locale`, além de ícone vetorial `favicon.svg`.
- **Dados Estruturados (JSON-LD):** implementação do esquema `LocalBusiness` (`schema.org`) no `<head>` do `index.html` com nome, descrição, URL, imagem, endereço em Uberaba-MG e área de atendimento, validado no `validator.schema.org`.
- **Arquivos Técnicos na Raiz:** criação do `robots.txt` liberando rastreamento e apontando para o mapa do site, e do `sitemap.xml` listando as URLs absolutas das duas páginas (`index.html` e `sobre.html`).
- **Estrutura de Links e 2ª Página:** criação da página `sobre.html` detalhando a atuação da AFF Elétrica e as etapas da instalação, interligada à página inicial por meio de links internos descritivos no menu e no corpo do texto.
- **Otimização de Imagens:** conversão das 4 imagens principais de `.png` para `.webp` (redução de peso para melhoria do LCP), manutenção de atributos `alt`, `width` e `height` (evitando CLS) e aplicação de `loading="lazy"` nas imagens fora da primeira dobra.

---

## 3. Comparativo Lighthouse (Dispositivos Móveis)

Auditoria realizada via **PageSpeed Insights** (Lighthouse para dispositivos móveis) antes e depois das otimizações:

| Categoria | Antes (Atividade 1) | Depois (Atividade 2) | Evolução |
| :--- | :---: | :---: | :---: |
| **Desempenho** | 75 | **97** | +22 |
| **Acessibilidade** | 100 | **96** | -4 |
| **Práticas recomendadas** | 100 | **100** | 0 |
| **SEO** | 91 | **100** | +9 |

---

## 4. Validação de Dados Estruturados
O bloco JSON-LD (`LocalBusiness`) foi testado em `https://validator.schema.org/` sem erros de sintaxe ou campos inválidos.