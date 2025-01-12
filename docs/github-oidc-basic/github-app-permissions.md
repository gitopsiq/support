---
layout: default
title: GitHub App Permissions
parent: GitHub OIDC Basic
nav_order: 3
---

# GitHub App Permissions

The GitOpsIQ GitHub App requires specific permissions to automate the setup of your repository. These permissions are only used during initial setup and you can uninstall the app afterward.

## Required Permissions

### Repository Permissions

- **Contents**: `Write`
  - Create and modify repository files
  - Configure repository settings
- **Workflows**: `Write`
  - Create and modify workflow files
  - Configure workflow settings
- **Environments**: `Write`
  - Create and configure environments
- **Secrets and variables**: `Write`
  - Create OIDC configuration secrets
  - Set environment variables

### Organization Permissions

- **None required**

## Installation Scope

You can install the app on:

- Single repository (if you want to test the app on a single existing repository)
- Selected repositories (if you plan to configure multiple existing repositories)
- All repositories in an organization (if you want the app to configure or create the new repositories)
- All repositories in an enterprise (if you want the app to configure or create the new repositories in all organizations in the enterprise)

## Security Considerations

- App only requests minimum required permissions
- Permissions are only used during initial setup
- App can be safely uninstalled after setup
- No ongoing access required
