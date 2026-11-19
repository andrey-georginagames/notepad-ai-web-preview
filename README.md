# Georgina Games — Notepad AI Agent test preview

Latest public test build: **Concept 02 v0.8.0 · Quiet Intelligence + Paper Lite** (approved studio redesign A–E).

- Official preview: https://andrey-georginagames.github.io/notepad-ai-web-preview/
- UX: five main tabs Home / Notes / AI / Calendar / More; one-tap new note; simpler notes list, three presentation modes with grouped View & Order; Paper Lite writer and optional Clean Canvas / Soft Color.
- Preserves v0.7 stored web data by retaining localStorage key `notepad_ai_concept02_v1`, data schema v2 and JSON backup v3; avoid clearing browser storage.
- QA: **247/247** scoped Chromium checks passed (86 regression, 43 recovery/performance, 105 responsive UX, 13 paper settings). Real Android device and live-site persistence tests are still OPEN.
- AI, accounts, billing, sync and actual scheduled reminders are simulations. This is a text-only prototype; do not store sensitive real-life notes in a public test.
- Side-by-side Android debug test APK v080 uses a different package ID; Android data do not automatically transfer from v070. Use backup and restore copies for migration.
- Rollback to v0.7.0 available in the `notepad-v0.7.0-baseline` branch.

Released by Studio Brain Resident after owner approval on 19 November 2026.
