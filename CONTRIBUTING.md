# Contributing

We welcome issues and pull requests. Open an issue to discuss substantial changes, keep PRs focused, include tests and documentation where applicable, and respond to review feedback. Do not include secrets, confidential data, or proprietary SDK binaries.

## Developer Certificate of Origin

Every commit in a pull request must carry a `Signed-off-by: Name <email>` trailer matching its commit author identity. Sign off with `git commit -s` (or `git commit --signoff`). This certifies the Developer Certificate of Origin 1.1 below. No contributor license agreement (CLA) is required.

If a commit is missing a sign-off, amend your last commit with `git commit --amend --no-edit -s`, or for older commits use `git rebase -i` and amend each affected commit with `git commit --amend --no-edit -s`. Push the updated branch with `git push --force-with-lease` only to your own PR branch, never the protected default branch; coordinate first if others share the branch. A `Signed-off-by` comment on the PR does not replace commit trailers.

## Pull request process

1. Fork the repository and create a topic branch.
2. Add tests and documentation for changed behavior; run the project's checks.
3. Sign off every commit and open a PR explaining the change and linking any related issue.
4. Address review and ensure required checks, including DCO, pass.

## Developer Certificate of Origin 1.1 (verbatim)

Source: https://developercertificate.org/

```text
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.

```
