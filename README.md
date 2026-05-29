# GIS Engineer Test Task — Amudar.io

Welcome — and thanks for your interest. We're hiring a **GIS Engineer (Geospatial + GeoAI)** to join [Amudar.io](https://amudar.io) in Tashkent. The full role and offer are in [JOB_DESCRIPTION.md](./JOB_DESCRIPTION.md) (English / Русский / Oʻzbekcha).

This exercise is **not** a coding task. We want to see how you think about a real geospatial system and how you'd use AI tools to ship one — not 40 hours of your weekend.

---

## Scenario — "FieldVision"

Amudar.io operates a network of weather and pest-trap stations across Uzbekistan. Around each station, a set of farmer fields with polygon boundaries is registered.

Design a system that **fuses satellite imagery with ground-station data** to produce a useful crop-monitoring product for the fields around each station.

A typical user story: a user opens our map, clicks a field, and sees the latest fused view — satellite-derived signals combined with the station's local weather — plus a periodic plain-language summary they can read in under a minute.

### Constraints

- Small team. Cost-conscious.
- Must be cheap to re-run over several years of historical data.
- A problem with one field must not break the rest of the platform.

**You choose the tech stack, the data sources, the indices, the storage, and the modeling approach — everything.** The task is open-ended on purpose.

---

## Deliverables (bare minimum)

1. **Architecture diagram** — PNG / SVG / Excalidraw / draw.io / Miro link. Your choice of tool.
2. **Mockup screens** of how the end user sees this system — hand-sketched wireframes on paper, an AI-generated mockup, or anything in between. We don't care about polish; we care about whether the screen tells a real user something useful.
3. **Written explanation** (2–3 paragraphs) — focus on **what the end user can learn from this system** and **how it helps them make day-to-day decisions**. Tell the story from the user's seat, not from the engineer's.
4. **Key metrics to monitor** — what you'd watch to know the pipeline is healthy.

Open-ended — no single right answer. We want to see how you make decisions.

We'll discuss the deeper system-design questions with you in person during the interview.

---

## What we evaluate

- Sensible trade-offs over fancy architecture.
- Understanding of failure modes.
- How you reason about cost and re-runnability for historical backfills.
- Clear writing and honest about what you don't know.

---

## How to submit

- Combine your diagram + mockup screens + writeup + metrics into a **single PDF or markdown document** (whichever you prefer).
- Send it to **info@amudar.io** *or* Telegram **[@s_abdullaev_uk](https://t.me/s_abdullaev_uk)**.
- Subject line: `GIS Engineer Test Task — [Your Name]`.
- Please mention roughly **how many hours** you spent on it. No deadline pressure.

---

## License

MIT — see [LICENSE](./LICENSE).
