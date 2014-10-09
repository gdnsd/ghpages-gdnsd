---
  layout: post
---

The project github URL (and all related github links) is changing from:

[https://github.com/blblack/gdnsd/](https://github.com/blblack/gdnsd/)

to:

[https://github.com/gdnsd/gdnsd/](https://github.com/gdnsd/gdnsd/)

Basically, the repo is moving to a Github Organization-level role account
instead of my personal github account.

The purpose is to allow me to upload experimental branches in my personal
fork without affecting the state of the "main" repo, and to be able to sanely
do fork + pull-req traffic against forks of the main repo other than my own,
(e.g. paravoid's fork for debian packaging).  There remains no real "organization"
in the true sense of the word behind the gdnsd project :)

I'll refrain from creating a gdnsd fork at blblack/gdnsd for a while to avoid
conflict (and github will continue to redirect http and git-clone requests for
the old path to the new location so long as I do so).

Users who clone/fork this repo should update the remotes of any git clones by
replacing "blblack/gdnsd" with "gdnsd/gdnsd" in the relevant .git/config file.
