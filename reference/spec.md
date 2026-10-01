# Phase 0 Audit Spec (Blocked)

## Status
Phase 0 is currently blocked because the reference URL cannot be resolved from this environment:
- `https://airbnb-clone-umber-two.vercel.app`

## Evidence
- Playwright browser navigation failed with `net::ERR_NAME_NOT_RESOLVED`.
- DNS lookup failed (`No address associated with hostname`).
- `web_fetch` failed with `failed to lookup address information`.

## What I completed
- Created `/home/runner/work/airbnb-clone/airbnb-clone/reference/screens`.
- Set up browser automation tooling locally and attempted live-page capture.
- Confirmed the blocker is network/DNS resolution for the reference domain.

## Required to continue Phase 0
Please provide one of the following so I can finish the audit exactly as requested:
1. A reachable reference URL, or
2. Access to the current reference domain from this environment, or
3. A complete screenshot pack/video at 1440x900 plus computed-style exports.

## Pending Phase 0 outputs (will produce immediately once unblocked)
- Full screenshot set in `/home/runner/work/airbnb-clone/airbnb-clone/reference/screens` for:
  - Listing page key scroll positions
  - Photo Tour overlay
  - Lightbox overlay
  - Both 1440x900 and 1920x1080 checks
- Final measured spec (layout px, typography, colors, gradients, motion timings, interaction behavior, asset URLs)
