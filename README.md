# dhis2-bot

Your friendly neighborhood dhis2-bot.

# Features

-   Pulls: Labels
    -   [ ] Auto-merge pull requests when checks pass and there is an `automerge` label
    -   [ ] Trigger `dhis2-preview-pr` workflow when there is an `preview`
            label.
-   Pulls: Comments
    -   [ ] Add useful information to a pull request, e.g. size changes on
            the bundle, or warn against when changes introduce breaking
            changes.
    -   [ ] Automatically add links back to Jira if a ticket key can be
            found in a commit, description, or comment. Optionally, add a link
            to the PR in the Jira ticket.
