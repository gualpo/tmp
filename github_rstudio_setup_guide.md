# set up git

## Guide for Mac

Create a repository on [GitHub](https://github.com/).    

**Link Rstudio to GitHub**    
Rstudio > Tools > Global Options > Git/SVN > Copy SSH RHA key    
GitHub > Settings > SSH and GPG keys (Access) > New SSH key > Paste SSH RSA key    

**Clone GitHub repository into desired working directory**    
Send to terminal:    
`git clone <copy SSH URL from GitHub>`    
`git clone git@github.com:<username>/<reponame>.git`    

`ssh-agent -s`

**Create new Rproject from existing directory:**    
Tools > Global Options > Git/SVN > Copy path of SSH RHA key

`ssh-add ~/.ssh/id_rsa`