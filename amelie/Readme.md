# Amelie

A simple RSS reader built with n8n and Telegram.

The workflow fetches items from an RSS feed, organizes them into categories, and sends a formatted summary message to Telegram on a schedule.

## Version

v0.3

## Features

- Scheduled RSS checks
- Telegram notifications
- Categorized summaries
- RSS content parsing
- Error handling

## Workflow

```text
Schedule Trigger
      ↓
RSS Read
      ↓
Parse & Format
      ↓
Telegram
```

## Requirements

- n8n
- Telegram Bot Token
- Telegram Chat ID

## Installation

1. Import the workflow JSON into n8n.
2. Configure Telegram credentials.
3. Set your target RSS feed.
4. Enable the workflow.

## Usage

The workflow runs automatically on schedule or request and sends a formatted summary of new RSS items to Telegram.

