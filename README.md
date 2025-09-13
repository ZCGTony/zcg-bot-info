# ZCG Checklist Crawler — Bot Info

**User-Agent:** `ZCGTony/1.0 (+https://zcgtony.github.io/zcg-bot-info/)`  
**Purpose:** Fetch printable checklist pages from Trading Card Database (TCDB) for personal offline parsing.

## Overview
This crawler retrieves the printable checklist view for baseball sets so I can analyze them offline. It is single-threaded, polite, and narrowly scoped.

## Scope and Pacing
- **Sport:** Baseball
- **Years:** 2020–2023 (inclusive)
- **Includes:** Inserts and related sets
- **Rate:** 1 request at a time, ~1.5 seconds between requests
- **Concurrency:** 1

## Endpoints Touched
- Discovery: year and set browse pages  
- Capture: `PrintCenter.cfm?Report=PrintChecklist&SetID={SID}`

## Output
- **Saved format:** HTML only (no images, CSS, JS)  
- **Use:** Personal, non-commercial offline research

## Contact & Opt-Out
Email **t.hombel@outlook.com** with the path, timestamp, and (if possible) source IP, and I will pause or adjust.
<!-- If you prefer an alias, switch to t.hombel+bot@outlook.com and set a mail rule. -->

## Etiquette
- Keep polite pacing and avoid authenticated areas
- Honor `robots.txt` or site requests to stop

## Change Log
- 2025-09-12: Initial public note and scope definition

## Canonical Source
If this README is out of date, the User-Agent page at **https://zcgtony.github.io/zcg-bot-info/** is the source of truth.
