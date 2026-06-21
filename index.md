# Privacy Policy — Lexifolio

**Last updated:** June 21, 2026

Lexifolio ("the App") is developed by Cengiz Oger. This privacy policy explains what data the App collects, how it is used, and your choices.

## Summary

Lexifolio is designed with privacy in mind. **All your library data stays on your device.** The App has no analytics, no tracking, no advertising, and no user accounts.

## Data Stored on Your Device

All of the following data is stored locally on your device and is never uploaded to any server:

- **Book library** — titles, authors, cover images, categories, and file references
- **Reading positions** — your current page/chapter in each book
- **Personal dictionary** — saved words, definitions, translations, and spaced repetition data
- **Annotations** — highlights, notes, and their locations within books
- **Reading statistics** — session dates, durations, and reading progress
- **Monitored folders** — references to folders you choose for automatic book import

This data is stored in the App's private sandbox on your device.

## Keychain Storage

If you choose to use the OpenAI summarization option, your API key is stored securely in the iOS Keychain with device-only protection. It is never shared with anyone other than OpenAI's API when generating summaries.

## Network Requests

The App makes network requests only in the following user-initiated scenarios:

### 1. ISBN / Barcode Lookup (Open Library)
When you scan a barcode or enter an ISBN, the App sends the ISBN number to [Open Library](https://openlibrary.org) (a project of the Internet Archive) to retrieve book metadata (title, author, cover image). No personal data is sent — only the ISBN.

### 2. AI Summaries via OpenAI (Optional)
If you provide an OpenAI API key and select "OpenAI" as your summary provider, the App sends a portion of the book's text (up to 30,000 characters), along with the book's title and author, to OpenAI's API to generate a summary. **This is entirely optional.** You can use the on-device Apple Intelligence summarization instead, which processes text locally on your device with no network requests.

### 3. Online Dictionary Lookup (Wiktionary)
When you tap "Look Up Online" for a word definition, the App sends the word to [Wiktionary](https://en.wiktionary.org) to retrieve its definition. No personal data is sent — only the word itself.

## On-Device AI Features

The App uses Apple's on-device FoundationModels framework for:
- Book summaries (when "On-Device" provider is selected)
- Word definitions in the personal dictionary

These features run entirely on your device using Apple Intelligence. No text is sent to any server.

## Translation

The App uses Apple's Translation framework to translate saved dictionary words based on your configured language pair (e.g., English → Turkish). Translations are processed by the system Translation service on your device. Language packs may be downloaded by the system when needed.

## Camera Access

The App requests camera access solely for scanning book barcodes (ISBN/EAN). The camera feed is processed locally to detect barcodes. No images or video are stored or transmitted.

## File Access

The App accesses PDF and EPUB files you select through the system file picker or from monitored folders. Files are accessed using iOS security-scoped bookmarks. The App does not access files you have not explicitly selected.

## What We Do NOT Collect

- No analytics or usage tracking
- No crash reporting to external services
- No advertising or ad identifiers
- No user accounts or registration
- No location data
- No contacts, calendar, or health data
- No data shared with third parties for marketing purposes

## Backup & Restore

You can export your full library catalog (book titles, authors, categories, source file paths), dictionary, highlights, reading positions, and sessions as a `.lexifolio` backup file. This file is saved to a location you choose (e.g., Files app, iCloud Drive). Lexifolio never uploads backups to any server — the file stays wherever you save it.

## Data Deletion

All App data is stored locally on your device. To delete all data, simply delete the App. You can also delete individual books, dictionary entries, annotations, and reading history from within the App.

## Children's Privacy

The App does not knowingly collect any personal information from children.

## Changes to This Policy

If this policy is updated, the changes will be posted on this page with an updated date.

## Contact

If you have questions about this privacy policy, please contact:

**Cengiz Oger**
Email: lexifolio.app@gmail.com
