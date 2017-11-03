# GitLesson2

This is a place where I learn and practice Git commands. 

This is an example showing how to use Amends to cleanly remove a unwanted submit.

$ echo 18 > 1.txt

$ git add .

$ git commit -m 18

$ echo 18.1 > 1.txt

$ git add .

$ git commit --amend -m 18.1

