# Folclore Brasileiro

> Site informativo e multi-página sobre as lendas e mitos do folclore brasileiro, desenvolvido como projeto de Front-End. Apresenta a história e origem de quatro personagens icônicos da cultura popular do Brasil, com textos detalhados, imagens e navegação entre páginas.

---

## Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Páginas e Conteúdo](#-páginas-e-conteúdo)
- [Layout e Design](#-layout-e-design)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Conceitos de HTML e CSS Aplicados](#-conceitos-de-html-e-css-aplicados)
- [Como Visualizar](#-como-visualizar)

---

## Sobre o Projeto

Este site é um trabalho de pesquisa e desenvolvimento web dedicado ao **folclore brasileiro** — um dos patrimônios culturais mais ricos e diversos do Brasil. O projeto apresenta a origem, as características e os mitos que cercam quatro das lendas mais famosas da cultura popular brasileira, desde seus primeiros registros históricos até as variações regionais que persistem até hoje.

Cada personagem possui uma página dedicada com texto aprofundado, imagem ilustrativa e navegação integrada entre as demais lendas.

---

## Páginas e Conteúdo

### `index.html` — Página Principal
Introdução ao conceito de folclore brasileiro: sua origem, seu papel na identidade cultural do país e a diferença entre **lendas** (mistura de fatos reais com fantasia) e **mitos** (narrativas simbólicas para explicar o mundo). Navegação completa para todas as lendas.

---

### `saci.html` — Saci-Pererê
Uma das lendas mais emblemáticas do folclore nacional. O conteúdo cobre:

- **Descrição:** menino negro, travesso, de uma só perna, que usa cachimbo e carrega uma carapuça vermelha que lhe confere poderes mágicos
- **Travessuras:** fazer tranças nos rabos de animais, esconder objetos, trocar sal por açúcar, assustar viajantes e distrair cozinheiras
- **Papel:** guardião das ervas e plantas medicinais
- **Como capturá-lo:** arremessando uma peneira nos redemoinhos de vento e retirando o gorro
- **Ciclo de vida:** nasce de um broto de bambu, vive 7 + 77 anos e, ao morrer, torna-se um cogumelo venenoso
- **Origem:** tribos indígenas do sul do Brasil; nome derivado do tupi *sa'si* (um pássaro); a perna perdida e o cachimbo vieram da influência africana; o gorrinho vermelho tem raízes no folclore português (o lendário *Trasgo*)
- **Variações regionais:** Saci-Cererê, Matimpererê, Matita Perê, Saci-Saçurá e Saci-Trique

---

### `curupira.html` — Curupira
Protetor milenar das florestas, com origem nos povos indígenas do Norte do Brasil. O conteúdo abrange:

- **Descrição física:** anão de cabelos vermelhos e pés virados ao contrário (calcanhares para frente), com grande força física; variações regionais incluem versões careca ou com corpo cabeludo e dentes verdes
- **Papel:** protetor da floresta contra caçadores e desmatadores; era temido pelos indígenas, que lhe ofereciam fumo e cachaça como presentes ao entrar na mata
- **Poderes:** fazer caçadores se perderem na floresta, assobiar continuadamente para atormentá-los; seus pés ao contrário tornam seu rastreamento impossível
- **Como escapar:** fazer um nó em um pedaço de cipó caso seja encontrado
- **Etimologia:** do tupi, com significados possíveis de "corpo de menino", "coberto de pústulas" ou "pele de sarna"
- **Registro histórico:** uma das mais antigas lendas brasileiras; mencionada pelo padre jesuíta **José de Anchieta** em **1560**, em São Vicente (atual litoral de SP)

---

### `boto.html` — Boto Cor-de-Rosa
Lenda amazônica com raízes que remontam à Grécia Antiga. O conteúdo inclui:

- **A lenda:** o boto se transforma em um homem sedutor de roupas e sapatos brancos que frequenta festas ribeirinhas para seduzir mulheres; o chapéu que usa esconde as narinas — o único sinal de que a transformação não é completa
- **Versões:** em algumas, a transformação ocorre em qualquer festa; em outras, só na Lua cheia de junho, durante os festejos de Santo Antônio, São João e São Pedro
- **Função social:** a lenda era usada para explicar filhos que cresciam sem pai — todo filho sem paternidade declarada era chamado de "filho do boto"
- **Origem histórica:** o antropólogo **Luís da Câmara Cascudo** traça a ligação com o culto ao golfinho na Grécia Antiga, associado a **Afrodite** e à luxúria; o boto como amuleto amoroso (olho seco) fazia parte de práticas populares brasileiras
- **Abrangência:** lendas semelhantes existem na Argentina, Chile e em partes da Europa

---

### `lobisomem.html` — Lobisomem
A lenda universal que chegou ao Brasil pelos portugueses. O conteúdo abrange:

- **Descrição:** homem que se transforma em lobo em noites de lua cheia; vulnerável apenas à prata
- **Formas de transmissão:** maldição, pacto com o diabo, hereditariedade ou mordida
- **Origem grega:** o rei **Licaon** da Arcádia foi transformado em lobo por **Zeus** como punição; o nome "licantropo" vem do grego *lykos* (lobo) + *anthropos* (homem)
- **Em Roma:** existia o culto *lupercália* (festa dos lobos) e o chamado *versipélio*; a crença se espalhou pelas conquistas romanas pela Europa
- **Versão brasileira — variações regionais:**
  - **Geral:** o sétimo filho após seis filhas seria um lobisomem
  - **Norte:** homens anêmicos transformavam-se na noite de quinta para sexta-feira e bebiam sangue para compensar
  - **Sul:** o incesto era a causa da transformação
  - **Interior de SP:** o lobisomem perseguia crianças não batizadas
- **Cura:** ser ferido por uma bala banhada em cera de três missas do galo ou de domingo

---

## Layout e Design

O site adota um design sóbrio e legível, com uma paleta de **tons escuros** que remete ao clima misterioso das lendas:

| Elemento | Cor |
|---|---|
| Header e Footer | Cinza escuro (`#333`) |
| Barra de navegação | Cinza médio (`#444`) |
| Links da navegação | Branco (`#fff`) |
| Fundo da página | Branco padrão do navegador |
| Texto dos parágrafos | Preto padrão |

**Destaques de layout:**
- Logo circular (`border-radius: 50px`) alinhada ao título com `vertical-align: middle`
- Conteúdo principal centralizado com `max-width: 800px` e `margin: auto`
- Texto dos parágrafos justificado (`text-align: justify`) e com fonte de `20px` para facilitar a leitura
- Imagens das lendas com dimensões fixas de **500×500px**, classes individuais por personagem (`.foto1`, `.foto2`, `.foto3`, `.imagemBotoRosa`)
- Imagem do Boto envolta em `<figure>` + `<figcaption>` para acessibilidade

---

## Estrutura do Projeto

```
Folclore-brasileiro/
│
├── index.html          # Página inicial — introdução ao folclore
├── saci.html           # Lenda do Saci-Pererê
├── curupira.html       # Lenda do Curupira
├── boto.html           # Lenda do Boto Cor-de-Rosa
├── lobisomem.html      # Lenda do Lobisomem
│
└── assets/
    ├── css/
    │   └── style.css           # Folha de estilos global
    └── images/
        ├── logo.png            # Logo circular do site (header)
        ├── saci2.jpg           # Ilustração do Saci-Pererê
        ├── curupira2.jpg       # Ilustração do Curupira
        ├── boto.webp           # Ilustração do Boto Cor-de-Rosa
        └── lobisomem2.jpg      # Ilustração do Lobisomem
```

---

## Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica de todas as páginas |
| **CSS3** | Estilização, tipografia, layout e imagens |

Nenhuma dependência externa, framework ou biblioteca é utilizada. O projeto roda diretamente no navegador, sem necessidade de conexão com a internet.

---

## Conceitos de HTML e CSS Aplicados

### HTML

| Tag / Atributo | Uso no Projeto |
|---|---|
| `lang="pt-br"` | Idioma declarado em todas as páginas |
| `<meta charset="UTF-8">` | Suporte a caracteres especiais e acentuação |
| `<meta name="viewport">` | Base para compatibilidade com dispositivos móveis |
| `<header>` | Cabeçalho com logo e título do site |
| `<nav>` + `<ul>` + `<li>` | Barra de navegação entre as páginas |
| `<main>` | Área de conteúdo principal de cada página |
| `<section>` | Divisão temática do conteúdo dentro de cada página |
| `<footer>` | Rodapé com copyright do autor |
| `<h1>` | Títulos das seções de cada lenda |
| `<p>` | Parágrafos com os textos históricos e descritivos |
| `<figure>` + `<figcaption>` | Imagem do Boto com legenda acessível |
| `<img>` com `alt` e `title` | Imagens com descrição alternativa para acessibilidade |
| `<a href>` | Navegação interna entre todas as páginas |

### CSS

| Recurso | Uso no Projeto |
|---|---|
| `background-color` | Tons escuros no header, nav e footer |
| `text-align` | Centralização no header/footer; justificado no conteúdo |
| `max-width` + `margin: auto` | Centralização e limitação do conteúdo em 800px |
| `display: flex` | Layout horizontal dos itens da navegação |
| `justify-content: center` | Centralização dos links do menu |
| `list-style: none` | Remoção dos marcadores da lista do menu |
| `text-decoration: none` | Remoção do sublinhado dos links |
| `border-radius: 50px` | Logo com formato arredondado |
| `vertical-align: middle` | Alinhamento vertical da logo com o título |
| `font-size: 40px / 20px` | Hierarquia tipográfica entre títulos e parágrafos |
| Classes `.foto1`, `.foto2`, `.foto3`, `.imagemBotoRosa` | Dimensionamento individual das imagens (500×500px) |

---

## Como Visualizar

Por ser um projeto estático em HTML/CSS puro, não requer instalação.

**Opção 1 — Abrir diretamente no navegador:**

1. Clone ou baixe o repositório:
   ```bash
   git clone https://github.com/seu-usuario/Folclore-brasileiro.git
   ```
2. Abra o arquivo `index.html` no seu navegador.
3. Use a barra de navegação para explorar as lendas.

**Opção 2 — Live Server (recomendado para desenvolvimento):**

1. Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code.
2. Clique com o botão direito em `index.html` → **"Open with Live Server"**.

> **Atenção:** Mantenha a pasta `assets/` no mesmo diretório dos arquivos HTML para que as imagens e o CSS carreguem corretamente.
