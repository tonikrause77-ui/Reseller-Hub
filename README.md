# Reseller Hub – eBay OAuth Pages

## Vor dem Upload
Öffne `privacy.html` und ersetze:
- `[NAME / UNTERNEHMEN]`
- `[KONTAKT-E-MAIL]`

## GitHub Pages
1. Neues PUBLIC Repository erstellen, z. B. `reseller-hub-oauth`.
2. Alle Dateien aus diesem Ordner in das Repository hochladen.
3. Repository: Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: `main`, Folder: `/ (root)`, danach Save.
6. Nach kurzer Zeit zeigt GitHub die HTTPS-URL an.

Beispiel bei Benutzer `meinname` und Repository `reseller-hub-oauth`:
- Privacy: `https://meinname.github.io/reseller-hub-oauth/privacy.html`
- Accepted: `https://meinname.github.io/reseller-hub-oauth/oauth-success.html`
- Declined: `https://meinname.github.io/reseller-hub-oauth/oauth-declined.html`

## eBay RuName
- Display Title: `Reseller Hub`
- Privacy Policy URL: deine `privacy.html`
- Auth Accepted URL: deine `oauth-success.html`
- Auth Declined URL: deine `oauth-declined.html`

Danach bei eBay speichern, OAuth aktivieren und den Production User Token erzeugen.
