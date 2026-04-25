# Click Counter — Spec

## Overview
Single-page toybox click counter app. One big button, one number, satisfying to use.

## Design Direction
Toybox aesthetic. Warm cream background, candy blue button with 3D press effect, bouncy counter animation. Milestone confetti. See `.impeccable.md` for full design context.

## Phases

### Phase 1 — Core Counter ✅
- Big candy-colored button with tactile press animation (scale down + shadow shift)
- Large bold counter number with bouncy pop/scale animation on each increment
- Subtle confetti burst on milestones (10, 50, 100)
- Small understated reset text link
- Single index.html, all CSS/JS inline
- Mobile-friendly

### Phase 2 — Combo Mode ✅
- Click speed tracker (CPS) — real-time, subtle display
- Combo multiplier that builds on fast clicking (2x, 3x, 5x, 7x, 10x)
- Escalating visual intensity: blue glow → orange glow → red glow + screen shake
- Combo breaks after ~1s of no clicking, deflates smoothly
- Session best-combo counter

### Phase 3 — Design Sweep (Bubblegum Pop) 🔄
- Full visual redesign using impeccable skill
- Direction: Y2K revival — translucent plastics, iridescent highlights, bubbly shapes
- Think iMac G3, Tamagotchi, jelly sandals
- Questions and design direction pending approval

## Success Criteria
- Button feels tactile
- Number animates on each click
- Milestones trigger celebration
- Combo mode adds fidget-game energy
- Passes the AI slop test

## Decisions Log
- Phase 1: approved, button changed from coral to blue per Pan's request
- Phase 2: approved as-is
- Phase 3: Bubblegum Pop direction chosen from 5 options, design questions in progress
