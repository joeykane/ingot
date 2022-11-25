# ingot
A bookmarklet to disable extensions based on LTBEEF with an interface based on the chrome extension page

Installation
For easy setup go the the website at https://fognetwork.github.io/Ingot

Show your bookmarks bar with ctrl + shift + b

Right click on the bar and choose Add Page

Set the name to Ingot and the URL to the code below or here

javascript:(function () {var a = document.createElement('script');a.src = 'https://cdn.jsdelivr.net/gh/FogNetwork/Ingot/ingot.min.js';document.body.appendChild(a);}())
