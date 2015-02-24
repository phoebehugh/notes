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
