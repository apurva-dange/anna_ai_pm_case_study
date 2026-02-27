# Anna AI (End-to-End Travel Planner)

This repository contains the complete "Anna AI" product build, documenting its journey from a basic idea to a research-driven, user-focused solution.

## What's Inside:

* Concept Deck
* Market & Competitor Analysis
* Product Requirements Document (PRD)
* User Stories & Feature Mapping
* Wireframes (Low and High Fidelity)
* Figma Designs
* Full Product Roadmap


# Anna AI (MVP) — Travel planning that feels like texting a friend

<p align="center">
  <img src="assets/anna-ai-hero.png" width="600" alt="Anna AI hero banner showing the product name and a simple tagline">
  <br>
  <em>Figure: The “why” in one line — Anna AI helps you go from messy travel ideas to a real plan, fast.</em>
</p>

## The Vision (Executive Summary)

Anna AI is a travel planning MVP that turns vague plans like “I want a chill weekend in LA” into a clear itinerary you can actually use.

Here’s the problem it solves: planning trips is weirdly exhausting. You open 15 tabs, get lost in options, and still don’t know what to book or what to do first.

Anna AI is for people who want **a plan that matches their vibe**, without spending hours researching. It helps you:
- pick the right area to stay
- build a realistic day-by-day itinerary
- keep everything organized in one place
- adjust on the fly when your priorities change

This project is my flagship portfolio build because it’s a real product problem: clear **pain points**, real **market research**, practical **user flows**, and a focused **prioritization** mindset to ship an MVP that actually works.

---

## The Problem & Discovery

### What we observed (the real problem, not the surface one)

People don’t just struggle with “finding places.” They struggle with:
- **decision fatigue**: too many options, no confident next step
- **planning anxiety**: fear of choosing the wrong place / wasting money
- **fragmentation**: info scattered across Notes, Maps, TikTok, group chats, and bookings
- **time mismatch**: plans that look good online but don’t fit real time, distance, or energy

In user interviews, a pattern kept repeating:
> “I’m not lazy. I just don’t want to plan a second full-time job.”

<p align="center">
  <img src="assets/user-quotes-collage.png" width="600" alt="A collage of 4 to 6 short user quotes about travel planning frustrations">
  <br>
  <em>Figure: Real interview snippets — the strongest signals behind our MVP decisions.</em>
</p>

---

### Market research (what we learned before building)

We looked at how people plan trips today:
- Google search + blogs for “best things to do”
- TikTok/Instagram saves for inspiration
- Maps for distance planning
- Booking sites for hotels and flights
- Notion/Docs/Notes to stitch it together

The big insight: existing tools help with **pieces** of planning, but not the **full journey** from idea → itinerary → action.

---

### Competitive audit (what’s missing in current solutions)

We reviewed common categories of travel tools:
- **Trip aggregators**: good for booking, weak at personalization
- **Itinerary builders**: structured, but often manual and time-consuming
- **AI chat tools**: fast ideas, but not organized, not “plan-ready”
- **Content platforms**: great inspiration, poor execution path

The gap we chose to own:
**A product that creates a plan you can follow**, not just suggestions you scroll past.

<p align="center">
  <img src="assets/competitive-audit-matrix.png" width="600" alt="Simple matrix comparing 5 to 7 competitors across personalization, structure, usability, and effort">
  <br>
  <em>Figure: Competitive audit summary — we built where the overlap was weakest: personalized + structured + low effort.</em>
</p>

---

## Who We Are Building For (Personas)

### Persona 1: The Busy Planner
**Goal:** “Give me a good plan quickly. I’ll pay for convenience with my time.”

**Frustrations we’re fixing:**
- hates opening 20 tabs
- wants a default plan they can tweak
- needs travel decisions broken into steps

<p align="center">
  <img src="assets/persona-busy-planner.png" width="600" alt="Persona card for Busy Planner with goals, frustrations, and behaviors">
  <br>
  <em>Figure: Persona 1 — we optimized the user flow for speed and clarity.</em>
</p>

---

### Persona 2: The Vibe-First Traveler
**Goal:** “I want the trip to feel like me.”

**Frustrations we’re fixing:**
- generic recommendations feel wrong
- doesn’t know which neighborhood matches their vibe
- wants day plans based on energy (chill vs packed)

<p align="center">
  <img src="assets/persona-vibe-first.png" width="600" alt="Persona card for Vibe-First Traveler with goals, frustrations, and behaviors">
  <br>
  <em>Figure: Persona 2 — this is why personalization is a core MVP requirement, not a nice-to-have.</em>
</p>

---

### Persona 3: The Group Trip Coordinator
**Goal:** “I just want fewer arguments and fewer last-minute changes.”

**Frustrations we’re fixing:**
- planning becomes coordination chaos
- people share random links but nobody decides
- itinerary changes constantly

<p align="center">
  <img src="assets/persona-group-coordinator.png" width="600" alt="Persona card for Group Trip Coordinator with goals, frustrations, and behaviors">
  <br>
  <em>Figure: Persona 3 — we designed the MVP to reduce back-and-forth, not increase it.</em>
</p>

---

## Connecting the Dots (Strategy & User Flow)

### Strategy (how we translated needs into product decisions)

We kept the strategy simple:
1. **Reduce decision fatigue** with guided inputs and clear defaults.
2. **Make it personal** by capturing vibe + constraints early.
3. **Make it actionable** with an itinerary that respects time + distance.
4. **Make it editable** because travel plans always change.

This is where prioritization mattered. We didn’t try to build “everything travel.”
We focused on the core user flow that delivers value in the first 2 minutes.

---

### Core user flow (MVP)

**Step 1: Quick intake**
- destination, dates, budget range
- travel style (foodie, nature, nightlife, relaxed, etc.)
- constraints (walking tolerance, must-do places, dietary needs)

**Step 2: Plan generation**
- recommended areas to stay (with reasons)
- day-by-day itinerary with realistic pacing
- optional swaps: “more chill” / “more packed”

**Step 3: Save + refine**
- edit blocks, reorder, lock must-dos
- export/share (simple format)

<p align="center">
  <img src="assets/user-flow-diagram.png" width="600" alt="User flow diagram from onboarding to itinerary generation to saving and editing">
  <br>
  <em>Figure: The MVP user flow — we optimized for speed, clarity, and easy edits.</em>
</p>

---

### What we deliberately did NOT build (yet)

This was a hard prioritization call:
- full booking engine
- real-time pricing comparison
- social feed / travel content discovery
- “perfect” personalization models

Those can come later. For the MVP, the goal is simple:
**turn messy intent into a plan you can use.**

---

## Bringing it to Life (Wireframes to MVP)

### 1) Low-fidelity sketches (fast learning)

We started with low-fidelity wireframes to test:
- Do users prefer a “chat-first” flow or a “form-first” flow?
- What inputs feel natural vs annoying?
- How much structure is helpful before it feels restrictive?

The biggest learning:
Users want freedom, but they also want guidance.
So we designed a hybrid: guided intake + conversational refinements.

<p align="center">
  <img src="assets/lofi-wireframes.png" width="600" alt="Low-fidelity wireframes showing onboarding and a rough itinerary screen">
  <br>
  <em>Figure: Low-fi wireframes — quick experiments to validate the user flow before polishing UI.</em>
</p>

---

### 2) Mid-fidelity wireframes (locking layout + logic)

At this stage we focused on:
- clear hierarchy (what matters first)
- a scannable itinerary (not paragraphs)
- editability without breaking the plan

We iterated heavily on the itinerary screen.
Because if that screen isn’t great, the product doesn’t matter.

<p align="center">
  <img src="assets/midfi-itinerary-iterations.png" width="600" alt="3 to 5 mid-fidelity itinerary layout options side by side">
  <br>
  <em>Figure: Itinerary layout iterations — we kept what users scanned fastest and removed the rest.</em>
</p>

---

### 3) High-fidelity designs (final MVP experience)

The final high-fidelity MVP design focused on:
- a calm interface (planning should feel lighter, not heavier)
- strong defaults with easy customization
- transparency: “why Anna chose this” for trust

<p align="center">
  <img src="assets/hifi-mvp-screens.png" width="600" alt="High-fidelity screens of onboarding, preferences, itinerary, and edit flow">
  <br>
  <em>Figure: High-fidelity MVP — the full journey from inputs to a usable itinerary.</em>
</p>

---

### MVP scope (what we shipped)

**Included**
- guided intake (vibe + constraints)
- itinerary generation (day-by-day)
- stay-area suggestions (with reasons)
- quick edit actions (swap, reorder, regenerate section)
- save/export (basic)

**Not included**
- bookings
- real-time price tracking
- group voting
- offline mode

<p align="center">
  <img src="assets/mvp-scope.png" width="600" alt="MVP scope table showing included vs not included features">
  <br>
  <em>Figure: MVP scope — what we shipped vs what we intentionally cut to move faster.</em>
</p>

---

## What’s Next (Roadmap)

This roadmap is based on early user feedback and the next layer of prioritization.

### Near-term (next 2–4 weeks)
- **Better editing controls** (drag/drop blocks, lock time windows)
- **Neighborhood matching** (show 2–3 options with pros/cons)
- **Smarter pacing** (less rushing, more “real travel time” built in)
- **Export improvements** (Google Maps links, calendar format)

<p align="center">
  <img src="assets/roadmap-near-term.png" width="600" alt="Roadmap board showing near-term features and why they matter">
  <br>
  <em>Figure: Near-term roadmap — based on what users asked for repeatedly.</em>
</p>

---

### Mid-term
- **Collaboration for group trips** (share + comment + decision prompts)
- **Saved preferences** (repeat travelers shouldn’t re-enter everything)
- **Trip templates** (weekend, 5-day, work trip, budget trip)

---

### Longer-term
- **Live data integrations** (hours, closures, events, reservations)
- **Personalization engine** (learn from your edits over time)
- **Destination packs** (curated, local-feeling plans)

<p align="center">
  <img src="assets/roadmap-long-term.png" width="600" alt="Long-term roadmap showing themes like collaboration, integrations, and personalization">
  <br>
  <em>Figure: Longer-term vision — expanding capability without losing the simple core user flow.</em>
</p>

---

## How to Use This Repo

> Replace this section with your actual stack + commands once you paste them in.
> I’m keeping it clean so hiring managers can scan it fast.

### MVP Demo
<p align="center">
  <img src="assets/mvp-demo.gif" width="600" alt="Animated demo of the MVP user flow from intake to itinerary">
  <br>
  <em>Figure: MVP demo — the end-to-end experience in under 30 seconds.</em>
</p>

### Tech (MVP)
- Frontend: **[Add framework here]**
- Backend: **[Add backend here]**
- AI/LLM: **[Add model + orchestration here]**
- Database: **[Add DB here]**
- Hosting: **[Add hosting here]**

### Run locally
```bash
# 1) clone
git clone https://github.com/<your-username>/anna-ai.git
cd anna-ai

# 2) install
# (add your real commands)
npm install

# 3) run
npm run dev
