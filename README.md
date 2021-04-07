# uniofcam-recipes
Autopkg recipes from University of Cambridge Apple Support Team.

## To use the PostProcessor

    autopkg repo-add ucam-apple-support-recipes

    autopkg run ---post=com.github.autopkg.ucam-apple-support-recipes.postprocessors/TeamsPostJSS --key=webhook_url=<webhook_url> <recipe> 

## To use .jamf.recipes

The .jamf.recipe files require adding the grahampugh-repo to ensure the processors are available:

    autopkg repo-add grahampugh-recipes