# SBOM Deployment Workflow

This project contains a GitHub Actions workflow to generate and upload SBOMs for multiple repositories to DependencyTrack.

## Repository List
The list of repositories is stored in `repos.json`. To add or remove repositories:
1. Edit `repos.json` to include the repository `name` and `url`.