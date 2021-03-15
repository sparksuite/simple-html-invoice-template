# How to contribute

First of all, thanks for your willingness to help improve this project! 🎉

We strive to make contributing to our open source projects easy, in part by following industry standard conventions and workflows, and by making testing and code formatting simple.

_If you’ve never contributed to an open source project before, check out [this project](https://github.com/firstcontributions/first-contributions), which guides people through their first contribution._

## A high-level overview

From a high-level, here’s what the contribution process looks like:

1. Choose something to contribute
1. Fork this repository
1. Prepare your local environment
1. Make the proposed changes
1. Test your changes
1. Update the docs/README
1. Format the code
1. Commit your changes
1. Open a PR
1. Iterate through the review cycle
1. Changes are accepted 🚀

It looks like a lot of steps, but it’s actually pretty easy. If you’ve contributed to open source projects before, it’s probably a familiar process. Let’s go over each step in more detail…

## 1. Choose something to contribute

Check out the issues tab if you don’t already have something in mind. We usually keep ideas for future improvements in there.

Choose one cohesive thing to work on per PR, rather than lumping together unrelated changes.

## 2. Fork this repository

This one is pretty straightforward. If you’re not a designated collaborator on this project (usually reserved for Sparksuite engineers), you won’t be able to create a new branch inside _this_ repository. But, by forking the repository (making a copy in your own account or organization), you’ll be able to create a new branch in the forked repository and commit your proposed changes there.

## 3. Prepare your local environment

Start by cloning the forked repository, then create a new branch off of `master`. Check out that new branch, then hop over to your favorite terminal. At the root of the repository, run `yarn dev` to prepare the repository for local development.

_Note: good branch names are usually succinct phrases that describe the change. So, for example, if a change fixes a typo in the README file, the branch name might read `fix-typo-in-readme`._

## 4. Make the proposed changes

Using the IDE of your choice, code your changes into existence. Try to follow the conventions and patterns already established in this codebase, particularly when it comes to commenting, spacing, naming, etc. Also, code readability and maintainability are very important; try to avoid “clever” code. During the review process, we’ll help catch anything that doesn’t look quite right.

## 5. Test your changes

You can do this by running `yarn test` at the root of the repository using your favorite terminal. All PRs have to pass every test before they can be accepted.

If you’ve introduced functionality that isn’t already covered by a test, which is often the case, you should add appropriate test(s). If you don’t know where or how to add test(s), just skip this step for now and let us know you need help with this part when you open the PR.

## 6. Update the docs/README

Many, but not all, changes will require updates to the documentation and/or README. Take some time to update those as necessary so that they remain accurate and up-to-date.

## 7. Format the code

To standardize the code’s stylization into our preferred format, run `yarn format` at the root of the repository. Most problems can automatically be fixed, but if some can’t, go ahead and address those manually.

## 8. Commit your changes

Commit your changes to the new branch you created in your forked repository. For organization, you may want to break up your work into multiple commits. Try to use descriptive and succinct commit messages.

_Note: if your commit messages are low quality, we’ll probably end up squash-merging your changes so that your commit messages don’t pollute the `master` branch’s commit history._

## 9. Open a PR

Visit your forked repository and open a new pull request. Make sure the source branch is the new branch you created, and the target branch is the `master` branch on this repository (not the `master` branch on your forked repository).

Try to describe the changes as best as you can in the description, including why you think the change is needed, how to take advantage of the change (if applicable), your design rationale, etc.

If your PR closes one or more issues, write `Closes #X` for each in the PR description (`X` being the issue number).

_Note: If your implementation or tests are incomplete, we recommend opening the pull request as a draft. This helps indicate there’s still more work left to be done._

## 10. Iterate through the review cycle

Opening a PR will notify Sparksuite’s engineers on Slack, and one of us will review your proposed contribution. If it’s not a good fit for our project, we’ll let you know why and will close the PR. Otherwise, we’ll leave feedback as necessary to help ensure the contribution meets our high standards of quality. Make any requested changes and then let us know when you want us to take another look.

## 11. Changes are accepted 🚀

Eventually, the PR will reach a point where we’re satisfied with the quality and we’ll incorporate your work into our project! The changes will usually be deployed with the next published release.
