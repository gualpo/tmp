# set up git

## Guide for setting up GitHub and Rstudio connection (Mac)

**Connect Rstudio to GitHub**    

1. Extract SSH RHA key from Rstudio
> Rstudio > Tools > Global Options > Git/SVN > Copy SSH RHA key    

2. Create a repository on [GitHub](https://github.com/).    

3. Link Rstudio to GitHub    
> GitHub > Settings > SSH and GPG keys (Access) > New SSH key > Paste SSH RSA key    

**Clone GitHub repository into desired project directory**    

4. Copy SSH URL from GitHub
> GitHub > Repository > Code > Copy SSH URL (`git@github.com:<username>/<reponame>.git`)    

5. Clone repo (send to terminal)    
`git clone <paste SSH URL from GitHub>`

6. Set proper settings (send to terminal)    
`ssh-agent -s`    

7. Adjust path for id_rsa (if needed)
> Rstudio > Tools > Global Options > Git/SVN > Copy path of SSH RHA key    
`ssh-add ~/.ssh/id_rsa`


**Create new Rproject from existing directory**    

8. Create new R project    
> Rstudio > File > New Project... > New project from existing directory > Choose your cloned GitHub directory    

9. Push your first commit to GitHub