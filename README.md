# Realtime Code Collaboration Plugin v1.0.0 (alpha)

This is plugin for Microsoft Visual Studio Code which enables real-time collaboration of files.

Github link for UI : https://github.com/THE-WIRE/web-rt (The development of this is still on!)

## Index 
 * [Features](#features)
 * [Requirements](#requirements)
 * [Initial Setup](#intial-setup)
 * [How to Install](#how-to-install)
 * [Demo](#demo)
 * [Applications](#applications)
 * [Further](#further)

## Features

<ul>
  <li>Real time code collaboration with team members</li>
  <li>Can create teams using a seperate web interface</li>
</ul>

## Requirements

VS Code

## Initial Setup

<h4>Install NodeJS: https://nodejs.org/en/</h4>
<h4>Install the following using npm</h4>
<ul>
  <li><b>Typescript</b> - npm install -g typescript</li>
  <li><b>Firebase</b> - npm install firebase</li>
</ul>

## How to Install
<h3> First Download the project or clone </h3>

```bash
git clone <github-repo-url>
```

<h3> Now open the project in VS Code Editor </h3>
<h5> Navigate to <b>extension.ts</b> file </h5>
<h4> Now to run the extension - </h4>

```bash
Press CTRL + F5 to Run the extension.ts
```

<h4> A new window will open with the extension loaded </h4>
<h4> Open any project file to collaborate </h4>

```bash
To start the collaboration use CTRL + SHIFT + P
Write `start wire` in that extension loading box.
then,
A new dialog box will open at the top to get the username and then the password
```

```bash
For testing purpose we have created two usernames and passwords
1. Username - test1@test.com   Password - rootuser
2. Username - test2@test.com   Password - rootuser

Feel free to use them and give it a try
```

<h4> Wait for the login till you get a dialog box saying 'You have logged in as xxx@xxx.com' </h4>

<h4> Once you get this, you are done! You are collaborating </h4>
<hr>
<h4> Note - If you want to collaborate, both the systems must have logged in and also the file name and its extension must be the same </h4>

### Demo

![test1-gif](https://cloud.githubusercontent.com/assets/15127164/24349094/9a056a2c-12fb-11e7-872e-aa8c01e6c5af.gif)

### Applications

<ul>
<li> Aplications to this system can be numerous. Few of the applications are listed below: </li>
  <li> Real time code collaboration for programmers with their favourite code editor for their comfort </li>
  <li> A real time code collaboration team viewer system </li>
  <li> For online tutors to share and help other students to debug their code </li>
  <li> This can also be used for the purpose of interviews during the technical round to test the students with their coding      skills </li>
  <li> And many more ...</li>
  </ul>

### Further

* Currently the extension uses firebase. We plan to convert it to websockets.
* To make it more fast and reliable, the local server code hosting feature is to be added. It will also increase code security.
* More ideas are invited...

<h4> We will be publishing our package on VS Code Extensions Market soon </h4>

**Enjoy!**
