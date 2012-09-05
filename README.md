# Hooker

## Install
1. `cd .git`
2. `rm -rf hooks`
3. `git clone http://github.com/unn/hooker.git hooks`
4. `ln -s hook-chain $HOOK`
5. [$HOOK](http://www.kernel.org/pub/software/scm/git/docs/githooks.html#_hooks)

## Usage
1. Create the chains by naming them `hookname.action` in .git/hooks/bin/

Largely stolen from <http://stackoverflow.com/a/8734391/130195>