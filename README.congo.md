* Initial setup

```
# Create standard hugo site and push to github

hugo new site tensor.group.congo
cd tensor.group.congo
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:tensorgroup/tensor.group.congo.git
git push -u origin main

# Initialize the hugo module system

hugo mod init github.com/tensorgroup/tensor.group.congo.git
hugo mod tidy

# Setup configs for Congo

mkdir -p config/_default
mv hugo.toml config/_default
cp /Users/billyz/Library/Caches/hugo_cache/modules/filecache/modules/pkg/mod/github.com/jpanther/congo/v2@v2.9.0/config/_default/* config/_default

# Comment unneeded stuff from config/_default/hugo.toml
```

* Create new content with the command

```
hugo new content <SECTIONNAME>/<FILENAME>.<FORMAT>
```

* Start the embedded web server with the command

```
hugo server --buildDrafts
```

* Updating

```
hugo mod get -u
hugo mod clean
```

* Hugo cache dir

```
~/Library/Caches/hugo_cache

~/Library/Caches/hugo_cache/modules/filecache/modules/pkg/mod/github.com/jpanther/congo
```
