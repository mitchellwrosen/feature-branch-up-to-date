## feature-branch-up-to-date

rebase master on a feature branch

should keep feature branch up to date with master branch that has pull request.
BLAH DUDE

Change 1
Change 2

## Usability options:
1) merge request from dev to test. dev should remain up to date.
2) merge request from external fork to dev. merged branch should remain up to date.


## Hypotheseis
```bash
git checkout dev
git merge <feature_branch>
git checkout <feature_branch>
git rebase rebase --no-ff
```

