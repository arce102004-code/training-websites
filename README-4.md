# Training Gyms

A small, growing collection of single-page tools for practicing skills on purpose — instead of letting an algorithm decide what you consume today.

Each one lives in its own folder, runs as a single static HTML file with no backend, and keeps everything you do in your own browser's local storage. No accounts, no tracking, no server.

## What's here

| Tool | Trains | |
|---|---|---|
| [**Thinking Gym**](./thinking-gym) | Reasoning — forced synthesis between unrelated ideas, Socratic self-interrogation, reverse-engineering real-world outcomes | [→ README](./thinking-gym/README.md) |
| [**Speaking Gym**](./speaking-gym) | Spoken communication — presentations, conversational fluency, and interview answers, with live transcript and filler-word tracking | [→ README](./speaking-gym/README.md) |

More may get added over time — the pattern is the same for each: pick a skill that usually only improves through passive exposure or expensive coaching, and build a small, honest, repeatable way to practice it alone.

## Running any of them

Every tool is a single `index.html` with no build step and no dependencies to install.

- **Locally:** download the folder and open `index.html` in a browser.
- **Hosted:** enable GitHub Pages on this repo (Settings → Pages → deploy from this branch), and each tool becomes reachable at its own path, e.g. `https://<your-username>.github.io/<repo-name>/thinking-gym/`.

Each subfolder's README has the specifics — browser support caveats, what's stored where, and what each tool actually does session to session.

## Philosophy

These aren't polished products — they're personal training equipment. The goal isn't a slick onboarding flow, it's showing up and doing the actual rep: writing the bridge between two ideas, defending a belief under pressure, or just recording yourself talking and listening back. The tools stay out of the way as much as possible so that friction lives in the thinking, not the interface.

## License

MIT across the repo — use any of it, fork it, adapt it into whatever you're trying to get better at.
