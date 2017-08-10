# GitLab Runner Script

This is a quick script to start a docker gitlab-runner. It also enables docker privilege so it can run docker itself, this is useful for if in your GitLab CI pipeline you build a docker image.

## Requirements:

- sh
- docker