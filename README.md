# Gemini Workflow for PR Summaries
Creates a workflow for whole PR diffs and inserts the AI generated summary (from Gemini) in the description field of the PR. 

## To Use:
- Create a GEMINI_API_KEY in GitHub Secrets -> Actions
- Add the workflow to your repo in `.github/workflow.yml`
- It will activate on PR updates and creations
