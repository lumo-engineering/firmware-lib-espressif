# Espressif official framework and library repositories

To update, execute:

```
git submodule update --init --remote
git commit --all
git submodule update --init --recursive
```

or

```
git submodule foreach 'git remote update; (git checkout origin/main || git checkout origin/master); git reset; git checkout .; git clean -xdff'
```
