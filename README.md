# Ronney Guimarães Belmont — site oficial

Site institucional de Ronney Guimarães Belmont, poeta e escritor brasileiro.

## Desenvolvimento local

Requer Node.js 22+.

```bash
npm install --legacy-peer-deps
npm run dev
```

Para validar a versão de produção:

```bash
npm run build
npm run preview
```

## Deploy no GitHub Pages

O deploy é automático via GitHub Actions (`.github/workflows/deploy.yml`) a cada push na branch `main`.

1. Coloque as 7 capas em `public/capas/` (veja `public/capas/LEIA-ME.txt`).
2. Suba o projeto para um repositório no GitHub.
3. Em **Settings → Pages → Source**, escolha **GitHub Actions**.
4. O workflow detecta sozinho se o repositório é `usuario.github.io` (raiz) ou um site de projeto (`/nome-do-repo/`).

## Stack

- React + TypeScript
- Vite
- TanStack Router
- Tailwind CSS v4
