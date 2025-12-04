---
name: General Issue
about: Standard issue template for problems or feature updates across the project
title: ""
labels: []
assignees: ""
---

## Issue description
Current Step 2 deployment does not accept changes made by the user in the Step 1 chat interface.

## Link
2.X.X

## Technology
- GPT 5.1
- Container app deployment on Azure

## Solution description
- Add an AI layer (GPT 5.1) that understands the user’s additional requests and determines where they fit in the general workflow.
- Inject the instructions from the model into the specific section to make the required changes (e.g., adding a country to benchmark).
- Always use the framework agreed upon in Step 1 instead of relying on pre-existing frameworks.
- Limit sections to the ones agreed upon with the user.

## Testing
Describe how this should be tested, including expected outcomes, test steps, and any specific scenarios that must be validated.
