# TOO-Many-CommunityProblems

**Too Many Problems!** — *How to choose the right problem*

An interactive 3D presentation that runs from a single HTML file.
EN103 group presentation · Bangkok University · 19 November 2026

**Live site:** https://hyperdusxdeveloper.github.io/TOO-Many-CommunityProblems/

---

## The idea

Every group is told to pick a community problem. Our community problem is the one that happens *before* any of those get solved: four people in a room who cannot agree on which problem to pick.

So instead of talking about a problem, we act this one out on stage. We try four different ways of choosing, and the first three all fail in front of the audience.

## What happens on screen

| Speaker | Section | On screen |
| --- | --- | --- |
| 1 | Opening & voting | We ask AI for five community problems, five sticky notes drop onto the table, and the group votes — one vote each, most votes wins. A tie carries on to the next round. |
| 2 | O-Noi-Ok | The Thai hand game. One round, four hands, and nobody wins. |
| 3 | Spinning wheel | A wheel with the problems on it. We press stop. It does not stop. |
| 4 | Ask AI | One clear question to the AI, and the chosen problem is plated in gold. |

The point we end on: the tool is not what decides. A clear question is.

## Running it

- **Online** — open the live link above. Nothing to install.
- **Offline** — download `index.html` and open it in any browser. No build step, no internet needed. Everything (fonts, 3D engine, textures) is inside that one file.

Press **F** for fullscreen before you start.

## Controls

| Key | What it does |
| --- | --- |
| `→` `Space` | Next slide (or click anywhere on screen) |
| `←` | Back (or click the left edge) |
| `1` `2` `3` `4` | Jump to a speaker's section |
| `F` | Fullscreen |
| `R` | Reset everything — back to the first slide, votes and timers cleared |
| `V` | Clear the votes and vote again |
| `O` | Play the hand game again |
| `S` | Try to stop the wheel |
| `E` | Settings — edit the five problems, the names and the AI's answer |
| `H` | Show all shortcuts |
| Click a sticky note | Cast a vote for that problem (4 votes, one per member) |

The voting is live. If one problem gets more votes than the others it wins straight away; if two tie, only those two go on to the wheel and to the final question.

## Built with

- [three.js](https://threejs.org) for the 3D stage — sticky notes, the hand game, the wheel, the gold plating
- Plain JavaScript and CSS, no framework
- [esbuild](https://esbuild.github.io) to bundle everything, fonts included, into one self-contained `index.html` (~700 KB, zero external requests)
- Poppins and Noto Sans Thai, embedded as base64

The pile of sticky notes on the opening screen is drawn from a pool of 100 community problems — 50 of them are picked at random, in a new arrangement, every time the page is opened.

## Team

| Name | Student ID | Section |
| --- | --- | --- |
| Akkarawin Seribuskorn | 1670703311 | Opening & voting |
| Natchanon Saileamonpiwat | 1670700044 | O-Noi-Ok |
| Mekin Kantawichai | 1670703675 | Spinning wheel |
| Jeerapat Watcharamoon | 1670703162 | Ask AI |
