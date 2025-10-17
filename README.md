# Compute stats on recently reviewed PRs

A Jupyter Notebook that can compute stats on your recently reviewed PRs, such as line count summary statistics.

## Usage

Supply a .env file with the following:

- `GITHUB_TOKEN` - the GitHub token with which you will make authenticated requests to the GitHub API. If you have authenticated with the GitHub CLI, you can find this by running `gh auth token`.
- `GITHUB_USERNAME` - the GitHub username of the user whom you will compute statistics about.

## More information

Created using GPT-4.1 using Agent Mode in VS Code, with some light human-modifications to improve usability, customize the output, and fix bugs.

This was the prompt provided:

> I was asked about the 'average size of a pull request' I have been asked to review. I would like to create a Jupyter notebook that does the following:
>
> - Gets statistics about the pull requests that I most recently reviewed (say, the last 100)
> - Compute summary statistics about these pull requests
> - Create graphs that communicate the spread, mean, and median line count of these pull requests.
