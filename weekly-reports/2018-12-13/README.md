# Summary

Reward withdrawals in the Haskell model; Began integrating the STS framework
from cardano-chain into Haskell model; Reworked the reward withdrawals in the
latex spec to align with our new plan for them.

# PRs and issues completed

| Issue | PR | Summary |
|-------|----|---------|
|       | x | [Anytime rewards rules #113](https://github.com/input-output-hk/fm-ledger-rules/pull/113) |
|       | x | [experiment to try small step sem. with lhs2tex #114](https://github.com/input-output-hk/fm-ledger-rules/pull/114) |
|       | x | [STS implementation of `UTXO` rule #115](https://github.com/input-output-hk/fm-ledger-rules/pull/115) |
|       | x | [Use lenses from `mircolens` where appropriate #116](https://github.com/input-output-hk/fm-ledger-rules/pull/116) |
|       | x | [adding reward withdrawals #120](https://github.com/input-output-hk/fm-ledger-rules/pull/120) |
|       | x | [Update `UTXO` rule for new STS framework #121](https://github.com/input-output-hk/fm-ledger-rules/pull/121) |
| x     |   | [Reward Withdrawals (executable model) #88](https://github.com/input-output-hk/fm-ledger-rules/issues/88) |

| Issue/PR | Summary | Epic | Contributors | Created | Finished | Comments|
|----------|---------|------|--------------|---------|----------|---------|
| [13](https://github.com/input-output-hk/fm-ledger-rules/issues/13) | literate haskell? | | [mgudemann](https://github.com/mgudemann), [JaredCorduan](https://github.com/JaredCorduan) | 2018-10-19 | 2018-12-13 | |
| [41](https://github.com/input-output-hk/fm-ledger-rules/issues/41) | preservation of total ada & deposits | | [JaredCorduan](https://github.com/JaredCorduan) | 2018-10-29 | 2018-12-13 | |
| [55](https://github.com/input-output-hk/fm-ledger-rules/issues/55) | Property Tests for Value Transactions | | [mgudemann](https://github.com/mgudemann) | 2018-11-06 | 2018-12-13 | |
| [59](https://github.com/input-output-hk/fm-ledger-rules/issues/59) | Generators for invalid data | | [mgudemann](https://github.com/mgudemann) | 2018-11-07 | 2018-12-13 | |
| [60](https://github.com/input-output-hk/fm-ledger-rules/issues/60) | Investigate Property Coverage Analysis | | [mgudemann](https://github.com/mgudemann) | 2018-11-07 | 2018-12-13 | |
| [74](https://github.com/input-output-hk/fm-ledger-rules/issues/74) | Discuss delegation | | [polinavino](https://github.com/polinavino) | 2018-11-15 | 2018-12-13 | |
| [75](https://github.com/input-output-hk/fm-ledger-rules/issues/75) | Discuss witnessing and complete ledger state transitions | | [polinavino](https://github.com/polinavino) | 2018-11-15 | 2018-12-13 | |
| [76](https://github.com/input-output-hk/fm-ledger-rules/issues/76) | Discuss the accounting model | | [polinavino](https://github.com/polinavino) | 2018-11-15 | 2018-12-13 | |
| [77](https://github.com/input-output-hk/fm-ledger-rules/issues/77) | Write introduction and outline UTxO updates | | [polinavino](https://github.com/polinavino) | 2018-11-15 | 2018-12-13 | |
| [78](https://github.com/input-output-hk/fm-ledger-rules/issues/78) | Discuss updated accounting model | | [polinavino](https://github.com/polinavino) | 2018-11-15 | 2018-12-13 | |
| [80](https://github.com/input-output-hk/fm-ledger-rules/issues/80) | Resolve double-depositing in the LaTeX spec rules | | [polinavino](https://github.com/polinavino) | 2018-11-15 | 2018-12-13 | |
| [81](https://github.com/input-output-hk/fm-ledger-rules/issues/81) | Discuss epoch boundary ledger state updates | | [polinavino](https://github.com/polinavino) | 2018-11-15 | 2018-12-13 | |
| [84](https://github.com/input-output-hk/fm-ledger-rules/issues/84) | Write generators / mutators for `DelegationData` | | [mgudemann](https://github.com/mgudemann) | 2018-11-16 | 2018-12-13 | |
| [91](https://github.com/input-output-hk/fm-ledger-rules/issues/91) | Add "no double-spend" to Properties and implement property based test for it | | [mgudemann](https://github.com/mgudemann) | 2018-11-19 | 2018-12-13 | |
| [94](https://github.com/input-output-hk/fm-ledger-rules/issues/94) | Implement replay protection for transactions | | [mgudemann](https://github.com/mgudemann) | 2018-11-20 | 2018-12-13 | |
| [110](https://github.com/input-output-hk/fm-ledger-rules/issues/110) | Make rewards possible to withdraw any time (LaTeX) | | [polinavino](https://github.com/polinavino) | 2018-12-03 | 2018-12-13 | |
| [123](https://github.com/input-output-hk/fm-ledger-rules/pull/123) | Transactions update fees and deposits in UTxOState | | [JaredCorduan](https://github.com/JaredCorduan) | 2018-12-12 | 2018-12-14 | |
| [124](https://github.com/input-output-hk/fm-ledger-rules/pull/124) | Witnesses cleaned up | | [polinavino](https://github.com/polinavino), [JaredCorduan](https://github.com/JaredCorduan) | 2018-12-12 | 2018-12-14 | |
| [125](https://github.com/input-output-hk/fm-ledger-rules/pull/125) | Add weekly report 2018-12-13 | | [mgudemann](https://github.com/mgudemann), [boothead](https://github.com/boothead), [JaredCorduan](https://github.com/JaredCorduan) | 2018-12-13 | 2018-12-13 | |
| [127](https://github.com/input-output-hk/fm-ledger-rules/pull/127) | Property-based tests after witness checking | | [mgudemann](https://github.com/mgudemann) | 2018-12-14 | 2018-12-14 | |
| [129](https://github.com/input-output-hk/fm-ledger-rules/pull/129) | Remove unused module | | [mgudemann](https://github.com/mgudemann) | 2018-12-14 | 2018-12-14 | |
| [130](https://github.com/input-output-hk/fm-ledger-rules/pull/130) | Implement `UTXO` part of rule hierarchy | | [mgudemann](https://github.com/mgudemann) | 2018-12-14 | 2018-12-14 | |
| [131](https://github.com/input-output-hk/fm-ledger-rules/pull/131) | adding version, IOHK team author, and page breaks | | [JaredCorduan](https://github.com/JaredCorduan) | 2018-12-14 | 2018-12-14 | |
| [133](https://github.com/input-output-hk/fm-ledger-rules/pull/133) | Pointer addresses | | [polinavino](https://github.com/polinavino), [JaredCorduan](https://github.com/JaredCorduan) | 2018-12-16 | 2018-12-18 | |
| [134](https://github.com/input-output-hk/fm-ledger-rules/pull/134) | Swapping the names created and destroyed | | [JaredCorduan](https://github.com/JaredCorduan) | 2018-12-17 | 2018-12-17 | |
| [136](https://github.com/input-output-hk/fm-ledger-rules/pull/136) | STS rule `DELRWDS` | | [mgudemann](https://github.com/mgudemann) | 2018-12-17 | 2018-12-17 | |
| [137](https://github.com/input-output-hk/fm-ledger-rules/pull/137) | STS rule `DELEG` | | [mgudemann](https://github.com/mgudemann) | 2018-12-17 | 2018-12-18 | |
| [138](https://github.com/input-output-hk/fm-ledger-rules/pull/138) | Further changes to delegation design doc | | [kantp](https://github.com/kantp) | 2018-12-17 | 2018-12-18 | |
| [140](https://github.com/input-output-hk/fm-ledger-rules/pull/140) | Delegation design doc V1.0 | | [kantp](https://github.com/kantp) | 2018-12-18 | 2018-12-18 | |

# Milestone status

List of all milestones

## [Milestone title](https://github.com/input-output-hk/repo/milestone/1)

Summary of underway milestone

| Title                             | Value      |
|-----------------------------------|------------|
| Start Date                        | YYYY-MM-DD |
| Target end Date                   | YYYY-MM-DD |
| Estimated end Date                | YYYY-MM-DD |
| Issues Completed this week        | 1          |
| Total issues (complete/remaining) | 5/10       |

## [Milestone title](https://github.com/input-output-hk/repo/milestone/2)

No started yet

# Epic status

## [Epic title](https://github.com/input-output-hk/repo/issues/1)

| Title                             | Value |
|-----------------------------------|-------|
| Issues Completed this week        | 1     |
| Total issues (complete/remaining) | 5/10  |

## [Epic title](https://github.com/input-output-hk/repo/issues/2)

Not started yet

# Lessons learned from last week

 - When challenges come up while working on an issue, then create a new issue
   for this with additional estimation
 - Connect PRs to issues, can be several PRs for one issue

# Things to try next week

 - Think about merging `fm-ledger-rules` into `cardano-chain`
