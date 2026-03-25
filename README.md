# Postman Debian/Ubuntu Builder

This repository automatically:

- Fetches latest Postman Linux release
- Builds a .deb package
- Publishes it to GitHub Releases

## Workflow

- Runs daily via GitHub Actions
- Manual trigger supported

## Output

- postman_<version>_amd64_debian.deb
- postman_<version>_amd64_ubuntu.deb
