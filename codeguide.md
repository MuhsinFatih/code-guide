
# Organization of code.java

### RULE 1: Always use  **<span style="font-family:UbuntuMono Nerd Font;color:#3dc6db">comic sans</span>**  in your code editor
### RULE 2: LOTR is overrated

```properties
nietzscheshell: There is no objective structure to any code, there is only interpretations
[nietzscheshell] sudo !!
nietzscheshell: salonda ejderya var hoca

```

## Git flow:  
Follow this style guide:  
https://github.com/agis/git-style-guide  

Especially follow this for feature branches:  
For each feature, create a branch with following style: `feature-description#version/person`  
e.g.: a branch for a new AR algorithm: `feature-new_AR_algo`  
If there are other branches with earlier versions: `feature-new_AR_algo#2`  
If multiple people have their own branches on same feature: `feature-new_AR_algo#2/muhsin`  

**Also especially this!!1!**:  
Commits **must** describe changes !!1!11

```bash
# good:
git commit -m "added private key to master in a public repo"
# bad:
git commit -m "up"
```

## Code guide
Nothing too specific about code style, but the organization of code must follow:  
- Any **utility** code that can be seperated based on their utility must be in its own file so that each function in a viewcontroller is an easily readable, reasonably short code.
- No commenting of old code. Code should always be committed cleanly. If the old version of a function will be useful to have around, copy it to another file and name it like so: `legacy/<function name>.swift.old`
```swift
// --- bad: ---

// let mx = Int(newSize[0]/2)
// let my = Int(newSize[1]/2)
// var dx = x-mx
// var dy = y-my
// dx *= Int(newSize[0] / Float(imageSize[0]))
// dy *= Int(newSize[1] / Float(imageSize[1]))
// x = mx + dx
// y = my + dy


// --- good: ---

```
