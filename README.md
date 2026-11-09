# Communication Coach

A single-page HTML communication coach. Open `index.html` in any browser — no install needed.

Mobile-first, light green design: bottom tab bar on phones (top bar on desktop), a Home dashboard with today's session, a 100-day progress ring, a 🔥 day streak, sessions/minutes done and a phrase of the day. On a phone, use **Add to Home screen** to open it like an app.

Live: https://amjad-ra.github.io/communication-coach/

- **Home** – skill modules (English Communication and Public Speaking are live; more coming).
- **English Practice – 100-Day Program** (10 minutes a day). Each day card shows the topic, goal, useful words and the full coaching prompt.
  - **Phase 1 · Fast Track (Days 1–30)** – speak with confidence, fast (Beginner 1–10, Intermediate 11–20, Advanced 21–30). Gemini corrects only the biggest mistakes so you keep talking.
  - **Phase 2 · Lock It In (Days 31–100)** – 10 themed weeks to make it accurate and permanent. Each week: 5 new topics → 🔧 Fix-It day (repeated mistakes + a grammar note) → 🔁 Review day (reuses the week's words and revisits three Phase 1 topics). Week 10 ends with a final test (Day 99) and a lifelong practice plan (Day 100).
  - A **Start / Continue** button jumps to your next unfinished day.
  - **Grammar Boost** (below the 100 days) – 16 sessions on sentence structure, grammar and questions, each with a short note: the rule plus ✔ correct / ✘ wrong examples.
- **Public Speaking** – 30 daily 10-minute drills (Foundations 1–10, Building 11–20, Mastery 21–30): stage fear, voice, structure, storytelling, Q&A, presentations, pitches and debates.
- **Gemini button** (right side of each card) – copies the day's prompt and opens Gemini with it. If Gemini's chat box is empty, just paste and send.
- **Mark as done** – progress is saved in your browser.

To add or edit days, change `ENGLISH_DAYS` (Phase 1), `LOCK_WEEKS` / `MASTERY_WEEK` (Phase 2), `GRAMMAR_DAYS` or `SPEAKING_DAYS` in `index.html`.
