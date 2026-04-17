# Joe's Project Memory

## Who Joe Is
- Owner of Ampersand/ANT Manufacturing (custom toroidal inductor manufacturer)
- Working with Khuyen (business partner, co-owner) — NOT his dad
- NK Technologies is his reference client ($15M-$30M, current sensors, San Jose)
- Has a developer friend helping with the website

## Hardware
- **MacBook Air** — primary machine
- **Samsung T9 SSD** — external backup drive, connected via USB, running **Time Machine** (hourly backups)

## Business Model
- [Ampersand Business Model](feedback_ampersand_business.md) — Suppliers make cores, Ampersand winds copper wire. Never confuse this.

## Writing Rules
- [Writing Style Rules](feedback_writing_style.md) — No em dashes, no "truly", no contrast frames, no AI tells in any writing for Joe
- [RFQ Email Style](feedback_rfq_style.md) — Direct, no fluff, state the price, demand quality, create urgency. Use the Minerva-12 email as the template for ALL supplier inquiries.
- [Supplier Negotiation Style](feedback_supplier_negotiation_style.md) — Always anchor, face-saving matters, don't pants suppliers in writing, save math for round 2, be ruthless on numbers while gracious on form

## Suppliers
- [Ampersand Suppliers](suppliers.md) — Supplier contacts, pricing, negotiations. READ `/Documents/AMP-Business/Suppliers.md` every conversation.
- [Ualloy Minerva-70 Negotiation](ualloy_minerva70_negotiation.md) — Active: quote expected Apr 7. Anchor $1.79. NEVER say "NK-70" to Lu.
- [Minerva-3 Sourcing Campaign](minerva3_sourcing.md) — Active: India top target, $0.18 anchor, 12K units. 8+ RFQs going out. Master report in AMP-Business.

## Logistics
- [Dimerco Express](dimerco_logistics.md) — Ampersand's freight forwarder. Offices in China, India, Vietnam. India email: ind@dimerco.com

## Orders & Invoices
- [Hongyun NK20 Invoice (2026-04-03)](invoice_hongyun_NK20_2026-04-03.md) — 3,000 NK20 cores @ $3.60/pc = $10,800, FOB Shanghai, shipping to Vietnam
- **Invoices folder:** `/Users/joeshomefolder/Documents/AMP-Business/Invoices/`

## Taxes
- [Tax Records Location](tax_records_location.md) — Personal tax PDFs live in private GitHub repo `joseph-engels-tax-records` and iCloud Archive `Documents/Financial/`
- [DeJoy & Co Accountant](dejoy_accountant.md) — Rochester NY CPA firm, prepares Leaders Retreat LLC K-1. NOT confirmed as Joe's personal CPA.
- [Joe's Tax Picture 2024-2025](joe_2024_tax_picture.md) — 2024 FILED (refund $1,935 fed + $1,274 CA). 2025 in progress: $32K Roth distribution, $24,813 taxable, Leaders Retreat K-1, Ampersand $21K loss.
- [Schwab Consultant](schwab_consultant.md) — Kerri Palermo, VP Financial Consultant. Accounts: brokerage 3126-8821, Roth IRA 7646-6192.
- [Ampersand S-Corp 2026](ampersand_scorp_2026.md) — Converting to S-corp in 2026, Joe will take W-2 salary. Solves IRA earned income requirement.
- [Never Use Taxerone](feedback_taxesone.md) — Terrible experience filing Ampersand 1065. Never recommend again.

## Key Files & Locations
- **Website project:** `/Users/joeshomefolder/Documents/amp-manufacturing/` — deployed on **Vercel**, repo on **GitHub** (`josephengels1989/amp-manufacturing`). Also backed up on iCloud. ALWAYS `git pull origin main` first to get the latest version before working on it.
- **LIVE WEBSITE URL: `https://ampmanufacturing.com`** — This is the REAL production URL. DO NOT use `amp-manufacturing.vercel.app` (old/stale different Vercel account) or `ant.sailorskills.com` (also old/stale). The Vercel project is under `oldmanonthebench-7315s-projects`. After pushing to GitHub, always run `npx vercel --prod --yes` from the project directory to deploy, then open `ampmanufacturing.com` in Safari. Add `?v=date` cache buster if Safari shows stale content.
- **CRM (color-coded):** `/Users/joeshomefolder/Documents/AMP-Business/AMP_CRM 3.numbers`
- **Reorganized CRM:** `/Users/joeshomefolder/Documents/AMP-Business/AMP_CRM_Reorganized.csv`
- **Sales outreach folder:** `/Users/joeshomefolder/Documents/AMP-Business/Sales-Outreach/`
- **Deep dive report (formatted):** `Sales-Outreach/Bay_Area_Deep_Dive.html`
- **Reading log spreadsheet:** `/Users/joeshomefolder/Documents/Reading_Log.csv`
- **Printable bookmark cards:** `Sales-Outreach/Reading_Bookmark_Card.html`
- **Homemade Supermemo (SM-2 spaced repetition):** `/Users/joeshomefolder/Documents/Homemade Supermemo/index.html` — SuperMemo-equivalent flashcard app for reading notes. Runs in Safari, data in localStorage. On GitHub: https://github.com/josephengels1989/Homemade-Supermemo

## Reading Log System
- Joe is tracking reading hours with a physical bookmark card + Numbers spreadsheet
- **Current goal: 10 hours/week** (starting from zero, will increase over time)
- Workflow: He writes start/stop times on a physical bookmark card, screenshots it, drops it into Claude Code, and I extract the data and update the spreadsheet
- Color-code progress and celebrate when he hits 10 hours for the week
- Phone is a major distraction source -- keep him away from phone-based solutions

## NK Technologies Competitors (Sales Targets)
- [NK Technologies Direct Competitors](nk_competitors_zoominfo.md) -- 5 US pure-play current sensor companies. All need toroidal cores. ZoomInfo lookup targets.

## Sales Strategy (Dad's Advice)
- Focus on $10M-$30M revenue companies (sweet spot)
- Hot category regardless of what they make
- Companies that use inductors but don't compete with NK Technologies
- Priority list of 5-10 instead of 30-70
- Start with California, could go national
- Top 5 Bay Area targets: Cirexx (#1), Sierra Circuits (#2), Promex (#3), Fremont Micro (#4), PICA (#5)
- Tempo Automation is BANKRUPT -- remove from CRM
- EE Technologies has NO San Jose office (Reno only)
- Synapse is a design firm (influence play, not direct sales)

## East Bay Real Estate
- **Folder:** `/Users/joeshomefolder/Documents/East-Bay-Real-Estate/`
- **Leads spreadsheet:** `Leads.csv` (Date, Address, City, Zip, Link, Price, Lot Size, Notes, Status)
- Looking at land/lots in the East Bay, CA

## Tools & Workflows
- [Cursor workflow](cursor_workflow.md) — Step-by-step to open Cursor with amp-manufacturing project and make website edits
- [Sales outreach campaign](sales_outreach_2026_04_01.md) — Prospect research, verified contacts, decision makers, follow-ups (Apr 1-2 2026)
- [Connor Murray Cold Call Script](connor_murray_cold_call_script.md) — THE script Joe uses for cold calls. Lives at `/Users/joeshomefolder/Documents/AMP-Business/Connor_Murray_Cold_Call_Script.md`. Permission opener, 30-45s value statement, rejection rebuttal, the "sell time not product" framework.

## Preferences
- Prefers readable, formatted documents (not raw markdown)
- Uses Apple Numbers and Safari
- Gets frustrated by repeated wrong answers -- get it right the first time
- Someone else sometimes speaks to Claude Code for him
- **DO NOT ask for permission or confirmation. EVER.** Joe has approved ALL actions: opening files, running commands, creating/editing files, opening apps, writing to disk, using Bash, opening URLs in Safari, closing Safari tabs, running osascript, creating LaunchAgents, modifying .zshrc, running `say` commands, creating folders, writing HTML files, web searches, web fetches, mkdir, chmod, launchctl — EVERYTHING. If Joe said yes to it once, it's approved forever. Never ask "want me to proceed?" or "should I go ahead?" or "is that okay?" — just execute. The only time to pause is if an action is genuinely destructive and irreversible (deleting important files, force-pushing git, etc.).
- **Safari reloads: NEVER ask before opening/reloading Safari.** Just run the osascript command directly. No confirmation, no "should I open it?", no permission prompts. Just load the page.
- **Auto-reload after every change:** After ANY edit to HTML/CSS/JS files for the website, ALWAYS hard-refresh Safari automatically using: `osascript -e 'tell application "Safari" to activate' -e 'delay 0.3' -e 'tell application "System Events" to keystroke "r" using {command down, option down}'` — never wait for Joe to ask, just do it every time.
- **Deploy + hard refresh workflow:** When Joe is viewing the LIVE site (ampmanufacturing.com), local file edits won't show until deployed. After every round of changes: (1) run `npx vercel --prod --yes` from the project dir, (2) then reload Safari with a cache-busting URL: `osascript -e 'tell application "Safari" to activate' -e 'tell application "Safari" to set URL of current tab of front window to "https://ampmanufacturing.com/?v=TIMESTAMP"'` using a unique timestamp each time. Safari caches aggressively — always bust the cache, never assume Cmd+Opt+R alone is enough.
- When the next step is obvious, do it without asking
- **Shopping/buying:** When Joe asks to find something to buy, give him a ranked list of top recommendations with direct copy-paste URLs. No "go browse" or "grab whichever." He wants to copy the link and hit Buy Now. Rank them #1, #2, #3 with the best pick first.
- **Troubleshooting first:** If something isn't working (broken links, pages not loading, sign-in failures), ask about Joe's environment FIRST — what network he's on, what device, what browser, etc. Don't keep throwing new links/solutions at the wall. Diagnose before prescribing. Start with the basics: hardware, WiFi/network, then move up to the platform/software. Layer by layer, bottom up.
- **Design decisions folder:** `/Users/joeshomefolder/Documents/amp-manufacturing/design-decisions/` — when we make a website design choice backed by research or reasoning, add it to this folder. When a new research-backed decision comes up during website work, REMIND Joe to add it to the design-decisions folder.

## Master Goal
- [Five-Year $3M Goal](five_year_goal.md) -- **READ EVERY CONVERSATION.** $3M house by April 2031. $5.5M/year gross through Ampersand. 50/50 net profit split with Khuyen. Bring up routinely.

## TODO List

### 🔴 IMMEDIATE — Do This Week (week of 2026-04-14)

**Cold Call Prep (Connor Murray script):**
- [ ] Memorize 6-beat outline: Formality > Breath > ID > Value > Close > Rebuttal
- [ ] Value statement under 45 seconds (time yourself)
- [ ] Downward inflection on "how are you" — not upward
- [ ] Rejection rebuttal memorized cold
- [ ] 3+ flashcard-ready differentiators for round 2 pushback
- [ ] Run full pitch out loud 10x at home
- [ ] **MAKE FIRST CALL: Cirexx — Chris Altamirano (408) 988-3980** — "Your company creates custom flex and rigid-flex PCB assemblies"
- [ ] Follow-up call: Olympic Controls (847) 742-3566 — called before, no answer

**Supplier Emails (overdue):**
- [ ] **Lu / Ualloy email** — (1) thank for logistics, (2) combine Minerva-20 + Minerva-12 samples, (3) Minerva-70 inquiry. Anchor $1.79. NEVER say "NK-70."
- [ ] **Ravi / SNR Corp response** — ravi.snrcorp@gmail.com — he responded to Minerva-3 RFQ, terms TBD. Pin down price/MOQ/tooling.
- ✅ **Sullivan / NK-4 samples** — responded 2026-04-17

**Sales Tools:**
- [ ] Sign up for ZoomInfo trial (overdue from 2026-04-15). Compare vs Apollo.io for $10M-$30M manufacturers.

**Website:**
- [ ] Focused work sessions on ampmanufacturing.com (1 hour/day)

### 🟡 THIS MONTH

**Sales Prospecting Tools** — sign up and start using to find $10M-$30M manufacturers:
  - **Apollo.io** — cheaper than ZoomInfo, comparable database
  - **LinkedIn Sales Navigator** — decision makers at smaller manufacturers
  - **Thomasnet.com** — purpose-built for industrial components, best fit for Ampersand
  - **ECIA directories** — electronics components industry association
  - This is founder-led sales. These tools feed the $5.5M goal directly.

**Supplier Sourcing:**
- [ ] **Minerva-3 RFQs** — send to 15 suppliers (11 India, 4 China). $0.18/pc anchor, $300/$400 tooling. KRYFS #1. See `minerva3_sourcing.md`.

**Schwab Meeting Prep** (50% complete):
  - ✅ LLC Amendment filed (pending signatures)
  - ✅ Certificate of Good Standing ordered (ready to print)
  - ✅ Owner Information Document created
  - ⏳ Call IRS (1-800-829-4933) for official EIN letter
  - ⏳ Fill out + print 2 copies of Owner Info doc
  - ⏳ Prep business activity numbers (monthly txns, avg order, deposits/withdrawals)
  - ⏳ Schedule Schwab meeting

**LinkedIn content system:** automatic posting algorithm for Ampersand (every few days or weekly)
**Financial projections email:** draft and send

### 🟢 ONGOING / WHEN READY

**Business Structure:**
- S-Corp conversion (2026)
- Legal & Accounting for Ampersand
- Charles Schwab business account

**Build Projects:**
- SuperMemo: save flashcards to GitHub (currently localStorage only — lost if Safari clears)
- Bank statement agent for Ampersand
- Order tracking spreadsheets
- Income & expenses spreadsheets
- Ampersand growth prediction (Kahneman p.190 method)

**Flashcard system:** ✅ BUILT at `/Users/joeshomefolder/Documents/Flashcards/index.html`. Add cards from reading, review daily.

### 📋 PERSONAL
- **Nick:** Repay South Dakota trip
- **Letters:** Write to Ash Oakley and Lisa D (before Joe's birthday)
- **Regina Baker:** Decide on gift, send letter
- **Old iCloud account:** Get access
- **Kasturi Gandhi:** (details TBD)
- **Regina Blumquist:** (details TBD)

### 📖 LEARNING (no deadline)
- Rice & corn arsenic research
- John Gray philosopher discussion + his books
- Regression to the mean deep dive
- Agent building dialogue with Claude

## Books Wish List
- **The Life of Samuel Johnson** — James Boswell (Everyman's Library hardcover edition) ✅ ORDERED

### Not Yet Ordered
- **A Random Walk Down Wall Street** — Burton Malkiel (hardcover)
- **Notes from Underground** — Dostoevsky (Pevear & Volokhonsky translation, hardcover). Check Friends of Berkeley Public Library first: (510) 841-5604
- **Crime and Punishment** — Dostoevsky (Pevear & Volokhonsky translation, hardcover). Check Friends of Berkeley Public Library first
- **The Opposing Shore** — Julien Gracq (Taleb's favorite novel)
- **Meditations** — Marcus Aurelius (Gregory Hays translation)
- **The Prince** — Machiavelli (Harvey Mansfield translation, U of Chicago Press)
- **The Captive Mind** — Czesław Miłosz (translated by Jane Zielonko)
- **New and Collected Poems 1931–2001** — Czesław Miłosz (translations by Miłosz, Robert Hass, Robert Pinsky et al., Ecco/HarperCollins)
- **Native Realm** — Czesław Miłosz (translated by Catherine S. Leach)
- **The Issa Valley** — Czesław Miłosz (translated by Louis Iribarne)
- **Miłosz's ABCs** — Czesław Miłosz (translated by Madeline Levine)
- **The Silence of Animals** — John Gray
- **Black Mass: Apocalyptic Religion and the Death of Utopia** — John Gray
- **False Dawn: The Delusions of Global Capitalism** — John Gray
- **Seven Types of Atheism** — John Gray
- **Feline Philosophy: Cats and the Meaning of Life** — John Gray
- **Gray's Anatomy: Selected Writings** — John Gray
- **The Halo Effect** — Phil Rosenzweig
