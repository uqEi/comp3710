# comp3710

eilee@Eileen_LENNB MINGW64 ~
$ git clone http://github.com/uqEi/comp3710.git
Cloning into 'comp3710'...
warning: redirecting to https://github.com/uqEi/comp3710.git/
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

eilee@Eileen_LENNB MINGW64 ~
$ cd comp3710
eilee@Eileen_LENNB MINGW64 ~/comp3710 (main)
$ nano README.md

eilee@Eileen_LENNB MINGW64 ~/comp3710 (main)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

eilee@Eileen_LENNB MINGW64 ~/comp3710 (main)
$ git commit om "This is a commit"
error: pathspec 'om' did not match any file(s) known to git
error: pathspec 'This is a commit' did not match any file(s) known to git

eilee@Eileen_LENNB MINGW64 ~/comp3710 (main)
$ git commit -m "This is a commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'eilee@Eileen_LENNB.(none)')

eilee@Eileen_LENNB MINGW64 ~/comp3710 (main)
$ git config --global user.email "e.ip@student.uq.edu.au"

eilee@Eileen_LENNB MINGW64 ~/comp3710 (main)
$ git commit -m "This is a commit"
[main 63a8432] This is a commit
 1 file changed, 2 insertions(+), 1 deletion(-)

eilee@Eileen_LENNB MINGW64 ~/comp3710 (main)
$ git log --pretty="%h, %an, %ae, %ad, %s" --date=short
63a8432, Eileen Ip, e.ip@student.uq.edu.au, 2025-08-10, This is a commit
11e1c11, uqEi, e.ip@student.uq.edu.au, 2025-08-10, Initial commit
