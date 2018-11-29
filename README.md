# git-skip

skip-worktreeを簡単に管理するツール


# example

```
$ cd YOUR_REPO/
$ echo "// Would not like to commit" >> hello.go

$ git status
  >> Changes not staged for commit: ...

$ git skip hello.go # skip-worktree wrapper
 
$ git status
  >> nothing to commit, working tree clean
```

# commands

#### skip
Skip [file]

#### unskip
Unskip [file]

#### skip-all
Skip all unstage

#### unskip-all
Unskip all skipped

#### skips
Skipped files

#### skip-refuge
Commit skipped files to new branch ( named `{CURRENT_BRANCH_NAME}-skip` )

#### skip-reattach
Refuged files come back to current branch

# install

Copy `bin/` shell scripts to your bin directory

# License

MIT


