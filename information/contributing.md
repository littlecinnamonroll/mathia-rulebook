---
title: Contributing to the Mathia Rulebook
layout: default
permalink: /contributing/
---

Hey! Good to hear that you want to help out.

This wiki is hosted on GitHub! What you're reading right now has been generated by a site generator called _Jekyll_. How it works isn't really important, but you have to understand a few things before you can contribute:

1. Your changes must be in a specific format in order to make everything work. Let's say you want to create a new role. There is a template, in [New Role Template]({{ site.baseurl }}{% link information/new-role-template.md %}). Follow it religiously. Stick to the guidelines and the rules.
2. All changes are made using something called Git. Mathia uses the Github Flow system. Let me break down what that means:
  * Any edits are made in plain text, using something called Markdown. Or, specifically, a version of Markdown called Kramdown. Google it to see how to write in Markdown.
  * These plain text files are stored at https://github.com/denosawr/mathia-rulebook.
  * If you want to make changes **to the documentation or rules**, they're stored as Markdown files \(`.md`\) in the `information` and `roles` folders. Click the relevant file, click the Edit button (pencil icon) in the top right and make your changes. You'll need a GitHub account.
  * You **do not** have edit permissions for the main repository. What you can do after you've made your changes, is click on the green "Make a Pull Request" button. A Pull Request is essentially a request to merge your changes with the main version, to update the rulebook with your own version of the rules. This has to be accepted by a maintainer (like @denosawr#8290) before it gets submitted to the live rulebook. This also can facilitate discussion of changes before they go live.
  * In your Pull Request, feature a brief description of your change(s). If your change is **a clarification of an existing role**, set the base branch as `base:master`. If you have a suggestion for a change to a role, or a new role, make sure that your pull request goes to the `base:changes` branch.
3. Due to the nature of the pull request, you can submit changes which you think will be controversial. This can facilitate later discussion as they review your proposed changes, but of course there's a chance your Pull Request may be closed without merging your changes.

Here's the way the branches work (for the programmers):
* Documentation changes are submitted to the `changes` branch, which will merge with `master` after the current game finishes.
* Code changes and documentation clarifications go to the `master` branch, they can come live immediately if accepted

Thank you for contributing :)