# git hooks examples
| Hook | Description |
| --- | ---|
| pre-commit | Edits version.cfg file for manual version change |
| prepare-commit | Add info about commit type (commit, merge, rebase) <br> and hash in specific cases (rebase) |
| post-commit | Notifies jenkins to build application <br>Need to setup 2 config variables:<br> user.jenkins-user<br>user.jenkins-api-key|
