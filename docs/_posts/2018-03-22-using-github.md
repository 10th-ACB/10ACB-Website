---
layout: post
title: "Using GitHub.com"
description: "How the 10th ACB's J-6 Shop uses GitHub.com to achieve better development"
keywords: ""
---

**This page is marked to be updated,** for now we'll just outline a typical workflow for an update to a repo:
1. Create a new branch from the one you wish to update (usually "master" or the default branch) and call it `yourname/subject`. For example, if Badger wanted to add a new beret, we would name the new branch: `badger/nco-cap`
2. Update your local directory until you think you are ready to merge into the original branch.
3. Create a pull request with an appropriate name, give it the `pr/rdy` label and enter this in the description if it has a related issue: `closes #x` _(where `x` is the issue number)_
4. Add a code supervisor (probably John, so use `capriciousalex`) and wait for any feedback.
5. Once all feedback is resolved, your update will then be marked as ready for merging. Now you just have to wait for the merge!