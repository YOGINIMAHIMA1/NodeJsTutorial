## What is Node Js??
### we know javascript is browser type language it works on browser 
## working  of javascript on browser-
 ## browser  contain javascript engine we cant run javascript code outside browser because javascript engine is present inside browser which allows to run javascript code
 ## borwser use javascript engine to run js code
 ## chrome use  chromev8 js engine, firefox use spider monkey js engine, safari use apple js engine
 ## most famous js engine is- v8 engine which found in chromium
 ## Ryan take v8 engine from chrome and embed it in c++ engine and created node js----- benefit of doing this -------> >we can run js code outside the browser ---->js can talk to native machine because of c++ -------- you can create web servers using js language--------- now js can do file handling
 ## Js some feature are not supported by node.js i.e window feature ,DOM-Manipulation. for ex- document.getElementById, alert etc
 ## if you do console.log(window)and save thatjs file then command nodemon <filename>-----it will give window is not defined
 ## if you do console.log(alert('NodeJs'))and save then run command nodemon <filename>-----it will give alert is not defined and also DOM features are also not supported by Nodejs
 ## but if you run these above command i.e  console.log(alert('NodeJs')) in browser console then they will supported by browser as js is browser type language but note node js support evry code of js as it is just a js Run environment but it will not support some features of js i.e Dom Manipulation
 ##  reason behind this is that all the window related element are extracted  or terminated from node js 
 ## nodejs contain core functionalities of js
 ### npm- node package manager----it automatically get installed when install node.js, when we make any new project we have to give command npm init which will create  a file name(package.json) which is a template or file which will manage our file or project.
 ## we can make dependencies and install external packages these are benefits of node.js
 ### package.json is configuration file in which we can create scripts , create dependencies make files

