# Instructions for Gemini

This file contains instructions for the Gemini CLI agent on how to perform tasks in this project.

## Local Testing

When asked to "test run" or similar, start a local web server to preview the website.

-   **Command:** `npm run preview`
-   **Directory:** `cnorth-source`
-   **Execution:** Run the server in the background or a new window to avoid blocking the current session.

## Git Workflow

The agent is responsible for the entire Git workflow. The user will provide high-level instructions, and the agent will execute the necessary `git` commands.

-   **Staging:** `git add .`
-   **Committing:** `git commit -m "Your descriptive message here"`
-   **Pushing:** `git push`. The agent will execute this command, and the user will handle any authentication prompts.
