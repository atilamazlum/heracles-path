# ⚡ Heracles Path

**Myth · Psychology · Adler**

Heracles Path is a symbolic psychology tool that analyzes everyday struggles through the lens of Heracles' 12 Labors and Alfred Adler's Individual Psychology. Powered by AI.

🔗 **[heraclespath.netlify.app](https://heraclespath.netlify.app/)**

---

## What It Does

1. User describes their problem, struggle, or whatever is on their mind
2. AI (Groq/Llama) analyzes the text and matches it with the most fitting Heracles labor
3. The app presents:
   - **Mythological story** — the full myth behind the matched labor
   - **Adlerian psychological interpretation** — deep analysis using Adler's concepts
   - **AI-generated personal analysis** — tailored specifically to the user's words
   - **3 actionable steps** — concrete things to do today
   - **Reflection question** — for deeper self-exploration

## The 12 Labors

| # | Labor | Theme |
|---|-------|-------|
| 1 | Nemean Lion | Fear, courage, first step |
| 2 | Lernaean Hydra | Recurring problems, cycles |
| 3 | Ceryneian Hind | Patience, unreachable goals |
| 4 | Erymanthian Boar | Anger, loss of control |
| 5 | Augean Stables | Chaos, procrastination, disorder |
| 6 | Stymphalian Birds | Distraction, noise, social pressure |
| 7 | Cretan Bull | Obsession, addiction |
| 8 | Mares of Diomedes | Toxic patterns, harmful environments |
| 9 | Belt of Hippolyta | Broken trust, miscommunication |
| 10 | Cattle of Geryon | Comfort zone, fear of change |
| 11 | Apples of Hesperides | Feeling stuck, asking for help |
| 12 | Cerberus | Loss, darkness, meaninglessness |

## Adlerian Psychology Concepts Used

- **Inferiority Feeling** (Minderwertigkeitsgefühl) — the universal engine of growth
- **Striving for Superiority** (Überlegenheitsstreben) — healthy vs unhealthy compensation
- **Lifestyle** (Lebensstil) — childhood patterns shaping adult behavior
- **Fictional Finalism** (fiktiver Finalismus) — future goals directing present behavior
- **Life Tasks** (Lebensaufgaben) — work, love, community
- **Social Interest** (Gemeinschaftsgefühl) — the measure of psychological health
- **Courage** (Mut) — acting without perfection
- **Private Logic** (Privatlogik) — self-told stories that don't match reality
- **Creative Power** (schöpferische Kraft) — humans as creators, not victims
- **Encouragement** (Ermutigung) — the most powerful therapeutic tool

## Tech Stack

- **Frontend:** React + Vite
- **AI:** Groq API (Llama 3.3 70B)
- **Backend:** Netlify Functions (serverless)
- **Hosting:** Netlify
- **Languages:** Turkish & English (TR/EN toggle)


## Local Development

```bash
npm install
npm run dev
```

Note: AI features require Netlify Functions. For local AI testing, use `netlify dev`.

## Deployment

1. Push to GitHub
2. Connect repo to Netlify
3. Add `GROQ_API_KEY` in Netlify → Site configuration → Environment variables
4. Deploy

---

**Design by Mazlum ATİLA**
