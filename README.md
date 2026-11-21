# Rounds

A light networking checklist for photographers: a few people to write to each day, on its own.
The same app lives inside Documenting Fictions (screenersbear.github.io/documenting-fictions/rounds/).

The master copy is the suite: `Documenting Fictions/rounds/`. Don't edit this folder; edit the
suite and copy it out with

    python3 tools/sync.py export rounds

(run in the Documenting Fictions folder). That leaves out the suite's hook and the parts that need
the other notebooks, and gives this copy its own storage (names starting df-rounds), so it never
shares data with Rounds inside the suite.
