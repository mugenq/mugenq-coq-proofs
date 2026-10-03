# Coq Proofs and Exercises

A small archive of introductory work I did with the Coq proof assistant over roughly two months.

I used Coq to learn the mechanics of formal proof: propositions, tactics, induction, recursive definitions, and reasoning about natural numbers. The repository is intentionally modest in scope. It shows early hands-on experience with a proof assistant rather than a completed formal-verification project.

## What I worked on

Among the exercises and proofs in this repository:

- defined recursive functions over natural numbers, including addition and parity checks;
- proved associativity for a recursively defined addition function;
- worked with induction over natural numbers;
- proved basic facts about boolean negation and inequality;
- developed parity results such as proving that numbers of the form `2n` are even and numbers of the form `2n + 1` are odd;
- practiced propositions, conjunctions, disjunctions, existence proofs, rewriting, contradiction, and tactic-based proof construction;
- experimented with divisibility notation and small arithmetic lemmas.

Some exercises remain unfinished and use `Admitted`. They are kept deliberately as part of the learning history rather than being presented as completed proofs.

## Files

- `Introduction_to_Coq.v` — introductory definitions and proofs, including recursive addition and associativity.
- `Tactics_Examplex.v` — tactic and proof experiments.
- `Tutorial.v` — a longer learning file covering propositions, naturals, induction, recursive functions, parity, and related exercises.
- `test_evenb.v` — experiments around a recursive parity function and even/odd proofs.
- `test1.v` through `test4.v` — smaller exercises and experiments.
- `nahas_tutorial.v` — tutorial/reference material retained with the original learning archive.

## Current direction

I am now moving from Coq toward Lean for further experimentation with theorem proving and formal mathematics. The Coq material remains here as a record of my first experience working with a proof assistant.

## Dependencies

Some files use Coq's standard libraries and MathComp/ssreflect imports. Exact compatibility may depend on the Coq and MathComp versions installed.
