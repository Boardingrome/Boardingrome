# Hi, I'm Drake 🤠

I built my first computer at 8 and I've been fixing and building things ever since, with software and with my hands.

I grew up in a rodeo family in Northern Colorado and worked in our family's fence-building business. Since then I've been a power equipment mechanic, a professional brewer, an HOA night manager and a blinds business owner. I've turned an '03 Shadow Spirit 750 into my own bobber, I still have an old '94 Ranger, and these days I also work on a 500 acre luxury hunting and fishing ranch.

By day I'm a software engineer, building on Salesforce (Apex). The rest of the time I build software for the kind of people I grew up around and work alongside: rodeo producers, cowboys, and hard workers. I like building things that real people use on the ground.

Most of my personal work is in **TypeScript** and **Python**. The repos below are private, so here's what they are and what they do. Happy to walk through any of them.

## 🐂 Rodeo and ranch software

**Go-Round** ([live demo](https://go-round-demo.vercel.app/d/beta-rodeo), made-up rodeo, no login): a modern platform for running local rodeos (junior, county fair, 4-H, ranch rodeos, jackpots). Producers set up events, take entries, build the run order and record results, and everyone at the rodeo follows along on one live "Daysheet" link with no app or account. The payout logic is built and tested, with the screens coming next.
*Next.js · Expo / React Native · TypeScript · Supabase (Postgres, Auth, Realtime, RLS) · pnpm monorepo*

**RoperReady**: a cloud-synced team roping manager for backyard jackpots and ranch ropings: entries, fair partner draws, run order, results and payouts, on desktop and mobile.
*Next.js · Expo · TypeScript · Supabase*

**Rodeo Sheet Manager**: the Google Apps Script system that actually ran real junior rodeos: contestant entries, printable daysheets, turnouts, fees and automatic payouts from a single spreadsheet.
*Google Apps Script · Google Sheets / Drive*

**Rod.io**: a Python pipeline that scrapes Colorado Pro Rodeo day sheet PDFs, extracts every event and contestant, and turns them into structured data.
*Python · Selenium · PDF parsing · Firebase*

## 🔧 Tools for makers

**ScrollSmith**: a desktop app for metal engravers (Western, bright-cut, scroll work). Load a photo of a buckle or knife, paint where the engraving goes, and export a scaled vector pattern as SVG.
*Electron · React · TypeScript · Python FastAPI sidecar*

**3D printing profiles**: tuned slicer profiles for engineering filaments like carbon-fiber nylon.

## 🎮 Just for fun

**Frontiers** (demo on request): a 1990s-style real-time strategy game (think Red Alert) where your army is creatures you discover, capture, train and evolve. Built on a deterministic simulation core at 20 ticks per second, which is what makes saves, replays and lockstep multiplayer possible.
*TypeScript · Phaser · Vite · Vitest*

**Daylist Archiver**: saves Spotify's daily auto-generated "daylist" playlists before they disappear.
*Node.js · Express · Spotify OAuth · Firebase*
