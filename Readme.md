### 🌐 Curiosidades sobre HTML

O *HTML (HyperText Markup Language)* é a base da web — simples, poderosa e em constante evolução.  
Abaixo estão algumas curiosidades e informações interessantes sobre essa linguagem que molda a internet desde 1991.

---

#### 💡 Curiosidades sobre HTML

1. A primeira página da web, feita por *Tim Berners-Lee* em 1991, ainda está no ar — e você pode vê-la no site do CERN.  
2. O *HTML* foi criado originalmente para *compartilhar documentos científicos*, não para criar sites bonitos.  
3. O *HTML 2.0* (1995) foi a *primeira versão oficial* da linguagem.  
4. As tags `<blink>` e `<marquee>` eram usadas para *animar textos* há décadas atrás.  
5. A tag `<dialog>` permite criar *modais nativos*, sem precisar de frameworks.  
6. O atributo `contenteditable` torna *qualquer elemento editável* diretamente no navegador.  
7. O HTML é um *padrão vivo (Living Standard)*, atualizado continuamente pelo **WHATWG**.  
8. O atributo `loading="lazy"` em imagens melhora a *performance* ao carregar apenas o que está visível.  
9. É possível renderizar páginas HTML *no terminal*, usando navegadores como o **Lynx**.  
10. Você pode criar *aplicações mobile e desktop* com HTML e tecnologias da web.  
11. HTML, CSS e JS formam a base das *PWA (Progressive Web Apps)*, que podem ser instaladas no celular.  
12. O HTML também é usado para *criar emails ricos*, com formatação e imagens.  
13. O HTML5 trouxe APIs como *Geolocation* e *Web Storage*.  
14. O HTML foi *inspirado no SGML*, uma linguagem de marcação mais antiga.  
15. Com o elemento `<canvas>`, é possível *criar jogos* diretamente no navegador.  
16. O HTML permite usar *SVG* para criar gráficos vetoriais escaláveis.  
17. *Tim Berners-Lee*, o criador do HTML, **ainda é ativo** no desenvolvimento da web.  
18. O HTML foi criado para ser *retrocompatível*, garantindo que sites antigos funcionem até hoje.  
19. O *VSCode* foi desenvolvido usando *HTML, CSS e JavaScript* (via Electron).  
20. O HTML é a forma como *robôs de busca e leitores de tela* enxergam a web.

---

#### 🧱 Principais Tags HTML

##### 🏗️ Estrutura Básica

| Tag | Função |
|-----|--------|
| `<!DOCTYPE html>` | Define o tipo de documento (HTML5). |
| `<html>` | Elemento raiz de uma página HTML. |
| `<head>` | Contém metadados, título e links para scripts e estilos. |
| `<body>` | Contém todo o conteúdo visível da página. |

##### 📝 Texto e Conteúdo

| Tag | Função |
|-----|--------|
| `<h1>` a `<h6>` | Títulos e subtítulos, do maior para o menor. |
| `<p>` | Parágrafo. |
| `<br>` | Quebra de linha. |
| `<strong>` | Dá ênfase semântica (importância) ao texto. |
| `<b>` | Deixa o texto em negrito, sem ênfase semântica. |
| `<em>` | Dá ênfase leve (itálico). |
| `<i>` | Deixa o texto em itálico, sem semântica. |
| `<mark>` | Destaca o texto. |
| `<blockquote>` | Citação em bloco. |
| `<code>` | Exibe código-fonte. |

##### 🔗 Links e Mídia

| Tag | Função |
|-----|--------|
| `<a>` | Cria links. |
| `<img>` | Exibe imagens. |
| `<picture>` | Define imagens responsivas. |
| `<video>` | Reproduz vídeos. |
| `<audio>` | Reproduz sons. |
| `<source>` | Define fontes alternativas de mídia. |

##### 📦 Estrutura e Layout

| Tag | Função |
|-----|--------|
| `<div>` | Bloco genérico para agrupar conteúdo. |
| `<span>` | Agrupa conteúdo em linha. |
| `<section>` | Define uma seção temática. |
| `<article>` | Define um conteúdo independente (como post ou notícia). |
| `<header>` | Cabeçalho de página ou seção. |
| `<footer>` | Rodapé da página ou seção. |
| `<nav>` | Define links de navegação. |
| `<main>` | Define o conteúdo principal. |
| `<aside>` | Conteúdo lateral ou complementar. |

##### 🧾 Formulários

| Tag | Função |
|-----|--------|
| `<form>` | Cria um formulário. |
| `<input>` | Campo de entrada. |
| `<label>` | Rótulo para um campo. |
| `<textarea>` | Área de texto. |
| `<button>` | Botão de envio ou ação. |
| `<select>` | Menu suspenso. |
| `<option>` | Opção dentro de um select. |

##### ⚙️ Interatividade e Scripts

| Tag | Função |
|-----|--------|
| `<script>` | Executa scripts JavaScript. |
| `<noscript>` | Conteúdo mostrado quando o JS está desativado. |
| `<dialog>` | Cria janelas modais nativas. |
| `<details>` e `<summary>` | Criam seções expansíveis. |
| `<canvas>` | Permite desenhar e criar animações via JavaScript. |

##### 🖼️ Gráficos e Recursos

| Tag | Função |
|-----|--------|
| `<svg>` | Cria gráficos vetoriais escaláveis. |
| `<figure>` | Agrupa imagens e legendas. |
| `<figcaption>` | Legenda de uma figura. |
| `<table>` | Cria uma tabela. |
| `<tr>`, `<td>`, `<th>` | Linhas e células da tabela. |

---

#### 🧩 Exemplo Prático de Documento HTML

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Primeiro Site</title>
</head>
<body>
  <h1>Olá, Mundo!</h1>
  <p>Bem-vindo à minha primeira página HTML.</p>
</body>
</html>
