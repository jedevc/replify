# replify

Tool for transforming single-use tools into full on REPLs!

You can take a command that takes input on argv and outputs to stdout, and
turns it into a REPL that takes input from stdin and output to stdout.

For example:

```bash
$ replify git
$ status
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
$ branch
  master
* dev
```

It's super useful for CTFs and stuff like that.

