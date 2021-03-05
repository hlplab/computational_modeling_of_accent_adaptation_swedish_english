# Cloning this repository

You can clone this repository, for example, through RStudio. Go to RStudio's file menu and select "New Project ...". Then select "Version control", then "Git". Then enter the URL to clone from. Then before knitting the document, download and install git lfs from https://git-lfs.github.com/. This is required because this repository contains some large files (the bootstrap simulations that would take a long time to complete otherwise) and they are stored and shared through git's Large File Storage (LFS) system.

After install git LFS, go the directory of your new project and run:

`git lfs install`

and

`git lfs track *.RData`

You can do so from the R terminal. Then make sure to pull the most recent version from the remote repository on github.com. Now your document should knit!


