super-code
==========
mkdir ~/super-code
# Creates a directory for your project called "Hello-World" in your user directory

cd ~/super-code
# Changes the current working directory to your newly created directory

git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/you/Hello-World/.git/

touch README
# Creates a file called "README" in your Hello-World directory

git add README

git commit -m 'first commit'

git remote add origin https://github.com/bedrosian/super-code.git

git push origin master
