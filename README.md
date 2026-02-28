# 🏝️ Anna.ai — AI Travel Planning App
### Designed by: Apurva Dange | Arizona State University

> *"Trip planning shouldn't feel like a second job. That was the first thing I wrote on my FigJam board when I started this project and honestly, that one sentence drove every single design decision after it."*

---

## What Is Anna.ai?

Anna.ai is an AI-powered mobile travel companion I designed from scratch: from the first sticky note on a FigJam board all the way to a high-fidelity Figma prototype.

The core idea is simple: right now, planning a trip is *exhausting*. You're jumping between Google Flights, Reddit, TripAdvisor, a group chat with your friends, and three different booking apps, all just to figure out where to go and how much it'll cost. Nobody has built one app that brings all of that together in a way that actually feels lightweight and easy to use.

That's the gap Anna.ai fills. One conversational AI that helps you find deals, plan your itinerary, split expenses with your group, and get travel inspiration but without the overwhelm.

**In this project I am covering:** Market Research → Competitive Analysis → User Interviews → Persona Building → Journey Mapping → Business Model Canvas → Lo-Fi Wireframes → Hi-Fi Prototype

---

## The Problem!

Before I designed anything, I needed to understand *why* trip planning is broken. Not assume but by actually understanding it.

When I looked at the current experience, the friction points were everywhere. Users are spending hours across multiple platforms with zero continuity between them. There is no single place where you can discover a destination, check if flights are affordable, coordinate with your travel group, and split the final bill. Every one of those tasks lives in a different app.

And here is the thing about friction which I understood over the years in technology innovation and entrepreneurship  — in product thinking, we know that every extra step between a user and their goal is a drop-off risk. Every unnecessary decision costs cognitive load. The travel planning experience today is basically one long chain of unnecessary decisions that nobody has bothered to simplify.

So the product question I started with was: **what is the minimum number of interactions a user needs to go from "I want to go somewhere" to "my trip is booked and my group is synced"?**

Anna.ai is my answer to that question.

---

## Phase 1: Research — Understanding Before Designing

I want to be clear about something, I did not start designing screens first. I know that is tempting, especially when you already have ideas, but I have learned that the most dangerous thing a designer or PM can do is fall in love with their solution before they have validated the problem. So I spent a good chunk of this project just researching.

---

### Market Research (is this idea worth it?)

The first thing I wanted to know was: is this even a real market opportunity, or is it just a personal frustration?

Turns out, it is a massive opportunity.

The AI in Travel and Tourism market is sitting at **$2.95 billion in 2024 and is projected to hit $13.38 billion by 2030.** That is not slow growth. That is a 4.5x increase in 6 years. The market signal is loud and clear which is that travelers want AI assistance, and the current solutions are not fully delivering yet.

A few more data points that shaped my thinking:
- **60%** of travelers are already open to using AI for trip planning
- **40%** of what I call "experimenter" travelers are actively testing AI tools right now
- **20%** of millennials already rely on AI-generated itineraries

And when I looked at where AI is being applied in travel, there are three main areas: **itinerary generators, chatbots, and dynamic pricing**. The interesting thing is that nobody has connected all three into one coherent user experience yet and I saw this as an big opportunity.

*Research tools I used: Statista, Google Search, Reddit, Google Gemini*

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/strategy/Market%20research%20ai%20help.png?raw=true" 
       alt="Market Research Board" width="80%" />
</p>

---

### Competitive Analysis — What Is Already Out There in the MARKET?

I analyzed six competitors. I did not just look at features — I looked at their *strategic positioning*, what user segment they were going after, and most importantly, **where each of them was leaving value on the table.**

| Competitor | Their Angle | What They're Missing |
|---|---|---|
| **Mindtrip** | Socially-driven AI — blends group chat with shared itineraries | No automated deal-finding, no expense splitting |
| **Layla** | Instant AI itineraries, handles complex multi-stop routing | Limited social/community features, fewer real traveler photos |
| **Pilot** | "Notion for trips" — collaborative planning with PDF export | Heavy for simple trips, no coupon or deal finder built in |
| **Skoot** | Family-first, kid-safe travel booking with destination comparisons | Very narrow audience appeal, deals interface not mature |
| **Booked AI** | Automated bargain hunting with a conversational agent feel | Zero community or inspiration feed |
| **GuideGeek** | Zero-install WhatsApp/Instagram chatbot, great for quick local tips | Not a full itinerary builder, no cost-splitting or group tools |

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/strategy/competitor%20research.png?raw=true" 
       alt="Competitive Research Board" width="80%" />
</p>

After mapping all of this, I created a **Similarities, Differences, Learnings, and Opportunities** framework to synthesize the findings. This is something I think is really underrated in product work, most people do a competitive analysis and then move on. But the real gold is in the synthesis of: what patterns do you see, what can you learn from what everyone is doing *wrong*, and where is the white space?

**What I found everyone is doing the same:** All of them have some version of AI chat as the core UI, some form of itinerary generation, and some level of booking or deal integration.

**Where they are all different:** Audience focus, platform scope, and how deep the deal-finding actually goes.

**Key Learnings:** Users love AI for research but hate cluttered UIs. They want to share trip plans with the people they travel with. And they strongly prefer lightweight apps that are fast and simple over power-packed platforms that feel like work.

**Opportunities I identified:** Mood-based trip filters (Beach Vibes, Roadtrip, Casino mode, etc.), a coupon finder built directly into the AI flow, a WhatsApp chatbot extension, real-time expense tracking, and even an AR destination preview for places you're considering.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/strategy/similarities%2C%20differences%2C%20opportunities%2C%20etc.png?raw=true" 
       alt="Similarities Differences Learnings Opportunities" width="80%" />
</p>

---

### User Research - where facts meet the reality

Honestly, this was my favorite part of the whole project. I went on-campus at ASU and conducted real interviews with people who actually travel eg, students, professors, families, and international students. I wanted to learn the real stories about real trips that went well and trips that didn't.

I designed 17 open-ended interview questions specifically to avoid leading the participant toward any particular answer. I learned early on that if you ask "do you find trip planning stressful?" you are going to get "yes" because that is a leading question. It feeds them the answer. Instead, I anchored my questions in their past behavior rather than hypothetical future promises. I asked things like "tell me about a trip that didn't go well, what happened?" because users are highly reliable historians of their own past pain, but terrible at predicting what they might do in the future.

During the sessions, I leaned into core UX techniques to get bottom of the ocean full of opportunities to solve these painpoints. I learned to embrace the "awkward pause"—simply waiting a few seconds after a participant answered. People naturally want to fill the silence, and that is usually when they dropped their guard and revealed deeper emotional frustrations. When they mentioned a specific pain point, I used the "Five Whys" technique to drill down to the root cause, rather than just accepting the first thing they said.

One of the most valuable things I looked for during these interviews were "workarounds." If someone told me they had to use three different apps, take a screenshot, and text it to their partner/group of friends just to coordinate a flight, I paid close attention. Whenever a user uses their own manual solution, it means the problem is painful enough that they are actively spending time trying to solve it. Those are the massive neon signs pointing to real product opportunities.

After wrapping up the interviews, I had ton of raw qualitative data. To make sense of it all and turn it into actionable insights, I used affinity mapping. I pulled out the most impactful quotes and observations, grouped them by theme, and looked for the overlaps. I wasn't just looking for what one person said but I was looking for the patterns across all the users. Those are the insights the one's which will connect the dots.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/strategy/user%20interview%20questions.png?raw=true" 
       alt="User Interview Questions" width="80%" />
</p>

From the interviews, I built **6 detailed user personas** — and I want to be clear that these are not made-up characters. These are AI-summarized versions of real people I actually spoke to on campus.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/strategy/User%20persona%20-%20ASU%20campus.png?raw=true" 
       alt="User Personas ASU Campus Overview" width="80%" />
</p>

Here is a quick look at who they are and what they each need:

| Persona | Who They Are | Their Core Pain Point | What Would Help Them |
|---|---|---|---|
| **Jordan** | Geography undergrad, travels solo or with 2-3 friends | Wants student discounts but finding them takes too long | Study-aligned itineraries, automatic student deal highlights |
| **Steve Choe** | Professor, extremely budget-conscious, avoids upsells | Gets overwhelmed by cluttered booking flows and abandons | Genuine bargains shown upfront, option to book by phone |
| **Meenakshi** | Mom of 2, family road trips | Managing 4 schedules, finding kid-safe activities on the road | Family activity filters, mapped driving routes, calendar sync |
| **Madhav** | International student, Vegas trips | Live USD-INR exchange rate matters every single decision | Currency conversion built into deal displays, loyalty point tracking |
| **Palak** | Travels with husband, books through agents | Needs "husband-approved" options, prefers agents for complex trips | Couple-friendly package filters, offline-printable itineraries |
| **Ankush** | Solo traveler, best friend trips, last-minute booker | Can't stand upsells or complicated checkout flows | Clean no-noise UI, sub-2-tap booking, last-minute solo deals |

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/strategy/user%20persona%20zoomed%20.png?raw=true" 
       alt="User Persona Zoomed Detail" width="80%" />
</p>

I also built **User Journey Maps** for four additional personas — Kristen, Gauri T, Diane Katz, and Jyoti — mapping their experience across five stages: Awareness, Consideration, Decision, Experience, and Post-Trip. For each stage I documented what they are doing, what they are feeling, where the pain points are, and where the opportunities for the product live.

This is something I feel strongly about: journey mapping is not a deliverable, it is a thinking tool. The point is not to make a pretty diagram — it is to find the moments where your user's expectations and their actual experience diverge the most. Those divergence points are where your product creates the most value.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/strategy/full%20figjam.png?raw=true" 
       alt="Full FigJam Brainstorming Board" width="80%" />
</p>

---

## 💡 Phase 2: Define — Translating Research Into a Product Direction

After all that research, I had a lot of information. The challenge now was: what do I actually *build*?

This is the phase that I think separates okay product thinking from great product thinking. It is easy to collect user feedback and build a feature list. It is hard to look at all that feedback and identify the *underlying need* that one elegant solution could address.

For Anna.ai, the underlying need was: **reduce the number of context switches a traveler has to make between discovery, planning, booking, and coordination.** Everything I designed flows from that.

---

### 🏗️ Business Model Canvas

Before designing any screens, I wanted to make sure the product could actually work as a business. A good product that has no viable business model is just an expensive side project.

Here is the full Business Model Canvas I built for Anna.ai:

| Section | Anna.ai's Answer |
|---|---|
| **Value Propositions** | Personalized AI itinerary · Group chats & trip coordination · Expense splitting · Coupon finder · Flight deal finder · Real-time price alerts · Voice interface · AR destination preview |
| **Customer Segments** | Solo travelers · Families · Friend groups · Business travelers · Budget travelers · Luxury travelers · Teens · Explorers |
| **Key Partnerships** | Airlines · Hotel chains · Tourism boards · Local guides · Influencer platforms · API providers |
| **Key Activities** | Itinerary generation · Data analysis · UX design · AI training · Platform integration · Customer support |
| **Key Resources** | LLM · Travel data APIs · Dev + QA team · Cloud infrastructure · User insights · Knowledge base |
| **Channels** | Mobile app · Web app · WhatsApp bot · App stores · Social media · Ads · Email · API |
| **Customer Relationships** | 24/7 in-app support · Push notifications · Email · Loyalty rewards · Social travel forum |
| **Revenue Streams** | Freemium subscriptions · Advertising · Commission on bookings |
| **Cost Structure** | Cloud hosting · Supabase · Data licenses · R&D · Marketing · API fees · Dev team · Infra |

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/strategy/BMC.png?raw=true" 
       alt="Business Model Canvas" width="80%" />
</p>

The revenue model I landed on — freemium + ads + commissions — is intentional. Freemium lowers the barrier to entry for budget travelers (a huge segment, as my personas showed). Commissions on bookings create alignment between Anna.ai and the user: we both benefit when they find and book the best deal. And ads, if done right, can actually be useful in a travel context (think targeted local experiences or partner promotions in a destination you're already researching).

---

## 🎨 Phase 3: Design — From Sketches to Screens

This is where all the research becomes something you can actually *see and touch*. I went through two rounds of design: lo-fidelity wireframes first to figure out the flows and structure, then hi-fidelity screens to make it feel like a real product.

---

### ✏️ Lo-Fidelity Wireframes

I sketched three primary user flows before touching Figma. The reason I do lo-fi first is not because it is faster — it is because low-fidelity thinking forces you to focus on *structure and flow* rather than getting distracted by colors and typography. You cannot hide a bad UX behind nice visuals in a pencil sketch.

**Flow 1 — Flight Deal Flow**

The user enters from login, navigates to the Flight Deals section, selects an AI agent (Cheap Flight Agent, Coupon Finder, Track Price Drops, or Flight Comparison), gets results, and confirms a booking.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/user%20workflow/Flight%20Deals%20User%20Flow.png?raw=true" 
       alt="Flight Deal User Flow Wireframe" width="80%" />
</p>

**Flow 2 — Sharing Trip Plan Flow**

User accesses their itinerary, taps the share option (triggered by voice or three-dot menu), selects contacts or a group trip, and confirms the share. This flow was specifically designed around one of my key research insights: travelers want to share plans with their travel companions without having to copy-paste or screenshot.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/user%20workflow/Sharing%20PLAN.png?raw=true" 
       alt="Sharing Plan Wireframe" width="80%" />
</p>

**Flow 3 — Trip Expense Split Flow**

User goes to My Trips, selects a trip, opens Trip Splits, sees the breakdown of who owes what, and either adds an expense or settles up. Clean, direct, no complexity.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/user%20workflow/Trip%20expense.png?raw=true" 
       alt="Trip Expense Wireframe" width="80%" />
</p>

---

### 📱 Hi-Fidelity Prototype — The Full Screen-by-Screen Breakdown

This is the part I am most proud of. The hi-fi prototype has 12+ screens and covers the full user journey from first open to post-trip. Here is what each screen is doing and *why* it was designed that way:

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/High%20fidelity%20wireframes/all%20frames.png?raw=true" 
       alt="All Frames Overview" width="100%" />
</p>

---

**Sign Up & Login Screen**

I kept this as clean as possible — just the essentials. Full name, email, password, and Google/Facebook SSO. The reason is simple: every extra field on a signup form is a drop-off risk. I wanted to minimize friction at the top of the funnel because acquiring a user who never completes onboarding is worse than not acquiring them at all.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/High%20fidelity%20wireframes/login%20screen.png?raw=true" 
       alt="Login and Sign Up Screens" width="80%" />
</p>

---

**AI Assistant + Slider Navigation**

The main experience is conversation-first. Anna is an AI you *talk to*, not a form you fill out. The dark slide-out navigation gives you access to Inspirations, My Chats, Trip Split, Flights Deals, Hotel Deals, and Search History — but it lives behind a hamburger menu so it does not clutter the primary experience.

The design principle here is **progressive disclosure**: show the user what they need right now and hide complexity until they actively ask for it.

---

**Inspirations Screen**

This is a Pinterest-style feed of destinations and travel content. But the difference from a regular inspiration board is that each destination card has a contextual AI Pro Tip embedded in it — for example, "Visit Fushimi Inari early in the morning to avoid the crowds."

I included this because my user research told me something interesting: travelers do not just want to know *where* to go, they want to feel like they are getting insider knowledge. That is the job of a good travel companion, and it is exactly what Anna should be doing.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/High%20fidelity%20wireframes/inspiration%20screen.png?raw=true" 
       alt="Inspiration Screen" width="80%" />
</p>

---

**My Trips Screen**

A dashboard showing upcoming and past trips. Each trip has a View Plan and Edit button. This is the central hub for the user's travel life — past, present, future. The design prioritizes upcoming trips at the top with a clear status badge (Upcoming / Past) so the most relevant information is always first.

---

**Trip Splits Screen**

This is probably the most underrated feature in the app and one I am really happy with. You see your group members, the total balance, what you are owed versus what you owe, broken down by expense. "Dinner at Shibuya — you are owed $80.00" — that level of clarity.

What I found in my research is that expense tracking in group trips is one of the *biggest* sources of friction and relationship tension. People avoid the conversation because it is awkward. Making it automated and transparent removes the awkwardness entirely. Good product design should dissolve social friction, not just functional friction.

---

**My Chats Screen**

Group and individual chat view, with three smart action buttons at the bottom: AI Summarizer, Create Expense, Create Poll. The AI Summarizer was a direct response to a user insight — when you are in a chaotic group travel chat, nobody wants to scroll back through 200 messages to find out if someone already confirmed the hotel. One tap and Anna summarizes the thread for you.

---

**Flight Deals Screen**

This is the deal-finding engine. You have four AI Travel Agents: Cheap Flight Agent, Coupon Finder, Track Price Drops, and Flight Comparison. Below that, you have Saved Flights and a Recently Used section.

The mental model I used here is exactly the same as a human travel agent — you do not call a travel agent and ask them to do everything at once, you call them for a specific job. The AI agents are designed around discrete jobs-to-be-done: find the cheapest option, apply a coupon, alert me when the price drops, compare carriers.

<p align="center">
  <img src="https://github.com/apurva-dange/anna_ai_pm_case_study/blob/main/High%20fidelity%20wireframes/flight%20deals%20.png?raw=true" 
       alt="Flight Deals Screen" width="80%" />
</p>

---

**Search History & Profile**

Search history is clearable and shows recent queries with enough context to understand what you were looking for without having to remember. Profile gives you Settings, Payment Methods, Travel Preferences, and Help — nothing excessive.

---

## 🛠️ Tools I Used

- **Figma** — Hi-fi prototype and screen design
- **FigJam** — The full research board: competitive analysis, user personas, journey maps, BMC, wireframes
- **Statista + Google Search + Reddit** — Market sizing and trend research
- **Google Gemini** — Secondary research synthesis
- **On-campus ASU interviews** — Primary qualitative user research

---

## 🧠 What I Learned From This Project

I want to be honest here — I started this project thinking I already knew what the app should do. I've planned enough trips to know the pain. But the research genuinely surprised me and changed the design.

I did not know how differently a budget-focused international student and a family traveler think about the same trip. I did not realize that the *post-trip memory sharing* experience was something users cared so much about. I did not expect that several users would say the most important thing to them is just being able to trust the information they're getting.

Those insights came from the research. Not from me sitting at my desk making assumptions.

If there is one thing I would tell anyone building a product — spend more time in the problem space than you think you need to. The design phase is actually the easy part once you deeply understand who you are designing for and what they are trying to do.

---

## 🔗 Links

- 🎨 **Figma Prototype:** *[Add link here]*
- 📋 **FigJam Research Board:** *[Add link here]*
- 📄 **Case Study Presentation:** *[Add link here]*

---

## 👤 About Me

**Apurva Annasaheb Dange**
*Arizona State University — MS Information Technology*
Interested in product management, UX design, and building things people actually want to use.

---

> *"I didn't just design an app — I figured out why trip planning is broken, talked to real people about it, mapped the whole system, and then designed a solution that addresses the actual root cause. That is what this project is about."*
