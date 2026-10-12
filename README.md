# The 23rd Floor — Murder at Vesper Tower

**An original murder-at-the-masquerade social-deduction experience, designed for 22 guests plus a non-playing host.**

## Premise

Twenty-two guests attend Aditya's midnight masquerade on the 23rd floor of Vesper Tower. When the clock strikes thirteen, Aditya is discovered dead. Yet a series of messages he recorded before his death begins arriving on the guests' phones. Who murdered the host—and who has been concealing a different crime?

## Prototype scope

The initial `index.html` is a **standalone, single-browser host console and public projection prototype**. It demonstrates six narrated scenes, act selection, a count-up timer, and an alternate same-device projector view. This is **not** yet a secure live multiplayer app. The initial prototype deliberately does not contain the murderer, private guest identities, or the canonical solution.

## Design rules

- The 22 attending friends use their real names in private game configuration, not public repository source.
- Real couples remain real couples; no fabricated affairs or romantic betrayal.
- Each guest gets consequential information, meaningful choices, and a reason to participate.
- Social deduction and negotiation are live and face-to-face; the app enables and orchestrates those moments.
- Fixed case solution and independently verifiable evidence; no retroactive plot changes.
- No player elimination; everyone remains active throughout.
- Host can run the entire experience without playing as a suspect.
- A paper-based failover must be available.

## Planned architecture

- **Phase 1:** host screen and public projection proof of concept.
- **Phase 2:** canonical mystery design, 22 role packets, all clue dependencies, role and timing audits.
- **Phase 3:** authenticated participant sessions, private dossiers, real-time host-triggered events, shared investigation, secret submissions, voting.
- **Phase 4:** automated reliability tests and an in-person playtest with independent testers.

The future multiplayer version will need a backend with server-side access controls; **GitHub Pages alone cannot keep secret content safe or synchronize 22 live players**.

## Local preview

Open `index.html` in a browser, or serve the repository with any local static web server. The current scene is saved in session storage; the elapsed timer is not retained across reloads. The public-screen view is an alternate view of the same device, not a network-connected second screen.

## Inspiration

Inspired by the participatory Storyteller and social-deduction design principles of *Blood on the Clocktower*, but this is an independently designed game, not an adaptation of its role powers, scripts, characters, or artwork.

## Current files

- `index.html` — rebranded single-browser demo for *The 23rd Floor*
- `GAME_DESIGN.md` — original gameplay loop, fairness contract, story premise, and testing plan

**Not yet implemented:** 22 private player accounts, secret role distribution, real-time connection, votes, and the solved canonical mystery. The prototype is not ready for game night.
