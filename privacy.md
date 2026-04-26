# CatchMeUp Privacy Policy

Last updated: April 26, 2026

## Overview

CatchMeUp ("the Bot") is a Discord bot that helps users summarize recent channel activity. This Privacy Policy explains what data is processed, what is stored, and how that data is handled.

By using CatchMeUp, you acknowledge this Privacy Policy.

## Data We Process

To generate summaries, CatchMeUp reads recent Discord messages in channels where the command is used. This may include message text and, when needed for multimodal summaries, certain image attachments that are still available through Discord.

This message content is processed ephemerally for summarization only.

## What We Do Not Store Permanently

CatchMeUp does **not** permanently store Discord message content, chat logs, or image attachment contents in its local database.

Message content is only processed temporarily to generate a response and is discarded immediately after summarization is completed.

## Data We Store

CatchMeUp stores only minimal operational data in a local SQLite database:

- Discord Server/Guild ID
- Discord User ID
- `last_read` message position identifier (stored as an integer) used to track a user's catch-up position

This data is used solely to provide bot functionality.

## Third-Party Processing (Google Gemini API)

For summary generation, relevant message data is sent to the Google Gemini API. This processing is necessary to provide the bot's AI summary features.

Use of Google services is subject to Google's terms and privacy practices.

## Security and Data Handling

CatchMeUp is designed to process data securely and with data minimization principles:

- Only data needed for summarization is processed
- Message content is not retained after processing
- Stored operational identifiers are limited to core functionality

## Data Sales and Sharing

CatchMeUp data is **never sold**.

Data is not shared for advertising purposes. Data is only disclosed when required for core service operation (for example, processing through the Gemini API) or when legally required.

## Retention

- Ephemeral message content: discarded immediately after summary generation
- Stored operational identifiers (Server/User IDs and `last_read` position): retained until no longer needed for bot operation or upon administrative deletion

## Your Choices

Server admins and users can stop using CatchMeUp at any time by removing the bot or discontinuing command use.

## Discord Developer Terms

CatchMeUp is intended to operate in alignment with Discord's Developer Terms and platform requirements.

## Contact

If you have questions about this Privacy Policy, contact the CatchMeUp developer/maintainer through the bot's listed support channel or repository contact method.
