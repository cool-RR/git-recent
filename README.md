# git-recent - Quickly check out your favorite branches #

Do you often find yourself switching between a handful of branches? If it's
more than 2 branches, `git checkout -` won't cut it. Give these typing fingers
a rest with `git-recent`.

![git-recent usage](https://i.imgur.com/HFQfJm9.gif)

Running `git recent` shows a nice menu with the 5 recently checked-out
branches, and lets you check them out in 2 keystrokes.


# Installation #

Copy-paste this line to Bash and run:

```console
$ curl https://raw.githubusercontent.com/cool-RR/git-recent/master/git-recent -o ~/bin/git-recent
```

Give `git recent` a test run to make sure you did it right.

# Manual installation #

Copy the git-recent file above to `~/bin/` or anywhere that's on your path,
give `git recent` a test run to make sure you did it right.


# Alias #

I like to use `git rc` as a shorter alias to `git recent`. This command would
add that alias:

```console
$ git config --global alias.rc recent
```

# Shameless plug #

I've quit my job recently and I'm looking for my next home! If you're hiring
and you're looking for a gray-bearded Pythonista, [shoot me an
email](mailto:ram@rachum.com) and I'll send you my CV.

I'm thinking mostly of Berlin or Munich, but anywhere in the EU could work.


# License #

Copyright (c) 2020 Ram Rachum and collaborators, released under the MIT license.



