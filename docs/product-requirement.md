# FableForce Social AI Platform (PRD)

## Vision

Build an AI-powered social media publishing platform for FableForce that automatically creates, schedules, and publishes content across multiple social media platforms with minimal human intervention.

---

# Objectives

- Fully automate social media publishing.
- Publish to YouTube, Instagram, and Facebook.
- Generate AI-powered titles, descriptions, captions, hashtags, and keywords.
- Schedule content automatically.
- Maintain a publishing history.
- Scale to support multiple brands and clients.

---

# Phase 1 – Core Publishing Engine

## Input

- Google Drive
- Video Folder
- One video = One content item

## AI Processing

Claude (Anthropic) will generate:

- YouTube Title
- YouTube Description
- Instagram Caption
- Facebook Caption
- Hashtags
- Keywords
- Category
- Call to Action

---

## Database

Google Sheets

Status values:

- New
- AI Ready
- Scheduled
- Published
- Failed

---

## Publishing Platforms

- YouTube Shorts
- Instagram Reels
- Facebook Reels

---

## Scheduler

Automatically schedule:

- 1 posts/day across all connected platform


---

# Phase 2 – Smart Automation

- Duplicate detection
- Retry failed uploads
- AI quality checks
- Content categorization
- Automatic publishing calendar

---

# Phase 3 – Analytics

Track:

- Views
- Likes
- Comments
- Shares
- Subscribers
- Watch Time
- Best posting time

---

# Phase 4 – Multi Brand Support

Support multiple brands from one platform.

Examples:

- FableForce
- FableKids
- Client A
- Client B

Each brand should have:

- Separate Google Drive
- Separate AI prompts
- Separate publishing schedule
- Separate analytics

---

# Technology Stack

Automation:
- Make.com

AI:
- Claude API (Anthropic)

Storage:
- Google Drive

Database:
- Google Sheets

Publishing APIs:
- YouTube Data API
- Meta Graph API

Version Control:
- GitHub

---

# Long-Term Vision

Build FableForce Social AI into a commercial SaaS platform capable of managing content publishing for multiple businesses with minimal human intervention.
