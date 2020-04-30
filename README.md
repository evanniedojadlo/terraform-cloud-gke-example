# terraform-cloud-gcp-experiment

## You can follow these steps and review the resource documentation as needed

Launch and manage a GKE cluster using Terraform Cloud.

Clone this repo and add it as a new repo within your github account

Create a [Terraform Cloud] account, workspace, and connect to a version control provider specifiying the cloned repo

Log into your [Google Cloud] account, if you haven't created one, create one

If you're not familiar with any of the above please reference this [video] which will visually take you through the process

Create the GCP service account and create a key

Add this key output as a variable within Terraform Cloud named gcp_credentials

On a new branch, make a minor change in the cloned repo and commit this to github

Merge this branch to master (depending on how you setup VCS in Terraform Cloud)
 
Navigate back to Terraform Cloud and watch your Terraform Plan

Select Terraform Apply and watch your infrastructure build

Destroy the infrastructure

## Questions?

Open an issue.

[Terraform Cloud]: https://www.terraform.io/docs/cloud/index.html
[Google Cloud]: https://cloud.google.com/
[video]: https://www.youtube.com/watch?v=5_DHR5wVVRo