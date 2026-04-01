# Website Improvement Instructions — theaiandweb3book.com
*Prepared for Claude Code review — approve/edit before submitting*

---

## Priority 1 — Add an email capture block inside the hero section

**Goal:** Capture emails from visitors who never scroll past the fold. Currently the only sign-up form is near the bottom of the page, after the instructor resources section. Most visitors bounce before reaching it.

**What to build:**

In the existing hero section (the one containing the headline "Entrepreneurship in the Age of AI and Web3"), add a compact email capture block immediately below the two existing CTA buttons ("Explore Chapters" and "Request Instructor Copy").

The block should contain:
- A single-line email input field with placeholder text: `Enter your email address`
- A submit button with label: `Get Early Access`
- A one-line value hook above the input: `Get the first chapter free — delivered at launch.`
- A one-line trust note below the input: `No spam. Unsubscribe any time.`

Wire the form to the same backend/service already used by the existing "Stay Updated" sign-up form at the bottom of the page (so both forms feed the same list). If the existing form uses a third-party embed (e.g. Mailchimp, ConvertKit, Buttondown), replicate the same form action and hidden fields in this new block.

Style the block to match the existing hero aesthetics — keep it compact, no card border, consistent font sizing with the rest of the hero.

---

## Priority 2 — Add a lead magnet incentive to both email forms

**Goal:** Replace the passive "Get notified at launch" framing with a concrete value exchange that gives visitors a reason to subscribe now rather than bookmark and forget.

**What to change:**

1. **Hero form** (new block from Priority 1): headline already set to `Get the first chapter free — delivered at launch.` — no further change needed here once Priority 1 is implemented.

2. **Existing "Stay Updated" section** (near the bottom of the page): 
   - Replace the current `## Get notified at launch` heading with: `## Get the first chapter free`
   - Replace the current paragraph (`Join the mailing list for publication updates...`) with: `Join the mailing list and receive Chapter 1 as a free PDF the day the book launches — plus early access to companion materials and chapter previews.`
   - Change the submit button label from `Subscribe` to `Send Me Chapter 1`
   - Keep all other existing form elements, trust note, and unsubscribe language unchanged.

No backend change is needed — this is copy and label updates only. The actual chapter PDF delivery can be handled manually at launch or via an automated welcome email sequence, whichever is already in place.

---

## Priority 3 — Add a Training section to the navigation and page

**Goal:** Introduce the training offer (three tiers) as a distinct section on the landing page, and add it to the top navigation. This is a placeholder section — institutional partnership details are intentionally omitted and will be added in a future update once confirmed.

### 3a — Navigation update

In the top navigation bar, add a new item `Training` between `For Instructors` and `About`. It should anchor-link to `#training` on the same page (the new section added in 3b below).

### 3b — New Training section

Insert a new full-width section with `id="training"` between the existing "For Instructors" section and the "About the Author" section.

The section should follow the same visual structure and spacing conventions as the rest of the page.

**Section heading:** `Applied Training Programmes`

**Section subheading:** `From self-paced foundations to live masterclasses and corporate programmes — built around the book's frameworks for AI and Web3 venture building.`

**Add a short partnership note** (one line, muted text, below the subheading — styled consistently with the "Forthcoming" eyebrow label used elsewhere on the page):
`Delivered in partnership with a leading business school. Details to be announced.`

**Three training tier cards** laid out in a horizontal 3-column grid (matching the existing instructor resources grid style):

| Field | Tier 1 | Tier 2 | Tier 3 |
|---|---|---|---|
| Label | Self-Paced | Live Masterclass | Corporate & Institutional |
| Name | Foundations | AI & Web3 Venture Masterclass | Team & Faculty Training |
| Audience | Students · Practitioners · Founders | Executives · MBA Alumni · Advanced Practitioners | Innovation Teams · VC Firms · Business Schools |
| Format | On-demand · theaiandweb3book.com | Cohort-based · Live · In-person or hybrid | Custom · On-site or virtual · EN / FR · Worldwide |
| Key items (bullet list) | Full curriculum based on the book, Frameworks workbook, Token simulator access, Certificate of completion | 4–6 week cohort, Live sessions with the author, Book frameworks applied to own venture, Institutional certificate | Tailored to organisation's context, Group workshop on AI & Web3 venture strategy, Faculty development for business schools, Institutional textbook licensing option |
| Price | €49 – €149 | €599 – €1,500 | Custom pricing |
| CTA button label | Join Waitlist | Join Waitlist | Request a Conversation |
| CTA button href | `#contact` | `#contact` | `mailto:theaiandweb3book@gmail.com?subject=Corporate%20Training%20Enquiry` |

All three CTA buttons should use the same button style as the existing "Request Instructor Access" button.

**Important:** Do not mention any specific institution, partner name, city, or campus in this section. All institutional references are placeholders until confirmed.

---

## Priority 4 — Expand the author bio with credentials and publication link

**Goal:** The current author bio omits the most important trust signals for academic and institutional visitors: institutional affiliation logo/text, the peer-reviewed publication, and a photo placeholder.

**What to change in the existing "About the Author" section:**

1. **Photo:** The current section shows a "ZM" initials avatar. If there is already a photo asset available in the project, replace the avatar with it. If not, leave the avatar but increase its size to at least 80×80px so it reads as intentional, not a fallback.

2. **Add institutional affiliation line** directly below the existing name "Zishan A. Mohammad" and above the existing "Researcher · Entrepreneur · Educator" descriptor:
   `ReTech Fellow · École des Ponts Business School`
   Style this as a secondary label (smaller, muted colour), consistent with the existing descriptor line styling.

3. **Add a publications subsection** after the existing bio paragraph and before the existing skill tags. Insert the following text block:

   > **Peer-Reviewed Research**
   > Co-author of *"Token Business Model Canvas: A Framework for Designing Token Economies"*, published in *Frontiers in Blockchain* (2024). [Read the paper →](https://www.frontiersin.org/journals/blockchain)

   The link text "Read the paper →" should open in a new tab (`target="_blank"`). Replace the href with the actual DOI or article URL if available in the project files — otherwise use the journal homepage URL above as a placeholder.

4. **Update the institutional references** in the existing bio paragraph. The current text reads "With academic roots at École des Ponts ParisTech - Business School and University of Durham". Keep this sentence but make "École des Ponts ParisTech - Business School" a hyperlink to `https://pontsbschool.com/` opening in a new tab.

No layout changes needed — these are text and link insertions within the existing bio card structure.

---

## Priority 5 — Add a launch timeline signal to the hero section

**Goal:** "Forthcoming" creates no urgency and no reason to subscribe now. A concrete publication horizon makes the mailing list feel time-sensitive and relevant.

**What to change:**

1. **In the hero section**, replace the existing label text `Forthcoming — Graduate Textbook` with:
   `Publishing 2026 — Graduate Textbook`

   If a more specific season or quarter is known (e.g. Q3 2026, Autumn 2026), use that instead. This is a single text node change in the hero eyebrow label.

2. **In the hero stats row** (the row showing "8 Chapters / 3 Original Frameworks / 100+ Case Studies & Examples / 1st AI + Web3 Convergence Text"), add a fifth stat item:

   | Stat number | Stat label |
   |---|---|
   | 2026 | Publication Year |

   Match the exact same markup and styling as the existing stat items.

3. **No other changes** to the hero section are needed as part of this task — hero email capture is handled in Priority 1.

---

## Implementation notes for Claude Code

- Treat each Priority as an independent, self-contained task. They can be implemented in any order.
- Do not change any existing section IDs, anchor links, or navigation items other than those explicitly specified above.
- Do not modify the Token Economy Simulator embed, the infographics page, the slide decks page, or the reading lists page.
- Match all new copy exactly as written — do not paraphrase or rewrite.
- Preserve existing mobile responsiveness. Any new elements (hero form, training cards) must be responsive: stack to single column on screens below 768px.
- The training tier cards (Priority 3) should degrade gracefully on mobile — full-width stacked cards, consistent padding, readable at 16px base font.
- After implementing all changes, verify that all internal anchor links (`#training`, `#contact`, `#chapters`, etc.) still resolve correctly.
