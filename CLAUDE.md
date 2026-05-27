# Participation Tracker

## What this is
A web app for Prof. Kitchens (McIntire) to track student participation 
during class. Used on iPad in-class, reviewed on laptop post-class.

## Core flow
1. Professor opens session view, sees a seating chart of 30 students as tiles
2. Taps a student tile during class
3. Modal opens, picks quality (Substantive / Okay / Just talking) + optional note
4. Submits, contribution logged with auto-timestamp
5. Post-class: reviews session, optionally adds notes
6. Grade time: opens semester summary per student

## Constraints
- Single user for now (just the professor logs in)
- Touch-first UI (iPad), but works on laptop too
- Reliability matters more than features

## Stack
Next.js 15 App Router, TypeScript, Tailwind, shadcn/ui, Supabase, Vercel

## Things to NOT do
- No real-time multi-user collaboration
- No fancy animations that delay taps
- No client-side state that can't survive a refresh
