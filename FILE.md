| branch  | commit | command                                                                           |
|---------|--------|-----------------------------------------------------------------------------------|
| main    | 0      | git clone <URL>                                                                   |
| main    | 0      | git add FILE.md                                                                   |
| main    | 0      | git commit -m "Commit 0: Clone repo, create FILE.md with git clone, add & commit" |
| main    | 1      | git add FILE.md                                                                   |
| main    | 1      | git commit -m "Commit 1: Edit FILE.md with git add & commit"                      |
| main    | 2      | git add FILE.md                                                                   |
| main    | 2      | git commit -m "Commit 2: Edit FILE.md with git add & commit"                      |
| bug-fix | 3      | git checkout -b bug-fix 602585775ef8415aaa00ae6fd0adb460221e69d9                  |
| bug-fix | 3      | git add FILE.md                                                                   |
| bug-fix | 3      | git commit -m "Commit 3: Edit FILE.md with git checkout, add & commit"            |
| bug-fix | 4      | git add FILE.md                                                                   |
| bug-fix | 4      | git commit -m "Commit 4: Edit FILE.md with git add & commit"                      |
| bug-fix | 5      | git merge main                                                                    |
| bug-fix | 5      | git add FILE.md                                                                   |
| bug-fix | 5      | git commit -m "Commit 5: Edit FILE.md with git merge, add & commit"               |
| bug-fix | 6      | git add FILE.md                                                                   |
| bug-fix | 6      | git commit -m "Commit 6: Edit FILE.md with git add & commit"                      |


