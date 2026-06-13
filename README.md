# Vanaga Ligzda — Biznesa pusdienas

Weekly business-lunch ("Biznesa pusdienas") page designs for the restaurant **Vanaga Ligzda** (Baltezers, Latvia), styled to match [vanagaligzda.lv](https://www.vanagaligzda.lv): dark header/footer, white menu body, Enriqueta + Barlow type, warm brown/cream palette.

## Versions

Three layouts of the same content:

| File | Name | Layout | Live |
|------|------|--------|------|
| `version-1-pergaments.html` | **Saraksts** | Editorial day-by-day list | https://vanaga-pusdienas-saraksts.vercel.app |
| `version-2-vakara.html` | **Ēdienkarte** | Centered printed-menu style | — |
| `version-3-moderns.html` | **Moderns** | Interactive day tabs + price card | https://vanaga-pusdienas-moderns.vercel.app |
| `index.html` | Chooser | Live previews of all three | — |

## Notes

- Each version file is **self-contained** — the eagle logo is embedded as a base64 data URI and fonts load from Google Fonts, so the file can be pasted straight into a **Wix HTML embed** with no external assets.
- **Friday** is "Šefpavāra pārsteigums" (chef's surprise made from the week's dishes).
- Dishes and prices are **sample content** (structure modelled on porthotel.lv) — swap in the real weekly menu.
- Header/footer replicate the live site (LV·EN·ES switcher, centered eagle, contacts, Instagram grid, newsletter sign-up).

## Preview locally

```bash
python -m http.server 8099
# then open http://localhost:8099/
```
