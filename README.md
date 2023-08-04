# GithubsActionDemo

Github Actions Step by Step By DEMO for Beginners

DEMO
1. Signup and Login to Github.com
2. Create new repository
3. In the repo create a folder .github/workflow
4. In the folder create a YAML file with extension .yml extension
5. Add the content of the workflow in the file
6. Commit and pushes changes
7. Go to Repo main page and click "Actions" tab
8. Select the workflow from left sidebar and check the logs and results.

TERMINIOLOGY USED
1. WORKFLOW: Collection of jobs, defined in yaml file
   name:
2. EVENTS: any activity in the repo that can trigger a workflow
   on:
3. JOBS: Collections of steps
   jobs:
4. STEPS: Action to be taken, commands, scripts
   steps:
5. Chain Jobs: needs
