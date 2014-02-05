# We've Moved!

![we've moved][we-have-moved]

Moved to stash: https://stash.corp.squareup.com/projects/cu/repos/blimlimb

To migrate your machine, run:

    git remote rename origin ghe
    git remote add origin ssh://git@stash.corp.squareup.com:7999/cu/blimlimb.git

Then reset your master branch (only do this if you have no local changes):

    git checkout master
    git fetch origin
    git reset --hard origin/master

[we-have-moved]: http://www.thegildedstag.com/wp-content/uploads/2013/06/we-have-moved.jpg
