+++
author = "AMAAN"
date = ""
draft = true
hero = "/images/max-di-capua-AhHICglxxx8-unsplash.jpg"
tags = []
title = "Test Artikel 001"
type = "blog"

+++
Repository administrators can require that all pull requests receive at least one approved review from someone with _write_ or _admin_ permissions in the repository or from a designated code owner before they're merged into a protected branch. For more information, see "[About protected branches](https://docs.github.com/en/enterprise/2.13/user/articles/about-protected-branches)."

When required reviews are enabled, anyone with access to the repository can approve changes in a pull request. However, you won't be able to merge your pull request until someone with _write_ or _admin_ permissions in the repository approves your pull request's changes in their review. For more information about repository permission levels, see "[Repository permission levels for an organization](https://docs.github.com/en/enterprise/2.13/user/articles/repository-permission-levels-for-an-organization)." If review is required from a designated code owner and the pull request affects code that has a designated owner, approval from that owner is required.

If a pull request has changed since it was reviewed and the person who requested changes isn't available to give an approved review, repository administrators or people with write access can dismiss a review. For more information, see "[Dismissing a pull request review](https://docs.github.com/en/enterprise/2.13/user/articles/dismissing-a-pull-request-review)."

After all required reviewers have approved a pull request, you won't be able to merge it if there are other open pull requests with pending or rejected reviews and those pull requests have a head branch pointing to the same commit. Someone with _write_ or _admin_ permissions will need to approve or dismiss the blocking review on the other pull requests before you can merge.

### [Merging a pull request on GitHub Enterprise](https://docs.github.com/en/enterprise/2.13/user/articles/merging-a-pull-request#merging-a-pull-request-on-github-enterprise)