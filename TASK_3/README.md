# FUTURE_PE_03 — AI SEO Blog & Content Cluster Generator

**Internship:** Future Interns — Prompt Engineering Track
**Intern:** Eedhi Venkata Sai Varshith
**CIN:** FIT/APR26/PE2489
**Task:** Task 3 — AI SEO Blog & Content Cluster Generator for Business Websites

---

## Business Chosen

**Velvet Touch Salon & Spa**
*A premium full-service salon and spa located in Hyderabad, Telangana.*

A realistic local business created to demonstrate how structured AI prompts can generate a complete SEO content cluster — the same strategy used by professional SEO agencies for local business clients.

---

## What is a Content Cluster?

A content cluster is a group of interlinked blog articles that together help a website rank for multiple related keywords:

```
PILLAR BLOG (Main Article)
"Best Salon in Hyderabad – Services, Prices & What to Expect"
        |
        ├── Supporting Blog 1: Bridal Makeup in Hyderabad
        ├── Supporting Blog 2: Keratin Hair Treatment Cost Hyderabad
        ├── Supporting Blog 3: Best Facials for Indian Skin
        ├── Supporting Blog 4: How to Choose a Salon in Hyderabad
        └── Supporting Blog 5: Self-Care Routine for Working Women
```

All blogs link back to the pillar and to each other — building topical authority on Google.

---

## Keyword Strategy

| Blog | Primary Keyword | Search Intent | Monthly Volume (Est.) |
|---|---|---|---|
| Pillar Blog | best salon in Hyderabad | Navigational + Commercial | High |
| Supporting 1 | bridal makeup in Hyderabad | Commercial | High |
| Supporting 2 | keratin hair treatment cost Hyderabad | Commercial | Medium |
| Supporting 3 | best facial for Indian skin | Informational | High |
| Supporting 4 | how to choose a salon | Informational | Medium |
| Supporting 5 | self-care routine for working women | Informational | Medium |

---

## Prompt Logic & Variable System

All prompts use a modular `{{variable}}` system — swap values to generate SEO content for any business:

| Variable | Example Value |
|---|---|
| `{{business_name}}` | Velvet Touch Salon & Spa |
| `{{business_type}}` | Premium full-service salon and spa |
| `{{location}}` | Hyderabad, Telangana |
| `{{primary_keyword}}` | best salon in Hyderabad |
| `{{target_audience}}` | Women 20–45 in Hyderabad looking for salon services |
| `{{services}}` | Hair, bridal, facials, spa, nail art |
| `{{tone}}` | Helpful, warm, expert — like advice from a beauty professional |

---

## SEO Strategy — How This Content Ranks

| Technique | Applied Where | SEO Impact |
|---|---|---|
| **Keyword in H1** | Every blog title | Tells Google what the page is about |
| **Local modifiers** | "in Hyderabad" in headings | Targets local search intent |
| **H2/H3 structure** | All blogs | Improves crawlability and featured snippets |
| **Internal linking** | Each blog links to pillar + others | Builds topical authority |
| **Search intent match** | Informational vs Commercial blogs | Reduces bounce rate |
| **FAQ sections** | Supporting blogs | Targets "People Also Ask" on Google |

---

## Repository Structure

```
FUTURE_PE_03/
├── README.md
├── prompts/
│   ├── 01_pillar_blog_prompt.md        ← Prompt for main pillar article
│   ├── 02_supporting_blogs_prompt.md   ← Prompt for content cluster blogs
│   └── 03_local_seo_prompt.md          ← Prompt for local SEO optimization
├── outputs/
│   ├── pillar/
│   │   └── 01_pillar_blog.md           ← Full pillar blog article
│   └── supporting_blogs/
│       ├── 02_bridal_makeup.md
│       ├── 03_keratin_treatment.md
│       ├── 04_best_facials.md
│       ├── 05_how_to_choose_salon.md
│       └── 06_self_care_routine.md
└── website_preview/
    └── index.html                      ← Visual SEO Content Pack preview
```

---

## Adaptability — Reuse for Any Business

### 🦷 Dental Clinic (Hyderabad)
```
{{business_name}} = SmileCare Dental Clinic
{{primary_keyword}} = best dental clinic in Hyderabad
{{services}} = teeth whitening, implants, braces, root canal
{{tone}} = Professional, reassuring, medically credible
```

### 📚 Coaching Institute (Hyderabad)
```
{{business_name}} = BrightPath Academy
{{primary_keyword}} = best JEE coaching in Hyderabad
{{services}} = JEE, NEET, foundation, crash courses
{{tone}} = Motivating, results-focused, parent-friendly
```

### 💻 Digital Marketing Agency (Hyderabad)
```
{{business_name}} = PixelGrow Digital
{{primary_keyword}} = digital marketing agency in Hyderabad
{{services}} = SEO, social media, PPC, web design
{{tone}} = Professional, data-driven, results-oriented
```

---

## How to Reuse for a New Client

1. Open any prompt in `/prompts/`
2. Replace all `{{variables}}` with your client's details
3. Paste into Claude, ChatGPT, or Gemini
4. Format output in Google Docs or Notion
5. Upload to client's website CMS

**Total time to generate a full SEO Content Pack for a new client: under 20 minutes.**
