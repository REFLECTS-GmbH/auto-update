Auto-update is a minimalist [JavaScript GitHub action](https://help.github.com/en/articles/about-actions#javascript-actions) to keep pull requests [up to date with their base branch](https://developer.github.com/changes/2019-05-29-update-branch-api/).

It is the missing piece to really automatically merge pull requests when [strict status checks](https://help.github.com/en/articles/types-of-required-status-checks) are set up to protect against [semantic conflicts](https://bors.tech/essay/2017/02/02/pitch/).

Add [.github/workflows/auto-update.yml](.github/workflows/auto-update.yml) to your repository to use this action.
