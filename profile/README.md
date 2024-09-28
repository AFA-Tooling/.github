# AFA-Tooling

This is an organization dedicated towards the AFA Tooling Resources developed under Connor Bernard in Dan's R&D Group.

## How To Contribute

1. __DO NOT PUSH TO DIRECTLY TO THE DEFAULT BRANCH__.
2. Make sure you are added to this organization (contact Connor Bernard if needed).
3. Make sure you are added to the organization [Jira](https://dashbd.atlassian.net/jira) (contact Connor Bernard if needed).
4. You may only commit to the default branch with [Pull Requests (PRs)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).
5. All PRs should be associated with a Jira ticket in the respective project.
    - Your branch name should match the format: `<ticket-id>/<brief-description-of-change>`.  eg: `GV-16/create-project-readme`
    - Your PR name should match the format: `[<ticket-id>] <brief-description-of-change>`.  eg: `[GV-16] Add README`
    - Keep your Jira ticket up to date with the status of your ticket.
6. Once a PR has been merged, do not continue using that branch.
8. You should use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for __ALL__ commit messages.
9. Review your code before committing (please don't commit any secrets).

## PR Etiquette

1. You __MUST__ test your code prior to opening a PR as ready for review ([open it as a draft](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-stage-of-a-pull-request) if you push before then).  If your commit breaks something, it is your responsibility to [revert the PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/reverting-a-pull-request) and complete any necessary emergency maintinance to resolve the issue.
2. PRs should cover __ONLY__ what is considered relevant for the PR (you make make minor cleanups or related refactors).
3. All automated tests must pass prior to opening your PR for review.
4. Upon opening your PR for review, please link your PR in the associated slack channel or otherwise notify the team.
5. All PR comments must be resolved prior to merging.
6. All PRs must have at least one review prior to merging (this can be done by anyone in the team).
7. Once you open your PR, it is your responsibility to merge it in a timely manner, so be proactive in responding to comments and making necessary changes.
8. Please review PRs if you feel comfortable with the change types (remember to update the respective Jira tickets as necessary).
