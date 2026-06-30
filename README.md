# 100Hires Portfolio Project

## Project 2: LinkedIn Organic Content Strategy for B2B SaaS — Research

### Why I chose this topic
I chose LinkedIn organic content strategy for B2B SaaS because it sits directly at the intersection of my marketing background and a channel I can research deeply using primarily manual collection — keeping the technical complexity (APIs) focused on YouTube transcript extraction, while still requiring real research judgment on source quality.

### What I collected and why
I identified 10 practitioners — not generic "LinkedIn guru" accounts — who are actively building, scaling, or executing LinkedIn content strategy for B2B SaaS companies right now. My selection criteria:

- Active posting within the last 3 months
- Demonstrable real-world results tied to their content (revenue, ARR growth, follower growth backed by a specific strategy)
- A distinct point of view rather than recycled generic advice
- A mix of founder-led and marketer-led perspectives, since these two groups approach LinkedIn very differently

Full details and reasoning for each expert are in [research/sources.md](https://github.com/omsingh2222/100Hires---portfolio/blob/main/research/sources.md).

### Repository structure
```
research/
  sources.md              <- all 10 experts with links and annotations
  linkedin-posts/          <- posts collected per author (10 files, 26 posts total)
  youtube-transcripts/     <- transcripts/podcast summaries per video (10 files, one per expert)
  other/                   <- supporting podcast/book/playbook materials (5 files)
```

### The 10 experts
Lara Acosta, Dharmesh Shah, Adam Robinson, Emily Kramer, Natalie Marcotullio, Pranav Piyush, Lashay Lewis, Talya Heller, Tas Bober, and Shiv Narayanan. Each spans a different angle on B2B SaaS GTM — founder-led growth, product marketing, demand gen measurement, competitive positioning, PLG, and BOFU content strategy — so the research covers the full buyer journey rather than just top-of-funnel LinkedIn tactics.

### Tools used
- Web research and Claude-assisted analysis to identify, verify, and summarize relevant YouTube/podcast appearances for each expert, since not all 10 had a single obvious long-form video to pull a direct transcript from
- Cursor IDE with Claude Code extension for setting up the repo structure and writing collection scripts
- youtube-transcript-api (Python, free) for pulling YouTube transcripts where applicable
- Manual collection for LinkedIn posts, since LinkedIn's terms of service restrict automated scraping — I prioritized data accuracy and compliance over automation here

### Issues I ran into and how I solved them
**Issue:** Several experts only had first names in my initial research sources (industry roundup articles), not full LinkedIn handles.
**Solution:** Flagged these clearly in `sources.md` as placeholders to be completed once I manually searched and verified their exact LinkedIn profiles — this ensured I was linking to verified, active accounts rather than guessing.

**Issue:** LinkedIn doesn't have a public API for post scraping.
**Solution:** Used manual collection for LinkedIn posts instead of trying to scrape, since scraping would violate LinkedIn's terms of service. Reserved API/scripting use for YouTube transcripts where a legitimate free method exists.

**Issue:** Not every expert had a transcript-friendly long-form YouTube video (some are primarily LinkedIn-native creators with no podcast/keynote presence).
**Solution:** For each expert, I researched their actual long-form appearances (podcasts, keynotes, webinars) and built sourced summary files using direct quotes and episode timestamps rather than fabricating content — each file includes a methodology note explaining exactly how it was compiled.

### Early patterns worth flagging for a future playbook
A few cross-expert patterns emerged repeatedly across the research, which I think are strong candidates to anchor an eventual playbook:

1. **Personal brand consistently outperforms company brand.** Adam Robinson spent $800K on a company domain and still found his own LinkedIn storytelling outperformed branded content; Shiv Narayanan and Talya Heller both independently make versions of the same point about generic company messaging getting ignored.
2. **AI is a co-pilot inside a proven human framework, not a replacement for one.** This shows up almost identically in Dharmesh Shah's keynote ("use AI to test your thinking... but don't use it to replace your thinking"), Lashay Lewis's BOFU.ai philosophy (teach AI a human-built framework, don't let it freelance), and Natalie Marcotullio's caution about over-indexing on "AI-powered" messaging.
3. **The real competitor is inertia, not the competition.** Talya Heller's "biggest competitive threat is your buyer doing nothing" and Pranav Piyush's incrementality framework ("most marketing isn't moving the needle, it's claiming credit for what would have happened anyway") are independently arriving at the same conclusion from completely different disciplines (sales enablement vs. paid media measurement).
4. **Top creators package complex ideas into short, named, repeatable frameworks** — Lara Acosta's SLAY framework, Dharmesh Shah's PART framework and "this doesn't work, yet" mantra, Talya Heller's Win Map™ — rather than relying on long explanations.

### Status
This research is complete. All 10 experts identified in `sources.md` have been fully documented with LinkedIn posts (26 posts total, with real engagement data and analysis), YouTube/podcast transcript entries (10 files, one per expert), and 5 additional supporting-materials entries in `other/` covering books, playbooks, and consultancy frameworks referenced directly in their LinkedIn content. Commits were made incrementally as sources were verified and content was collected, rather than as one final batch commit.

## Project 1: Tool Setup (previous step)
See earlier commits for the initial Cursor IDE / Claude Code installation documentation.
