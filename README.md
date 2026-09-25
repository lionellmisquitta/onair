# OnAir
**by Lionell Misquitta** · public beta

Live charts and slides that float beside you on a video call. Point at them, drill into them, swipe through them — with your hands.

**Free. Local-first. No account. No uploads.**

**▶ [Open OnAir](https://lionellmisquitta.github.io/onair/OnAir.html)** · or download `OnAir.html` and open it in your browser.

---

## What it is

OnAir is a single HTML file. Start your camera and your charts appear on glass right next to you. Share that browser window in Teams, Zoom or Google Meet, and your audience sees *you* presenting the data — not a slide deck that shrinks you to a thumbnail.

- **Charts that live on the call** — bars, columns, line, KPI, table, donut and funnel.
- **Your hands are the clicker** — point, hold two fingers to drill in, flick an open hand to turn the page.
- **Stories, not slides** — mix live charts and your own PDF slides in the order you'll tell it.
- **Use the whole frame** — put yourself on one side, your chart and a short note on the other.
- **Share in one file** — *Share…* makes one HTML file your colleague opens and presses **▶ Play**.
- **Record a clip** — you and the chart together, with your voice.

## Start

1. **Download** this repository (or just `OnAir.html`), or use the link above.
2. **Open `OnAir.html`** in **Chrome or Edge**.
3. Choose **Try it with sample data**, or **+ New blank story** and paste a table / import a PDF.
4. **▶ Rehearse** — allow camera access when asked; practise with your hands.
5. **● Go live** — in your call, *Share screen → this browser window*, and turn your own camera tile off.

Press **?** in the app any time for a two-minute tour.

## See it in action

Open **`examples/Meet OnAir.html`** and press **▶ Play**. It's a short story about OnAir itself — big-type slides, live charts and notes beside them — built with made-up business data. Swipe or use the arrow keys to move through it.

## Good to know

- **Browsers:** Chrome or Edge on a laptop or desktop is recommended. Safari is untested.
- **Camera:** presenter mode needs camera permission. On tablets and phones, use the hosted link (browsers only allow cameras on https pages).
- **Your data:** tables, stories and slides stay in your browser. OnAir downloads only its fonts, the hand-tracking model (first time you use gestures) and the PDF reader (first time you import a PDF).
- **PowerPoint:** save as PDF first (*File → Export → Create PDF*), then drop the PDF in.
- **Backups:** *Data → Export everything* saves your whole workspace to a file you can move to another machine.
- **Sharing:** presentations you export with *Share…* open in any Chrome or Edge browser. Opening one never changes the recipient's own work.

## Hands

| Gesture | Does |
|---|---|
| ☝️ one finger | point and highlight |
| ✌️ two fingers, hold | drill in · go back · lock · jump to a tile |
| 🖐️ open hand, right → left | next item (reversible in Settings) |
| 🖐️ open hand, upward | back out of a drill |
| 🤏 pinch and drag | move the chart |
| 🤏🤏 both hands, spread | resize |
| ✊ hold a fist | see every item at once |

Keyboard: ← → move · **G** overview · **R** rehearse · **P** live · **V** record · **K** lock · **Esc** back.

## Publish your own copy

Upload this repository to GitHub, then **Settings → Pages → Deploy from a branch → `main` / root**. `index.html` simply forwards to `OnAir.html`.

---

## For developers

OnAir is intentionally delivered as a self-contained HTML application. The application source is the file itself, and the project is released under the MIT License.

## License

MIT © 2026 Lionell Misquitta. Part of *Hidden Mathematics of Work* — more at [lionellmisquitta.com](https://lionellmisquitta.com).