# terraform-template
Terraform template repository

# Fetching new version of the template 

Within your repository you need to add the template as a remote to your local working env. you can do this using the git cli within your local execution environment

`git remote add template [URL of the template repo]`

Then within your local execution environment run the git fetch command to pull in all the branches from the template.

`git fetch --all` 


After fetching the latest version of the templates branches you can merge them in using the following command 

`git merge template/[name of the branch] --allow-unrelated-histories`

