[//]: # (SPDX-License-Identifier: CC-BY-4.0)
# Project Onboarding

## License Requirements

- Project source should be either under the Apache-2.0 or MIT license
- Documentation should be CC-BY-4.0

Any other license will need legal approval

## Requesting a Github repo

1. Decide on an initial name for the repo (see [tsc/11](https://github.com/pq-code-package/tsc/issues/11)) of the form `algorithm-language[-optionalplatform][-optionaldescriptor]`, for example `mlkem-assembly-avx2-jasmin`

2. Use the [tsc repo issues](https://github.com/pq-code-package/tsc/issues) to request a repository for the implementation including:
   - name
   - description
   - Appropriate access groups (teams):
     - admins
     - maintainers
     - core contributors
   - anything else relevant...

    - Alternatively in the issue specify the source repo to migrate the code from & engage in a discussion as to the best way to achieve this

## Teams

All access will be controlled through teams defined at the organization level.

## Repository configuration


DCO will be enabled, ie all changes need to be [signed off](https://wiki.linuxfoundation.org/dco). This is required to submit to the project.

There may be some variations on other configuration, particularly for any well-established projects, but by default:

* default branch is 'main'
* repository is public
* changes are done through a pull request
    * merge, squash, rebase all allowed
    * pull request branch should be up to date
    * auto-merge is allowed
    * head branches are not deleted
* changes need to be approved by 1 approver
* issues & projects are enabled

For contributors we'd expect a typical open source [fork and pull model](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/about-collaborative-development-models#fork-and-pull-model) to be used

