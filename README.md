# Management Tools

This script will clone, clean, and push back a github repository.<br>
  The bfg jar (from https://rtyley.github.io/bfg-repo-cleaner/) is required to do the clean and will remove duplicate objects, clean branches and tags but does not delete it.  Running big is required because the repository will be too large (>2G) to be pushing back to a new repository.<br>
  Requirements:<br>
  <ul>
  <li>GitHub connection</li>
    <li>Access to the repository to copy</li>
    <li>Java to run; https://rtyley.github.io/bfg-repo-cleaner/</li>
    <li>GitHub target repository, already created (recommended to be empty)</li>
    <li>At least 3Gb of storage on local file system</li>
  </ul>

  Parameters:<br>
  <ol>
    <li>the source owner name (usually GitHub username)</li>
    <li>the name of the repository</li>
    <li>the name of the target repository; <github_username>/<repository></li>
      </ol>
<br>
This script may take approximately 30 minutes to complete.  When complete you can view the copied repository on github and review the "Active Branches" to determine any that may contain unmerged changes.
