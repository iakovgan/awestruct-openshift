## Awestruct on OpenShift

#### Running on OpenShift
You can launch an Awestruct site on OpenShift using the [QuickStart on the OpenShift Hub](https://hub.openshift.com/quickstarts/161-awestruct)

#### Updating your site
- Clone your OpenShift application to your local workstation
- Make updates to your site
- git commit your changes
- git push

That's it! Your static site files will be generated on your gear and placed in the correct directory.  

This QuickStart supports both single gear and scaled deployments.  

The hot_deploy marker is set for this repository (.openshift/markers/hot_deploy) so your website will not go down while it's being updated.  The files will just be replaced while the server is running.

### Bug Reports

Please report bugs or log feature requests using Github Issues, pull requests are welcome.
