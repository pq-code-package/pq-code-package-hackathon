[//]: # (SPDX-License-Identifier: CC-BY-4.0)
# Actions

It's expected most projects will use Github actions where the capabilities are sufficient, and that the following will be set up:

## build / test / package / linting

As needed by the project

## OSSF Scorecard

[OSSF scorecard](https://securityscorecards.dev/) assesses a project for best practice. 

Each project should integrate a scan using the OSSF scorecard github action.


## vulnerability scanning

[CodeQL](https://codeql.github.com/) is available for open-source projects, and should be considered if appropriate for the language used.

