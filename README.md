# wargit

Weekly Activity Report git

Reports all your commits in all your projects in the past week.

## Requirements

Your projects need to be organised in folders named after their groups. For example:

    $ tree ~/github.com
    .
    ├── ansible
    │   └── ansible
    └── docker
        ├── docker
        └── distribution

## Install

    cd ~/bin
    curl -O https://raw.githubusercontent.com/jonatanblue/wargit/master/wargit
    chmod +x wargit

## Use

    $ cd ~/github.com
    $ wargit your.email@example.com
    * ansible/ansible:
    new feature1
    added tests 
    ---
    * docker/distribution:
    here be tags 

