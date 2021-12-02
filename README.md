# App in a Box - Scaler 

This is a simple thumbnail maker that uses a Cloud Storage bucket and a Cloud 
Functions based watcher to make thumbnails for uploaded images. 

It's meant to be a very simple example to illustrate the Storage Bucket with a 
Function attached pattern. 

![Scaler architecture](/architecture.png)

## Install
You can install this application using the `Open in Google Cloud Shell` button 
below. 

<a href="https://ssh.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https%3A%2F%2Fgithub.com%2FGoogleCloudPlatform%2Fappinabox_scaler&cloudshell_print=install.txt&cloudshell_open_in_editor=README.md">
        <img alt="Open in Cloud Shell" src="https://gstatic.com/cloudssh/images/open-btn.svg">
</a>

Once this opens up, you can install by: 
1. Creating a Google Cloud Project
1. Then typing `./install`

## Cleanup 
To remove all billing components from the project
1. Typing `./uninstall`


This is not an official Google product.