# Grafana Go regexp package
This repo is a fork of the upstream Go `regexp` package, with some code optimisations to make it run faster.

All the optimisations have been submitted upstream, but not yet merged.

All semantics are the same, and the optimised code passes all tests from upstream.

The `main` branch is non-optimised: switch over to `speedup` branch to see the improvements.

