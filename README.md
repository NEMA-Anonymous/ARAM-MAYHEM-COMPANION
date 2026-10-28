# ARAM Mayhem Coach

**A coach talks, the player plays.**

The Coach is a companion for League of Legends' ARAM Mayhem mode. It watches the same game you're watching and speaks what it sees — out loud, in the moment — the way a friend who knows the mode would over your shoulder. It never touches your inputs, never plays a single second for you, and never sees anything your own client doesn't.

**Free. Donations only. No account.**
Download: https://aram-mayhem-coach.nema-anonymous.workers.dev

## What it does

- **Champion select:** reads your client session — your team, your rolls, the bench — and gives one spoken hedge: the pick it favors, and why.
- **Augment calls:** every time you're offered three cards, it weighs them against your champion, where your build is heading, what your team is missing, and whether you're ahead or behind — and calls the pick out loud.
- **A living build:** as items land and the game swings, the build recommendation re-weighs itself.
- **Moments:** all game long it flags your plays — every moment where you had a hand in 2+ takedowns, counting kills *and* assists, because in Mayhem the setup is the play — and celebrates them. A loss can still be your best game.

## What it is — and isn't

- It is **not AI-run**. There is no model in there making things up. It's wires: rules and weights set by hand, connected carefully, tested and tuned game after game.
- It's a **registered Riot developer app**. Nearly everything arrives through Riot's own local channels: the League client session (LCU) before the game, and the Live Client Data feed during it. No memory reading, no injection, nothing hidden — it only ever knows what your own client knows.
- One honest workaround, stated plainly: Riot publishes no feed for the augment cards themselves, so the Coach reads those three cards off your own screen — the same screen you're looking at. That's the weakest wire in the app. A read can come back partial, and when it does you hear the hedge, not a bluff. Honesty is a feature, not a disclaimer.

## Community

The house lives at [r/EatCakeU](https://www.reddit.com/r/EatCakeU/) — the design philosophy, the updates, the scoreboard.

## About this repository — please read

This page is a **landing card only**. The Coach's source code is **not published here and never will be**. The software is proprietary — © 2026 Raphael Morales / EAT CAKE-U — and is distributed solely as the official download linked above. Nothing on this page grants any right to copy, redistribute, or reimplement the Coach, its name, or its text. Clones have happened before; they are noticed, and they are not the Coach.

---

*ARAM Mayhem Coach is not affiliated with Riot Games. League of Legends is a trademark of Riot Games, Inc.*
