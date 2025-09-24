# Secrets Configuration for CI/CD Workflow

This document outlines the secrets required to configure the GitHub Actions workflow for deploying to Cloudflare Pages (with optional Netlify fallback).

## Required Secrets

| Secret Name         | Description                                                     |
| ------------------- | --------------------------------------------------------------- |
| `CF_API_TOKEN`      | Cloudflare Pages API Token with write access                    |
| `CF_ACCOUNT_ID`     | Your Cloudflare Account ID                                      |
| `CF_PROJECT_NAME`   | The name of the Pages project                                   |
| `NETLIFY_AUTH_TOKEN`| (Optional) Netlify API Token for fallback deployment            |
| `NETLIFY_SITE_ID`   | (Optional) Netlify Site ID for fallback deployment              |

### Steps to Add Secrets
1. Go to your repository on GitHub.
2. Navigate to `Settings` > `Secrets and variables` > `Actions`.
3. Click `New repository secret`.
4. Add each secret with the appropriate value.
