<h3>How to start with Git and Github</h3>

<ol>
<li>First of all make a GitHub account and tell Lama to add you as a contributor </li>
<li>Download Git from here <a>https://git-scm.com/downloads</a></li>
<li>Download VSCode from here <a>https://code.visualstudio.com/download</a></li>
<li>Make a new folder and <strong>give it a proper name <u style="color:red;"><em >PLEASE</em></u></strong></li>
<li>Open VSCode and drag the folder you made into it</li>
<li>Open Terminal (CTRL+` as a shortcut) </li>
<li>type the following commands</li>
-Make a new repository

```
git init
```
-Configure the global user name and email address for Git
```
git config --global user.name "myName"
git config --global user.email "myEmail"
```
-Add the link of the remote repository, make your main branch name "branch"
```
git remote add origin https://github.com/Lama-23/web_projct.git
git branch -M main
```
-Pull files from main repository from github
```
git pull origin main
```
every time you want to work pull first, now you can work on your own file, then do these instructions to keep the remote repository up to date.

-Next, add your work to the staging directory, the dot here is important, you can replace it with the files you want to add but the dot will add everything
```
git add .
```
-Commit your changes to the local repository and <strong> <u style="color:red;"><em >PLEASE</em></u> write a meaningful message (your teammates will see this message) write what you did briefly like "I worked on the navbar and added some CSS styles"</strong> 
```
git commit -m "write a meaningful message here"
```

-Finally, push your work to the remote repository

this command for first time
```
git push --set-upstream origin main
```

-Sometimes, when you push and someone just before you pushed, an error will appear to you, so you have to pull and get the new changes before you push

```
git pull origin main
```


future pushes just use this
```
git push
```
</ol>   
