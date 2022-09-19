# set up git

## Guide for Mac
Create a repository on github

Link Rstudio to gitHub

Tools > Global Options > Git/SVN > Copy SSH RHA key

send to terminal:
`git clone <copy SSH URL from GitHub>`
`git clone git@github.com:gualpo/tmp.git`

`ssh-agent -s`

create new Rproject from existing directory:    
Tools > Global Options > Git/SVN > Copy path of SSH RHA key

`ssh-add ~/.ssh/id_rsa`