# sb-a

## subtree setting

```
git remote add shared git@github.com:yutaono/sb-s.git
git fetch shared
git subtree add --prefix=shared shared master --squash
```

## run

```
sbt 'project core' 'run-main practice.core.Main'
```
