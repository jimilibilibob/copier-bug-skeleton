# Copier bug reproduction

Create copier template to reproducde bug from issue [Created new file after copier update seems to be deleted](https://github.com/copier-org/copier/issues/1202).


To test, run command (into a specific folder):
```
copier -r v1.0.2a1 copy https://github.com/jimilibilibob/copier-bug-skeleton.git .
```

```
git init .
```

```
git add .
```

```
git commit -m "feat: Copy copier skeleton v1.0.2a1"
```

```
copier -f -r v1.0.2a3 update .
```