# git-find-squashed

This is a tool that finds branches in your repository that were squash-merged
into master.

This is useful if you work on a project that squashes branches into master. `git
branch -d` does not detect squash-merges, so it's not easy to clean up local
repository from branches that were merged.

# Usage

    $ git-find-squashed

# Related

`git-find-squashed` is a trivial rewrite of
[`git-delete-squashed`](https://github.com/not-an-aardvark/git-delete-squashed).
The differences are:

- Does not delete branches automatically
- Does not pull in 23 megabytes of various dependencies into `node_modules`.

# License

MIT
