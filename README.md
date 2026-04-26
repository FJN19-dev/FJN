# FJN

Site pessoal feito com React + Vite.

## Como publicar — RECOMENDADO: Vercel (mais facil)

1. Cria conta gratis em https://vercel.com (entra com seu GitHub)
2. Clica em "Add New" -> "Project"
3. Escolhe seu repositorio do GitHub
4. NAO mexe em nada, so clica em "Deploy"
5. Pronto, em 30 segundos vai gerar um link tipo `seu-projeto.vercel.app`

## Como publicar no Netlify

1. Entra em https://netlify.com
2. "Add new site" -> "Import an existing project"
3. Escolhe seu repositorio
4. NAO mexe em nada, so clica em "Deploy site"

(O arquivo `netlify.toml` ja configura tudo sozinho.)

## IMPORTANTE: estrutura no GitHub

Os arquivos abaixo precisam ficar na raiz do repositorio (nao dentro de outra pasta):

```
package.json
vite.config.ts
tsconfig.json
index.html
netlify.toml
vercel.json
.gitignore
src/
  App.tsx
  main.tsx
  index.css
  vite-env.d.ts
  assets/
    perfil.gif
    musica.mp3
```

## Rodar no seu computador

```bash
npm install
npm run dev
```
