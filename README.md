# GMAIF Workflows

Workflows used by the Greater Manchester AI Foundry[^1] to manage OS repositories. They automatically add issues, pull requests, and review requests to project boards (for a repository) created using the 'Automated kanban with reviews' template.

## Auto-Assign Workflow

The `auto-assign.yml` workflow automatically adds issues and pull requests to the project board. It uses https://github.com/srggrs/assign-one-project-github-action.

## Review Requested Workflow

The `review-requested.yml` workflow automatically moves cards to the appropirate column when a reviewer is assigned. It uses https://github.com/peter-evans/create-or-update-project-card.

[^1]: This work is a direct result of working on the ERDF Greater Manchester AI Foundry which is part funded by the European Regional Development Fund.
