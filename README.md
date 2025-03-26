<!---
# SPDX-FileCopyrightText: 2025 Deutsche Telekom AG
#
# SPDX-License-Identifier: Apache-2.0
-->

# Iris-Hydra

Iris-Hydra is an Ory Hydra fork, with modifications required so that it can be
used as the "Iris" OAuth2.0 Authorization Server component.

Original ory-hydra [README](HYDRA_README.md)

## Branching

Active development does not take place on the master branch, which is only used
to track Ory Hydra's master branch. Instead, a branch named `iris-hydra-X.Y.Z`
is used, where `X.Y.Z` is the version of Hydra that Iris-Hydra is based on. All
non-Hydra commits should appear AFTER the last Hydra commit in the branch.

**When switching to a new Hydra version, the branch should be rebased on top of
the new Hydra version.**

## Versioning

Iris-hydra uses the same versioning as Hydra, with the addition of a suffix to
indicate the Iris-Hydra specific part. Suffix is in the format `-iris-A.B.C`,
where `A.B.C` is the major, minor and patch version.

Example: `2.3.0-iris-0.1.0`

# License

Since Iris-Hydra is a fork of Hydra, it is licensed under same license, Apache
2.0. For new files, the license header should be added as per the
SPDX-License-Identifier tag at the top of the file.
