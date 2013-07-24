rebase
======

testing git rebase -i

add some commits on a feature branch. 

    git checkout -b myfeature

make changes

    git commit -am "changed some stuff"

switch to upstream

    git checkout develop

rebase

    git rebase -i myfeature


overwrite