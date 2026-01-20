# Git branching

## Trunk-Based Development

It is a Git branching stategy that emphasizes frequent intergration and testing on the main branch to ensure a high level of collaboration and continuous delivery.
For projects with frequent code changes and continuous releases.
Smaller teams.
High collaboration and communication needed, as all changes are made directly to *main*.

## Feature Branching

It is a Git branching strategy that involves creating separate branches for individual features or changes to allow for isolation, testing, and review before merging into the *main* branch.
For project with simulataneous development of different features.
Medium or large sized teams.
Moderate collaboration maturity, as changes occur on separate branches before merging into *main*.

## Git Flow

It is a Git branching model that builds on **Feature Branching** by adding additional branches for managing releases and hotfixes, providing structure approach for managing realeses and hotfixes, providing a structured approach for managing diff types of changes in larger teams or more complex projects.
For projects requiring structured approach.
Larger teams.
High collaboration maturity, as changes involve multiple branches and a formalized release process.