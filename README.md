# Travic CI Laravel and VuePress
<img src="https://travis-ci.org/kennyLtv/TravisCiDeploymentTesting.svg?branch=master"/>

Travis CI deployment for Laravel and VuePress projects. 
* Deploy's docs to GitHub Pages.
* Runs unit tests against Laravel Application.
* On tag of master branch will create a release zip and add it to GitHub releases.

Deploys to GitHub Pages when a push is made to the master branch.

Need to set `GITHUB_OAUTH_TOKEN` in TravisCI Environment with a User Token to be able to push to the branch.