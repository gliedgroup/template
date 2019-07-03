# Project Template

Usage:

While Starging a new project, first create a new repo at https://github.com/gliedgroup. Let's assume you created a repo at  `gliedgroup/NEW_REPO`. 

On you local machine, clone this template repo in your preferred destination. 

`git clone https://github.com/gliedgroup/template.git`
`git remote rm origin`  

The first line clones this template and the second line, unlinks the this repo from it's remote origin. Now rename the `template` folder to `NEW-REPO`, i.e. the project name. Next step is to change the `remote origin` of this local folder to point at the clone link of   `gliedgroup/NEW_REPO`. Copy this link and run  

`git remote add origin PASTE` 

Where `PASTE` is the cloning link of `gliedgroup/NEW_REPO`. The local repo is now ready! 
