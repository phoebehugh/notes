## git tag v1
tag the current version

## git tag v1-beta
add another tag

## git tag
view which tags are available

## git co v1^
checkout previous version to v1

## git reset HEAD <file>
The reset command resets the staging area to be whatever is in HEAD. This clears the staging area of the change we just staged.

## git log --pretty=oneline
all on a line

## git log --pretty=oneline --max-count=2
only prints two lines of the log

## git log --pretty=oneline --since='5 minutes ago'
only prints what was written within last 5 minutes

## git log --pretty=oneline --until='5 minutes ago'
prints what was coded before the last 5 minutes

## git log --pretty=oneline --author=phoebe
only prints what I personally put

## git log --pretty=oneline --all 
prints everything

## git log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short
prints everything in a visually appealing way

## --pretty="..." 
defines the format of the output.

## %h 
is the abbreviated hash of the commit

## %d 
are any decorations on that commit (e.g. branch heads or tags)

## %ad 
is the author date

## %s 
is the comment

## %an 
is the author name

## --graph 
informs git to display the commit tree in an ASCII graph layout

## --date=short 
keeps the date format nice and short

## co 
checkout

## ci
commit

## st
status

## br
branch

## hist
log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short
  
## type
cat-file -t

## dump
cat-file -p


## gs
git status 

## ga 
git add

## gb
git branch 

## gc
git commit

## gd 
git diff

## go 
git checkout 

## gk 
gitk --all&

## gx 
gitx --all

## got
git 

## get
git 

