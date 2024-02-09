# Use GitHub Actions to create repository labels

This repo demonsrates an actions workflow, in `.github/workflows/labels.yml`, which runs only when that file itself is edited.

The workflow creates any missing labels in the repo that are defined in its JSON configuration.
