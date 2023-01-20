# Management Tools

This script will clone, clean, and push back a github repository.
  The bfg jar is required to do the clean and will remove duplicate objects, clean branches and tags but does not delete it.  Running big is required because the repository will be too large (>2G) to be pushing back to a new repository.
  Requirements:
    GitHub connection
    Access to the repository to copy
    Java to run; https://rtyley.github.io/bfg-repo-cleaner/
    GitHub target repository, already created (recommended to be empty) 
    At least 3Gb of storage on local file system

  Parameters:
    the source owner name (usually GitHub username)
    the name of the repository
    the name of the target repository; <github_username>/<repository>
