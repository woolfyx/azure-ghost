# Ghost for Azure Web Apps

![Ghost version used](https://img.shields.io/badge/ghost-v1.22.7-green.svg)
[![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

To work with Azure Web Applications, Ghost application need some adaptation.
This repository permit the deployment of ghost instance in a web application with insights.

## How to use?
1. Login to Azure
2. [Deploy template to Azure](https://azuredeploy.net/)
3. In console, rebuild npm modules:
```bash
npm rebuild
```
4. Initialize your database:
```bash
node db.js
```
5. Connect to your website and enjoy !


## Optional step
### Want to customize ?

If you want to customize the version or files you can fork this repository.
You can also create a branch for each of your site if you need customization :
```bash
git checkout azure
git checkout -b my_blog
```
You can keep your fork up to date(if you want the latest ghost version).
[https://help.github.com/articles/syncing-a-fork/](https://help.github.com/articles/syncing-a-fork/)

OR

```bash
git checkout my_branch
git pull https://github.com/skaario/azure-ghost azure
```

## Credits
_This repository is a fork and an adaptation of [solvsoftware repository](https://github.com/solvsoftware/Ghost-Azure)_
