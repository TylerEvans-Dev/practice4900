# Welcome to Git!
This tutorial is best done on the terminal or WLS for windows this is not cmd compatable.
git is a source control program feel free to skip sections if you already know
git. This is a markdown file README.md

## starting your own git
init/start a git this command is used to create a repo
I have already completed this step here. Do not do this for the tutorial.
``` git init ```

## cloning
however
git clone will get a repo
```git clone {the url from above}```

## git branching
git branching is creating a seprate branch of code where you can manage and have a working version
of a code

``` git branch {enter in your name for your branch} ```

## git ignore

if there are files that you want to ignore using a ```.gitignore``` is helpful
to see your folders one can use
`ls -a` this will show all files in a dir. including hidden ones not vis.



to create a git ignore

``` touch .gitignore ```

to open and add files

``` code .gitignore```

this file will be empty
to not add files type the file name in here
like so
``` example.txt ```
to ignore dir. type
``` ./vscode ```
now save.

### git status adding files and
git status gives the current status of the file
it is good practice to use this before commiting in your branch

```git status ```

## adding files to git
add files by using
``` touch {name your file}.txt ```

to edit your file in vscode use

```code {name of your file}.txt ```
one could use nano, or vim but for now vscode should be okay.

now add a random phrase inside the txt file and save

now that files are created to track the files one will have to
use a git add command
one can do

``` git add {filename}.{filetype}```
or

``` git add . ```

to finalize the action or save your action
use the git commit command a message can be attached and seen in your history.
this helps you once your reading and would like to see your changes.

```git commit -m "{enter what you would like here}"```

to see the history of the git repo
use

```git log```
it will show commits and history of the repo
now delete the file you have created
``` rm {your file name}.txt ```
now use the git add command
``` git add . ```
and commit it
```git commit -m "removing a file " ```
now use
```git log```
this will show your past two commits



ADD NAME BELOW

Tyler Evans u1313811
