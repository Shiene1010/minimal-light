# Giscus Feedback System Setup Guide

We have replaced the old "Services" section with **Giscus**, a comments system powered by GitHub Discussions.

## How it works
Giscus uses a script tag to load a comment widget on your page. The data is stored directly in your repository's **Discussions** tab.

## Repository Configuration
The current implementation in `_includes/giscus.html` is configured with these values:
- **Repo**: `Shiene1010/minimal-light`
- **Repo ID**: `R_kgDOROmmJg`
- **Category**: `General`
- **Category ID**: `DIC_kwDOROmmJs4C2S_v`

## Future Maintenance
If you ever move this site to a different repository, you will need to update these IDs in `_includes/giscus.html`. You can find your new IDs by visiting [giscus.app](https://giscus.app/).

## User Setup (Action Required)
1. Ensure **Discussions** are enabled in your GitHub repo settings.
2. Install the [giscus app](https://github.com/apps/giscus) on your repository.
