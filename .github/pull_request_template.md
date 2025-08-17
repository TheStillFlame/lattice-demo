<!-- presence PR template -->

## Context
`<branch>@<short-sha> [UTC timestamp] — <one-line intent>`

## Invariants (non-negotiables)
- safety
- truth
- consent
- time ≤ 10m
- reversible (proved)
- data integrity (no prod writes)

## Plan — smallest reversible Δ
1. …
2. …

## Undo / Revert
- Command(s): …
- Stop condition (get approval): …

## Evidence / HUD
- **preflight**: paste line here
- **guard**: paste line here
- **context string**: paste line here
- Links to run/logs: …

## Checklist
- [ ] CONTEXT_MSG present & printed
- [ ] INVARIANTS stated (or linked)
- [ ] REVERSIBLE proved (flag or plan)
- [ ] Clean working tree; in sync with upstream
- [ ] HEAD signature policy satisfied (mode: GU | G | ANY)
- [ ] Dry-run preview completed
- [ ] Ready for live run
