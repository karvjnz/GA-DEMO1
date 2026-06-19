# GA-DEMO1
Github Actions Demo
Source: https://www.youtube.com/watch?v=sZ_Z8l95g4s

# how to create your first GitHub workflow using GitHub Actions. Here is a breakdown of the process:

1. Project Setup : You must create a specific directory structure in your repository: .github/workflows. This is where all your workflow configuration files (YAML) reside.

2. Workflow Configuration: A workflow is defined by a YAML file containing:
  Name: A descriptive label for the workflow.
  Trigger: The on section defines which events (e.g., a push to the main branch) execute the workflow.
  Jobs: A workflow must have at least one job. The demo job uses ubuntu-latest as the runner.
  Steps: These are individual tasks within a job. The example shows a greetings step that executes a shell command to print "hello world."

3. Execution and Monitoring: After committing the file, the workflow triggers automatically in the Actions tab.
  You can:
  View the success status and execution time.
  Inspect job logs to see the runner environment, specific step outputs, and cleanup processes.
  Review the raw logs or download them for troubleshooting.

