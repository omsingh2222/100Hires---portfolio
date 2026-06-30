YouTube Transcripts

This folder is for transcripts of relevant YouTube content from the experts in /research/sources.md, where applicable (not all 10 experts are YouTube-active — this folder may be smaller than the LinkedIn posts folder, and that's fine).

How to collect these using Claude Code

Since this task specifically asks you to use Claude Code or Codex with APIs, here's the simplest free method:

Option A — Supadata (mentioned in the task brief)





Sign up for a free Supadata account (supadata.ai) — they offer a YouTube transcript API



Get your free API key



Ask Claude Code in your terminal:

"Write a Python script that takes a YouTube video URL and fetches its transcript using the Supadata API, then saves it as a markdown file"



Run the script for each relevant video



Option B — youtube-transcript-api (free Python library, no signup needed)





In your terminal, ask Claude Code:

"Install the youtube-transcript-api Python package and write a script that takes a video URL, extracts the video ID, and saves the transcript as a markdown file in research/youtube-transcripts/"



Claude Code will handle the installation and script creation for you



Run it on each video you want to transcribe



Naming format

Save each transcript as:
expert-name_video-title-short.md

Example: dharmesh-shah_how-i-built-hubspot.md

Format inside each file

# [Video Title]
**Creator:** [Name]
**Link:** [YouTube URL]
**Published:** [date]

## Transcript
[paste transcript here]

## Key takeaways
[2-3 bullet points on what's useful from this video for the LinkedIn content strategy research]

