&nbsp;
<p align="center">
  <a href="https://ghost.org">
    <img src="https://user-images.githubusercontent.com/120485/43974508-b64b2fe8-9cd2-11e8-8e58-707254b8817c.png" width="200px" alt="Ghost" />
  </a>
</p>
<h3 align="center">Deploy Ghost application on Azure Web Applications</h3>
<p align="center">To work with Azure Web Applications, Ghost application need some adaptation.<br>
This repository permit the deployment of ghost instance in a web application with insights.</p>
<hr />
<p align="center">
    <a href="https://ghost.org">
        <img src="https://img.shields.io/badge/ghost-v2.2.0-green.svg" alt="Ghost version used" />
    </a> <br/> <br/>
    <a href="https://azuredeploy.net/">
        <img src="https://azuredeploy.net/deploybutton.png" alt="Deploy to Azure" />
    </a>
</p>



<p align="center">
    <img src="https://user-images.githubusercontent.com/120485/43994697-62e2bdc2-9d99-11e8-94fc-021ab9756f33.gif" width="800" />
</p>

<br>

---

## How to use?

### New deployment
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

### Upgrade
Full **update** process is available [**here**](https://github.com/woolfyx/azure-ghost/wiki/How-I-can-update-my-site-%3F)

## How I update my site ?

Check the process on the [dedicated page](https://github.com/woolfyx/azure-ghost/wiki/How-I-can-update-my-site-%3F).

## Optional step

Check the [wiki](https://github.com/woolfyx/azure-ghost/wiki) for more details and optional steps

## Credits
_This repository is a fork and an adaptation of [solvsoftware repository](https://github.com/solvsoftware/Ghost-Azure)_  
_Graphic presentation by [TryGhost](https://github.com/TryGhost/Ghost)_
