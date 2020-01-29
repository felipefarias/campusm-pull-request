[![alt text](https://raw.githubusercontent.com/ExLibrisGroup/campusm-pull-request/master/PR.png "Vinta Logo")](https://www.exlibrisgroup.com/products/campusm-mobile-campus-app-platform/)

## 1. Pull request workflow
  * [ ] Read thoroughly the feature description to check if everything is implemented.

  * [ ] Run the code and use it as the end user would. Double check requested feature’s description.
  * [ ] Run final version on Real device (Android/Ios)

## 2. Creating the pull request

  * [ ] Create Pull Request (but don't assign it yet).v
  * [ ] Refer to Jira issue and make sure the issue contains all relevenat info to test it (urls, environment, customer info, credetails etc.)
  * [ ] Rebase your feature branch against master branch and fix any conflicts that mey apear inside your feature branch 
  * [ ] Add screenshots of the new behavior, if applicable.
  * [ ] Add a description including the context and the chosen implementation strategy.
  * [ ] Explain code lines which the reviewer might not understand correctly:
    * Don't do it in the description, do it in the code itself as comments.
    * Consider refactoring and changing variable/function/method names to make it clearer.

## PR Self Review: 
#### General guidlines:

  * [ ] Make sure code follows code style guidelines or standard usage
  * [ ] Naming convention: make sure you would understand your code if you read it a few months from now. Make your code self explenatory.
  * [ ] Reuse code - Try generalizing your code for future usage, and resue existing code as much as possible 
  * [ ] Architecture errors: could there be a better separation of concerns or are there any leaky abstractions?
  * [ ] Clean Code - too many nested 'if's are a bad sign.
  * [ ] Performance issues - make sure your solution is not taking more resouce then it needs (memory and cpu usage, thread management and network payloads), use Dev monitoring tools if needed 
  * [ ] Forgotten TODOs and noop lines: make sure they're mapped in your Jira issues board
  * [ ] Grammer and spelling - go over before submitting
  * [ ] If the feature needs regression tests, write them.
  * [ ] Once all problems are addressed, allocate the reviewer.

## Responding to feedback
  * [ ] If any problem hasn’t been addressed and the PR needs to be accepted ASAP, create new issues in Jire for remaining problems.
  * [ ] Respond all of the reviewer's comments ASAP:
    * Be grateful for the reviewer's suggestions. ("Good call. I'll make that change.").
    * Don't take it personally. The review is of the code, not yourself.
    * Try to understand the reviewer's perspective.
  * [ ] Once you receive feedback and address all issues, merge/rebase and close the PR/branch.
