# Use ADRs to Capture Architecturally Significant Decisions

* Status: proposed
* Deciders: Elf 1, Elf 2
* Date: 2022-12-22

Technical Story: Some jira ref...

## Context and Problem Statement

As a team, we want to capture architecturally significant decisions in a log so that we have explicit points of reference and context for past decisions made to help us evaluate our own workflows, and onboard new team members into how and why decisions were made.

## Decision Drivers

* Light-touch process
* Support for the MADR lifecycle (proposed -> accepted/rejected -> deprecated/superseded)

## Considered Options

* Agree to use ADRs

## Decision Outcome

Chosen option: "Agree to use ADRs", because team consensus was unanimous that ADRs should be used

### Positive Consequences

* Decisions (including this one to use ADRs) will be explicit captured including chronology of deprecations and superceding decisions
* We must choose tooling to manage the ADRs

## Pros and Cons of the Options

### Agree to use ADRs

Agree to capture architectural decisions in a running log of records

* Good, because Allows the team to see how decisions were made and evolved over time
* Good, because Allows new team members to understand how the team got to where it is today
* Good, because Explicitly captures context and implicit knowledge about decision
* Bad, because Introduces another potential process into our workflow
* Bad, because Requires iteration to settle on what size of decision constitutes an ADR
