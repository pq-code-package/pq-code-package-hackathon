[//]: # (SPDX-License-Identifier: CC-BY-4.0)
# Standard files/template

The following standard files are recommended. As the project evolves we may revise this list.

| File | Description |
| -- | -- |
| README.md | Introduction to the project |
| LICENSE | LICENSE notices |
| CODE_OF_CONDUCT.md | Code of Conduct |
| MAINTAINERS.md | List of maintainers |
| CONTRIBUTING.md | Guidance for contributors |
| GOVERNANCE.md | Information about how the project is governed |
| SECURITY.md | Security Policy, including how to report a security bug |
| SUPPORT.md | Support policy and information |
| CODEOWNERS | defines owners (for automatic approval assignment). *Must use group definitions* |
| antitrust.md | Linux Foundation anti-trust statement |

Some of the content needs to refer to policies that we have yet to write, so will need to updated later, likely with a link to the main pqcp docs.

## Template

A template is available at [https://github.com/pq-code-package/template-code](https://github.com/pq-code-package/template-code)

This can be used to create new repositories, and additionally adds:

### OpenSSF Scorecard workflow

[OpenSSF scorecard] has been added to run by default.

This makes some assessments about the project's safety. Some issues will be noted in code scanning results, but will act as 'todos' as the project matures.

### Standard Issue/PR templates

* issue templates under `.github/ISSUE_TEMPLATE`
* PR templates under `.github/pull_request_template.md`

These files will need to be customized. **TODO** markers have been added.