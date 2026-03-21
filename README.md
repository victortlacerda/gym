# ⚡ GainTrack

**PWA de academia offline-first** — zero custo, instalável no celular.

## Stack

* HTML + CSS + Vanilla JS
* **Dexie.js** (IndexedDB — todos os dados ficam no aparelho)
* **Chart.js** (gráficos de evolução)
* Service Worker (funciona offline)
* PWA (instalável como app)

## Funcionalidades

|Módulo|Descrição|
|-|-|
|🏠 Início|Streak, stats semanais, histórico recente|
|💪 Treino|Treino ativo com timer de descanso e referência do último treino|
|📈 Evolução|Gráficos de carga/volume + records pessoais|
|📅 Semana|Calendário da semana + heatmap 28 dias|
|🧍 Corpo|Mapa muscular SVG com heatmap de intensidade|

## Deploy no GitHub Pages

```bash
# 1. Crie um repositório no GitHub
git init
git add .
git commit -m "GainTrack v1.0"
git remote add origin https://github.com/SEU\_USER/gaintrack.git
git push -u origin main

# 2. No GitHub → Settings → Pages
# Source: "Deploy from a branch" → branch: main → folder: / (root)
# Pronto! Seu app estará em: https://SEU\_USER.github.io/gaintrack
```

## Instalar no celular

1. Abra o link no **Chrome** (Android) ou **Safari** (iOS)
2. Menu → "Adicionar à tela inicial"
3. Use como app nativo — funciona offline!

## Dados

Todos os dados ficam no **IndexedDB** do navegador (no aparelho).  
Nenhum servidor, nenhum custo, nenhum cadastro.

## Exportar / Importar (em breve)

* Export JSON para backup
* Import para restaurar ou compartilhar planos

