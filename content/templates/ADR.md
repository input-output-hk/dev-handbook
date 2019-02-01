---
title: "ADR: Architectural Decision Record"
date: 2019-02-01T13:50:34Z
---

An ADR is a point in time record of a concrete endineering decision taken. It
includes sections outlining the context the decision was taken in, a description
of the decision itself and any consequences that should be born in mind for the
future.

You can use the following markdown as a github issue or epic template

```
# Context

<What is the issue that we are seeing that is motivating this decision or
change. Give any elements that help understanding where this issue comes from.
Leave no room for suggestions or implicit deduction.>


# Decision

<Give details about the architectural decision and what it is doing. Be
extensive: use schemas and references when possible. Do not hesitate to use
schemas and references when possible.>


# Acceptance Criteria

<Use standard vocabulary to describe requirement levels RFC-2119: Must-Should-May.
e.g.: The API _must_ support creation of wallets through a dedicated endpoint.>

1. - [ ] ...


---

# PR

| Number    | Base      |
| ---       | ---       |
| [][PR-1] | `develop` |

[PR-1]: https://github.com/input-output-hk/cardano-wallet/pull/


# Consequences

<To be completed in retrospective. What becomes easier or more difficult to do
because of this change.>
```
