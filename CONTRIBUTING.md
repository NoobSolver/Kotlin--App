# Contributing


When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Pull Request Process

Ensure any install or build dependencies are removed before the end of the layer when doing a build.
Check that there are no conflicts and your request passes Travis build. Check the log of the pass test if it fails the build.
Give the description of the issue that you want to resolve in the pull request message. The format of the commit message to be fixed - Fixes #[issue number] [Description of the issue]
Wait for the maintainers to review your pull request and do the changes if requested.
We use danger, so to update go to https://travis-ci.org and login with github. Next you will see a + near my repositories. Click on it and select your fork enabling it for Travis. Then go the dashboard and add two environment varibales which won't get displayed in the terminal(There's an option). The first one must be named USERNAME and should contain your github username. The second one should be named API_TOKEN and should contain a github personal token with atleast scope to public repos. It enables fast and easy moderation adequate testing.
Best Contribution Practices
Commits

Write clear meaningful git commit messages (Do read http://chris.beams.io/posts/git-commit/)
Make sure your PR's description contains GitHub's special keyword references that automatically close the related issue when the PR is merged. (More info at https://github.com/blog/1506-closing-issues-via-pull-requests )
When you make very very minor changes to a PR of your's, (like for example fixing a failing travis build or some small style corrections or minor changes requested by reviewers) make sure you squash your commits afterwards so that you don't have an absurd number of commits for a very small fix. (Learn how to squash at https://davidwalsh.name/squash-commits-git )
When you're submitting a PR for a UI-related issue, it would be really awesome if you add a screenshot of your change or a link to a deployment where it can be tested out along with your PR. This makes it very easy for the reviewers and you'll also get reviews quicker.
Feature Requests and Bug Reports
