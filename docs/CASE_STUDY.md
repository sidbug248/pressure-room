# Pressure Room — from planning experiment to game

Pressure Room is the first release in **Experiments in What If**, a collection of playable ideas by Siddy.

## The design problem

The original release made a decision's consequences easy to inspect. Its visual language and premise worked, but revealing every answer before commitment left little tension. The second pass gives the player a goal, limits perfect information, and makes the aftermath a dramatic event.

## What changed in v0.2

Three contracts create distinct win conditions within the same fictional launch. Pressure mode offers two forecast scans: the player chooses which response deserves exact information. Sandbox preserves unrestricted exploration. One rewind offers recovery without refunding scans. After the ending, branching from a prior call encourages comparison without repeating every earlier choice.

Incoming transmissions react to earlier choices. A specialist hired during integration changes the tone of the next message; sponsor and access choices influence later messages. These reactions add continuity without undisclosed numerical effects.

Full-screen consequence scenes use fading, blurred text, spatial layers, and optional sound. Titles respond to the choice and actual forecast. The game does not invent a failure just to produce a dramatic message. Scenes can always be continued or dismissed immediately; motion can be disabled.

The map now uses shallow CSS perspective and layered field effects. It is a spatial treatment of the existing dependency graph, not a freely navigable 3D world. The timeline remains available.

## Preserving the original run

The v1 reference route A → C → B → B → B still produces day 19, $4,000 reserve, energy 67, and trust 87. The new balanced-contract ending is: **YOU OPENED. YOU SPENT THE CUSHION.**

That route fulfills the balanced contract. It misses the audience contract's trust target and the crew contract's energy target. Different goals give the same decisions different meanings.

## Honest scope

This release still contains one scenario and five fixed incidents. Three contracts, partial information, adaptive narration, and branching increase ways to play without implying three entirely different scenarios. The schedule remains an authored planning forecast rather than a simulation of elapsed calendar time or completed work.

There is no scoring claim about a real person's leadership. The model is fictional, deterministic, and limited.

## Verification

Fifteen model, director, and session tests pass. They examine all 243 complete paths, reachable director outputs, contract feasibility, unchanged legacy results, and replay/control invariants. Forty DOM integration assertions exercise the real application handlers. JavaScript syntax checks pass.

DOM checks do not establish visual quality, native keyboard navigation, screen-reader behavior, actual clipboard or downloads, or audio quality. A full desktop and mobile browser playtest is the next release-quality gate.

## Authorship

Creative direction and review: Siddy. Development: created with ChatGPT and AI coding assistance. No real client material, private EF product implementation, or personal records form part of the game.
