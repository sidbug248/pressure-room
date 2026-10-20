# Pressure Room — project overview

Pressure Room is a small static web application. The live experience runs in the browser without an account or external runtime API calls.

## Design structure

| Layer | Responsibility |
|---|---|
| Rules model | Dependency scheduling, budget accounting, authored incident effects, and deterministic outcomes. |
| Session | Mission, mode, forecast scans, rewind, branching, and replay decoding. |
| Narrative direction | Transmissions, consequence headlines, pressure, and contract endings grounded in the actual state. |
| Interface | Decisions, dependency map, timeline, cinematics, optional sound, run archive, and sharing. |

Separating these responsibilities allows the game rules to be checked independently of the visual effects. The presentation can become more expressive while preserving old replay results.

## Verification evidence

The v0.2 implementation passed 15 model, director, and session tests. These include all 243 complete decision paths, dependency ordering, budget and gauge invariants, mission feasibility, forecast-scan accounting, rewind, branching, and replay validation.

Forty DOM integration assertions execute the actual interface handlers in a simulated document environment. They cover mission selection, forecasts, consequences, endings, rewind, branching, archive behavior, replay links, and sharing/export handler logic.

These checks do not establish rendered-browser quality, actual sound, native keyboard focus behavior, screen-reader behavior, clipboard permissions, operating-system downloads, or mobile usability. A real desktop/mobile browser playtest is the remaining verification gate.

## Boundaries

The release contains one fictional scenario with five fixed incidents and three contracts. It has no backend accounts, multiplayer, empirical forecasting, or claim to evaluate leadership ability. Its spatial map uses CSS perspective rather than a navigable 3D world.

This document describes the implementation at a high level. The public showcase does not distribute the application source or development history.
