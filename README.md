# GITHUB REPO AUTO GENERATE
Simple bash script to automatic generate new repo from commandline

# INSTALLATION

First create the personal access token for your github account, give permission to repo's activities.
https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token

Windows :
  1. Git clone this repo to your project folder
  2. Open script with any text-editor, change the #TOKEN# with your personal access token

Linux   :
  1. Git clone this repo to your project folder
  2. Open script with any text-editor, change the #TOKEN# with your personal access token
  3. If you want to use the script globally, you can move it to /usr/bin or /usr/local/bin
 
# USAGE

1. Create new repo (default to public)<br/>
    creategit REPO_NAME
3. (OPTIONAL) Create new public repo privately<br/>
  creategit REPO_NAME true
