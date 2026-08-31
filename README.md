# Legal pages (GitHub Pages) — Rendix

Mesmo padrão do **Registro+** (`professor-app/legal-pages/` → GitHub Pages).

## URLs publicadas

| Uso | URL |
|-----|-----|
| **Site (landing + SEO)** | `https://deneralbuquerque37-boop.github.io/rendix/` |
| **Política de privacidade** | `https://deneralbuquerque37-boop.github.io/rendix/privacidade.html` |
| **robots / sitemap** | `…/robots.txt` · `…/sitemap.xml` |

Plano detalhado: [`docs/PLAN-site-github-pages-rendix.md`](../docs/PLAN-site-github-pages-rendix.md).

## Play Console

- **Site do app:** raiz `https://deneralbuquerque37-boop.github.io/rendix/`
- **Política de privacidade:** `…/privacidade.html`

## Publicar (conta `deneralbuquerque37-boop`)

Repo: `https://github.com/deneralbuquerque37-boop/rendix`

```powershell
cd c:\Users\dener\assessor-app\legal-pages
git add .
git commit -m "docs: landing SEO Rendix + sitemap"
git push origin main
```

Se o repo ainda não existe:

```powershell
cd c:\Users\dener\assessor-app\legal-pages
git init
git add .
git commit -m "docs: site Rendix GitHub Pages"
git branch -M main
git remote add origin https://github.com/deneralbuquerque37-boop/rendix.git
git push -u origin main
```

**Settings → Pages:** branch `main`, folder `/ (root)`.

Arquivo espelho da política: `docs/legal/privacidade.html`.
