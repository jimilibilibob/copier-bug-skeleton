# Copier bug reproduction

Create copier template to reproducde bug from issue [Created new file after copier update seems to be deleted](https://github.com/copier-org/copier/issues/1202).


To test, run command (into a specific folder):
```
copier -r v1.0.0 copy https://github.com/jimilibilibob/copier-bug-skeleton.git
```

```
git init .
```

```
git add .
```

```
git commit -m "feat: Copy copier skeleton v1.0.0"
```