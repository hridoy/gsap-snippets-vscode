# GSAP Snippets

**Now Updated for 1.18.0 release**

This extension for Visual Studio Code adds snippets for GSAP. More Snippets will be becoming soon just release.

[Use Extension](https://github.com/hridoy/gsap-snippets-vscode/raw/master/img/preview.gif)

## Contributors
[![Hridoy](https://avatars.githubusercontent.com/hridoy?s=100)<br /><sub>Hridoy</sub>](http://github.com/hridoy)<br />
See the [CHANGELOG](https://github.com/hridoy/jquery-snippets-vscode/master/CHANGELOG.md) for the latest changes



# Usage

The snippets are listed below in alphabetical order. The '`{$1}`' indicates the initial position of the caret. Some snippets have multiple stops, as indicated by '`${2} ${3} ${4}`' where the number is the order in which you one through the snippet.
      

**Draggable**   
`Draggable.create(${1:element},{type: "${2:drag_type}",${3:vars}});`      
  
---   

**from**     
`.from(${1:element},${2:1},{${3:vars},ease:${4:Power3.easeInOut}})`      

---   

**fromTo**  
`.fromTo(${1:element},${2:1},{${4:fromVars}},{${5:toVars}})`   

---   

**set**  
`.set(${1:element},{${2:vars}})`   

---   

**SplitText**  
`SplitText(${1:element},{type:"${2:words,chars,lines}"});`  

---   

**stagger**   
`.stagger${1:To}(${2:element},${3:0.5},{${4:vars},ease: ${5:Power3.easeInOut}},${6:0.25})`   

---   

**staggerFromTo**   
`.staggerFromTo(${1:element},${2:0.5},{${4:fromVars}},{${5:toVars}}, ${6:0.25})`   

---   

**Timeline**   
`new Timeline${1:Max}(${2:{options\}})`   

---   

**to**   
`.to(${1:element},${2:1},{${3:vars},ease: ${4:Power3.easeInOut}})`   

---   

**Tween**   
`Tween${1:Lite}.${2:to}(${3:element}, ${4:1}, {${5:vars}, ease: ${6:Power3.easeInOut}});



Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

## Installation



1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code
