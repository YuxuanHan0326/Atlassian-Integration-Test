# Atlassian-Integration-Test
This repo is used to test the GitHub functionalities integration with Atlassian tools (Jira + Confluence)

This repo is linked to the ticket GCT-2. Here are some subtasks:
- GCT-3 : Create a branch, edit README.md, commit, pull-request (CL), review and merge.


## General Project Development Workflow
I usually disable main branch commitment. You need to branch and pull-request to merge (a.k.a. changelist). One member to review to approve merge. All comments on changelist during review need to be re-solved.

**Full Process:**

Branch (Create CL) ---> Edit code and testing ---> Commit and push to branch ---> Pull-request (Request review) ---> Go through review (re-edit code to resolve comments) ---> Merge to main

## Reminders
To enable updates in Jira, you need to:
- Include Jira ticket number in branch name (e.g. *GCT-3-Test*).
- Include Jira ticket number in commit name (e.g. *GCT-3 Update README.md*)
- Include Jira ticket number in pull request (e.g. *GCT-3 Update README.md PR*)
