# Project Map

## Purpose
System design practice repo. Phase 1: LLD problems in TypeScript, w/ design patterns revised and learned alongside. Phase 2 (later): HLD.

## Requirements
- Language: TypeScript.
- LLD first, HLD later.
- Each problem should exercise/revise design patterns.
- Progress gradually thru common LLD problem list (learner decision).

## Components
- `src/<nn>-<problem>.ts`: one file per problem, written by learner (learner decision).
- `test/<nn>-<problem>.test.ts`: tests per problem, written by Claude on request (learner decision).

## Main Flow
Parking Lot (problem 01) in scoping. Learner draft entities: ParkingLot, Car, Ticket (proposed, not confirmed).

## Data and Trust Boundaries
Not applicable yet.

## Build and Deployment
- Implemented: `npm test` = `tsc` then `node --test "dist/test/**/*.test.js"`. TypeScript 7.0.2, strict + noUncheckedIndexedAccess, ESM (nodenext). Verified w/ smoke test 2026-10-28.

## Definition of done (learner decision)
Problem done when learner understands it and can explain reasoning + architecture tradeoffs.

## Unknowns
- Exact problem order beyond "common list, gradual".
