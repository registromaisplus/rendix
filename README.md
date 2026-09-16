# Legal pages (GitHub Pages) — Rendix

Mesmo padrão do **Registro+** (`professor-app/legal-pages/` → GitHub Pages).

**Cutover (~16/09/2026):** conta GitHub `deneralbuquerque37-boop` → `registromaisplus`. Checklist: [`docs/CUTOVER-GITHUB-PAGES-RENDIX.md`](../docs/CUTOVER-GITHUB-PAGES-RENDIX.md). URL antiga morre no rename. **Não** fazer push até o Dia D.

## URLs publicadas (alvo)

| Uso | URL |
|-----|-----|
| **Site (landing + SEO)** | `https://registromaisplus.github.io/rendix/` |
| **Política de privacidade** | `https://registromaisplus.github.io/rendix/privacidade.html` |
| **robots / sitemap** | `…/robots.txt` · `…/sitemap.xml` |

Plano detalhado: [`docs/PLAN-site-github-pages-rendix.md`](../docs/PLAN-site-github-pages-rendix.md).

## Play Console

- **Site do app:** raiz `https://registromaisplus.github.io/rendix/`
- **Política de privacidade:** `…/privacidade.html`

## Publicar (conta `registromaisplus`, após rename)

Repo: `https://github.com/registromaisplus/rendix`

```powershell
cd c:\Users\dener\assessor-app\legal-pages
git remote set-url origin https://github.com/registromaisplus/rendix.git
git add .
git commit -m "docs: landing SEO Rendix + sitemap"
git push origin main
```

**Settings → Pages:** branch `main`, folder `/ (root)`.

Arquivo espelho da política: `docs/legal/privacidade.html`.

Manter `google98cf4ffc3b740a7e.html` (**não apagar**).

## AdMob (app-ads.txt)

Google exige `app-ads.txt` na **raiz do domínio** do site do desenvolvedor (Play → Site), não só em `/rendix/`:

| Onde | URL |
|------|-----|
| **Obrigatório (domínio raiz)** | `https://registromaisplus.github.io/app-ads.txt` → repo `registromaisplus/registromaisplus.github.io` (pasta `github-user-site/` no monorepo) |
| **Cópia (projeto Pages)** | `https://registromaisplus.github.io/rendix/app-ads.txt` → este repo |

Após publicar: AdMob → app → **Verificar se há atualizações** (pode levar até 24h).
