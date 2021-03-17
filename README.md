# GITHUB SCRIPTS
Simple bash scripts to automatic do some github stuff from command line

# INSTALLATION

First create the personal access token for your github account, give permission to repo's activities.
https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token

Then don't forget to assign git config<br/>
git config --global user.name "YOUR_GITHUB_USERNAME"<br/>
git config --global user.email "YOUR_GITHUB_EMAIL"<br/>
 
# USAGE

Create new repo (default to public)<br/>
  <b>creategit REPO_NAME</b><br/><br/>
(OPTIONAL) Create new public repo privately<br/>
  <b>creategit REPO_NAME true</b><br/><br/>
Push commit<br/>
  <b>push</b><br/>
