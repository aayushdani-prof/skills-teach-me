# Teach Me — the engine (skill)

The teaching agent as a skill: the pure behavior contract the runtime app calls.

- Discovery (separate) owns the curriculum graph.
- This skill owns: teaching loop, review scheduling, mastery, exams, artifacts, calibration.
- It never invents curriculum, never adds content it didn't author, never pretends state exists.

## Privacy
Learner state (journal, mastery, review history) never lives in this repo.
All personal learning data stays local to the runtime's `state/` and `artifacts/`.
