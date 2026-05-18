# FUTURE_PE_02 — AI Content Marketing using UGC Ads

**Internship:** Future Interns — Prompt Engineering Track
**Intern:** Eedhi Venkata Sai Varshith
**CIN:** FIT/APR26/PE2489
**Task:** Task 2 — AI Content Marketing using UGC Ads

---

## Brand Chosen

**GlowLab Skincare**
*A D2C skincare brand selling science-backed, minimalist skincare products online across India.*

**Hero Product:** GlowLab Vitamin C Brightening Serum
**Target Audience:** Women aged 18–35 in Tier 1 & Tier 2 Indian cities dealing with dullness, uneven skin tone, and dark spots
**Platform Focus:** Instagram Reels, Facebook Ads, YouTube Shorts

A realistic D2C brand created to demonstrate how structured AI prompts can generate high-converting UGC ad content — the same type of work real content marketing agencies produce for paying clients.

---

## What is UGC-Style Ad Content?

UGC (User Generated Content) ads are short-form videos or scripts that:
- **Look** like honest customer reviews, not polished brand ads
- **Sound** like a real person sharing their experience
- **Convert** better than traditional ads because they build instant trust

---

## Prompt Logic & Variable System

All prompts use a modular variable system — swap values to generate UGC ads for any brand:

| Variable | Example Value |
|---|---|
| `{{brand_name}}` | GlowLab Skincare |
| `{{product_name}}` | Vitamin C Brightening Serum |
| `{{product_benefit}}` | Visibly brighter skin in 14 days |
| `{{target_audience}}` | Women 18–35 with dull skin or dark spots |
| `{{pain_point}}` | Dull, uneven skin tone despite trying many products |
| `{{platform}}` | Instagram Reels |
| `{{tone}}` | Honest, relatable, conversational — like a friend's recommendation |
| `{{cta}}` | Link in bio / Use code GLOW20 for 20% off |

---

## Ad Framework Used

All scripts follow the proven **Problem → Agitate → Solution → CTA** framework:

```
HOOK         → Stop the scroll (first 3 seconds)
PROBLEM      → Identify the pain point the viewer feels
AGITATE      → Make it relatable ("I tried everything...")
SOLUTION     → Introduce the product naturally
PROOF        → Add a result or trust signal
CTA          → Clear, low-friction call to action
```

---

## Conversion Strategy — Why These Scripts Work

| Technique | Where Applied | Why It Converts |
|---|---|---|
| **Pattern Interrupt Hook** | Opening line | Stops the scroll before viewer swipes away |
| **Pain Point Mirroring** | Problem section | Viewer feels "this is about me" |
| **Social Proof Language** | Result claims | "14 days", "dermatologist-tested" builds credibility |
| **Authentic Tone** | Full script | Sounds like a real person, not a brand |
| **Urgency + Offer** | CTA | Discount code creates immediate action |
| **Platform Adaptation** | Script length/style | Reels vs Shorts vs Facebook have different viewer behavior |

---

## Repository Structure

```
FUTURE_PE_02/
├── README.md
├── prompts/
│   ├── 01_hooks_prompt.md         ← Prompt for generating multiple hooks
│   ├── 02_ugc_scripts_prompt.md   ← Prompt for full ad scripts
│   └── 03_captions_cta_prompt.md  ← Prompt for captions and CTAs
├── outputs/
│   ├── 01_hooks_output.md         ← 8 generated hooks
│   ├── 02_ugc_scripts_output.md   ← 3 full platform-specific ad scripts
│   └── 03_captions_cta_output.md  ← Captions and CTAs for each platform
└── website_preview/
    └── index.html                 ← Visual UGC Ad Content Pack preview
```

---

## Adaptability — Reuse for Any Brand

### 💪 Fitness Supplement Brand
```
{{brand_name}} = MuscleForge
{{product_name}} = Whey Protein Isolate
{{pain_point}} = Not seeing results despite months of training
{{tone}} = Energetic, gym-bro authentic, results-driven
```

### 💆 Local Salon
```
{{brand_name}} = Glamour & Glow Studio
{{product_name}} = Keratin Hair Treatment
{{pain_point}} = Frizzy, unmanageable hair every single morning
{{tone}} = Friendly, relatable, before/after storytelling
```

### 🧘 Wellness SaaS App
```
{{brand_name}} = CalmPath
{{product_name}} = Guided Meditation App
{{pain_point}} = Constant anxiety, can't sleep, brain won't switch off
{{tone}} = Soft, empathetic, calming
```

---

## How to Reuse for a New Client

1. Open any prompt file in `/prompts/`
2. Replace all `{{variables}}` with your client's details
3. Paste into Claude, ChatGPT, or Gemini
4. Refine outputs and organize into a Content Pack
5. Deliver to client or upload to ad manager

**Total time to generate a full UGC Ad Pack for a new client: under 15 minutes.**
