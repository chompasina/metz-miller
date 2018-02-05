# Our wedding site

## Developing locally

* Edit assets in the static directory, except the banner.jpg which needs to replace the theme's banner in the themes directory.
* Run server with `hugo server`

## Deploying with Surge.sh

* first compile assets with `hugo` (which creates a copy of the compiled files in the public directory)
* cd into the public directory and run `surge`
* press enter to confirm the directory, then make sure to enter custom domain `metz-miller.com`
