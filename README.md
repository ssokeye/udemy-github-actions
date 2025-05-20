# udemy-github-actions for development
Repository with all learnings of github actions for development

Github Action Fundamentals
Is a CI/CD solution provided by Github
We have workflows, jobs and steps.

Workflows
- Defined at the repository level
- Deine which triggers (e.g on) actually start the workflow.
- Are composed of one or more jobs
    Jobs - 
    - Are Defiend at the workflow level
    - Define in which execution environment they are run
    - Are composed of one or more steps
    - Jobs run on independing machines
    - Run parrallel by default
        Steps
        - Are defined at the jobs leve
        - Define the actual script or GitHub action that will be executed
        - Run sequential by default
