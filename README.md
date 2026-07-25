# Legal pages (GitHub Pages) — Rendix

Mesmo padrão do **Registro+** (`legal-pages/` → GitHub Pages).

## URL para a Play Console

```
https://deneralbuquerque37-boop.github.io/rendix/privacidade.html
```

## Publicar (conta `deneralbuquerque37-boop`)

1. No GitHub: **New repository** → nome `rendix` → **Public** (sem README).
2. No PowerShell, a partir desta pasta:

```powershell
cd c:\Users\dener\assessor-app\legal-pages
git init
git add .
git commit -m "docs: política de privacidade Rendix (Pages)"
git branch -M main
git remote add origin https://github.com/deneralbuquerque37-boop/rendix.git
git push -u origin main
```

3. No repo GitHub → **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
   - Save

4. Aguarde ~1 minuto e abra a URL acima no Chrome.
5. Cole a mesma URL em Play Console → Política de Privacidade → **Salvar**.

Arquivo espelho (rascunho): `docs/legal/privacidade.html`.
