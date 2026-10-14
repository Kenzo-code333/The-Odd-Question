# The Odd Question

A pass-and-play party game for 3–10 players, designed for older players: very large text, high contrast, big buttons, no timers and no typing during play. English and French.

Everyone gets the same question with a number answer, except one secret Odd One who gets a slightly different question. Everyone says their answer on 3, then the group votes on who had the odd question.

**Scoring:** catch the Odd One → +1 to everyone else. The Odd One escapes → +3 to them. Caught, but guessed the real question → +2 to the Odd One. First to 10 points wins (adjustable).

## Play

It's a single `index.html` with no dependencies. Open it in a browser, or serve it locally:

```sh
python3 -m http.server 8000
```

then visit `http://<your-computer's-IP>:8000` from a phone on the same Wi-Fi.

Player names, language, target score and the current game are saved in the browser, so a reload never loses a game (and never re-shows a secret question).
