# Welcome to Git!
This tutorial is best done on the terminal or WLS for windows this is not cmd compatable.
git is a source control program feel free to skip sections if you already know
git. This is a markdown file README.md

## starting your own git
init/start a git this command is used to create a repo
I have already completed this step here. Do not do this for the tutorial.

to put your name
``` git config --global user.name "enter your name here" ```
``` git config --global user.email "enter your email name here" ```


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

## git status
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
say you did something to your file git resotre will bring it back to the original condtion
it was on your last commit.
the command
``` git restore .``` will restore all of the files
``` git restore {your specific file} ``` will restore your file you wrote

last of all for this beg. tutorial since this is a lot

add your {your file name}.txt to your .gitignore

edit this file and commit at the bottom
by using
code ``` code README.md  ```

add the stuff as above and commit

next week we will go over merging and what we will do
thanks see you next week!

## ADD NAME HERE BELOW

Tyler Evans u1313811
