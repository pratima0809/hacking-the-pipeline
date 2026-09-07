# Hack the Pipeline

This repo is the target for Haxnation Session 2. Fork it, then work through
the four cycles from the session. Each cycle asks you to find a leak first,
then fix it in your own fork before moving to the next one.

Submit flags on the separate leaderboard repo shared with you in the
session, not here.

## The pipeline

`.github/workflows/ci.yml` runs on every push and pull request. It looks
like a completely normal build pipeline. It is not.
The pipeline
