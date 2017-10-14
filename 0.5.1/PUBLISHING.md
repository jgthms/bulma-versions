# Publishing

## 1. Edit these files

1. `bower.json`
1. `bulma.sass`
1. `package.json`

## 2. Build everything

```
npm run deploy
```

## 3. Commit version

```
git commit -am 'Deploy 0.5.1'
```

## 4. Tag, push master, push tag

```
gcm
git tag 0.5.1
ggp
git push origin 0.5.1
```

## 5. Publish to npm

```
npm publish
```


# Archive docs

## 1. Edit _config.version.yml

## 2. Buil folder

```
cd docs
jekyll build --destination versions/0.5.1 --config _config.version.yml
git add .
git commit -am 'Archive version 0.5.1'
```