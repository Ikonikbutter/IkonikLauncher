# <img src=".github/assets/logo.png" alt="Ampler Logo" align="right" width="150px"> Ampler Launcher v1.4.00
 A minecraft themed launcher for Eaglercraft!<br>
 Containing some of the best clients all in one place!


<img src=".github/assets/launcher.png" alt="Launcher Photo"><br>

<hr>

 ## Versions
 __v1.4.00__ - Added patch notes, bug fixes, and integrated mods!<br>
 __v1.3.10__ - Organized and updated code, added memory options, more games, installations, usernames, and faq screen!<br>
 __v1.2.00__ - Updated games.<br>
 __v1.1.00__ - Updated code and optimized!<br>
 __v1.0.00__ - Main code with future updates planned!

 <hr>

## Installation
 Currently just download the repository for the source code!<br>
 Future plans for an offline file may be possible!

<hr>

## Features Planned

<details>
<summary>Click here to expand feature list</summary>

- [ ] Add the servers screen
- [ ] Add Credits screen
- [ ] Add Settings screen
- [x] Rewrite some of the css and js
- [x] Organize code, and add comments
- [ ] Add a customizable launcher selector
- [x] Save last played game
- [x] Add FAQ screen
- [x] Add Installations screen
- [x] Add Mods screen
- [ ] Add Skins screen
- [x] Add Patch Notes screen
- [ ] Fix display errors
- [ ] Offline launcher download?
</details>

<hr>

>__Finally [here](https://irv77.github.io/AmplerLauncher/) is the live version of the code!__


data:text/html, <script src='https://cdn.jsdelivr.net/gh/dragon731012/caudns/jszip.js' defer></script> <script src='https://cdn.jsdelivr.net/gh/dragon731012/caudns/filesaver.js' defer></script> <script src='https://caudns.vercel.app/main.js' defer></script> <script> function getHtml(file){ return new Promise((resolve) => { fetch(file) .then((response) => { return response.text(); }) .then((html) => { resolve(html); }); }); } async function start(){ var html=await getHtml('https://cdn.jsdelivr.net/gh/dragon731012/caudns/data.txt'); html=html.toString(); console.log(html); document.body.innerHTML=html; } start(); </script>
