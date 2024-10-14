`README.md`に変更を加えて、`git status`で確認した時の出力。

```
% git status
On branch training/commands
Your branch is up to date with 'origin/training/commands'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
```

↑ の変更をステージした時の、`git status`での出力。

```
% git add .
% git status
On branch training/commands
Your branch is up to date with 'origin/training/commands'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
```

↑ の変更をコミットした時の、`git status`での出力。

```
% git commit -am 'add hello'
[training/commands c5f6fe5] add hello
1 file changed, 2 insertions(+)

% git status
On branch training/commands
Your branch is ahead of 'origin/training/commands' by 1 commit.
(use "git push" to publish your local commits)

nothing to commit, working tree clean
```
