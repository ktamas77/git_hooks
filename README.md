# Git Hooks

## Precommit hook for Pivotal Tracker (PHP / OSX / Linux)

https://github.com/ktamas77/git_hooks/blob/master/pivotal_tracker/prepare-commit-msg

Usage:

    Location: <repository>/.git/hooks/prepare-commit-msg
    chmod +x <repository>/.git/hooks/prepare-commit-msg # make executable

This script will automatically add the correct
Pivotal Ticket ID to the beginning of each commit message
when the branch ID is starts with the Pivotal Message ID.
It can be overridden manually any time if the ID is specified 
in the commit message.

Example:

    1234567_branch_name => '[#1234567] commit message'

## Precommit hook for JIRA (PHP / OSX / Linux)

https://github.com/ktamas77/git_hooks/blob/master/jira/prepare-commit-msg

Usage:

    Location: <repository>/.git/hooks/prepare-commit-msg
    chmod +x <repository>/.git/hooks/prepare-commit-msg # make executable

This script will automatically add the correct
JIRA Issue ID to the beginning of each commit message
when the branch ID is starts with the JIRA Issue ID.
It can be overridden manually any time if the ID is specified 
in the commit message.

Example:

    JIRA-123_branch_name => 'JIRA-123 commit message'


