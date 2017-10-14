# PUBLISH

**1. Edit these files**

1. `bower.json`
2. `bulma.sass`
3. `package.json`

**2. Build everything**

npm run deploy

**3. Commit version**

git commit -am 'Deploy 0.6.0'

**4. Publish to npm**

npm publish

**5. Push master**

gcm
ggp

**6. Download npm release, zip it, upload to GitHub**

npm install bulma@0.6.0
bulma-0.6.0

# ARCHIVE docs

**1. Edit `_config.version.yml`**

**2. Edit `versions.html`**

**3. Build folder**

cd docs
jekyll build --destination versions/0.6.0 --config _config.version.yml
git add .
git commit -am 'Archive version 0.6.0'

**4. Edit `_config.yml`**
