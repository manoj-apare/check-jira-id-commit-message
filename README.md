# check-jira-id-commit-message
Check jira issue id in commit message using git commit-msg hook

# Installation
Clone or download the `commit-msg` file and place it to your repository `.git/hooks/` directory. Make this file executable using the command `chmod +x commit-msg`.

# Failure cases
1. Branch name with Jira ID and Commit message without Jira ID
1. Branch name without Jira ID and Commit message with Jira ID

# Success cases
1. Branch name with Jira ID and Commit message with Jira ID
1. Branch name without Jira ID and Commit message without Jira ID
1. Branch name with/without Jira ID and Commit message having `merge conflict` keyword.
