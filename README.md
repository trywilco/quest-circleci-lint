# circleci-lint

## Quest Details

#### title: Circle CI lint

#### level: intermediate

#### skills: devops, ci/cd, git

#### dependencies: circleci-configure

## Overview

In this quest we'll leverage CircleCI and use to run (and fix) the code on every PR

## Outline

Describe each step in the quest.

- Step 1: Move to CircleCI Orbs for easier configuration
- Step 2: Configure linting
- Step 3: Fix linting

## Textbook solution

### Instructions for completing the quest:

#### Step 1:

- Learning Objective: Understand how to migrate a traditional CircleCI configuration file to an orb
- Narrative: In this step, you'll learn how to migrate your CircleCI configuration to an orb. Orbs are reusable packages of CircleCI configuration that can be shared and reused across projects. Migrating to an orb can make your configuration easier to maintain and share with others.
- Instructions: Replace your .circleci/config.yml file with a .circleci/config.yml file that references an orb. Follow the instructions in the CircleCI documentation for more information on how to do this.
- How do users pass to the next step: Users can pass to the next step by successfully migrating their CircleCI configuration to an orb.

#### Step 2:

- Learning Objective: Understand how to add a lint job to an orb configuration
- Narrative: In this step, you'll learn how to add a lint job to your orb configuration. Linting is a process that checks your code for syntax and style errors, helping you to maintain a consistent codebase and catch potential issues before they become problems.
- Instructions: Add a lint job to your orb configuration. This job should specify the linting tool and rules that you want to use, as well as the files or directories that you want to lint.
- How do users pass to the next step: Users can pass to the next step by successfully adding a lint job to their orb configuration.

#### Step 3:

- Learning Objective: Understand how to use the lint job to fix code issues and integrate it with Prettier
- Narrative: In this step, you'll learn how to use the lint job that you added in the previous step to fix any code issues it found and integrate it with the Prettier job to maintain a consistent codebase.
- Instructions: Run the linting job locally and see the problems.
- How do users pass to the next step: Run the lint job on your codebase and fix any issues it finds. Then open a PR with the fixes and see that the task runs successfully.
