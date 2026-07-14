# Math domain reference

Read this before building a ladder for a math problem. It refines the core
methodology; it does not replace it.

## Crux taxonomy — what the key idea usually is

- Invariant / monovariant (processes, games, "can we reach state X?")
- Extremal principle (consider the largest / smallest / closest object)
- Pigeonhole principle
- Induction, infinite descent
- Parity and coloring arguments
- Double counting / counting in two ways
- Symmetry and transformations: reflection, rotation, homothety, spiral
  similarity, inversion, projective maps
- Auxiliary construction — an extra point, line or circle (the most common
  crux in olympiad geometry)
- Reformulation into another model: graphs, complex numbers, coordinates,
  vectors, generating functions, polynomials
- Algebraic identity or a clever substitution
- Working modulo a well-chosen number (number theory)

## Spoiler-power warnings

Naming these usually IS the solution. Never name them at level 2 — give a
broader family instead and push the specific name to level 4 or drop it:

- pigeonhole principle
- extremal principle
- the specific center/radius of an inversion, the specific rotation angle
- the specific auxiliary construction ("consider the midpoint of…")
- the specific invariant quantity
- the induction parameter when finding it is the difficulty

Usually safe at level 2: "this is combinatorics", "number theory helps",
"look for a quantity that does not change", "a geometric transformation
helps", "try to reformulate this as a graph problem".

## Building simpler analogs (level 3)

- Shrink parameters: 2026 → 3 or 4; 100 objects → 2 or 3
- Drop one condition and see what breaks — the analog is the problem where
  it does not
- Degenerate the configuration: square → right triangle, circle → line,
  arbitrary point → midpoint
- Take the 1D version of a 2D statement
- Phrase the key lemma itself as a standalone exercise

Always check the transfer: solving the analog must genuinely light the path
to the original. If the analog is easy for an unrelated reason, it is
decoration, not a hint.

Prefer analogs the student can confirm are real: a standard, nameable lemma
beats one you invented, because the student can look it up and rule out a
hallucination. If you must invent one, say you solved it yourself, and
remember a numeric check only falsifies — it never proves the statement (see
the Honesty rules in SKILL.md).

Skip the analog entirely when the method is a one-step recognition
("quadratic ⇒ discriminant", "sum ⇒ telescoping", "process ⇒ look for an
invariant"): once you have named the method, only computation remains, and
an analog just restages it. A student reads such a rung as filler. Reserve
analogs for cruxes with real conceptual depth to transfer.

## Theory fragments (level 4)

Quote the statement only, without any note on where to apply it. Prefer the
formulation the student has likely met (the "school" or standard olympiad
form), not the most general one. If the theorem has a common name, give the
name too — it lets the student look it up and read around it, which is part
of the learning.

## Terminology traps (example pair: English ↔ Russian)

The same fact often carries unrelated names in different school traditions.
Name facts in the student's tradition and gloss them (see the Terminology
section of SKILL.md). Examples of how far apart names drift — the pattern
generalizes to any pair of traditions:

| English tradition | Russian tradition |
|---|---|
| pigeonhole principle | принцип Дирихле |
| incenter/excenter lemma, "Fact 5" | лемма о трезубце («куриной лапке») |
| power of a point | степень точки |
| AM–GM inequality | неравенство о средних (неравенство Коши) |
| cyclic quadrilateral | вписанный четырёхугольник |
| Vieta jumping | устоявшегося названия нет — описывать приём словами |

The last row is the general rule for any unnamed-locally fact: describe it
in plain words; a transliterated foreign name cannot even be looked up.
