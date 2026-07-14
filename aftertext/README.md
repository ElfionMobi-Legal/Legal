# AfterText legal pages

HTML pages for Google Play / in-app Privacy Policy and Terms of Use (EN + TR).

## Files

| File | Language |
|------|----------|
| `privacy-policy-en.html` | English privacy |
| `privacy-policy-tr.html` | Turkish privacy |
| `terms-of-use-en.html` | English terms |
| `terms-of-use-tr.html` | Turkish terms |

## Host on GitHub Pages (same pattern as BatteryGlow)

Copy the four HTML files into your `elfionmobi-legal` repo under:

```text
Legal/aftertext/
```

Expected public URLs:

- Privacy (EN — use this in Play Console):  
  `https://elfionmobi-legal.github.io/Legal/aftertext/privacy-policy-en.html`
- Privacy (TR):  
  `https://elfionmobi-legal.github.io/Legal/aftertext/privacy-policy-tr.html`
- Terms (EN):  
  `https://elfionmobi-legal.github.io/Legal/aftertext/terms-of-use-en.html`
- Terms (TR):  
  `https://elfionmobi-legal.github.io/Legal/aftertext/terms-of-use-tr.html`

Play Console **App content → Privacy policy** should use the **English** URL (or a single page that matches your store default language). TR pages are for Turkish users via the language switcher on each page.

## App wiring

`AppIntents` defaults to the EN GitHub Pages URLs above. After you publish the Pages, open paywall → Privacy / Terms to verify.
