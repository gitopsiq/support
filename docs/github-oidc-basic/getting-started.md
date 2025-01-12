---
layout: default
title: Getting Started
parent: GitHub OIDC Basic
nav_order: 1
---

# Getting Started with GitHub OIDC Basic

## Prerequisites

1. Azure Subscription with Owner rights
2. GitHub repository or organization access
3. Permissions to create resources in Azure
4. If using automatic setup:
   - Ability to install the GitHub App in the repository
   - [Required GitHub App permissions](github-app-permissions.md)

## Installation Steps

1. Access the [GitHub OIDC Basic](https://azuremarketplace.microsoft.com/...) in Azure Marketplace
2. Click "Get It Now"
3. Follow the deployment wizard
4. If using automatic setup:
   - Install GitHub App with required permissions
   - Select repository for configuration. If you installed the app on a single repository, you can select the repository for configuration. If you installed the app on all or multiple repositories in an organization, you can select between the repositories for configuration. If you installed the app on a organization, you can select an existing repository or if you write a name that not exists, the app will create a new repository with that name. The same will happen if you installed the app on an enterprise.
   - App can be uninstalled after setup

## Post-Installation

1. Verify managed identity creation
2. Check OIDC federation setup
3. Test run the GitHub Actions workflow "Test GitHub OIDC Basic"
