# NPM Package Template

To get started, use this repo as a template and do the following:

- Update the details in package.json
- Update the assignees in .github/dependabot.yml
- Add your NPM_TOKEN to the repository secrets
- Add your GIT_PUSH_TOKEN to the repository secrets

Branch protection is set up for the main branch, requiring you to PR into main, have at least one review, and verify that your Typescript
is valid. Creating a PR will also automatically increment the patch number.

Commits to main are automatically published to NPM (provided your CI checks pass).

NPM Package Template © 2024 by Decatur Robotics is licensed under CC0 1.0 Universal
