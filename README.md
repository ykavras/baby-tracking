# Bebeğim — Legal site (Privacy Policy + Terms)

Statik yasal site. GitHub Pages'te yayınlanır; App Store Connect'te
**Privacy Policy URL** ve **Terms / Age Suitability URL** olarak kullanılır.

## Dosyalar
- `index.html` — giriş (her iki belgeye link)
- `privacy.html` — Gizlilik Politikası (TR + EN)
- `terms.html` — Kullanım Koşulları (TR + EN), **13+ yaş şartı** + tıbbi sorumluluk reddi
- `styles.css` — ortak stil

## GitHub Pages ile yayınlama
1. Yeni bir public repo oluştur (ör. `bebegim-legal`).
2. Bu klasördeki dosyaları repoya at:
   ```
   git init && git add . && git commit -m "legal site"
   git branch -M main
   git remote add origin https://github.com/<KULLANICI>/bebegim-legal.git
   git push -u origin main
   ```
3. GitHub → repo → **Settings → Pages** → Source: `Deploy from a branch`,
   Branch: `main` / `root` → Save.
4. Birkaç dakika sonra site yayında olur:
   - Privacy: `https://<KULLANICI>.github.io/bebegim-legal/privacy.html`
   - Terms:   `https://<KULLANICI>.github.io/bebegim-legal/terms.html`

Bu URL'leri App Store Connect → App Information → **Privacy Policy URL** ve
(Age Rating override ekranındaki) **Age Suitability URL** alanlarına yapıştır.

> Not: Bu belgeler genel bir şablondur, hukuki tavsiye değildir. Yayınlamadan
> önce gözden geçirip (gerekirse bir hukukçuya danışarak) şirket/varlık adını ve
> yargı yeri bilgisini kendi durumuna göre teyit et.
