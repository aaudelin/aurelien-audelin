# Rebase feature with sprint branch
- git checkout _sprint_
- git pull
- git checkout _feature_
- git pull
- git rebase sprint
(git rebase --skip for unncessary commits)
- git pull
- git push

# Revert un commit
- git revert {id_commit}
- git pull
- git push

# Merging
- Resolve conflicts manually
- git add <files>
- git commit -m 'Merging files'

