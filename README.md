# firstRepo
This is my first time .
<br>
Hello World 
1.Configuring Git
<br>
git config --global user.name""
 git config --global user.email""
 <br>
 To check whether it is done or not :
 git config --list

 <br>
 <h2>Git Clone & Status</h2>
 Clone is use to import repository from github to local machine(laptop).
 Syntax: git clone link

 <br>
 Status : Gives you the status, whether you have change something in the code or not if you have change and you have not dont add & commit then it will through error
 Syntax: git status

 <h3>we genrally have 4 staus in git status they are<h3>
 <ul>
 <li>untracked [new file that git doesn't yet track]</li>
 <li>modified [changed]</li>
 <li>staged[file is ready to commit] </li>
 <li>unmodified [unchanged]</li>
<br>
<br>
<br>

<h2>Add & Commit</h2>
add-adds new or worked file in your working directory to Git staging area
Syntax: git add <--filename-->
But if we have many files or repository where we made change then we can add all by in a step
just write .   thatmean Syntax: git add . 
Here in above Syntax . mean all
The shorthand command for git add --all is git add -A



commit-it is the record of change
Syntax : git commit-m"some message"