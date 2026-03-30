# Companion Website & Promotional Materials Plan

**Book:** Entrepreneurship in the Age of AI and Web3 — Building Ventures in the Decentralized AI Internet
**Author:** Zishan A. Mohammad
**Plan Date:** March 30, 2026
**Target Launch:** Before SAGE proposal submission (mid-April 2026)

---

## 1. Strategic Purpose

This companion website serves two audiences simultaneously:

**For SAGE editors:** A live demonstration of the author's commitment to digital companion resources (directly addressing SAGE Requirement #8 — Online Teaching Resources). The URL will be referenced in the proposal's "Online Teaching Resources" section, transforming a "planned" status into a tangible deliverable.

**For faculty and students:** A public-facing home for the book that showcases its academic rigour, pedagogical apparatus, and unique AI+Web3 convergence thesis — driving course adoption and building pre-publication awareness.

---

## 2. Recommended Platform: GitHub Pages (Free) → Optional Upgrade

### Phase 1 Launch (Week 1–2): GitHub Pages + Hugo or Astro
- **Why:** Completely free hosting, custom domain support, SSL included, fast global CDN. Professional-quality static sites with full design control.
- **How:** Claude generates the entire site (HTML/CSS/JS or Hugo template). Zishan pushes to GitHub. Site goes live at `yourusername.github.io/book` or a custom domain.
- **Domain:** Register `web3entrepreneurship.com` or `aiandweb3book.com` via Freenom (free .tk/.ml) or pay ~$12 on Namecheap (the only potential cost). GitHub Pages supports custom domains natively.
- **Advantage:** Multi-page from day one — no single-page limitation. Full control over embeds, iframes, and interactive content.

### Phase 2 Expansion (Post-submission): Stay on GitHub Pages or Migrate
- **Option A (Free):** Continue on GitHub Pages — add blog via Hugo/Astro, add pages freely, no cost ever.
- **Option B (Upgrade):** Migrate to Netlify (free tier: 100GB bandwidth, forms, analytics) or Vercel (free tier) for additional features like serverless functions.
- **Option C (Low-cost):** Move to Carrd ($19/year) or WordPress.com (free tier) if you prefer a GUI editor over code.

### Why Not Paid Platforms First?
- GitHub Pages gives you everything Carrd/Squarespace offer for a landing page — for free.
- Claude can build the entire site, so no drag-and-drop builder is needed.
- You keep full ownership of the code and can migrate anywhere later.

---

## 3. Website Structure & Content Map

### 3.1 Landing Page Sections (GitHub Pages — Multi-Page from Day One)

| Section | Content | Priority |
|---------|---------|----------|
| **Hero** | Book title, subtitle, author name, cover mockup, tagline: *"The first graduate textbook integrating AI and Web3 for the next generation of entrepreneurs"* | P0 |
| **About the Book** | Elevator pitch (2 sentences from SAGE proposal Task 1.2), 3–4 key differentiators as icons/cards | P0 |
| **Chapter Overview** | Accordion or card grid showing all 8 chapters with 1-sentence descriptions | P0 |
| **For Instructors** | Highlight companion resources: slide decks, test bank, teaching manual, curated reading lists — with "Request Instructor Access" button | P0 |
| **Interactive Demo** | Embedded Token Economy Simulator (link to external app or iframe) | P1 |
| **Infographics Gallery** | Scrollable gallery of chapter infographics using Vibrant Fusion palette | P1 |
| **About the Author** | Photo, bio, credentials, link to publications | P0 |
| **Reading Lists** | Downloadable curated reading lists per chapter (PDF or embedded) | P1 |
| **Video Content** | Embedded promotional/explainer videos | P2 |
| **Contact / Mailing List** | Email signup form for launch announcements + contact form | P0 |
| **Footer** | Social links, institutional affiliation, SAGE acknowledgement | P0 |

### 3.2 Full Site Structure (GitHub Pages — Available from Launch)

Since GitHub Pages supports multi-page sites from the start, you can build toward this full structure immediately:

```
Home (landing page)
├── /chapters — Individual chapter pages with deeper content
│   ├── /ch1-web3-ai-opportunity
│   ├── /ch2-blockchain-fundamentals
│   └── ... (one page per chapter)
├── /resources — Instructor companion hub
│   ├── /slides — Downloadable slide decks
│   ├── /reading-lists — Curated reading per chapter
│   ├── /activities — Student activity guides
│   └── /test-bank — (Gated: instructor-only via Google Form request)
├── /simulator — Token Economy Simulator (full-page embed from Streamlit Cloud)
├── /infographics — Visual gallery of all book infographics
├── /about — Author bio, publications, teaching experience
├── /blog — Updates, Web3+AI commentary, chapter previews (Hugo/Astro blog)
└── /contact — Google Form embed or Formspree (free) for contact + mailing list
```

---

## 4. Materials Production Plan

### 4.1 Infographics (8 chapter infographics + 3 standalone)

**Design system:** Vibrant Fusion palette throughout.

| # | Infographic | Source Chapter | Type | Tool |
|---|------------|---------------|------|------|
| 1 | "The Web3+AI Convergence Map" | Ch 1 | Conceptual diagram | Figma |
| 2 | "How Blockchain Works — A Visual Guide" | Ch 2 | Process flow | Figma |
| 3 | "Token Supply Spectrum" | Ch 3 | Already created (Figure 3.1) | Existing |
| 4 | "Token Value Hierarchy" | Ch 3 | Already created (Figure 3.2) | Existing |
| 5 | "Token Business Model Canvas (TBMC)" | Ch 3/4 | Already created (Figure 3.3) | Existing |
| 6 | "Web3 Business Model Taxonomy" | Ch 4 | Classification matrix | Figma |
| 7 | "DAO Governance Decision Tree" | Ch 5 | Decision flowchart | Figma |
| 8 | "Web3 Fundraising Landscape" | Ch 6 | Comparison infographic | Figma |
| 9 | "Community Growth Flywheel" | Ch 7 | Cycle diagram | Figma |
| 10 | "The Autonomous Machine Economy" | Ch 8 | Already created (Figure 8.2) | Existing |
| 11 | "Book at a Glance" | All | 1-page visual summary of all 8 chapters | Figma |

**All free tools used:**
- **Figma** (free plan — up to 3 projects, unlimited personal files) — primary design tool for all new infographics
- **Claude-generated SVGs** — Claude can produce SVG code for simpler diagrams directly, which Figma can import and refine
- **Squoosh.app** (free, by Google) — image compression/optimisation for web

**Production workflow:**
1. Claude drafts content/layout specifications + generates SVG prototypes for each infographic
2. Zishan refines in Figma using Vibrant Fusion colour variables
3. Export as PNG (web) and PDF (downloadable) at 1200×1600px minimum
4. Compress via Squoosh.app to <500KB per image

**Timeline:** 5–7 days (3 already exist, 8 new ones needed)

---

### 4.2 Curated Reading Lists (8 lists, one per chapter)

Each reading list will contain 8–12 entries organised into three tiers:

**Tier 1 — Foundational (3–4 items):** Essential readings for understanding the chapter's core concepts. These overlap with the "Further Reading" sections in the book (SAGE Task 2.2) but are expanded with annotations.

**Tier 2 — Deep Dives (3–4 items):** Advanced academic papers, technical whitepapers, and industry reports for students who want to go further.

**Tier 3 — Practitioner Perspectives (2–4 items):** Podcasts, talks, blog posts, and case studies from founders and builders in the space.

**Format per entry:**
```
📖 [Title] — Author(s), Year
   Type: Book / Paper / Report / Podcast / Video
   Why read this: [1–2 sentence annotation]
   Access: [URL or DOI]
```

**Deliverable:** 8 individual PDFs (branded with Vibrant Fusion header) + 1 consolidated "Master Reading List" document.

**All free tools used:**
- **Claude** — drafts all reading list content with verified sources
- **Figma** — branded PDF template design (export as PDF from Figma)
- **Alternative:** Claude generates reading lists as styled HTML, then print-to-PDF from browser (zero tools needed)

**Production workflow:**
1. Claude drafts reading lists based on chapter content and verified sources
2. Zishan reviews for accuracy and adds personal recommendations
3. Design as branded PDFs using Figma template OR Claude generates styled HTML → print to PDF
4. Upload to GitHub repo for website hosting (free, unlimited downloads)

**Timeline:** 3–4 days

---

### 4.3 Token Economy Simulator

**Concept:** An interactive web-based tool where users can experiment with tokenomics parameters and see how different design choices affect token value, supply dynamics, and stakeholder incentives. This directly brings Chapter 3 (Tokenomics) and the TBMC framework to life.

**Features (MVP):**

| Feature | Description |
|---------|-------------|
| **Supply Controls** | Sliders for: total supply, initial distribution %, vesting schedule, inflation/deflation rate |
| **Demand Levers** | Toggles for: staking rewards, governance utility, DeFi composability, burn mechanisms |
| **Stakeholder Split** | Pie chart showing allocation: founders, investors, community, treasury, ecosystem |
| **Simulation Output** | Line chart showing projected token supply over 5 years under chosen parameters |
| **Scenario Presets** | Pre-loaded examples: "Bitcoin model", "Ethereum post-merge", "Utility token", "Governance token" |
| **TBMC Integration** | Overlay showing which TBMC canvas sections each parameter affects |

**Tech options (all free):**

1. **Streamlit app on Streamlit Cloud** (Recommended) — Python-based, deploy free on Streamlit Community Cloud (unlimited public apps). Claude builds the entire app. Embed via iframe on GitHub Pages site.
2. **React app on Vercel** — Free tier (100GB bandwidth/month). Most polished UI, but more development effort. Claude can build this too.
3. **Observable notebook** — Free JavaScript-based interactive notebook, embeddable. Good for data visualisation.
4. **Pure HTML/JS on GitHub Pages** — No external hosting needed at all. Claude builds it as part of the website. Zero dependencies.

**Production workflow:**
1. Claude builds a Streamlit prototype with core simulation logic
2. Zishan tests with real tokenomics scenarios from the book's case studies
3. Style with Vibrant Fusion colours
4. Deploy to Streamlit Community Cloud (free — no credit card required)
5. Embed on GitHub Pages landing page via iframe

**Timeline:** 3–5 days for MVP

---

### 4.4 Slide Decks (8 chapter decks)

These serve double duty: they're listed as a SAGE companion material (Task 4.1) AND they're a downloadable resource on the website for faculty considering adoption.

**Structure per deck (15–20 slides):**
1. Title slide (chapter title, book title, author)
2. Learning objectives (from chapter)
3. Key concept slides (3–4 concepts, 2–3 slides each)
4. Case study summary (company, challenge, outcome)
5. Discussion questions
6. Key terms recap
7. Chapter summary

**Design specs:**
- Vibrant Fusion palette: Blue Fusion (#435070), Quiet Violet (#8B6FA0), Golden Mist (#E8C547), Coral Pop (#FF6B6B), Cloud Dancer (#F0EEE9)
- Headings: Montserrat Bold (free on Google Fonts)
- Body: Georgia (system font — free)
- Max 5–7 bullet points per slide
- Speaker notes on every slide

**All free tools used:**
- **Claude** — generates all slide content, speaker notes, and builds .pptx files directly (via python-pptx)
- **LibreOffice Impress** (free) — open and refine .pptx files if needed, export to PDF
- **Google Slides** (free) — alternative: import .pptx, edit collaboratively, present online
- **Figma** — design custom slide templates if desired

**Production workflow:**
1. Claude generates slide content, speaker notes, and builds .pptx files for all 8 chapters
2. Review in LibreOffice Impress or Google Slides (both free)
3. Export as .pptx (downloadable) and .pdf (web preview via LibreOffice or Google Slides)
4. Upload to GitHub repo; gate full decks behind a Google Form "Request Instructor Access"

**Timeline:** 5–7 days (aligns with SAGE Task 4.1)

---

### 4.5 Video Content

Videos are the highest-effort, highest-impact material. A phased approach works best.

**Phase 1 — Before SAGE Submission (2 videos):**

| # | Video | Length | Format | Purpose |
|---|-------|--------|--------|---------|
| 1 | **Book Trailer** | 60–90 sec | Motion graphics + voiceover | Hook visitors, shareable on LinkedIn/X |
| 2 | **Author Introduction** | 2–3 min | Talking head (webcam/phone) | Build personal credibility, explain the book's thesis |

**Phase 2 — Post-Submission (6–8 videos):**

| # | Video | Length | Format |
|---|-------|--------|--------|
| 3–10 | **Chapter Previews** (one per chapter) | 3–5 min each | Slides + voiceover or talking head |

**All free tools used:**
- **DaVinci Resolve** (free — professional-grade video editor, no watermarks) — editing and colour grading
- **CapCut Desktop** (free) — simpler alternative for quick edits, auto-captions, transitions
- **OBS Studio** (free) — screen recording for slides-over-voice presentations
- **YouTube** (free) — hosting and embedding
- **Figma** — design title cards, lower thirds, and branded intro/outro frames (export as PNG, import into editor)
- **Google Slides** (free) — create animated slide sequences for the book trailer, export frames or screen-record

**Production workflow for Book Trailer:**
1. Claude writes the script (60–90 seconds, ~150–200 words)
2. Choose production method:
   - **Option A (DIY — Recommended):** Create animated slides in Google Slides with Vibrant Fusion design, screen-record with OBS Studio, add voiceover in DaVinci Resolve
   - **Option B (Slides + Music):** Design key frames in Figma, animate in CapCut with royalty-free music from Pixabay Audio (free) or YouTube Audio Library (free)
   - **Option C (Talking head + slides):** Record yourself presenting key slides, edit in DaVinci Resolve with Vibrant Fusion branded intro/outro
3. Add branded intro/outro (designed in Figma, animated in CapCut or DaVinci Resolve)
4. Upload to YouTube (unlisted or public) and embed on GitHub Pages site

**Production workflow for Author Introduction:**
1. Claude writes the script
2. Zishan records on phone/webcam (good lighting + audio matters most)
3. Edit in CapCut (free, auto-captions) or DaVinci Resolve (free, more control)
4. Upload to YouTube and embed

**Timeline:** 3–5 days for Phase 1 (2 videos)

---

## 5. Master Production Timeline

### Week 1 (March 31 – April 6): Foundation

| Day | Task | Owner | Deliverable |
|-----|------|-------|-------------|
| Mon | Create GitHub repo, set up GitHub Pages (free) | Zishan | Live URL at username.github.io/book |
| Mon | Claude drafts all website copy (hero, about, chapter summaries) | Claude | Website copy document |
| Tue | Claude drafts 8 curated reading lists | Claude | 8 reading list documents |
| Tue | Claude writes book trailer script + author intro script | Claude | 2 video scripts |
| Wed | Claude builds Token Economy Simulator (Streamlit MVP) | Claude | Deployed Streamlit app |
| Wed | Claude drafts infographic content specs for all 11 graphics | Claude | Infographic briefs |
| Thu | Zishan reviews all Claude outputs, provides feedback | Zishan | Approved/revised materials |
| Fri | Claude builds full landing page (HTML/CSS/JS) for GitHub Pages | Claude | Complete site code ready to push |
| Sat–Sun | Zishan creates 3–4 infographics in Figma | Zishan | First batch of infographics |

### Week 2 (April 7 – April 13): Materials & Polish

| Day | Task | Owner | Deliverable |
|-----|------|-------|-------------|
| Mon | Claude generates slide deck content for Ch 1–4 | Claude | 4 slide deck drafts |
| Tue | Claude generates slide deck content for Ch 5–8 | Claude | 4 slide deck drafts |
| Tue | Zishan records author introduction video | Zishan | Raw video file |
| Wed | Zishan creates remaining infographics (4–5 more) in Figma | Zishan | Complete infographic set |
| Wed | Claude creates branded reading list PDFs (HTML → PDF) | Claude | 8 PDF reading lists |
| Thu | Create book trailer (Google Slides + OBS + DaVinci Resolve) | Zishan + Claude | Book trailer video |
| Thu | Edit and upload author intro video | Zishan | YouTube upload |
| Fri | Integrate all materials into landing page | Claude + Zishan | Complete landing page |
| Sat | Final review, test all links, mobile responsiveness | Both | QA checklist |
| Sun | **LAUNCH** — go live, share on LinkedIn | Both | Live companion site |

### Week 3 (April 14–20): SAGE Submission Integration

| Task | Action |
|------|--------|
| Reference the live URL in SAGE proposal Task 1.7 (Online Teaching Resources) | Update proposal document |
| Add "visit the companion website" line to the book's front matter | Update manuscript |
| Share on LinkedIn, academic Twitter/X, relevant Telegram/Discord communities | Social promotion |
| Set up Google Analytics (free) or Umami (free, privacy-friendly) on the site | Analytics setup |

---

## 6. Content Specifications (Ready for Claude to Execute)

### 6.1 Website Copy — Hero Section
```
Headline: Entrepreneurship in the Age of AI and Web3
Subheadline: Building Ventures in the Decentralized AI Internet
Tagline: The first graduate textbook integrating artificial intelligence
         and Web3 for tomorrow's entrepreneurs
CTA Button 1: "Explore Chapters" (scrolls to chapter overview)
CTA Button 2: "Request Instructor Copy" (scrolls to contact form)
Author line: By Zishan A. Mohammad
Status badge: "Forthcoming — [Publisher/Year]"
```

### 6.2 Website Copy — Key Differentiators (4 cards)
```
Card 1: 🎯 Research-Grounded
   Original peer-reviewed frameworks including the Token Business
   Model Canvas (TBMC), developed from systematic literature reviews
   and empirical Ethereum research.

Card 2: 🔗 AI+Web3 Convergence
   The only textbook treating AI and Web3 as converging forces —
   not separate topics — preparing students for the decentralised
   AI internet.

Card 3: 📚 Full Pedagogical Apparatus
   Learning objectives, case studies, glossaries, discussion
   questions, activities, and curated reading lists in every chapter.

Card 4: 🛠️ Interactive Companion Resources
   Token economy simulator, chapter slide decks, test bank, and
   teaching manual — designed for the modern classroom.
```

### 6.3 Chapter Summary Cards
```
Ch 1: The Web3+AI Opportunity
   Why AI and blockchain are converging, and what it means for entrepreneurs.

Ch 2: Blockchain Fundamentals for Entrepreneurs
   The technical foundations every venture builder needs — without the CS degree.

Ch 3: Tokenomics — Designing Your Token Economy
   How to design, model, and evaluate token systems using original frameworks.

Ch 4: Business Models for Web3 Ventures
   From DeFi protocols to creator economies — mapping Web3 revenue models.

Ch 5: Governance and DAOs
   Designing decision-making systems for decentralised organisations.

Ch 6: Fundraising in Web3
   ICOs, IDOs, grants, and hybrid models — navigating the Web3 capital landscape.

Ch 7: Building and Growing Your Web3 Community
   Community as competitive advantage — strategies for acquisition,
   engagement, and retention.

Ch 8: The Future of Web3 Entrepreneurship
   Autonomous agents, machine economies, and what comes after Web3.
```

---

## 7. Token Economy Simulator — Technical Specification

### Input Parameters (User Controls)

| Parameter | Type | Range | Default |
|-----------|------|-------|---------|
| Total Supply | Slider | 1M – 10B | 100M |
| Initial Circulating % | Slider | 1% – 100% | 15% |
| Annual Inflation Rate | Slider | 0% – 20% | 5% |
| Burn Rate (% of transactions) | Slider | 0% – 10% | 1% |
| Staking APY | Slider | 0% – 50% | 8% |
| Staking Participation | Slider | 0% – 100% | 40% |
| Vesting Period (months) | Slider | 0 – 60 | 24 |

### Allocation Pie Chart

| Stakeholder | Default % | Adjustable? |
|-------------|-----------|-------------|
| Founders & Team | 20% | Yes |
| Investors (seed + series) | 15% | Yes |
| Community / Airdrop | 25% | Yes |
| Treasury / DAO | 20% | Yes |
| Ecosystem / Grants | 15% | Yes |
| Liquidity / Market Making | 5% | Yes |

### Output Visualisations
1. **Line chart:** Circulating supply over 60 months (showing inflation, burn, and vesting unlock effects)
2. **Pie chart:** Stakeholder allocation (updates dynamically)
3. **Metrics dashboard:** Fully diluted valuation at hypothetical prices, staking lockup %, net inflation/deflation rate
4. **Scenario comparison:** Side-by-side view of 2 parameter sets

### Preset Scenarios
- **Bitcoin:** Fixed supply (21M), halving-based emission, no staking, no burn
- **Ethereum post-Merge:** Dynamic supply, EIP-1559 burn, staking yield
- **Utility token (e.g., Chainlink):** Fixed supply, no inflation, usage-based demand
- **Governance token (e.g., Uniswap):** Treasury-heavy, governance utility, no burn

---

## 8. Budget Estimate

| Item | Cost | Free Alternative | Notes |
|------|------|-----------------|-------|
| Website hosting | **$0** | GitHub Pages | Free for public repos, SSL included, custom domain support |
| Domain registration (1 year) | $0–$12 | Freenom (.tk/.ml) or use github.io subdomain | Optional: ~$12/year on Namecheap for a .com |
| Infographics & design | **$0** | Figma (free plan) | Up to 3 projects on free tier — sufficient for this book |
| Slide decks | **$0** | Claude (python-pptx) + LibreOffice / Google Slides | Claude builds .pptx files; review in free tools |
| Token simulator hosting | **$0** | Streamlit Community Cloud | Free for public apps, no credit card needed |
| Video editing | **$0** | DaVinci Resolve / CapCut Desktop | Professional-grade, no watermarks |
| Screen recording | **$0** | OBS Studio | Open source, unlimited recording |
| Video hosting | **$0** | YouTube | Embed on site, unlisted or public |
| Royalty-free music | **$0** | YouTube Audio Library / Pixabay Audio | For book trailer background music |
| Mailing list | **$0** | Mailchimp (free up to 500 contacts) / Buttondown (free up to 100) | Email signup for launch announcements |
| Contact forms | **$0** | Formspree (free: 50 submissions/month) / Google Forms | Embedded on GitHub Pages site |
| Analytics | **$0** | Google Analytics (free) / Umami (self-hosted, free) | Track visitors and faculty interest |
| Reading list PDFs | **$0** | Claude generates HTML → browser print-to-PDF | Branded with Vibrant Fusion design |
| Image compression | **$0** | Squoosh.app (by Google) | Web-optimise all infographics |
| **Total for launch** | **$0** | | Everything free if using github.io subdomain |
| **Total with custom domain** | **~$12/year** | | Only cost is the domain name |

---

## 9. Success Metrics

| Metric | Target (first 3 months) | Tool |
|--------|------------------------|------|
| Unique visitors | 500+ | Google Analytics (free) |
| Instructor copy requests | 20+ | Formspree / Google Forms (free) |
| Mailing list signups | 100+ | Mailchimp free tier |
| Simulator interactions | 200+ | Streamlit built-in analytics (free) |
| Slide deck downloads | 50+ | GitHub release download counts (free) |
| LinkedIn post impressions (book trailer) | 5,000+ | LinkedIn analytics (free) |
| Reading list downloads | 100+ | GitHub release download counts (free) |

---

## 10. Immediate Next Steps (What Claude Can Do Right Now)

In our next working sessions, Claude can execute the following tasks in order:

1. **Build the full landing page** — Complete HTML/CSS/JS site with Vibrant Fusion design, ready to push to GitHub Pages
2. **Build the Token Economy Simulator** — Full Streamlit app with Vibrant Fusion styling, deployable to Streamlit Community Cloud
3. **Create 8 curated reading lists** — Verified sources, annotated, formatted as branded HTML → PDF documents
4. **Write video scripts** — Book trailer (90 sec) and author introduction (3 min)
5. **Generate 8 slide decks (.pptx)** — Full PowerPoint files with Vibrant Fusion styling and speaker notes (via python-pptx)
6. **Draft infographic content briefs + SVG prototypes** — Specifications and vector prototypes for Zishan to refine in Figma
7. **Create branded PDF templates** — Reading list and resource templates using Vibrant Fusion design (HTML → PDF)

---

## 11. SAGE Proposal Integration

This companion website directly strengthens multiple SAGE proposal components:

| SAGE Requirement | How the Website Helps |
|-----------------|----------------------|
| #3 Synopsis | The elevator pitch and blurb are refined through website copy |
| #6 Pedagogical features | The site demonstrates the complete pedagogical apparatus visually |
| #8 Online teaching resources | **Direct evidence** — a live URL showing slides, reading lists, simulator, and instructor resources |
| #9 The market | Website analytics (post-launch) provide data on faculty interest |
| #10 Competing titles | No competitor has a companion website with an interactive simulator — this is a differentiator |
| #11 Writing plan | The site demonstrates that companion materials are actively in development, not just "planned" |

**Key proposal language to add (Task 1.7):**

> *"A companion website is live at [URL], providing faculty and students with interactive resources including a token economy simulator, chapter-specific curated reading lists, downloadable slide decks, and infographic summaries. The site will continue to expand with test bank access, video content, and a teaching manual as the manuscript moves toward publication."*

---

---

## 12. Complete Free Tools Reference

Every tool in this plan is free (except Figma, which Zishan already uses on the free plan).

| Category | Tool | Cost | What It Does |
|----------|------|------|-------------|
| **Website** | GitHub Pages | Free | Static site hosting with custom domain and SSL |
| **Design** | Figma | Free plan | Infographics, templates, slide design, title cards |
| **Slides** | python-pptx (via Claude) | Free | Generates .pptx files programmatically |
| **Slides** | LibreOffice Impress | Free | Open/edit/export .pptx files |
| **Slides** | Google Slides | Free | Collaborative editing, web presentations |
| **Simulator** | Streamlit Community Cloud | Free | Host interactive Python apps |
| **Video** | DaVinci Resolve | Free | Professional video editing, colour grading |
| **Video** | CapCut Desktop | Free | Quick edits, auto-captions, transitions |
| **Video** | OBS Studio | Free | Screen recording |
| **Video** | YouTube | Free | Video hosting and embedding |
| **Audio** | YouTube Audio Library | Free | Royalty-free music for book trailer |
| **Audio** | Pixabay Audio | Free | Additional royalty-free music/SFX |
| **Email** | Mailchimp | Free (≤500 contacts) | Mailing list for launch announcements |
| **Forms** | Formspree | Free (50/month) | Contact forms on static sites |
| **Forms** | Google Forms | Free | Instructor access requests, surveys |
| **Analytics** | Google Analytics | Free | Website traffic and visitor tracking |
| **Images** | Squoosh.app | Free | Image compression/optimisation |
| **PDFs** | Browser print-to-PDF | Free | Convert Claude's styled HTML to branded PDFs |
| **Fonts** | Google Fonts (Montserrat) | Free | Heading font for Vibrant Fusion design |
| **Domain** | GitHub.io subdomain | Free | yourusername.github.io/book |
| **Domain** | Namecheap .com | ~$12/year | Optional custom domain |

---

*This plan is designed for execution by Zishan + Claude working in parallel, using entirely free tools (plus Figma free plan). Claude handles content generation, code (website + simulator), .pptx creation, and drafting. Zishan handles Figma design, video recording, GitHub setup, and all final approvals. Total cost: $0 (or ~$12/year with a custom domain).*
