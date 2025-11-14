# Cotton-Kitty

A tiny, private, single-purpose web app created to solve a very real question:

**“Do I currently have a tampon in?”**

Cotton-Kitty gives you a simple status toggle you can pin to your phone’s home screen.  
One tap switches between two clear states:

- Tampon in
- Tampon out

No accounts, no cloud, no tracking — everything stays on your device.

---

## Features

- Simple one-tap toggle for “In” / “Out”
- Timestamp showing when the status was last updated
- Light/dark mode with your preference remembered
- Reset button to quickly set everything back to “Out”
- Works offline
- Can be added to your home screen on both iOS and Android

---

## Live Link

**Link:** https://bananaph0ne.github.io/Cotton-Kitty/

---

## How It Works

Cotton-Kitty is a static HTML, CSS, and JavaScript app.  
There is no backend and nothing is sent or stored anywhere except locally in your browser.

The app uses the browser’s `localStorage` to save:

- `tampon_state` — `"in"` or `"out"`
- `tampon_state_time` — the timestamp of the last update
- `tampon_theme` — `"light"` or `"dark"`

On load, the app reads those values and updates the interface accordingly.

---

## Install Instructions

### iPhone (Safari)

1. Open the link in Safari.
2. Tap the Share icon.
3. Choose **Add to Home Screen**.
4. Name it (e.g., “Cotton-Kitty”).
5. Tap **Add**.

It will now open like an app.

### Android (Chrome)

1. Open the link in Chrome.
2. Tap the menu icon (top-right).
3. Select **Add to Home screen** or **Install app**.
4. Name it.
5. Confirm.

---

## Privacy

- No tracking or analytics
- No server or network calls
- No personal data collected
- Everything stays in your browser’s local storage

This is meant as a simple helper.  
When in doubt, always physically check and follow medical guidance.

---

## Customization

You can customize it easily:

- Change the title or subtitle in `index.html`
- Replace `icon.png` with your own icon (same filename)
- Adjust colors in the CSS
- Modify or remove the optional footnote text

---

## Tech Stack

- HTML  
- CSS  
- Vanilla JavaScript  
- Hosted via GitHub Pages  


