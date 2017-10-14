# PUBLISH

**1. Edit these files**

1. `bower.json`
1. `bulma.sass`
1. `package.json`

**2. Build everything**

```
npm run deploy
```

**3. Commit version**

```
git commit -am 'Deploy 0.5.3'
```

**4. Tag, push master, push tag**

```
gcm
git tag 0.5.3
ggp
git push origin 0.5.3
```

**5. Publish to npm**

```
npm publish
```

# ARCHIVE docs

**1. Edit `_config.version.yml`**

**2. Edit `versions.html`**

**3. Build folder**

```
cd docs
jekyll build --destination versions/0.5.3 --config _config.version.yml
git add .
git commit -am 'Archive version 0.5.3'
```

**4. Edit `_config.yml`**
