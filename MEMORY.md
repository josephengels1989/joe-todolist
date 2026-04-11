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
- **🔴 URGENT -- Sullivan / NK-4 samples:** Find out if Sullivan has provided samples for the NK-4 (quoted at $0.44). If she hasn't, order them from her. Follow up ASAP.
- **🔴 URGENT -- Try ZoomInfo by Wed 2026-04-15:** Sign up for ZoomInfo trial and test it out before next Wednesday. Compare against Apollo.io for the $10M-$30M manufacturer use case.
- **🔴 URGENT -- Sales prospecting tools:** Sign up and start using these to find $10M-$30M manufacturers:
  - **Apollo.io** -- cheaper than ZoomInfo, comparable database, good coverage of that revenue range
  - **LinkedIn Sales Navigator** -- decision makers at smaller manufacturers (owners, VP Engineering) are reachable here
  - **Thomasnet.com** -- purpose-built for industrial components, companies listed are actively sourcing. Best fit for Ampersand's use case
  - **ECIA directories** -- electronics components industry association, exactly the target market
  - This is founder-led sales. These tools feed the $5.5M goal directly.
- **LinkedIn content system:** Create an automatic algorithm for Ampersand posts on LinkedIn. Ampersand should always be posting (every few days or every week). Create LinkedIn posts with credible, on-brand content.
- **Old iCloud account:** Get access to old iCloud account
- **Letters:** Write letters to Ash Oakley and Lisa D ahead of Joe's birthday
- **Regina Baker:** Decide on gift for Regina Baker and send her a letter
- **Aunt Eileen:** Return Aunt Eileen's package with my own package
- **Aunt Eileen (ASAP):** Purchase drugs for Aunt Eileen
- **Karina:** Congratulate Karina and send her money
- **Nick:** Repay Nick for South Dakota trip
- **S Corp:** Convert Ampersand to an S corp
- **Legal & Accounting:** Find legal and accounting for Ampersand
- **Rice & corn research:** Research arsenic in rice and American corn flour health
- **Charles Schwab:** Open business account with Charles Schwab
- **John Gray:** Discuss John Gray the philosopher and his books (come back to this)
- **Ampersand growth prediction:** Use the process from p.190 of *Thinking, Fast and Slow* (Kahneman) to predict growth of Ampersand. Work with Claude on this.
- **Send email on financial projections:** Send financial projections email
- **Schwab meeting prep:** Gather all documentation for the Charles Schwab branch meeting. (Status: 50% complete)
  - ✅ LLC Amendment: Filed to add Joseph V. Engels as co-owner (50/50 with Khuyen) — pending both signatures
  - ✅ Certificate of Good Standing: Ordered from CA Secretary of State (ready to print from portal, not yet printed)
  - ✅ Owner Information Document: Created professional form at `/Users/joeshomefolder/Documents/AMP-Business/Schwab_Owner_Information.html` (warm orange theme, MM/DD/YYYY dates)
  - ⏳ EIN Letter: Call IRS (1-800-829-4933) to request official EIN letter — do this tomorrow morning
  - ⏳ Owner Information Document: Fill out with Joseph V. Engels & Khuyen V. Nguyen info, print 2 copies
  - ⏳ Business Activity Info: Prepare numbers on monthly transactions, deposits, withdrawals, and account usage
    - How many customer orders/transactions per month?
    - Average order value?
    - Expected monthly revenue total?
    - Typical monthly deposits (from customers)?
    - Typical monthly withdrawals (paying suppliers/vendors)?
    - Do you and Khuyen have employees, or just you two?
    - Will you need payroll processing through Schwab?
    - Primary account use: operating account, vendor payments, customer deposits, etc.?
  - ⏳ Schedule Schwab meeting and gather final documents
- **Regression to the mean:** Do a deep dive on regression to the mean so I fully understand it. Work with Claude on this.
- **Agent building:** Dialogue with Claude about how to build an agent
- **Bank statement agent:** Build an agent to review Ampersand's bank statements
- **Order tracking:** Create spreadsheets to track Ampersand's orders
- **Income & expenses:** Create spreadsheets to track Ampersand's income and expenses
- **Flashcard system:** ✅ BUILT — SM-2 spaced repetition flashcard app at `/Users/joeshomefolder/Documents/Flashcards/index.html`. Add cards from reading, review daily.
- **Lu / Ualloy email (TONIGHT 2026-04-02):** Finish the email to Lu. Need to: (1) thank him for covering logistics, (2) ask to combine Minerva-20 samples with Minerva-12 samples in one package, (3) hit him with Minerva-70 inquiry. Before sending, work out Minerva-70 pricing strategy with Claude first. Key question: is Minerva-70 the same core as NK-70? If so, Yori's $2.80 is the benchmark. What material, what qty, what price to target?
- **Minerva-3 sourcing:** Send RFQs to 15 suppliers (11 India, 4 China). $0.18/pc anchor, $300/$400 tooling fee. Pick up at #1 KRYFS. See `minerva3_sourcing.md` for full send list.
- **Kasturi Gandhi:** (details TBD)
- **Regina Blumquist:** (details TBD)

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
