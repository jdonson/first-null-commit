first-null-commit
=================

https://developer.github.com/guides/ => start here and ask questions here...

https://www.facebook.com/groups/osswebdevbackend/

New devs... first NULL commit to github....

Here are some git basics for those new to git and github.

http://www-cs-students.stanford.edu/~blynn/gitmagic/ch02.html

Also, this quicktime video is AWESOME:

http://urbanspectra.com/media/vids/GIT_VIDEOS.mov

Windows users may require installation
of the free quicktime player to see this video:

http://support.apple.com/kb/DL837
This is my first "null commit".

In order to accomplish this:

1.  Logged into github and created new public repo:

	https://github.com/jdonson/first-null-commit.git

2.  Cloned this repo to my desktop:

	$ git clone https://github.com/jdonson/first-null-commit.git

3.  Entered directory and made these edits.

4.  $ git status

	=> Shows that there are changes to this repo.

5.  $ git add .

	=> Add all changes to the repo.

6.  $ git commit -m "first null commit jdonson"

	=> Commits these changes to repo.

7.  $  git status

	=>  Confirm current repo.

macusers-MacBook-Pro:first-null-commit macuser$ git status
# On branch master
# Your branch is ahead of 'origin/master' by 1 commit.
#
nothing to commit (working directory clean)

8.  $ git push

	=> Push these changes and view them on github.
