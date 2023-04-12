# Aiplus Gitflow

## Branch names

### Name your branch using the structure [tag]/[taskNumber]-[shortDescription]
For example: feat/AIP-t23bmk2-add_datepicker, fix/AIP-mn1bh134-layout_index_page, fix/AIP-qn24nbi

Where tag is:

- **feat** - for features/other new functionals
- **fix** - for fix/error fixing
- **ci** - for ci settings
- **refactor** - for refactoring code
- **chore** - for small fixing

taskNumber needs to be obtained from ClickUp.

You don't have to provide a short description (shortDescription) for a branch name, but if you want to clarify its purpose, you can write a brief explanation. The important thing is not to overdo it and not to write overly long branch names. For example, you can use brief explanations like "change_env" (for changing the environment) or "moment_version_up" (for updating the version of Moment.js).

## Commit messages
1. Write all messages in English.
2. Start messages with a tag.
3. Begin message text with a verb: feat: added..., fix: deleted..., fix: changed...;
4. Write a short but fairly clear message.

## Use fixup

If you have completed a task, made a commit, and want to continue the task the next day, use --fixup=COMMIT_ID in the next commits.

  


