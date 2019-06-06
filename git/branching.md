# Branching

## Branches

1. `master` - main branch.
2. `dev` - main dev branch.
3. `dev-*` - feature branches.

## Process

1. `dev` branch is merged into `master` on a monthly basis via a PR.
2. `dev-*` branches are merged into `dev` branch via PRs upon completion of feature development.
3. Before `dev-*` branches are merged into `dev`, there should be no merge conflicts. If there are, `dev` branch should be merged into `dev-*`, and `dev-*` should be rebased.