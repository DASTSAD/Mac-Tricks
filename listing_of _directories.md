# Listnig of Directories

```shell
  ls -R | grep ":$" | sed -e 's/:$//' -e 's/[^-][^\/]*\//--/g' -e 's/^/ /' -e 's/-/|/'
```

```shell
  du -h -d 0 /Volumes/3HDD02A/.
```
