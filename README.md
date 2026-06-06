# Rings

Personal CRM built on Dunbar's circles.

Concentric rings — 3, 12, 30, 50, 100, 200 — each with a calibrated reminder cadence (every two weeks for the inner three; every four months for the outer hundred). Friends sit in a ring; the app reminds you when it's been long enough.

Started as a Python `tkinter` prototype. Currently Version 2.1 — a multi-device Swift app for iPhone and Mac with CloudKit sync.

## Why
The Dunbar number isn't a budget; it's an attention shape. Inner-three friends need you every two weeks. Outer-hundred get a polite check-in every four months. Without a system the inner three slip and the outer hundred get nothing.

## How it works
```
Add friend → assign ring → app schedules next check-in
  → when you contact them, tap "marked" → reschedule
```

## Stack
SwiftUI · CloudKit · iOS + macOS (catalyst) · Local-first

## Status
Version 2.1, Jan 2025 — in personal use.
