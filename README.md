# circleci-lint

## Quest Details 
#### title: Circle CI lint
#### level: intermediate
#### skills: devops, ci/cd, git
#### dependencies: circleci-configure


## Overview 
In this quest we'll leverage CircleCI and use to to run (and fix) the code on every PR


## Outline
Describe each step in the quest. 
- Step 1: Move to CircleCI Orbs for easier configuration
- Step 2: Configure linting
- Step 3: Configure prettier
- Step 4: Fix the code if we see some prettier problems


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
- Learning Objective: Understand how to add a prettier job to an orb configuration
- Narrative: In this step, you'll learn how to add a prettier job to your orb configuration. Prettier is a tool that automatically formats your code, helping you to maintain a consistent style and making it easier to read and review.
- Instructions: Add a prettier job to your orb configuration. This job should specify the prettier configuration and the files or directories that you want to format.
- How do users pass to the next step: Users can pass to the next step by successfully adding a prettier job to their orb configuration.

#### Step 4:
- Learning Objective: Understand how to set a prettier job to run in write mode
- Narrative: In this step, you'll learn how to set the prettier job to run in write mode. Running prettier in write mode will cause it to automatically make the necessary changes to your code files in place, saving you the need to manually fix
- Instructions: To set the prettier job to run in write mode, you'll need to add the --write flag to the prettier command in your orb configuration. For example: prettier --write "**/*.{js,css,html}"
- How do users pass to the next step: Users can pass to the next step by successfully setting the prettier job to run in write mode.
