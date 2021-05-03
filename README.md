# circleci-auto-merge
Automerges to another branch using circle ci

Implements steps from https://support.circleci.com/hc/en-us/articles/360018860473-How-to-push-a-commit-back-to-the-same-repository-as-part-of-the-CircleCI-job

- Any commit on a branch will update test-branch (used for testing that the functionality works)
- Merging `main` branch will auto update staging branch