# FUTURE_PE_01 — AI Website Copy Generator for Local Businesses

**Internship:** Future Interns — Prompt Engineering Track
**Intern:** Eedhi Venkata Sai Varshith
**CIN:** FIT/APR26/PE2489
**Task:** Task 1 — AI Website Copy Generator for Local Businesses

---

## Business Chosen

**Brewed & Beloved Café**
*A cozy specialty coffee café and all-day brunch spot located in Hyderabad, Telangana.*

A realistic local business created to demonstrate how structured AI prompts can generate professional, conversion-focused website copy that a real café owner or web agency could use immediately.

---

## Prompt Logic

The prompt system is built around 4 core principles:

1. **Role Assignment** — The AI is given a specific role ("You are a professional website copywriter specializing in local businesses...") to anchor tone and expertise.
2. **Business Context Injection** — Key business details are injected via variables into every prompt to avoid generic output.
3. **Section-Specific Instructions** — Each section (Homepage, Services, CTA) has its own dedicated prompt with clear output requirements.
4. **Tone Directive** — A tone parameter is explicitly stated so the output matches the business personality.

All prompts follow this modular structure:

```
[ROLE] + [BUSINESS CONTEXT VARIABLES] + [SECTION GOAL] + [TONE] + [OUTPUT FORMAT]
```

### Variable System (Reusable for Any Client)

Every prompt uses the following input variables. Simply swap values to generate copy for a new business:

| Variable | Example Value |
|---|---|
| `{{business_name}}` | Brewed & Beloved Café |
| `{{business_type}}` | Specialty coffee café and all-day brunch spot |
| `{{location}}` | Hyderabad, Telangana |
| `{{target_audience}}` | Young professionals, students, remote workers, families |
| `{{usp_1}}` | Single-origin specialty coffee |
| `{{usp_2}}` | All-day brunch with locally sourced ingredients |
| `{{usp_3}}` | Work-friendly space with Wi-Fi and charging points |
| `{{tone}}` | Warm, friendly, inviting — like a message from a trusted friend |

---

## Tool Used

- **Claude (claude.ai)** — Primary AI tool for all copy generation
- **Prompt Design** — Structured manually by intern using modular variable system

---

## Conversion Strategy — Why This Copy Works

Each section is engineered using specific copywriting techniques:

| Technique | Where Applied | Why It Converts |
|---|---|---|
| **Emotional Positioning** | Hero headline & intro | Connects with identity ("go-getters, dreamers") before selling a product |
| **Sensory Language** | Services copy | "Perfectly runny eggs", "punchy cold brew" — triggers appetite and desire |
| **Community Language** | CTA sections | "We've been expecting you" feels like belonging, not a transaction |
| **Trust Microcopy** | Footer & booking CTA | "No booking fee. Cancel anytime." removes purchase anxiety |
| **Local Relevance** | Address, audience | City-specific references build authenticity and local trust |

---

## Example Adaptations — Reuse These Prompts for Any Business

The same prompt framework works for any local business. Just change the variables:

### 🧖 Salon (Glamour & Glow Studio, Chennai, Tamilnadu)
```
{{business_name}} = Glamour & Glow Studio
{{business_type}} = Premium ladies salon and beauty parlour
{{location}} = Chennai, Tamilnadu
{{tone}} = Confident, empowering, glamorous
{{usp_1}} = Expert stylists with 10+ years experience
{{usp_2}} = Bridal and occasion packages
{{usp_3}} = Walk-in friendly, no appointment needed
```

### 🏥 Clinic (ClearCare Diagnostics, Visakhapatnam, Andhra Pradesh)
```
{{business_name}} = ClearCare Diagnostics
{{business_type}} = Full-body diagnostic and health checkup center
{{location}} = Visakhapatnam, Andhra Pradesh
{{tone}} = Professional, reassuring, clear
{{usp_1}} = Same-day reports for 200+ tests
{{usp_2}} = NABL accredited lab
{{usp_3}} = Home sample collection available
```

### 📚 Coaching Institute (BrightPath Academy, Pune, Maharashtra)
```
{{business_name}} = BrightPath Academy
{{business_type}} = JEE and NEET coaching institute
{{location}} = Pune, Maharashtra
{{tone}} = Motivating, results-focused, parent-friendly
{{usp_1}} = 95% success rate over 8 years
{{usp_2}} = Small batch sizes (max 20 students)
{{usp_3}} = Free demo class, no commitment
```

---

## Repository Structure

```
FUTURE_PE_01/
├── README.md                  ← This file
├── prompts/
│   ├── 01_homepage_prompt.md  ← Modular prompt for homepage copy
│   ├── 02_services_prompt.md  ← Modular prompt for services page
│   └── 03_cta_prompt.md       ← Modular prompt for CTA sections
├── outputs/
│   ├── 01_homepage_copy.md    ← Generated homepage copy
│   ├── 02_services_copy.md    ← Generated services page copy
│   └── 03_cta_copy.md         ← Generated CTA sections
└── website_preview/
    └── index.html             ← Visual HTML preview of full website
```

---

## How to Reuse for a New Client

1. Open any prompt file in `/prompts/`
2. Replace all `{{variables}}` with your client's details
3. Paste into Claude, ChatGPT, or Gemini
4. Copy output into your website builder (Framer, Webflow, Lovable, etc.)
5. Repeat for homepage, services, and CTA sections

Total time to generate copy for a new client: **under 10 minutes.**
