name: pr-creation
description: |
A skill for creating pull requests automatically. The title of the pull request is generated based on the changes detected in the repository and should include ticket id. It's description is also generated automatically to summarize the changes made.
The format of the title is:

[TICKET-ID] Short description of the changes

The format of description (in Markdown) is:

## Summary

Short description of the changes made in this pull request.

## Test results

Provided test results, screenshot links, logs etc.

### [Jira ticket](https://your-jira-instance/browse/TICKET-ID)