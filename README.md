# Vitacodex — Roadmap & Análises

Site estático com 4 páginas, pronto para deploy no Vercel.

## Estrutura

```
/
├── index.html                    ← Roadmap principal (página home)
├── market-analysis/
│   └── index.html                ← Análise de mercado genômico
├── backend-analysis/
│   └── index.html                ← Análise técnica do backend NutriNest
├── roadmap-vs-backend/
│   └── index.html                ← Cruzamento roadmap × gaps reais
└── vercel.json                   ← Roteamento clean URLs
```

## Deploy no Vercel

1. Suba esta pasta para um repositório GitHub
2. No Vercel: **Add New Project** → importe o repositório
3. Framework: **Other** (sem build step)
4. Root directory: `/` (raiz)
5. Clique em **Deploy**

As rotas `/market-analysis`, `/backend-analysis` e `/roadmap-vs-backend` funcionam com `cleanUrls: true` no `vercel.json`.
