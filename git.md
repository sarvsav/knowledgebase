To compare 2 tags

```shell
git diff tag1 tag2
```

show log between them

```shell
git log tag1...tag2
```

list of files changed between 2 tags
```shell
git diff tag1 tag2 --stat
```

look at differences between particular file
```shell
git diff tag1 tag2 -- some/file/name
```

And, make sure to pull all the tags using below command.

```shell
git pull --tags
```
