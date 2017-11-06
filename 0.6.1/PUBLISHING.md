# PUBLISH

**1. Edit these files**

1. `bower.json`
2. `bulma.sass`
3. `package.json`

**2. Build everything**

npm run deploy

**3. Commit version**

git commit -am 'Deploy 0.6.1'

**4. Publish to npm**

npm publish

**5. Push master**

gcm
ggp

**6. Download npm release, zip it, upload to GitHub**

npm install bulma@0.6.1
bulma-0.6.1

# ARCHIVE docs

**1. Edit `_config.version.yml`**

**2. Build folder**

cd docs
jekyll build --destination versions/0.6.1 --config _config.version.yml

**3. Edit `_config.yml`**
