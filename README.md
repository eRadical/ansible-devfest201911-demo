
## Requirements:
- an alias email to be used for sending emails (Ex.: gitlab@example.com) must exists prior to running the playbook,
- A user for LDAP search must exist already (this playbook uses "gitlab-connect"), see [envs/group_vars/all/gitlab.yaml#L41]

## Getting the code:

- Clone the repo on a machine:
 
        git clone --progress -vv --recurse-submodules -j8 «REPO-URL»

-  Add a (new) submodule:

        git submodule add git@github.com:username/repo.git path/for/submodule

- Initialize and update a submodule

        git submodule init --recursive
        git submodule update --init --recursive
