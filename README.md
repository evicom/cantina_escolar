# 🍽️ Cantina Escolar — PWA

Sistema web progressivo (PWA) para gerenciamento de cardápio e confirmação de presença na cantina escolar. Funciona **offline** e pode ser **instalado como app** em qualquer dispositivo.

## 🚀 Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `cantina-escolar`)
2. Faça upload de **todos os arquivos e pastas**:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` (pasta com todos os ícones)
3. Vá em **Settings → Pages → Source**, selecione `main` e clique em **Save**
4. Aguarde ~1 min. O site estará em:
   `https://SEU-USUARIO.github.io/cantina-escolar/`

> ⚠️ Para o PWA funcionar corretamente, o site **precisa ser servido via HTTPS** — o GitHub Pages já faz isso automaticamente.

## 📲 Instalar como App

| Plataforma | Como instalar |
|---|---|
| Android (Chrome) | Banner aparece automaticamente → toque em **Instalar** |
| iPhone/iPad (Safari) | Toque em **Compartilhar** → **Adicionar à Tela de Início** |
| Desktop (Chrome/Edge) | Ícone ➕ na barra de endereços → **Instalar** |

## 👤 Acessos padrão

| Perfil | Usuário | Senha |
|---|---|---|
| Gerente | `abc` | `abc` |
| Aluno | (matrícula) | `abc` |

## 📋 Funcionalidades

- Cardápio semanal com filtros
- Confirmação de presença por aluno
- Painel administrativo com CRUD de alunos
- Funciona **offline** (Service Worker)
- Instalável em **Android, iOS e Desktop**

## 🛠️ Tecnologias

- HTML5 + CSS3 + JavaScript puro
- **PWA**: Web App Manifest + Service Worker
- Dados no `localStorage` do navegador
