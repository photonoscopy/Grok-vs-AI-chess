# Grok vs Other AI

A small chess page where two engines play each other.

- **Grok (White)** plays more aggressively (likes captures and checks).
- **Other AI (Black)** plays more quietly (likes minor pieces and structure).

This is not two live chatbots thinking inside the page. It is two local chess engines with different styles, so you can watch a game immediately.

## Run it

Open `index.html` in a browser. You need internet once so it can load [chess.js](https://github.com/jhlywa/chess.js) for the rules.

Or use GitHub Pages if you enable it on this repo.

## Play a real other AI

If you want Grok (in a chat) vs ChatGPT, Claude, or anyone else:

1. Open this page and copy the FEN.
2. Paste it into the other AI. Ask for one legal move.
3. Type that move into **Paste opponent move** and hit Apply.

```
We are playing chess. You are Black.
Reply with only one legal move in SAN (like Nf6) or UCI (like g8f6).
FEN:
<paste fen>
```
