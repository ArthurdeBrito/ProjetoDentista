```markdown
# 🦷 Sorriso Perfeito — Landing Page PWA

Landing page **moderna, responsiva e instalável como aplicativo (PWA)** desenvolvida para o consultório odontológico fictício **Sorriso Perfeito**.

Projeto acadêmico com foco em **UX/UI**, **performance**, **boas práticas web** e **recursos avançados do navegador**.

---

## 🚀 Demonstração

> (Adicione aqui o link do deploy — ex: Vercel, Netlify ou GitHub Pages)

---

## 📁 Estrutura do Projeto

```

projetoSorrisoPerfeito/
├── index.html
├── manifest.json
├── sw.js
├── styles/
│   └── style.css
├── scripts/
│   └── script.js
└── assets/
└── icons/

````

---

## ✨ Funcionalidades

### 🌐 Integrações com API
- ViaCEP → preenchimento automático de endereço
- OpenWeatherMap → clima em tempo real

### 🌙 Tema Dark / Light
- Alternância manual
- Persistência com `localStorage`
- Detecção automática do sistema

### 🎬 Animações
- Entrada dinâmica de elementos (direções variadas)
- Hover com efeito **shimmer**
- Ícones com efeito **pulse**
- Microinterações modernas em toda a UI

### 📊 Estatísticas Animadas
- Contadores com `easeOutExpo`
- Barra de progresso sincronizada
- Ativação via `IntersectionObserver`

### 🧠 Formulário Inteligente
- Máscara automática de telefone
- Auto preenchimento de CEP
- Validação em tempo real
- Feedback visual de envio

### 📱 Navegação
- Menu hambúrguer animado
- Smooth scroll com offset
- Botão "voltar ao topo"
- Botão WhatsApp flutuante

### 📦 PWA (Progressive Web App)
- Instalável (mobile e desktop)
- Funciona offline
- Service Worker com cache inteligente:
  - Cache First (assets)
  - Network First (APIs)
- Banner de instalação personalizado

---

## 🎨 Design System

### Paleta de cores

| Cor | Hex |
|-----|-----|
| Azul claro | `#A9D6E5` |
| Azul escuro | `#3a86a8` |
| Verde suave | `#90BE6D` |
| Branco | `#FFFFFF` |
| Cinza claro | `#F3F4F6` |
| Azul noite | `#0d1b26` |

---

## 📱 Responsividade

| Dispositivo | Layout |
|------------|--------|
| Desktop | 3 colunas |
| Tablet | 2 colunas |
| Mobile | 1 coluna |

---

## 🛠️ Tecnologias Utilizadas

- HTML5 semântico
- CSS3 (Flexbox, Grid, Animations, Variables)
- JavaScript ES6+ (Vanilla)
- Service Workers (PWA)
- Fetch API
- IntersectionObserver

---

## ⚙️ Como Executar

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/seu-repo.git
````

### 2. Acesse a pasta

```bash
cd projetoSorrisoPerfeito
```

### 3. Execute localmente

#### Opção A — VS Code

Use a extensão **Live Server**

#### Opção B — Python

```bash
python -m http.server 8000
```

#### Opção C — Node

```bash
npx serve .
```

---

## 🔑 Configuração da API (Clima)

1. Crie uma conta em [https://openweathermap.org](https://openweathermap.org)
2. Gere sua API Key
3. No arquivo `script.js`, substitua:

```js
const OPENWEATHER_KEY = 'SUA_CHAVE_AQUI';
```

> A ativação pode levar alguns minutos.

---

## 📦 PWA

Para funcionamento completo:

* Deve rodar em **HTTPS ou localhost**
* Inclui:

  * `manifest.json`
  * `service worker (sw.js)`
  * ícones personalizados

---

## 🔮 Roadmap

* [ ] Integração com backend (PHP)
* [ ] Sistema de agendamento
* [ ] Banco de dados (MySQL)
* [ ] Painel administrativo
* [ ] Autenticação de usuários

---

## ✅ Checklist

* [x] Layout responsivo
* [x] Dark/Light mode
* [x] Animações avançadas
* [x] Integração com APIs
* [x] Formulário inteligente
* [x] PWA funcional
* [x] Offline support
* [x] UX otimizada

---

## 📌 Observação

Este projeto é **fictício e acadêmico**, criado apenas para fins de estudo e demonstração.

---

## 💙 Autor

Desenvolvido por Arthur de Brito da silva

```
```
