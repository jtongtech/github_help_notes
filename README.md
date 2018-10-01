# Begning Notes on using Git and Github
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

GitHub is a web-based hosting service for version control using Git.

# If you do not have git installed...

Download git from here https://git-scm.com/downloads

# How to Clone a Repository


   - click green button on right side of screen that says clone repo
    - copy the url that is displayed in a popup
    - navigate to the folder where you keep your code in powershell
    - enter following command where URL is the url you copied
```sh
git clone URL
```

# How to Initiate or Start and New a Repository

- build out your file structure in a minimal way
- navigate to folder in powershell
- go to github
- click new repository button
-  click initiate with readme
- copy first big chunk of code in grey box
- paste in your powershell or terminal and hit enter
- once complete, enter the following commands
```sh
git add .
git commit -m "initial commit"
git push origin master
```

- Now reload your page on github and marvel at the fact your code is on github!

# To push your existing project to existing repo
- navigate to the folder in powershell
- enter following commands where Your_Commit_Message = detailed discription of what changes you made in this commit

```sh
git add .
git commit -m "Your_Commit_Message"
git pull origin master
git push origin master
```
# *** IMPORTANT ***

- You must pull and push often.
- DO NOT keep code on your machine for more than 30 minutes to an hour without pushing it out.  
    -  This will cause merge conflicts and potentially cause major problems for you and your teammates.
    -  Ideally, you make a change, run your test, pull from git, then push for every change.
        -  Not big changes but little ones.
    -  Be descriptive on your commit messages.
        -  Your team should be able to tell exactly what you did by looking at your commit messages.
-  DO NOT PUSH WITH OUT PULLING FIRST.
    -  This will overwrite changes your team has made.
-  UNDER NO CIRCUMSTANCES SHOULD YOU EVER DO A FORCE PUSH OR A RESET BY YOURSELF.
    -  These have very big consequences and must be agreed upon by your team and be done together.

