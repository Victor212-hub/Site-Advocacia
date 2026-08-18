# Advocacia Anderson Luciano — Site Institucional

<div align="center">

![Status](https://img.shields.io/badge/Status-Ativo-brightgreen?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-Semântico-e34c26?style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-Puro-1572B6?style=flat-square)
![Responsivo](https://img.shields.io/badge/Responsivo-Mobile%20Ready-blue?style=flat-square)
![Acessibilidade](https://img.shields.io/badge/Acessibilidade-ARIA%20Labels-green?style=flat-square)

**Site institucional moderno e responsivo do Escritório de Advocacia Dr. Anderson Luciano**

Apresentando serviços jurídicos, facilitando contato direto e guiando clientes ao escritório.

[Visualizar Site](#como-acessar) • [Características](#características-principais) • [Tecnologias](#tecnologias-utilizadas)

</div>

---

## Sobre o Escritório

O **Escritório de Advocacia Dr. Anderson Luciano** oferece consultoria jurídica de alta qualidade em **Salvador, Bahia**. 

Com foco em **ética**, **transparência** e **excelência**, o escritório atua em diversas áreas do direito, com especialização em **Direito Previdenciário**.

**Localização:**  
R. Augusto de Mendonça, nº 3 (Vila Militar - Dendezeiros) | Bonfim | Salvador – BA | CEP: 40415-030

**Contato:**  
WhatsApp: [+55 71 98317-1235](https://wa.me/557183171235)

---

## Características Principais

**Design Moderno e Profissional**
- Paleta de cores sofisticada (azul marinho, branco e dourado)
- Tipografia elegante com **Playfair Display** (títulos) e **Lato** (corpo)
- Interface limpa e intuitiva

**Totalmente Responsivo**
- Desktop (layout completo)
- Tablet (adaptação fluida)
- Mobile (menu hamburguer CSS-only)
- Menu hamburguer funcional sem JavaScript

**Integração com WhatsApp**
- Links diretos para contato via WhatsApp com mensagens pré-configuradas
- CTA (Call-to-Action) estratégicos em múltiplas seções

**Navegação Intuitiva**
- Navegação fixa no topo (sticky header)
- Links âncora para todas as seções principais
- Smooth scrolling automático

**Acessibilidade**
- Semântica HTML5 completa
- Labels ARIA para ícones e elementos funcionais
- Contraste adequado entre cores
- Estrutura lógica de headings

**Performance**
- HTML e CSS puro (sem frameworks pesados)
- Sem dependências externas desnecessárias
- Otimizado para carregamento rápido
- Integração de mapas via iframe

---

## Estrutura do Projeto

```
Site-Advocacia/
├── index.html              # Página principal (estrutura HTML5)
├── style.css               # Folha de estilos completa (CSS3 puro)
├── img/                    # Pasta com imagens e logos
│   ├── logo_advocacia_adobe.png
│   ├── logo_advocia.png
│   └── foto_frente_advocacia.jpeg
└── README.md               # Esta documentação
```

---

## Seções do Site

| Seção | Funcionalidade |
|-------|---|
| **Header / Navegação** | Navegação fixa com logo, menu responsivo e botão de contato WhatsApp |
| **Hero** | Apresentação principal com CTA e chamada para contato |
| **Áreas de Atuação** | 6 cards com especialidades jurídicas (Civil, Bancário, Trabalhista, Empresarial, Família, Previdenciário) |
| **Serviços Previdenciários** | Detalhe com lista de ações e acompanhamentos especializados |
| **Documentos** | Orientação sobre quais documentos podem ser analisados |
| **Quem Somos** | Missão, valores e pilares do escritório |
| **Localização** | Endereço completo + mapa interativo do Google Maps |
| **Contato / Rodapé** | Informações de contato, navegação secundária e copyright |

---

## Tecnologias Utilizadas

**Frontend**
- **HTML5** — Marcação semântica com `<header>`, `<nav>`, `<section>`, `<article>`, `<address>`, `<footer>`
- **CSS3 Puro** — Sem dependências, sem frameworks
  - Flexbox para layouts fluidos
  - Grid CSS para seções responsivas
  - Media queries para adaptabilidade
  - Transições e transformações
  - CSS variables (quando aplicável)

**Serviços Externos**
- **Google Fonts** — [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (titulação elegante) e [Lato](https://fonts.google.com/specimen/Lato) (corpo)
- **Google Maps Embed** — Mapa interativo incorporado via iframe
- **WhatsApp API** — Links de contato via protocolo `wa.me`

**Não Utiliza**
- JavaScript (layout 100% CSS)
- Frameworks CSS (Bootstrap, Tailwind, etc.)
- Dependências NPM
- Build process

---

## Responsividade & Breakpoints

O site utiliza três breakpoints principais:

```css
/* Desktop (padrão) */
/* Navegação horizontal, layout multi-coluna */

/* Tablet (máx. 900px) */
@media (max-width: 900px) {
  - Localização em coluna única
  - Ajustes de espaçamento
}

/* Mobile (máx. 680px) */
@media (max-width: 680px) {
  - Menu hamburguer (CSS-only)
  - Cards em coluna única
  - Tipografia ajustada
  - Elementos em stack vertical
}
```

**Menu Hamburguer (CSS-Only)**

O menu hamburguer funciona através de um checkbox HTML + labels CSS sem qualquer JavaScript:

```html
<input type="checkbox" id="menu-toggle" class="menu-toggle" />
<label for="menu-toggle" class="menu-label">☰</label>
<nav class="navegacao"><!-- menu --></nav>
```

---
Estratégia de Design

**Identidade Visual**
- **Cor Primária:** #112138 (azul marinho escuro)
- **Cor Secundária:** #49a311 (verde vibrante)
- **Cor de Destaque:** #d4a94a (dourado)
- **Fundo:** #100f0f (preto muito escuro) e #F7F7FF (branco puro)

**Tipografia**
- **Títulos:** Playfair Display (elegância, serifa)
- **Corpo:** Lato 400/700 (legibilidade, sem serifa)
- **Tamanhos fluidos:** `clamp()` para tipografia responsiva

**Hierarquia Visual**
### Hierarquia Visual
- Cards com overflow e backdrops para profundidade
- Sombras sutis para elevação
- Espaçamento generoso para respiro visual
- Transições suaves em interações

---
Como Acessar

**Local (Desenvolvimento)**
### Local (Desenvolvimento)
1. Clone ou baixe este repositório
2. Abra `index.html` diretamente no navegador
3. Navegue entre as seções usando o menu ou scroll

```bash
# Exemplo com VS Code
cd Site-Advocacia
code .
# Depois abra index.html com Live Server ou similar
```
**Online**

### Online
O site está pronto para ser deployado em qualquer serviço de hospedagem estática:
- **GitHub Pages**
- **Netlify**
- **Vercel**
- **Servidor tradicional** (Apache, Nginx, etc.)

---Checklist de Funcionalidades

- Navegação responsiva com menu hamburguer CSS-only
- Header sticky com logo e CTA
- Hero section com chamada para contato
- Grid de cards com áreas de atuação
- Seção de serviços especializados
- Formulário de orientação de documentos
- Seção "Quem Somos" com missão e valores
- Integração de mapa Google Maps
- Rodapé com links e informações
- Acessibilidade (ARIA labels, semântica)
- Meta tags para SEO e redes sociais (Open Graph)
- Favicon personalizado
- Otimização mobile-first
- Favicon personalizado
- ✅ Otimização mobile-first
- ✅ Performance (sem dependências pesadas)

---

## 🔍 SEO & Meta Tags

O site inclui meta tags essenciais para SEO e redes sociais:

```html
<meta name="description" content="..." />
<meta property="og:title" content="..." />
<meta property="og:description" content="..." />
<meta property="og:image" content="..." />
<meta property="og:type" content="website" />
<meta property="og:locale" content="pt_BR" />
```

Isso garante exibição otimizada ao compartilhar em:
- 🔗 Google Search
- 💬 WhatsApp
- 📘 Facebook
- 🐦 Twitter/X
- 📱 LinkedIn

---

## 📄 Estrutura HTML

O HTML segue uma estrutura semântica clara:

```
<html lang="pt-BR">
  <head>
    <!-- Meta tags, fonts, stylesheets -->
  </head>
  <body>
    <header> (Cabeçalho e navegação)
    <main>
      <section id="inicio"> (Hero)
      <section id="atuacao"> (Áreas)
      <section> (Previdenciário)
      <section id="documentos"> (Documentos)
      <section id="quem-somos"> (Quem Somos)
      <section id="localizacao"> (Localização)
    </main>
    <footer> (Rodapé)
  </body>
</html>
```

---

## 🎨 Arquivo CSS

O `style.css` está organizado em seções bem comentadas:

```css
/* Reset básico */
/* Base geral (body, fonts) */
/* Cabeçalho / Navegação */
/* Hero */
/* Áreas de atuação (cards) */
/* Seção previdenciária */
/* Localização */
/* Rodapé */
/* Quem somos */
/* Documentos */
/* Responsividade */
```

Tamanho: ~1,200 linhas bem organizadas com comentários descritivos.

---Pontos de Destaque

**1. tos de Destaque

### 1. **Menu Hamburguer 100% CSS**
**2. Tipografia Fluida**

Uso de `clamp()` para tamanhos que se adaptam fluidamente entre breakpoints

**3. Grid Responsivo**

`grid-template-columns: repeat(auto-fill, minmax())` para cards que se adaptam automaticamente

**4. Integração WhatsApp**

Links diretos `wa.me/` com mensagens pré-configuradas em cada CTA

**5. Design Acessível**
mensagens pré-configuradas em cada CTA
Customização

**Mudar Cores**

Edit as cores principais em `style.css`:
```css
--cor-primaria: #112138;
--cor-secundaria: #49a311;
--cor-destaque: #d4a94a;
```

**Ajustar Contato WhatsApp**

Troque o número e mensagem nos links `wa.me`:
```html
<a href="https://wa.me/557183171235?text=...">
```

**Adicionar Seções**

Crie uma nova `<section>` e adicione estilos ao CSS mantendo a estrutura existente

**Trocar Fonts**
/wa.me/557183171235?text=...">
```Contato & Suporte

**Escritório:**
- R. Augusto de Mendonça, nº 3, Bonfim, Salvador – BA
- WhatsApp: [+55 71 98317-1235](https://wa.me/557183171235)
-Trocar Fonts
Altere os imports em `<head>` e atualize `font-family` no CSS

---

## 📞 Contato & Suporte

**Eitório:**
- 📍 R. Augusto de Mendonça, nº 3, Bonfim, Salvador – BA
- 📱 WhatsApp: [+55 71 98317-1235](https://wa.me/557183171235)
- 🕐 Horário: Seg-Sex, 9h-17h

**Sobre o Site:**
ParAutor & Desenvolvimento

**Site desenvolvido com foco em:**
- Performance (sem dependências)
- Acessibilidade (WCAG guidelines)
- Responsividade (mobile-first)
- SEO (meta tags, semântica)
-
---

## ✍️ Autor & Desenvolvimento

**Site desenvolvido com foco em:**
- 🎯 Performance (sem dependências)
- ♿ Acessibilidade (WCAG guidelines)
- 📱 Responsi(mobile-first)
- 🔍 SEO (meta tags, semântica)
- 🎨 Design moderno e profissional

---

<div align="center">

**[⬆ Voltar ao topo](#advocacia-anderson-luciano--site-institucional)**

Desenvolvido com ❤️ para excelência jurídica.

</div>

O menu hamburguer no mobile funciona **sem JavaScript**, usando apenas CSS com o truque de `checkbox` + `label`.

---


## Advogados do escritório

- Dr. Anderson Luciano
- Dr. Ercio Costa
- Dra. Ana Maria Costa

---

## Endereço

R. Augusto de Mendonça, nº 3 — Em frente à Vila Militar  
Dendezeiros, Bonfim — Salvador, BA  
CEP: 40415-030

---

*Desenvolvido com HTML5 e CSS3 puro.*
