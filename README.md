# Git Hooks

## Precommit hook for Pivotal Tracker (PHP / OSX)

https://github.com/ktamas77/git_hooks/blob/master/pivotal_tracker/prepare-commit-msg

Usage:

    Location: <repository>/.git/hooks/prepare-commit-msg

This script will automatically add the correct
Pivotal Ticket ID to the beginning of each commit message
When the branch ID is starts with the Pivotal Message ID.
It can be overridden manually any time if the ID is specified 
in the commit message.

Example:

    1234567_branch_name => '[#1234567] commit message'

