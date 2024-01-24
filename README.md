This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Build prod and serve static web site

1. In config file `next.config.mjs` parameter `output` must be `export`.
2. In config file `next.config.mjs` parameter `destDir` must be any word, for example `dist`.
3. Another config as you wish.
4. Enter the command:
```bash
npm run build
```
5. In folder `dist` (from step 2) ready to serve prod static web site.