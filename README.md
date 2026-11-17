# ♠ The Gilded Ace

### ▶ [Play now: qibbles.github.io/gilded-ace-poker](https://qibbles.github.io/gilded-ace-poker/)

A free Texas Hold'em poker school that runs entirely in your browser. No install, no sign-up, no server. Sit down at a practice table against computer opponents, learn the rules and the maths, and track how you improve.

I built it to learn poker from scratch, using Claude as a coding partner.

## What's inside

- **Practice table**: play $1/$2 No-Limit Hold'em against 1 to 8 computer opponents, from heads-up to a full ring.
- **Three opponent levels**: Novice (makes mistakes), Journeyman (solid) and Grandmaster (reads ranges). You can label their playing styles or read them yourself.
- **Coaching modes**: be quizzed on your outs, odds and pot price before you act, see full hints, get feedback after you act, or turn it off and just play.
- **Lessons** on the order of a hand, what you can do on your turn, ties and kickers, raise-or-fold when first in, and why good bluffs need a story.
- **Drills** for counting outs, checking your maths and quick bet sizes to memorise.
- **My progress**: a review at the end of each session with what you did well and what to work on next.
- **Table settings** for stack size, dealer speed and number of opponents.

Your progress is saved in your own browser (localStorage). Nothing is sent anywhere.

When opened inside Claude, an AI coach can also comment on your play and answer questions. On GitHub Pages the rest of the app works the same, just without the AI coach.

## Run it

- **Online:** go to **https://qibbles.github.io/gilded-ace-poker/**. Works on laptop or phone.
- **Offline copy:** download [`index.html`](index.html) and open it in your browser. It needs an internet connection only to load fonts.

## How it was built

A single HTML file with plain JavaScript and no framework or build step: a poker engine (dealing, betting rounds, hand ranking, side pots) plus the UI on top. The code was written with Claude as an AI pair programmer.

## License

MIT. See [LICENSE](LICENSE).
