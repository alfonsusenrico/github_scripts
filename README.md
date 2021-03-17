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
  <br/><b>creategit REPO_NAME</b><br/>
(OPTIONAL) Create new public repo privately<br/>
  <br/><b>creategit REPO_NAME true</b><br/>

Push commit<br/>
  <br/><b>push</b><br/>
