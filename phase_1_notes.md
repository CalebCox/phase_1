In 2-mindset, under "Emotional Roller Coaster", "a" should be "an". Also "your self" to "yourself"
In 3-code_editor, under Features -> Code Editing, "code and find and fix" change to "code to find and fix"?
General Idea: dictionary of potentially unknown terms (i.e. Repository, Parent Directory)
In 5 git-basics running #5 under workflow locally, get following error:
      Run

      git config --global user.email "you@example.com"
      git config --global user.name "Your Name"

      to set your account's default identity.
      Omit --global to set the identity only in this repository.

      fatal: unable to auto-detect email address (got 'Caleb@ARC.(none)')
Suggest including the git-config steps in the instructions for first time users
Error on #7
    $ git push
     fatal: The current branch main has no upstream branch.
     To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

   To have this happen automatically for branches without a tracking
   upstream, see 'push.autoSetupRemote' in 'git help config'.
You're already aware of the clone thing
Weird note, any time I open vs, it defaults to having the central repo open. Closing out doesn't seem to help. Not sure if that causes any weird overlaps