# GITHUB SCRIPTS
Simple bash scripts to automatic do some github stuff from command line

# INSTALLATION

First create the personal access token for your github account, give permission to repo's activities.
https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token

Then don't forget to assign git config
git config --global user.name "YOUR_GITHUB_USERNAME"
git config --global user.email "YOUR_GITHUB_EMAIL"
 
# USAGE

Create new repo (default to public)<br/>
  creategit REPO_NAME<br/>
(OPTIONAL) Create new public repo privately<br/>
  creategit REPO_NAME true<br/>

Push commit
  push
