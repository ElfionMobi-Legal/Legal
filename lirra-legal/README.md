# Lirra legal pages (GitHub Pages)

Privacy Policy, Terms of Use, and Account Deletion for App Store / Play Store listing and in-app links.

## Publish (örnek)

1. Public repo: `elfionmobi-legal` / `Legal` (Pages) — Timbr ile aynı
2. Bu klasördeki HTML dosyalarını repo’ya koy (`lirra-legal/` altında)
3. GitHub → Settings → Pages → Deploy from branch `main`
4. Canlı URL’ler (Elfion):
   - https://elfionmobi-legal.github.io/Legal/lirra-legal/privacy-policy-en.html
   - https://elfionmobi-legal.github.io/Legal/lirra-legal/terms-of-use-en.html
   - https://elfionmobi-legal.github.io/Legal/lirra-legal/account-deletion-en.html  ← **Play Delete account URL**
5. Mobil `Env.privacyUrl` / `Env.termsUrl` / (ileride) delete URL’yi bu adreslere set et  
   Domain gelince: `https://getlirra.com/privacy` vb. aynı HTML’i host et

Dosyalar bu monorepo’da: `docs/lirra-legal/`.

## Play Console’a yapıştır

**Delete account URL**
```
https://elfionmobi-legal.github.io/Legal/lirra-legal/account-deletion-en.html
```

**Account creation — Other (açıklama)**
```
Lirra creates an anonymous account automatically on first use via Supabase Auth (no username, password, or social sign-in required). The anonymous user ID syncs ritual history, streak, profile preferences, and subscription status. Users do not register with email or credentials.
```

## App content / Privacy formları

Store anketleri için: `docs/04-STORE-PUBLISHING.md`.
