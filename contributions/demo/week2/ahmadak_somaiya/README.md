**The pull request must both contain a README.md and have description following the template below. This README.md must be the only file affected by the PR, and its contents must match the PR description exactly. The pull request must be created 3 business days before the actual delivery.**
**The README.md file must be located in the directory**:

`contributions/<category>/[<week>/]<kth-id-1>-<kth-id-2>/README.md`

# Assignment Proposal

## Title

Rule-based automated test execution through CI-pipeline

## Names and KTH ID

- Ahmad Al Khateeb (ahmadak@kth.se)
- Somaiya Abdulrahman (somaiya@kth.se)

## Deadline

- Week 2, Wednesday 2025-09-03

## Category

- Demo

## Description

Build a CI-pipeline which chooses which tests shall be executed based on what modified/added. For instance, if a Python files added, only run Python-quality checks. Tag-based rules. Also, investigate the posibility of setting dependency-based rules.

**Relevance**

This idea matters to DevOps because in real life scenario, it's not realistic to execute all kinds of test for every push/pull request, and CI should be effective (be effective by being selective). At the same time, we need to make sure that not-verified code is not merged into production before verification. So, a decisive mechanism is needed to make sure only specific tests are executed for specific purpose.
