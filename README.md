# gconsole

Stripped down version of firefox used for local console webconfig access

## Update usage
  Add __#kojibuild__ to commit message to automatically build

* git clone git+ssh://git@github.com/clearos/gconsole.git
* cd gconsole
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/firefox.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
