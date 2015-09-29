## PatyArteBordados  

### Initial setup  
#### 2015-09-27  

```sh
$ meteor --version
Meteor 1.2.0.1
$ meteor create PatyArteBordados
$ cd PatyArteBordados
PatyArteBordados$ echo .meteor/local > .gitignore
PatyArteBordados$ echo "# PatyArteBordados" > README.md
PatyArteBordados$ echo MIT > LICENSE.txt
PatyArteBordados$ git init
PatyArteBordados$ git add -all
PatyArteBordados$ git commit -m "first commit"
PatyArteBordados$ git remote add origin https://github.com/ronasta/PatyArteBordados.git
PatyArteBordados$ git remote -v
origin	https://github.com/ronasta/PatyArteBordados.git (fetch)
origin	https://github.com/ronasta/PatyArteBordados.git (push)
PatyArteBordados$ git push origin master
```

### add Semantic UI  
#### 2015-09-29  

```sh
PatyArteBordados$ meteor add semantic:ui flemay:less-autoprefixer
PatyArteBordados$ mkdir -p client/lib/styles
PatyArteBordados$ cd client/lib/styles
PatyArteBordados/client/lib/styles$ touch custom.semantic.json
PatyArteBordados/client/lib/styles$ meteor
PatyArteBordados/client/lib/styles$ # ## edit custom.semantic.json
PatyArteBordados/client/lib/styles$ # ##      themes github -> true
PatyArteBordados/client/lib/styles$ meteor update

Changes to your project\'s package version selections from updating the release:

caching-html-compiler  upgraded from 1.0.1 to 1.0.2
ecmascript             upgraded from 0.1.4 to 0.1.5
meteor                 upgraded from 1.1.7 to 1.1.9
minimongo              upgraded from 1.0.9 to 1.0.10
mongo                  upgraded from 1.1.1 to 1.1.2
promise                upgraded from 0.4.8 to 0.5.0
reactive-dict          upgraded from 1.1.1 to 1.1.2
standard-minifiers     upgraded from 1.0.0 to 1.0.1
templating             upgraded from 1.1.3 to 1.1.4
tracker                upgraded from 1.0.8 to 1.0.9

PatyArteBordados: updated to Meteor 1.2.0.2.  
Your top-level dependencies are at their latest compatible versions.

PatyArteBordados$ mkdir -p client/lib/styles
PatyArteBordados$ git init
PatyArteBordados$ git add -all
PatyArteBordados$ git commit -m "first commit"
PatyArteBordados$ git remote add origin https://github.com/ronasta/PatyArteBordados.git
PatyArteBordados$ git remote -v
origin	https://github.com/ronasta/PatyArteBordados.git (fetch)
origin	https://github.com/ronasta/PatyArteBordados.git (push)
PatyArteBordados$ git push origin master
```
