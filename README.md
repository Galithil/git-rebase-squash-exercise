
# Git rebase and commit squashing exercise

On the `haiku` branch you find a script that prints a haiku:
```
$ python main.py

This is the haiku we got:

On a branch ...
                  by Kobayashi Issa

              On a branch
              floating downriver
              a cricket, singing.
```

The haiku is great but the
[commit history](https://github.com/bast/git-rebase-squash-exercise/commits/haiku) on
the `haiku` branch is not (on purpose).

Your task is to clone this repository and to rebase the `haiku` branch on top
of `master` and squash the several small "incomplete" commits into one single
self-contained cherry-pickable commit.

At the end you should obtain a linear history and the `haiku` branch should
contain one commit more than `master`. Verify also that the script still works.
