# 📋 Plano do projeto: Caca-Bug-1-4

_Gerado em 16/11/2026, 15:01:35 — sem IA, lendo os arquivos._

## 📊 Visão geral
| Item | Valor |
|---|---|
| Arquivos | 82 |
| Linhas | 6.181 |
| Telas/páginas | 2 |
| Rotas do backend | 0 |
| Chamadas do app | 3 |
| Tabelas do banco | 0 |
| Variáveis de ambiente | 3 |

**Linguagens:** JavaScript (49), Imagem (17), Outros (3), CSS (2), HTML (2), JSON (2), Python (2), Imagem SVG (2), Markdown (2), Ícone (1)

## 💡 O que fazer (em ordem)
1. 🧹 Tirar a Replit de 16 arquivo(s) (🏗️ Preparar → Fazer tudo)
2. 🔐 Criar um .env.example com: BASE_PATH, GITHUB_STEP_SUMMARY, PORT (os valores você coloca no servidor, nunca no código)
3. 📝 Criar um README.md explicando como rodar
4. 🚫 Criar .gitignore (não mandar node_modules ao GitHub)

## 🚀 Por onde começa
- `ferramentas/meu-chat/index.html`
- `index.html`

## 📱 Telas e páginas
| Endereço | Arquivo |
|---|---|
| `ferramentas/meu-chat/index.html` | ferramentas/meu-chat/index.html |
| `index.html` | index.html |

## 🖥️ Rotas do backend
_Nenhum encontrado._

## 📡 O que o app pede ao servidor
| Método | Endereço | Onde |
|---|---|---|
| POST | `/models/${encodeURIComponent(c.modelo)}:generateContent` | ferramentas/cirurgiao.js |
| POST | `/messages` | ferramentas/cirurgiao.js |
| POST | `/chat/completions` | ferramentas/cirurgiao.js |

## 🔌 O que falta no backend
✅ Tudo que o app chama tem rota no projeto (ou o app não usa servidor).

## 🗄️ Banco de dados
_Nenhuma tabela encontrada._

## 🔐 Variáveis de ambiente (configurar no servidor)
- `BASE_PATH`
- `GITHUB_STEP_SUMMARY`
- `PORT`

_Só os nomes. Os valores (chaves, senhas) nunca vão no código nem no GitHub._

## 🤖 IA usada
- api.openai.com
- api.groq.com
- openrouter.ai
- generativelanguage.googleapis.com
- api.anthropic.com
- console.groq.com
- platform.openai.com
- console.anthropic.com

## 🌐 Serviços de fora que ele acessa
- aistudio.google.com
- api-dashboard.search.brave.com
- api.anthropic.com
- api.deepseek.com
- api.groq.com
- api.mistral.ai
- api.openai.com
- api.perplexity.ai
- api.search.brave.com
- api.tavily.com
- api.x.ai
- app.tavily.com
- cdn.jsdelivr.net
- cdn.tailwindcss.com
- cdnjs.cloudflare.com
- console.anthropic.com
- console.groq.com
- esm.sh
- expo.dev
- fonts.googleapis.com
- fonts.gstatic.com
- generativelanguage.googleapis.com
- github.com
- google.serper.dev
- meuchat.local
- ollama.com
- openapi.monica.im
- openrouter.ai
- platform.deepseek.com
- platform.openai.com
- pypi.org
- r.jina.ai
- raw.github.com
- registry.npmjs.org
- serper.dev
- stuartk.com
- stuk.github.io
- u.expo.dev
- unpkg.com
- www.npmjs.com
- www.perplexity.ai

## 🧹 Arquivos com coisa da Replit
- ferramentas/analisador-universal.js
- ferramentas/cirurgiao.js
- ferramentas/meu-chat/js/33-contextos.js
- ferramentas/meu-chat/js/lib/guia-maikon.js
- ferramentas/meu-chat/js/lib/guia-versoes.js
- ferramentas/montar.py
- ferramentas/projeto-lab.js
- ferramentas/raiox.js
- js/30-projeto.js
- js/46-limpo.js
- js/60-comparar.js
- js/80-terminal.js
- js/99-app.js
- js/lib/expo-core.js
- js/lib/plano-core.js
- service-worker.js

## 🔁 Roteiro para recriar fora da Replit
1. Importar o projeto no Mini SK e tocar em 🏗️ Preparar → ✅ Fazer tudo (tira a Replit, cria os arquivos que faltam).
2. Não tem backend: o site sozinho basta (Netlify ou GitHub Pages).
3. Variáveis: cadastrar 3 variável(is) no servidor (lista acima).
4. Testar a prévia; se der erro, 🤖 Mandar os erros para a IA.
5. App: 📲 Instalável (PWA), 📦 APK ou 🖥️ Desktop (.exe) pelo 🏗️ Preparar.

## 🌳 Árvore de arquivos
```
├─ 📁 css/
│  └─ app.css
├─ 📁 ferramentas/
│  ├─ 📁 meu-chat/
│  │  ├─ 📁 css/
│  │  │  └─ app.css
│  │  ├─ 📁 icons/
│  │  │  ├─ icon-192.png
│  │  │  └─ icon-512.png
│  │  ├─ 📁 js/
│  │  │  ├─ 📁 lib/
│  │  │  │  ├─ cofre-arquivo.js
│  │  │  │  ├─ guia-maikon.js
│  │  │  │  ├─ guia-versoes.js
│  │  │  │  └─ jszip.min.js
│  │  │  ├─ 00-base.js
│  │  │  ├─ 10-banco.js
│  │  │  ├─ 20-provedores.js
│  │  │  ├─ 30-memoria.js
│  │  │  ├─ 33-contextos.js
│  │  │  ├─ 34-guia.js
│  │  │  ├─ 35-jeito.js
│  │  │  ├─ 40-voz.js
│  │  │  ├─ 50-internet.js
│  │  │  ├─ 60-previa.js
│  │  │  ├─ 70-texto.js
│  │  │  ├─ 80-chat.js
│  │  │  ├─ 85-config.js
│  │  │  ├─ 87-cofre.js
│  │  │  ├─ 90-backup.js
│  │  │  ├─ 95-ponte-lab.js
│  │  │  └─ 99-app.js
│  │  ├─ index.html
│  │  ├─ LEIA-ME.txt
│  │  ├─ manifest.json
│  │  ├─ sw.js
│  │  └─ voz-francisco.py
│  ├─ ai-code-studio.js
│  ├─ analisador-universal.js
│  ├─ cirurgiao.js
│  ├─ desembrulhar.js
│  ├─ gerador-eas.js
│  ├─ montar.py
│  ├─ ordem.txt
│  ├─ projeto-lab.js
│  ├─ raiox.js
│  └─ triagem.js
├─ 📁 icons/
│  ├─ apple-touch-icon.png
│  ├─ icon-128.png
│  ├─ icon-144.png
│  ├─ icon-152.png
│  ├─ icon-16.png
│  ├─ icon-180.png
│  ├─ icon-192.png
│  ├─ icon-32.png
│  ├─ icon-384.png
│  ├─ icon-48.png
│  ├─ icon-512.png
│  ├─ icon-72.png
│  ├─ icon-96.png
│  ├─ icon.svg
│  ├─ maskable-192.png
│  ├─ maskable-512.png
│  └─ maskable.svg
├─ 📁 js/
│  ├─ 📁 lib/
│  │  ├─ expo-core.js
│  │  ├─ organizar-core.js
│  │  └─ plano-core.js
│  ├─ 00-core.js
│  ├─ 20-zip.js
│  ├─ 30-projeto.js
│  ├─ 40-ferramentas.js
│  ├─ 45-organizar.js
│  ├─ 46-limpo.js
│  ├─ 50-relatorios.js
│  ├─ 60-comparar.js
│  ├─ 70-ia.js
│  ├─ 80-terminal.js
│  └─ 99-app.js
├─ 📁 lib/
│  ├─ acorn.min.js
│  ├─ diff-LICENSE.txt
│  ├─ diff.min.js
│  ├─ jszip-LICENSE.md
│  └─ jszip.min.js
├─ favicon.ico
├─ index.html
├─ LEIA-ME.md
├─ manifest.json
├─ service-worker.js
└─ sw.js
```
