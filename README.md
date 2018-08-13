# Ghost for Azure Web Apps

![Ghost version used](https://img.shields.io/badge/ghost-v1.25.4-green.svg)
[![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

To work with Azure Web Applications, Ghost application need some adaptation.
This repository permit the deployment of ghost instance in a web application with insights.

![ghost screenshot](https://ghost.org/images/vs/ghost-content-1152x.png)

## Upgrade to v1.25.X
With the release of the new Ghost editor *Koenig*, when you migrate your Ghost instance from a prior version to v1.25.X **you need to update your database**.
Following this specific procedure to migrate to v1.25.X from a 1.2X.X version:
1. **Update** your application as describe [**here**](https://github.com/woolfyx/azure-ghost/wiki/How-I-can-update-my-site-%3F)
2. In Azure portal, **open a console** for your application
3. Proceed to the database migration with the **following command**: `knex-migrator migrate`

## How to use?
1. [Deploy template to Azure](https://azuredeploy.net/)
2. Fullfill the form to perform the deployment
3. After a successful deployment, in wep application console, rebuild npm modules:
```bash
npm rebuild
```
4. Initialize your database:
```bash
node db.js
```
5. Connect to your website and enjoy !

## How I update my site ?

Check the process on the [dedicated page](https://github.com/woolfyx/azure-ghost/wiki/How-I-can-update-my-site-%3F).

## Optional step

Check the [wiki](https://github.com/woolfyx/azure-ghost/wiki) for more details and optional steps

## Credits
_This repository is a fork and an adaptation of [solvsoftware repository](https://github.com/solvsoftware/Ghost-Azure)_
