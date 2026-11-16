# Site pessoal: Fábio Ricardo Moraes da Silva

Site estático (HTML, CSS e JavaScript puro). Não tem dependências nem etapa de build.

## Estrutura

| Arquivo | Função |
|---|---|
| `index.html` | Página principal |
| `styles.css` | Estilos, tema claro/escuro e layout para celular |
| `script.js` | Menu no celular, troca de tema e animação ao rolar |
| `404.html` | Página de erro exibida pela Vercel |
| `robots.txt` | Permite indexação por buscadores |
| `vercel.json` | URLs limpas e cabeçalhos de segurança |

## Ver localmente

Abra `index.html` no navegador ou rode, nesta pasta:

```bash
npx serve .
```

## Publicar na Vercel

**Pelo painel (com Git):**
1. Envie os arquivos para o repositório (`git add . && git commit -m "Site pessoal" && git push`).
2. Em vercel.com, clique em **Add New → Project** e importe o repositório.
3. Em **Framework Preset**, escolha **Other**. Deixe o **Build Command** e o **Output Directory** vazios. O **Root Directory** é a raiz do repositório.
4. Clique em **Deploy**. Cada novo `git push` na branch `main` publica o site de novo.

**Pela linha de comando:**
```bash
npm i -g vercel
vercel          # cria uma pré-visualização
vercel --prod   # publica em produção
```
