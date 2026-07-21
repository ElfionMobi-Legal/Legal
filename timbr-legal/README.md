# Timbr legal pages (GitHub Pages)

Privacy Policy and Terms of Use for App Store / Play Store listing and in-app links.

## Publish (örnek)

1. Yeni repo: `timbr-legal` (public)
2. Bu klasördeki HTML dosyalarını repo köküne koy
3. GitHub → Settings → Pages → Deploy from branch `main` / root
4. URL’ler:
   - `https://<user>.github.io/timbr-legal/privacy-policy-en.html`
   - `https://<user>.github.io/timbr-legal/terms-of-use-en.html`
5. Mobil `Env.privacyUrl` / `Env.termsUrl` veya `--dart-define=PRIVACY_URL=...` ile güncelle

Dosyalar bu monorepo’da da durur: `docs/legal/`.
