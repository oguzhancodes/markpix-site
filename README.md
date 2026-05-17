# MarkPix — Marketing + Legal Site

`getmarkpix.com` için statik web sitesi. Vanilla HTML/CSS, hosting: Cloudflare Pages.

## Dosyalar

- `index.html` — Landing (hero, features, pricing)
- `privacy.html` — Gizlilik Politikası + KVKK aydınlatma metni
- `terms.html` — Kullanım şartları + abonelik koşulları
- `style.css` — Tek dosya stil (vanilla)
- `_redirects` — `/privacy` ve `/terms` URL'leri için pretty URL (Cloudflare Pages)

## Lokal preview

```
python3 -m http.server 8000
# http://localhost:8000 aç
```

## Deploy

Cloudflare Pages otomatik deploy — `main` branch'a push yapılınca canlı.

## Güncelleme notu

Yasal metinleri düzenlerken her iki dosyada da üstteki "Son güncelleme" tarihini güncellemeyi unutma.
