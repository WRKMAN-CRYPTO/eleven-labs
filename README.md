# WRKMAN Eleven Labs

A living fieldbook for Eleven Music experiments.

The goal is not to collect pretty prompts. It is to keep **repeatable evidence** about what the model actually does: which instructions it obeys, where it drifts, what improves vocals, and which prompt fragments are worth reusing.

## Live fieldbook

https://wrkman-crypto.github.io/eleven-labs/

## Canonical data

`data/experiments.json` is the source of truth.

Each run records:
- model/version
- duration and credit cost
- generation type
- full prompt
- lyrics when applicable
- observed result
- searchable tags

Confirmed findings are linked back to the test IDs that produced them.

## First useful finding

For vocal generations, emotional adjectives alone were not enough. The successful prompt described **vocal mechanics**: sustained notes, wide pitch movement, vibrato, bends, melisma, chest voice, and an explicit ban on talk-singing.

That reusable foundation is surfaced at the top of the fieldbook.

## Rule

We record what happened, not what we hoped would happen.
