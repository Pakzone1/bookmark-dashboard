# Offline Bookmark Dashboard

**A single-file dashboard for a bookmark collection that outgrew a list.**

## The problem

Saving the link was easy. Finding it later was apparently a separate project.

This started as an organized bookmark page and grew through practical requests: add a link directly, create a category, fix vague descriptions, and make the collection easier to maintain.

## The solution

An offline HTML bookmark dashboard with searchable cards, editable organization, browser-compatible import/export, and backup/restore.

## What it does

- Search, categories, tags, and notes.
- Add/edit bookmarks and create categories inside the dashboard.
- Favorites, recent items, filtering, and sorting.
- Bulk operations, undo, and duplicate review.
- Browser bookmark HTML import/export and JSON backups.
- Save-file support with a download fallback.

## Engineering highlights

Combines a portable HTML interface with browser storage, explicit save/export paths, and JSON backup/restore. Recoverable bulk edits and duplicate review turn a large personal collection into an editable tool that runs locally.

## Technology

HTML, CSS, vanilla JavaScript, browser storage, file save/download APIs.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.

