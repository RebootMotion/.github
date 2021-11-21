# Reboot Motion Github Settings

## Issue Templates

The [ISSUE_TEMPLATE](./ISSUE_TEMPLATE/) folder sets the organization-wide default for adding new issues to repositories, reflecting the types of issues in Reboot Motion's current workflow:

* [NEW FEATURE](./ISSUE_TEMPLATE/NEW_FEATURE.yml)
  This template is used when suggesting new functionality that does not currently exist, unless it introduces a breaking change.
* [BUG FIX](./ISSUE_TEMPLATE/BUG_FIX.yml)
  This template is used when reporting a bug that needs to be fixed, unless it introduces a breaking change.
* [ENHANCEMENT](./ISSUE_TEMPLATE/ENHANCEMENT.yml)
  This template is used when suggesting a change to existing functionality that is not tied to a bug report and does not introduce a breaking change.
* [BREAKING CHANGE](./ISSUE_TEMPLATE/BREAKING_CHANGE.yml)
  This template is used instead of the other templates if the changes suggested for a new feature, bug fix, or enhancement would introduce a breaking change.

Additionally, the `blank_issues_enabled: false` setting in [config.yml](./ISSUE_TEMPLATE/config.yml) ensures that blank issues cannot be created. 

## Pull Request Template

This template sets an organization-wide default for writing effective Pull Requests. 
