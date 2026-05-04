# Contributing — Robo-Greeno Data A

This repository is part of the **KamaTech OSS On-the-Job Training**
program. Contributions are expected primarily from program
participants and TAs, but issues, discussion, and pull requests from
the wider open-source community are welcome.

## How participants work in this repo

1. Each weekly phase in [`PLAN.md`](PLAN.md) corresponds to a folder
   that gets added when the phase begins.
2. Work happens on feature branches named `wkN/<short-topic>` (for
   example `wk2/forward-kinematics`).
3. Open a pull request when the branch is ready for review. Reviews
   are part of the OJT learning loop — expect comments, expect to
   iterate.
4. Each phase ends with a tagged release (`wk2-ik`, `wk5-imu`, ...)
   so the bootcamp lab corresponding to that phase has a stable
   reference point.

## Issue conventions

Use issue labels:

- `phase/wkN` — which week the issue belongs to
- `track/data-a` — vs cross-track issues
- `bootcamp` — when the work also feeds the future bootcamp lab
- `cross-team` — touches Embedded, Cloud, or Data B

## Cross-team coordination

For changes that touch shared interfaces (URDF, telemetry schema,
relative-pose conventions), open an issue with the `cross-team` label
and tag the relevant mentor before merging. See [`README.md`](README.md)
for the current mentor list.

## License

All contributions are accepted under the MIT license — see
[`LICENSE`](LICENSE).
