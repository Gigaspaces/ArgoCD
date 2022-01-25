# Argocd

This repository containing application yaml files that will be install in argocd.

The app of apps application install by the argocd terragrunt.hcl and point on kustomzaion file that in overlays directory.

In kustomization.yaml file we point on the resources that have to be install on argocd.

Evry application has her own configuration and you have to cgange them accordung to your project.

## Change configuration

_role-arn_ - in every application you have to change the role-arn in annotations to your role (you can find it in aws/iam/role)

_GigaCI.yaml_ - change repoURL to your repository

