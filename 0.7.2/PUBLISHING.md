# PUBLISH

**1. Edit these files**

1. `bower.json`
2. `bulma.sass`
3. `package.json`

**2. Build everything**

npm run deploy

**3. Commit version**

git commit -am 'Deploy 0.7.2'

**4. Publish to npm**

npm publish

**5. Push master**

gcm
ggp

**6. Download npm release, zip it, upload to GitHub**

npm install bulma@0.7.2
bulma-0.7.2

**7. Create GitHub release**

Tag version: 0.7.2

# ARCHIVE docs

**1. Edit `_config.version.yml`**

**2. Build folder**

cd docs
jekyll build --destination versions/0.7.2 --config _config.version.yml

**3. Edit `_config.yml`**
