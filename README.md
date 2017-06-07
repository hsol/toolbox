# toolbox

devops tools

## deploy script
copy from config-sample to config and setup config file

script list
* ./composer path (package_name)
* ./clone path commit_id (start_commit) - start_commit: for merge commit. before merge commit_id
* ./commit type (path) (commit_id) - type list: all, add, modify, delete
* ./clone_commit path commit_id - clone + commit all
* ./rollback start_rev (end_rev)

### Usage
* ./composer admin
* ./composer ./
* ./composer admin ridibooks/store
* ./clone admin d1deb2e
* ./clone admin d1deb2e 0c15436
* ./commit all
* ./commit add admin
* ./commit add admin d1deb2e
* ./commit modify admin d1deb2e
* ./clone_commit admin d1deb2e
* ./rollback 2012
* ./rollback 2012 2015