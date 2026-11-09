# Larize Web & Tech — Landing Page Institucional

> **"Tecnologia que impulsiona seu crescimento."**  
> Projeto desenvolvido por **Lara**, estudante de Análise e Desenvolvimento de Sistemas (ADS), para a disciplina **Web Standards** do Senac.

---

## 💜 Sobre o Projeto

A **Larize Web & Tech** é uma marca de soluções digitais criada para apoiar pequenos empreendedores, autônomos e prestadores de serviços no fortalecimento de sua presença na internet. O nome faz alusão ao verbo inglês *"rise"*, que simboliza ascensão, evolução e crescimento sustentável.

Este projeto é uma landing page de página única com qualidade visual profissional, desenvolvida estritamente com **HTML5 e CSS3 puros**, aplicando **Flexbox**, **Clean Code** e as diretrizes do **W3C Web Standards**.

---

## 🎨 Identidade Visual (Hybrid Purple)

O design foi estruturado segundo o conceito **Hybrid Purple**, equilibrando seções em fundo escuro sofisticado e seções em fundo claro contrastante:

- **Roxo Principal:** `#6B3DF6`
- **Violeta:** `#7A2FFF`
- **Lilás:** `#B794F6`
- **Lavanda:** `#EDE9FE`
- **Fundo Escuro:** `#0F0A1A`
- **Branco:** `#FFFFFF`
- **Tipografia:** Montserrat (Títulos e Destaques) & Inter (Corpo de Texto e Componentes)

---

## 📑 Estrutura das Seções

1. **Header & Navegação:** Barra fixa com efeito *glassmorphism*, logotipo oficial, menu de navegação responsivo em CSS puro (sem bibliotecas externas) e botão de ação rápida.
2. **Hero (Apresentação Principal):** Chamada de impacto conectando o slogan e o propósito da marca, duplo CTA, destaques de valor e card visual simulando a arquitetura de código limpo.
3. **Sobre a Marca & A Desenvolvedora:** Explicação do conceito do nome (*rise*), apresentação da **Lara** como estudante de ADS no Senac, e os três pilares essenciais de atendimento: transparência, contato direto e rigor técnico.
4. **Serviços Oferecidos:** 3 cards detalhados com tags, descrição e checklist do que está incluso:
   - *Desenvolvimento de Sites e Landing Pages*
   - *Automação de Atendimento via WhatsApp*
   - *Suporte e Manutenção de Sites*
5. **Vantagens & Benefícios:** Diferenciais práticos para autônomos (comunicação direta, foco em smartphones, código leve, custo acessível, autonomia e conformidade com o W3C).
6. **Metodologia de Trabalho (Como Funciona):** 4 etapas claras e organizadas (Diagnóstico, Planejamento, Desenvolvimento e Publicação/Suporte).
7. **Contato & Formulário:** Integração pronta com o serviço **Web3Forms**, e-mail oficial (`larizewebetech@gmail.com`), links de WhatsApp (número ainda a definir, ver *Pendências*) e identificação acadêmica da disciplina.
8. **Rodapé & Botão Flutuante:** Navegação secundária, direitos autorais e botão flutuante de atendimento ágil via WhatsApp.

---

## 🛠️ Requisitos Técnicos Atendidos (Web Standards)

- **HTML5 Semântico:** Utilização correta de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<form>`, `<label>` e atributos ARIA.
- **CSS3 Puro & Modular:** Variáveis CSS (`:root`), design tokens, semântica BEM simplificada, sem dependências de frameworks (sem Tailwind, Bootstrap ou React).
- **Layout com Flexbox:** Distribuição fluida de cards, colunas e cabeçalhos.
- **Totalmente Responsivo:** Breakpoints estratégicos para celulares (`480px`), tablets (`768px`) e desktops (`992px+`).
- **Acessibilidade (A11y):** Skip link inicial, contraste balanceado, etiquetas acessíveis em todos os campos de formulário e suporte a `@media (prefers-reduced-motion: reduce)`.
- **Ícones SVG em sprite:** cada ícone é definido uma única vez (`<symbol>`, no final do `index.html`) e reutilizado com `<use>`, o que evita repetição de código e mantém a cor controlada pelo CSS (`currentColor`).
- **Separação HTML/CSS:** sem atributos `style` inline; toda a apresentação fica em `css/style.css`.
- **Performance & SEO:** Pré-conexão de fontes, meta tags Open Graph, favicons em PNG/ICO (16x16, 32x32 e Apple Touch Icon) e dimensões explícitas nas imagens para evitar CLS (*Cumulative Layout Shift*).

---

## 📬 Configuração do Formulário de Contato (Web3Forms)

O formulário está conectado ao endpoint oficial do **Web3Forms** (`https://api.web3forms.com/submit`) via método `POST`, com validação HTML nativa e proteção contra bots.

A chave de acesso oficial está configurada no formulário:
```html
<input type="hidden" name="access_key" value="62cbe40f-4ae9-4653-b89b-1d0e1370d6f0">
```

As mensagens enviadas pelo formulário são direcionadas diretamente para o e-mail cadastrado: **`larizewebetech@gmail.com`**, utilizando a tela padrão e segura de confirmação do Web3Forms.

---

## ⏳ Pendências (projeto acadêmico)

- **WhatsApp:** os dois links (seção de contato e botão flutuante) usam `https://wa.me/?text=...`, ainda sem número, pois o projeto é acadêmico. Quando houver um número, o formato é `https://wa.me/55DDDNUMERO?text=...` (código do país + DDD + número, só dígitos).
- **Endereço do site (`og:url`):** após a publicação, trocar o valor atual (`./`) pela URL final, para a prévia de compartilhamento funcionar corretamente.

---

## 🎓 Informações Acadêmicas (Senac — Web Standards)

- **Instituição:** Centro Universitário Senac
- **Curso:** Tecnologia em Análise e Desenvolvimento de Sistemas (ADS)
- **Disciplina:** Web Standards
- **Desenvolvedora:** Lara
- **Critérios Atendidos:** Estrutura de página única semântica (HTML5 puro), estilização CSS3 com design tokens e Flexbox, Clean Code, acessibilidade (W3C), total ausência de frameworks/dependências externas e preparação para deploy estático no Netlify.

---

## 🚀 Como Publicar Gratuitamente no Netlify

O site é 100% estático (HTML e CSS puros) e não requer qualquer arquivo de configuração ou processo de compilação (*build*).

### Opção 1: Via Arrastar e Soltar (Drag & Drop — Mais Rápido)
1. Acesse sua conta no [Netlify](https://app.netlify.com).
2. Vá até a aba **Sites** e arraste toda a pasta do projeto (`larize-site`) diretamente para a área de upload do Netlify Drop.
3. Seu site estará online em poucos segundos com certificado SSL/HTTPS gratuito!

### Opção 2: Via GitHub / GitLab
1. Crie um repositório no seu GitHub e envie os arquivos desta pasta.
2. No Netlify, selecione **"Add new site" > "Import an existing project"**.
3. Escolha seu repositório. O diretório de publicação é a raiz (`.`).
4. Clique em **Deploy**.

---

## 📁 Estrutura de Arquivos

```text
larize-site/
├── index.html              # Landing page principal (HTML5 semântico e acessível)
├── README.md               # Documentação completa e guia acadêmico
├── favicon.ico             # Ícone do site para navegadores
├── css/
│   └── style.css           # Folha de estilos limpa com variáveis e Flexbox
└── assets/
    └── images/             # Identidade visual e favicons
        ├── favicon-32x32.png
        ├── favicon-16x16.png
        ├── apple-touch-icon.png
        ├── og-share.jpg    # Banner oficial de compartilhamento (Open Graph / Twitter)
        └── logo.png        # Logotipo oficial em alta definição
```

