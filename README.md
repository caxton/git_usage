# git_usage

#### clone with specifc single branch
```
git clone project.git --branch branch_name --single-branch target_folder
```

#### add all added files
```
git add $(git ls-files --added)
```

#### add all modified files
```
git add $(git ls-files --modified)
```

#### remove all deleted files
```
git rm $(git ls-files --deleted)
```
