## Stub readme file

This is a *stub* readme file to descibe your project

Please update it with contact information for your repository and team.

Formatting help can be found at [github](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)

## Requirements for private repositories

If this repository is intended to be private, please see the [CM requirements](https://snowflakecomputing.atlassian.net/wiki/spaces/~367958958/pages/671909031/Creating+a+new+repository)

## Metadata Requirements

This repository must have a metadata file located at `/.github/repo_meta.yaml`. This template repository already includes [that file](./.github/repo_meta.yaml).

In addition to having a metadata file, this repository must define the following metadata in the metadata file:
* `production` - set this field to `true` if this repository is used to develop, build, or deploy production services. Set this field to `false` otherwise. `true` is the default setting.
* `point_of_contact` - set this field to the GitHub user or team that should be the point of contact for this repository.
* `distributed` - set this field to true if code from this repository (including binaries created from this repository) is downloaded by or onto non-Snowflake computers”. Set this field to `false` otherwise. `false` is the default setting. For more information, please check [Snowflake Open Source Policy](https://docs.google.com/document/d/1lsyiafPrn_j5X10hMl62S6cVn26ru_Oxbnh9L6tgav4)
* `modified` - set this filed to `true` if the open source code in the repository is modified in anyway. Set this field to `false` otherwise. `false` is the default setting. 
* `code_owners_file_present` - set this field to `true` if this repository includes a code owners file. Set this field to `false` otherwise. `true` is the default setting.
* `jira_project_issue_type` - set this field with jira project and related issue type (e.g., `SNOW/BUG`). 
* `jira_area` - set this field with jira project area (e.g., `Data Platform: Ecosystem`). 
