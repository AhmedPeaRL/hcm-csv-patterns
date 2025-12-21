# Release Map

This document defines **where an artifact is allowed to appear**,
not where it must appear.

An artifact may exist without release.
An artifact may be released without promotion.
An artifact may be released to one interface and withheld from others.

## Possible Interfaces

- GitHub Releases
- Gumroad
- Lemon Squeezy
- Sellix
- itch.io
- GitHub Sponsors
- Ko-fi

Presence on an interface does not imply priority.
Absence does not imply rejection.

## Mapping Logic

Each artifact is evaluated against:
- Field condition
- Internal coherence
- Non-reactivity to market signals

Only interfaces marked as `allowed` in `platforms.lock`
may receive the artifact.

Release is an **interface**, not a goal.
