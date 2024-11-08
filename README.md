# Using GitHub Actions to Protect The Main

## Description

This app will demonstrate the utility of github actions as a tool for testing your code and protecting your main branch. Workflows are created using yml to trigger cypress tests when a pull request to the develop branch is made and when a merge request with the main is made. This app also makes use of automatic deployment when there is a successful merge with the main branch. Running tests such as these will make your app more robust and increase the likelyhood of a better user experience. 

## Installation

After cloning the repository, use an npm install. When you have the required packages, you will be able to run the tests using cypress. 

## Usage

The power of github actions are seen when changes are made in feature branches and pushed to the develop and main branches. The screenshots below illustrate how the github actions help protect the branches. Merging to the develop and main branches will not occur if these tests fail. 

![deploy to render](/assets/github-actions-deploy-to-render-for-main-merge.png)

![cypress test for pull request](/assets/github-actions-component-test-for-pr.png)

## Credits

This app utilized some start code to which the tests were added.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## How to Contribute

- Direct Request on GitHub [https://github.com/Theon87/github-actions-ci-cd-setup].

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)