# Reboot Motion Github Labels

Thanks to Robin for their article, [How we organize GitHub issues: A simple style guide for tagging](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues), which served as the inspiration for much of this structure. The labels described in this document are implemented on this repository and are visible in the [label settings for this repository](https://github.com/RebootMotion/.github/labels?sort=name-asc).

### Table of Contents

* [Label Categories](#label-categories)
* [Labels by Category](#labels-by-categoriy)
  * [Environment](#environment)
  * [Feedback](#feedback)
  * [Inactive](#inactive)
  * [Problem](#problem)
  * [Products](#products)
  * [Type](#type)
  * [Workflow/Status](#workflow)
  * [Uncategorized/Miscellaneous](#uncategorized)

### Label Categories <a name="label-categories"></a>

Like Robin, we group labels by color and by broad theme. For example, any label in the group `Problems` is the same shade of red and are all related in that they signify an issue in one of our products. As mentioned above, the [label settings for this repository](https://github.com/RebootMotion/.github/labels?sort=name-asc) adhere to the following structure, allowing for easy previewing of the relevant colors.

| Label Category                                               | Label Color       |
| ------------------------------------------------------------ | ----------------- |
| **Environment** | Cold Turkey #CEAFB6 |
| **Feedback** | Electric Purple #9F2BFF |
| **Inactive** | Solitude #EEF0F3 |
| **Problem** | Fire Engine Red #E51616 |
| **Products** | Niagara #2BA897 |
| **Type** | Pacific Blue #009BCC |
| **Workflow/Status** | Beeswax #EAD8AD |
| **Uncategorized/Miscellaneous** | Lavender Blue #C9BCFF |

Hex/color name combinations sourced from [Color Name Hue](https://www.color-blindness.com/color-name-hue/) by Daniel Flueck.

### Labels by Category <a name="labels-by-category"></a>

* **Environment** <a name="environment"></a>
  The labels in this category indicate a relation to a specific environment. ***Note:**  `production` is excluded here (and appears as a **Problem** label) since any such issues are likely to have significant effects on user experience.
  * `staging` - issues related to the staging environment.
  * `local` - issues related to the local developer environment.
  
* **Feedback** <a name="feedback"></a>
  The labels in this category indicate a need for futher conversation or detail on a particular issue before it can move to the next step in our development workflow.
  * `discussion` - issues where there is an active, ongoing discussion to scope the issue, set acceptance criteria, or make a decision on whether or not to accept it.
  * `needs more info`  - issues where there is not sufficient information and the reporter needs to provide further details before moving forward.
  * `question` - issues where a question is present in the issue comments that should be answered before moving forward (could be used on its own or in conjunction with `discussion`/`needs more info`.)
* **Inactive** <a name="inactive"></a>
  An extension of **Workflow/Status**, the labels in this category indicate an issue that is not actively being worked on and clarifies the reason for that status.
  * `duplicate` - issues that have been closed in favor of another issue with similar/the same suggested changes. 
  * `invalid` - issues that are no longer relevant.
  * `on hold`- issues where the decision has been made to delay or pause related work until some point in the future.
  * `wontfix` - issues where the requested changes have been denied or the decision has been made to permanently stop related work.

* **Problem** <a name="problem"></a>
  The tags in this category indicate an issue in our codebase that needs to be resolved.
  * `bug` - issues that describe unexpected behavior 
  * `production` - issues that are present in the production environment, will also be labeled with one or more of `bug`, `infrastructure`, or `security`. 
  * `security` - issues related to application or infrastructure security.

* **Products **<a name="products"></a>
  The tags in this category indicate which product group an issue belongs to. Each product may relate to one primary repository or may span multiple repositories.
  * `api` - Reboot Motion API
  * `dashboard` - Reboot Motion Dashboard (AKA Front-End)
  * `db` - Reboot Motion Shared Database Module
  * `mocap` - Reboot Motion Mobile Motion Capture
  * `pipeline` - Reboot Motion Biomechanics Pipeline

* **Type** <a name="type"></a>
  The tags in this category indicate the type of change suggested in the issue, unless it is a bug or other problem (see **Problem** above.)
  * `breaking` - issues that involve a potentially breaking change.
  * `code change` - issues that require changes to source code.
  * `design` - issues that involve design work to update visual components.
  * `documentation` - issues that require or implement a change to related documentation. 
  * `enhancement` - issues that enhance an existing feature by adding more functionality.
  * `feature` - issues that introduce new functionality that does not currently exist.
  * `infrastructure` - issues that involve a change to existing infrastructure.
  * `optimization` - issues that enhance an existing feature without adding more functionality.
  * `repository` - issues that spawn a new project/repository (for example, if something is being broken out into a reusable module.)

* **Workflow/Status** <a name="workflow"></a>
  The tags in this category organize issues according to their place in our agile project management process. The list that follows is organized by workflow stage progress rather than alphabetically. ***Note:** any issue that has been rejected will have a tag from the Inactive category.*
  * `awaiting acceptance` - issues that have not yet been accepted for development that needs further documentation, discussion, or a decision. AKA "the icebox."
  * `accepted` - issues accepted for development, pending being pulled into a sprint. AKA "the backlog."
  * `in progress` - issues that are actively being worked on. These issues will typically have one or more companion pull requests in Draft mode. 
  * `awaiting review` - issues that are done being worked on and need to be reviewed. These issues have a companion pull request that is not in Draft mode and reviews by one or more teammates have been requested.
  * `done` - issues that are completed, meaning they meet all acceptance criteria and their "definition of done."
* **Uncategorized/Miscellaneous **<a name="uncategories"></a>
  Anything else that doesn't fall into one of the above categories.
  * Currently, there are no uncategorized labels; this is just here as a placeholder.


Happy labeling!

