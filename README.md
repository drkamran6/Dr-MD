# Dr-MD
Dr-MD is a multi-device WhatsApp bot designed to provide enhanced functionality and automation for WhatsApp users. Developed by ROMEK-XD, this repository offers an easy-to-deploy solution for integrating with WhatsApp through a bot interface.



<p align="center">
  <h1 align="center" style="font-family: 'Orbitron', sans-serif; text-shadow: 0 0 10px #00ffff, 0 0 20px #0088ff;">Dr-MD</h1>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=100&pause=1000&color=ff0000&center=true&width=1000&height=200&lines=BMB-XMD-V4.0" alt="Typing SVG" /></a>
  </p>
  
---
  </p>

```
Dont forget to fork & star repo
```

---

<div align="center">
  <img src="https://files.catbox.moe/6k43w3.jpg" width="300" style="border-radius: 20px; box-shadow: 0 0 20px #00ffff;"/>
</div>
            `DEPLOMENT STEPS`

<div style="background: #000000; border: 1px solid #00ffff; border-radius: 15px; padding: 20px; box-shadow: 0 0 15px #00ffff; margin-bottom: 30px;">
  
<div style="background: #111111; padding: 15px; border-radius: 10px; border-left: 3px solid #ff00ff;">
  <a href='https://github.com/drkamran6/Dr-MD/fork' target="_blank">
    <img src='https://img.shields.io/badge/FORK_REPO-FF5500?style=for-the-badge&logo=github&logoColor=white&labelColor=000000'/>
  </a>
</div>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=100&pause=1000&color=ff0000&center=true&width=1000&height=200&lines=DEPLOYMENT.OPTION" alt="Typing SVG" /></a>
  </p>
---
<h4 align="center">2. heroku</h4>
<p style="text-align: center; font-size: 1.2em;">
  
<p align="center">
<a href='https://dashboard.heroku.com/new?template=https://github.com/drkamran6/Dr-MD/tree/main'' target="_blank"><img alt='Heroku' src='https://img.shields.io/badge/-heroku ‎Deploy-6971FF?style=for-the-badge&logo=Github&logoColor=white'/< width=150 height=28/p></a>


 --------
 <h4 align="center">8. Workflow</h4>
<p style="text-align: center; font-size: 1.2em;">


<details>

<b><strong><summary align="center" style="color: Yello;">Deploy On Workflow</summary></strong></b>
<p style="text-align: center; font-size: 1.2em;">
 
<h8>Copy the workflow codes and then frok the repo edit config add session id then save and now click on repo action tag then click on start new workflow then paste workflow codes name them deploy and save the file</h8>
<h3 align-"center"> Important</h3>
<h6 align-"center">Attention! We do not take responsibility if your github account is suspended through this Deploy method, I advise you not to use this workflow deploy method in the latest github accounts, github accounts created a year or more ago have not received the risk of suspension so far, this works It will only be done for 6 hours, you need to update the code to reactivate it.</h6>

```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```
</details> 

***
