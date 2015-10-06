# Dev Manifesto

This document describes how we, the developers at Tonsser, believe development should be done.

This document is not set in stone. If you see something that should be changed, or you think of some great new idea, don't hesitate to send a pull request.

## Mantras
- Get feedback on what you're building quickly.
- Don't be afraid to try new things. We believe in always using the best tool for the job.
- Do your best and ask for help when needed.

## Writing code
- Code for now, not for the future.
- Spend time refactoring.
- Pair programming is allowed and encouraged if you think it makes sense for what you're about to work on.
- "When you find you have to add a feature to a program, and the program's code is not structured in a convenient way to add the feature, first refactor the program to make it easy to add the feature, then add the feature." - Kent Beck.

## Project structure
- Each project should have a coding style. Enforcing this should be part of CI or some other automated process.
- Each project should have a script located at `script/bootstrap` which will get everything setup so you're ready to work on the project.

## Version control
- We use Git.
- We use GitHub pull requests for doing code review. Code review should be done most of time, but its not absolutely required. If you believe your change doesn't require a review, you can merge it once the tests have passed. Watch [this video](https://www.youtube.com/watch?v=PJjmw9TRB7s) about how to give good reviews.
- We use [git flow](http://nvie.com/posts/a-successful-git-branching-model/).
- We strive to write [good commit messages](http://chris.beams.io/posts/git-commit).

## Tasks and issues
- We use GitHub for tracking issues.
- When a pull request is open that fixes an issue, you're allowed to close the issue before the pull request is merged. This makes it easier to see which issues have not yet been worked on.
- We integrate GitHub issues with Trello (TODO).

## Testing
- All projects should have some form of automated testing.
- Doing TDD is encouraged whenever possible.
- All projects should use some form of continuous integration.
- Try to write code that is easy to test, and when things are hard to test, think about why.
- Strive not refactor code that doesn't have tests.
- Some testing is better than no testing at all.

## Documentation
- Write high level documentation about each class/module explaining what it does.
- If you code handles some strange edge case that might not be immediately obvious, write a comment that explains it.
- Each project should have some form of high level documentation explaining the architecture and the design decisions that have been made.

## Knowledge sharing
- You should be excited to learn new things and share them with your fellow developers.
- Acknowledge that programming is about learning.
- You're encouraged to give talks, or write about, new things you've learned.
