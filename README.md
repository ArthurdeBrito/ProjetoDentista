```markdown
# 🦷 Sorriso Perfeito — Landing Page PWA

Landing page **responsiva**, **interativa** e **instalável como aplicativo (PWA)** desenvolvida para um consultório odontológico fictício.

O projeto foi criado com foco em **experiência do usuário (UX)**, **interface moderna (UI)** e uso de **recursos avançados do navegador**, utilizando apenas tecnologias web nativas.

---

## 🚀 Visão Geral

A aplicação simula o site institucional de um consultório, com funcionalidades dinâmicas como:

- Preenchimento automático de endereço
- Clima em tempo real
- Tema escuro/claro
- Animações modernas
- Instalação como app (PWA)
- Funcionalidade offline

---

## 📁 Estrutura do Projeto

```

projetoSorrisoPerfeito/
├── index.html              # Estrutura principal
├── manifest.json           # Configuração do PWA
├── sw.js                   # Service Worker (cache e offline)
├── styles/
│   └── style.css           # Estilos da aplicação
├── scripts/
│   └── script.js           # Funcionalidades em JavaScript
└── assets/
└── icons/              # Ícones do aplicativo

````

---

## ✨ Funcionalidades

### 🔌 Integração com APIs
- **ViaCEP**
  - Preenchimento automático de endereço ao digitar o CEP
- **OpenWeatherMap**
  - Exibição do clima atual com ícone dinâmico

---

### 🌙 Tema Dark / Light
- Alternância manual via botão
- Persistência com `localStorage`
- Detecção automática da preferência do sistema

---

### 🎬 Animações e Interações
- Entrada de elementos com animações direcionais
- Efeito **shimmer** em cards
- Ícones com animação **pulse**
- Linha animada ao passar o mouse nos serviços
- Microinterações suaves em toda a interface

---

### 📊 Estatísticas Animadas
- Contadores com animação de `0 → valor final`
- Efeito de easing (`easeOutExpo`)
- Barra de progresso sincronizada
- Ativação ao entrar na viewport (`IntersectionObserver`)

---

### 🧠 Formulário Inteligente
- Máscara automática para telefone
- Busca de CEP com feedback:
  - carregando
  - sucesso
  - erro
- Validação em tempo real
- Feedback visual de envio

---

### 🧭 Navegação
- Menu hambúrguer animado (mobile)
- Scroll suave com compensação do header fixo
- Botão "voltar ao topo" com indicador de progresso
- Botão flutuante do WhatsApp com animação

---

### 📱 Progressive Web App (PWA)
- Instalável em dispositivos móveis e desktop
- Funciona offline com fallback personalizado
- Estratégias de cache:
  - **Cache First** para arquivos estáticos
  - **Network First** para APIs
- Banner de instalação customizado
- Atalhos rápidos (shortcuts)
- Tema adaptável ao modo claro/escuro

---

## 🎨 Design

### Paleta de Cores

| Cor          | Código Hex |
|--------------|------------|
| Azul claro   | `#A9D6E5`  |
| Azul escuro  | `#3a86a8`  |
| Verde suave  | `#90BE6D`  |
| Branco       | `#FFFFFF`  |
| Cinza claro  | `#F3F4F6`  |
| Azul noite   | `#0d1b26`  |

---

## 📱 Responsividade

| Breakpoint | Layout |
|------------|--------|
| ≥ 1025px   | Desktop (3 colunas) |
| 769–1024px | Tablet (2 colunas) |
| ≤ 768px    | Mobile (1 coluna) |
| ≤ 480px    | Small devices |

---

## ⚙️ Como Executar

### ▶️ Opção 1 — VS Code (Recomendado)
Utilize a extensão **Live Server** e clique em **"Go Live"**

---

### 🐍 Opção 2 — Python
```bash
python -m http.server 8000
````

Acesse: `http://localhost:8000`

---

### 🟢 Opção 3 — Node.js

```bash
npx serve .
```

---

## 🔑 Configuração da API de Clima

1. Crie uma conta em: [https://openweathermap.org](https://openweathermap.org)
2. Gere sua API Key
3. No arquivo `scripts/script.js`, substitua:

```js
const OPENWEATHER_KEY = 'SUA_CHAVE_AQUI';
```

> A ativação da chave pode levar algum tempo.

---

## 📦 PWA

Para funcionamento completo:

* Necessário **HTTPS ou localhost**
* Inclui:

  * `manifest.json`
  * `service worker`
  * ícones personalizados

---

## 🔮 Próximas Melhorias

* Integração com backend (PHP)
* Envio real de formulário (e-mail)
* Sistema de agendamento
* Banco de dados (MySQL)
* Painel administrativo

---

## 🛠️ Tecnologias Utilizadas

* HTML5 semântico
* CSS3 (Flexbox, Grid, Variáveis, Animações)
* JavaScript ES6+ (Vanilla)
* Fetch API
* IntersectionObserver
* Service Worker (PWA)

---

## ✅ Checklist

* [x] Estrutura HTML semântica
* [x] Estilização moderna com CSS
* [x] Tema Dark/Light
* [x] Animações e microinterações
* [x] Integração com APIs
* [x] Formulário inteligente
* [x] Responsividade completa
* [x] PWA funcional
* [x] Suporte offline

---

## 📌 Observação

Este projeto é **fictício** e foi desenvolvido para fins **educacionais**, com o objetivo de praticar conceitos modernos de desenvolvimento web.

---

## 💙 Sorriso Perfeito

Transformando sorrisos com tecnologia e inovação.

```
```
