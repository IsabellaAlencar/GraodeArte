# ☕ Grão & Arte — Torrefação e Café Especial

> Landing page desenvolvida para a **Grão & Arte**, uma marca fictícia de cafés especiais, focada em praticar arquitetura CSS, metodologia BEM, semântica HTML, responsividade e acessibilidade[cite: 1, 4].

---

## 📌 Visão Geral e Objetivo do Projeto

O objetivo deste projeto é simular o desenvolvimento front-end em um ambiente profissional, entregando uma solução completa, responsiva e acessível para o cliente fictício **Grão & Arte**[cite: 1, 4]. 

A aplicação apresenta uma *landing page* para apreciadores de cafés especiais, destacando:
- Apresentação da marca (Banner Hero);
- Catálogo de microlotes exclusivos em cards;
- Explicação do processo artesanal de torra;
- Planos comparativos do Clube de Assinatura Mensal[cite: 4];
- Seção de Perguntas Frequentes (FAQ) interativa[cite: 4];
- Botão flutuante para contato direto via WhatsApp;
- Menu e rodapé fixos com navegação suave[cite: 4, 5].

---

## 🚀 Tecnologias e Conceitos Aplicados

- **HTML5 Semântico:** Uso correto de tags como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<details>`, `<summary>` e `<footer>` para garantir acessibilidade e SEO[cite: 1, 4, 5].
- **CSS3 Puro:** Sem o uso de frameworks externos, priorizando a separação rigorosa de responsabilidades.
- **Metodologia BEM (Block Element Modifier):** Nomenclatura organizada de classes no HTML e seletores no CSS para garantir reutilização e facilidade de manutenção do código[cite: 1].
- **Design System com CSS Variables (`:root`):** Padronização de paleta de cores, tipografia, sombras e tempos de transição[cite: 3, 6].
- **Flexbox Layout:** Utilização de Flexbox para estruturação dos layouts e componentes[cite: 3, 4].
- **Escala Tipográfica com Unidade `rem`:** Configuração da escala da fonte base na raiz (`html`) e uso estrito de `rem` para textos, espaçamentos e bordas.
- **Unidades Relativas (`%`, `vh`, `vw`):** Controle fluido de larguras e alturas em seções de tela cheia, restringindo o uso de pixels apenas para detalhes específicos/bordas[cite: 2].
- **Responsividade (Media Queries):** Layout adaptável para smartphones, tablets e desktops com base em breakpoints pesquisados na documentação[cite: 2, 3].
- **Google Fonts:** Importação das famílias tipográficas **Merriweather** e **Open Sans**[cite: 2, 7].
- **WhatsApp API:** Botão flutuante interativo configurado com o número oficial do SENAI Henrique Lupo.

---

## 📁 Organização da Arquitetura de Arquivos

A estrutura do repositório foi organizadamente separada respeitando a regra de separação de responsabilidades (estilos inline ou blocos `<style>` no HTML não foram utilizados)[cite: 1]:

```text
grao-e-arte/
├── assets/
│   ├── css/
│   │   ├── variables.css      # Variáveis do Design System (:root)
│   │   ├── reset.css          # Reset CSS e escala REM base
│   │   ├── layout.css         # Estilos globais, header, footer e seções
│   │   ├── components.css     # Cards, botões, FAQ e microinterações
│   │   └── responsive.css     # Breakpoints e regras de responsividade
│   └── images/                # Imagens e ativos visuais do projeto
├── index.html                 # Estrutura HTML5 semântica da aplicação
└── README.md                  # Documentação do projeto