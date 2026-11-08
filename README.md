# QR Studio

Pulsuz, qeydiyyatsız QR kod generatoru — link və ya mətni QR koda çevir, ortasına logo qoy, PNG və ya SVG kimi endir. Bütün emal brauzerdə gedir, heç bir məlumat serverə getmir.

*A free, no-signup QR code generator — turn a link or text into a QR code, add a center logo, download as PNG or SVG. Everything runs in the browser; no data leaves the device.*

## Canlı sayt / Live
Repo **Public** olandan və **GitHub Pages** aktivləşəndən sonra sayt bu ünvanda açılır:

**https://eldanizomarov.github.io/QR-Generator/**

## İmkanlar / Features
- Link, mətn, Wi-Fi, e-poçt, telefon üçün hazır şablonlar
- Nöqtə forması: yumru, nöqtə, kvadrat
- Rəng seçimi, qradient, şəffaf fon
- Mərkəzə logo (avtomatik yüksək səhv-düzəliş)
- PNG (512–4096 px) və SVG endirmə, buferə kopyalama
- 4 dil: AZ · EN · TR · RU, işıqlı/qaranlıq tema
- Tam oflayn — tək HTML faylı + qrcode.js

## İstifadə / How to use
1. Linkini və ya mətnini yaz.
2. Rəng, forma seç; istəsən logo əlavə et.
3. **PNG endir** və ya **SVG** düyməsinə bas.

## Necə yerləşdirilib / Deployment
Statik saytdır (server lazım deyil). GitHub Pages ilə işləyir:
1. Repo **Settings → General → Danger Zone → Change visibility → Public** (pulsuz Pages üçün repo açıq olmalıdır).
2. **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
3. Bir neçə dəqiqəyə sayt yuxarıdakı ünvanda açılır.

## Kredit / Credits
QR kodlaşdırma: [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) (Kazuhiko Arase, MIT).
«QR Code» — DENSO WAVE Incorporated şirkətinin qeydiyyatlı ticarət nişanıdır.
