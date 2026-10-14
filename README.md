# The Odd Question

A pass-and-play party game for 3–10 players with a game-show look: clear, high-contrast text, easy-to-tap buttons, no timers and no typing during play. English and French.

Everyone gets the same question, except the Odd One, who gets a slightly different one. Like the Imposter game, answers are words, not numbers: a food, a place, an animal, an object, a film, a job, or someone in the room (everyone points on 3). The two questions are close enough for the Odd One to blend in, and the group's answers give them clues to guess the real question. Above the question, the Odd One sees a black banner with glowing red letters saying they are the Odd One, so they know to blend in; everyone else sees a calm green "You have the group's question". Everyone answers on 3, then the group votes on who had the odd question.

**Scoring:** catch the Odd One → +1 to everyone else. The Odd One escapes → +3 to them. Caught, but guessed the real question → +2 to the Odd One. First to 10 points wins (adjustable).

## Play

It's a single `index.html` with no dependencies. Open it in a browser, or serve it locally:

```sh
python3 -m http.server 8000
```

then visit `http://<your-computer's-IP>:8000` from a phone on the same Wi-Fi.

Player names, language, target score and the current game are saved in the browser, so a reload never loses a game (and never re-shows a secret question).
