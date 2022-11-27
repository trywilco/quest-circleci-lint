# circleci-configure

## Quest Details 
#### title: Circle CI configure
#### level: intermittent
#### skills: devops, cicd, git
#### dependencies: docker-localsetup


## Overview 
In this quest we'll configure circle ci on Anythink market


## Outline
Describe each step in the quest. 
- Step 1: Configure a simple workflow to make sure circle ci is reading the configuration from the repo
- Step 2: Go to CircleCI and re-run the task
- Step 3: Codnfiure the workflow to run tests on the frontend
- Step 4: Open a PR with the code changes.


## Textbook solution

### Instructions for completing the quest: 
#### Step 1: 
- Learning Objective: CircleCI basic configuration
- Narrative: We want to integrate CircleCI for better CI/CD, for start let's add this simple configuration
- Instructions: Copy this file and put in the .circleci folder, a new task will be created
- How do users pass to the next step: once the file was added and push, we can detect a new task in CircleCI
 
#### Step 2: 
- Learning Objective: CircleCI UI
- Narrative: ok, we see the task was failed, can you re-run it from CircleCI UI and send us the error?
- Instructions: Open an account, find your repo and see the task and the error
- How do users pass to the next step: Send the right error message
 
#### Step 3: 
- Learning Objective: CircleCI advanced configuration
- Narrative: Now we need to configure this properly and make the workflow run the frontend tests
- Instructions: Fix the errors from the prevoius step
- How do users pass to the next step: The task running succefully
 
#### Step 3: 
- Learning Objective: CircleCI advanced configuration
- Narrative: OK, we have everything we need now we need to make sure it's running on every PR
- Instructions: Open a PR with the changes
- How do users pass to the next step: Merge the PR
