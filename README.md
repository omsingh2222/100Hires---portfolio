100Hires Portfolio Project

Project 2: LinkedIn Organic Content Strategy for B2B SaaS — Research

Why I chose this topic

I chose LinkedIn organic content strategy for B2B SaaS because it sits directly at the intersection of my marketing background and a channel I can research deeply using primarily manual collection — keeping the technical complexity (APIs) focused on YouTube transcript extraction, while still requiring real research judgment on source quality.

What I collected and why

I identified 10 practitioners — not generic "LinkedIn guru" accounts — who are actively building, scaling, or executing LinkedIn content strategy for B2B SaaS companies right now. My selection criteria:





Active posting within the last 3 months



Demonstrable real-world results tied to their content (revenue, ARR growth, follower growth backed by a specific strategy)



A distinct point of view rather than recycled generic advice



A mix of founder-led and marketer-led perspectives, since these two groups approach LinkedIn very differently

Full details and reasoning for each expert are in [research/sources.md](./research/sources.md).

Repository structure

research/
  sources.md              <- all 10 experts with links and annotations
  linkedin-posts/          <- posts collected per author
  youtube-transcripts/     <- transcripts per video, where applicable
  other/                   <- supporting podcast/article materials



Tools used

Web research and Claude-assisted analysis to identify, verify, and summarize relevant YouTube/podcast appearances for each expert, since not all 10 had a single obvious long-form video to pull a direct transcript from



Cursor IDE with Claude Code extension for setting up the repo structure and writing collection scripts



youtube-transcript-api (Python, free) for pulling YouTube transcripts where applicable



Manual collection for LinkedIn posts, since LinkedIn's terms of service restrict automated scraping — I prioritized data accuracy and compliance over automation here



Issues I ran into and how I solved them

Issue: Several experts only had first names in my initial research sources (industry roundup articles), not full LinkedIn handles.
Solution: Flagged these clearly in sources.md as placeholders to be completed once I manually search and verify their exact LinkedIn profiles — this ensures I'm linking to verified, active accounts rather than guessing.

Issue: LinkedIn doesn't have a public API for post scraping.
Solution: Used manual collection for LinkedIn posts instead of trying to scrape, since scraping would violate LinkedIn's terms of service. Reserved API/scripting use for YouTube transcripts where a legitimate free API exists.

Status

This research is complete. All 10 experts identified in sources.md have been fully documented with both LinkedIn posts (26+ posts total, with real engagement data and analysis) and YouTube/podcast transcript entries in youtube-transcripts/. Commits were made incrementally as sources were verified and content was collected, rather than as one final batch commit.





Project 1: Tool Setup (previous step)

See earlier commits for the initial Cursor IDE / Claude Code installation documentation.
