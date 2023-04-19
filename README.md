# helpful_docs

Clone repo with Access token:
git clone https://nothing-to-add:access_token@github.com/nothing-to-add/repo.git

Set username for repo:
git config user.name nothing-to-add

Set email for repo:
git config user.email 36647739+nothing-to-add@users.noreply.github.com

Update the last commit with username and email:
git commit --amend --reset-author --no-edit

Update the last commit with timestamp:
git commit --amend --date="Wed Jan 6 19:41:16 2021 +0200" --no-edit

Update the last commit with timestamp and username:
git commit --amend --reset-author --date="Sun Jan 27 22:38:09 2019 +0200" --no-edit

Get log about commits:
git log

Make changes for all commits for particular repo:
git rebase -i --root

Finish with current commit and continue:
git rebase --continue

Force push:
git push -f

Link to instruction:
https://stackoverflow.com/questions/3042437/how-to-change-the-commit-author-for-a-single-commit
