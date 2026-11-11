# Studio Light

Turn any screen into an adjustable face light for video calls, streams and selfies: colour temperature, tint, softness, shape and position, all in one HTML file with no install.

**Live demo:** [danyilshkodiuk.github.io/studio-light](https://danyilshkodiuk.github.io/studio-light/)

<img src="docs/screenshot.png" alt="Studio Light with the beauty ring scene and the settings panel open" width="820">

## Features

- **9 light shapes:** full screen, softbox, window, ring light, key + fill, two strips, side light, top light and two-colour
- **Accurate colour:** temperature from 2000 K to 10000 K along the Planckian locus, green ↔ magenta tint as a real Duv shift, quick presets, or any custom RGB colour
- **Light character:** brightness in linear light (50% is half the light), fill and background level with an honest contrast readout, softness, size, proportions and corner rounding
- **Scenes:** 8 built-in looks (video call, beauty ring, portrait, warm evening, neon duo…), plus your own scenes saved in the browser with JSON export and import and smooth transitions
- **Positioning:** sliders or drag the light directly on screen, mirror mode
- **Camera meter (`C`):** live preview that tells you whether your face is well lit and what to change
- **Undo / redo**, keeps the screen awake, works on phones (double-tap or ⚙ for settings)

## Controls

| Key | Action |
|---|---|
| `H`, double-click or ⚙ | Show / hide the panel |
| `F` | Full screen |
| `Space` | Light on / off |
| `C` | Camera with light meter |
| `1`–`9` | Scenes |
| `↑` `↓` | Brightness |
| `←` `→` | Colour temperature |
| `[` `]` | Softness |
| `-` `=` | Source size |
| `Ctrl+Z` / `Ctrl+Shift+Z` | Undo / redo |
| Mouse wheel (+ `Ctrl` / `Shift` / `Alt`) | Brightness (size / softness / temperature) |
| `?` | All shortcuts |

Shortcuts work on any keyboard layout. Tip: the panel itself also lights your face, so hide it with `H` while filming, and set your monitor brightness to maximum.

## Run locally

Download [`studio-light.html`](studio-light.html) and open it in any modern browser. No build step and no dependencies.

## Tech

Vanilla HTML, CSS and JavaScript in a single file. Settings and scenes are stored in `localStorage`; the camera meter uses `getUserMedia`. `index.html` is an exact copy of `studio-light.html` for GitHub Pages, so keep the two in sync.

---

## Українською

Перетворює екран на налаштовуване студійне світло для обличчя: температура кольору, відтінок, м'якість, контраст, форма джерела, сцени.

**Демо:** [danyilshkodiuk.github.io/studio-light](https://danyilshkodiuk.github.io/studio-light/)

- **Форми світла:** весь екран, софтбокс, вікно, кільцева лампа, ключ + заповнення, дві смуги, бічне, зверху, двоколірне
- **Колір:** температура 2000–10000K за планківською кривою, відтінок зелений ↔ пурпурний (Duv), свій колір RGB, кольорові пресети
- **Інтенсивність:** яскравість у лінійних одиницях світла (50% = половина світлового потоку), заповнююче джерело, рівень фону з чесним показником контрасту
- **Характер:** м'якість країв, розмір, пропорції, товщина, заокруглення, положення (джерело можна перетягувати мишкою)
- **Сцени:** 8 готових, власні зберігаються в браузері, експорт та імпорт у JSON, плавний перехід між сценами
- **Камера (C):** показує, наскільки добре освітлене обличчя, і радить, що змінити
- Скасувати / повторити, дзеркальний режим, екран не засинає; на телефоні подвійний дотик або ⚙ відкриває налаштування

Гарячі клавіші ті самі, що в таблиці вище, і працюють у будь-якій розкладці, зокрема в українській. Перед роботою виставте яскравість монітора на максимум, а під час зйомки ховайте панель клавішею `H`.

Щоб запустити локально, відкрийте `studio-light.html` у будь-якому браузері. Нічого встановлювати не треба.
