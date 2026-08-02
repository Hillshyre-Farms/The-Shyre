# Historical Data Catalog

## Purpose

This document tracks every historical data source for the Rocky Mountain Players Club (RMPC), its verification status, and how it will be incorporated into The Shyre.

## Data Sources

| Source | Coverage | Status | Verification |
|--------|----------|--------|--------------|
| Yahoo Fantasy Sports API | Current + available historical seasons | Pending Approval | Primary |
| Commissioner Emails (Alex Faiks) | Season summaries | Available | High |
| Commissioner Tie-Out Spreadsheets | Season results | To be collected | High |
| League Documents | Rules and history | To be collected | Medium |
| Commissioner Verification | Missing or conflicting records | Ongoing | Highest |

## Verification Rules

- Yahoo API data is the primary source whenever available.
- Commissioner emails are treated as historical evidence.
- Conflicting data is never overwritten automatically.
- Every correction must be traceable to its source.
- Unknown values remain unknown until verified.

## Current Status

- GitHub repository established ✅
- Vercel application deployed ✅
- Supabase database initialized ✅
- Yahoo API application submitted ⏳ Pending
- Historical archive planning in progress ✅
