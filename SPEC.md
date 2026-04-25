# Click Counter — Spec

## Current State
Nothing exists.

## Desired State
A single-page toybox click counter app. One big button, one number, one reset link. Satisfying to use.

## Phases

### Phase 1 — Core Counter
- Big candy-colored button with tactile press animation (scale down + shadow shift on click)
- Large bold counter number with bouncy pop/scale animation on each increment
- Subtle confetti burst or celebration on milestones (10, 50, 100)
- Small understated reset text link below the button
- Rounded friendly Google Font
- Single `index.html`, all CSS and JS inline
- Mobile-friendly

### Phase 2 — Combo Mode
- Click speed tracker showing clicks per second in real time
- Combo multiplier that builds when clicking fast (2x, 3x, 5x) with escalating visual intensity
- Screen subtly shakes at high combos
- Combo breaks after ~1 second of no clicking, number deflates back down
- Small "best combo" counter that persists in the session

## Success Criteria
- Button feels tactile (visual press feedback)
- Number animates on each click
- Milestones trigger a small celebration
- Passes the AI slop test
- Combo mode adds genuine fidget-game energy

## Risks
None — this is a toy.
