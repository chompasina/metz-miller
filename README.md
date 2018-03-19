# Our wedding site

## Developing locally

* After first cloning down this repo, you'll need to cd into themes and `git clone https://github.com/MarcusVirg/forty` to install the theme
* Edit assets in the static directory, except the banner.jpg which needs to replace the theme's banner in the themes directory.
* Run server with `hugo server`

## Deploying with Surge.sh

* _Only permitted collaborators are authorized to deploy_
* first compile assets with `hugo` (which creates a copy of the compiled files in the public directory)
* cd into the public directory and run `surge`
* press enter to confirm the directory, then make sure to enter custom domain `metz-miller.com`
