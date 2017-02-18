# CONTRIBUTING

Contributions are welcome, provided that hey follow this guidelines.


## ISSUES GUIDELINES

Issues must use one of the available templates and all topics marked as required must be filled, by erasing the current help and example info on them and write your own.

All optional topics not used must maintain their title and have their body replaced by 'N/A'.

When any created issue do not follow this guidelines will not be considered.


## MERGE REQUESTS GUIDELINES

When opening your Merge Request ensure to do it against the branch from where the issue branch was created.

Merge requests must use one of the available templates and all topics marked as `required` must be filled.

All optional topics not used must maintain their title and have their body replaced by 'N/A'.


## DEVELOPMENT GUIDELINES

If you are not a Team member start by forking this Repository.

### Bug Fix / Security Fix

Starts with the [creation of an issue](https://gitlab.com/exadra37/my-base-repository/issues/new) following the applicable [issue guidelines](#issues-guidelines).

Each issue should only target a specific bug or security flaw, unless they are tightly coupled to the point you can't solve them separately.

After we create the Branch for this issue by using **_New Branch_** button in the Issue page, that by default will create the branch from `origin/master`.


### New Feature / Improve Feature / Refracting Code

Starts with the [Creation of a Milestone](https://gitlab.com/exadra37/my-base-repository/issues/new).

All development for this Milestone should have is own branch, so we must create one from `origin/master` using the Milestone title as the branch name.

Now we should split what we want to do in many tasks as we can by creating an Issue for each task and assign the issue to the Milestone.

The branch for this issue must be created from the Milestone branch.


### Type of Branches

As a result of the _Development Guidelines_ we will end up with different types of branches:

* master - this branch will contain the most recent code that will be released.
* last-release - as the name says.
* issue_number-issue_title - each issue will have is own branch for development.
* M-milestone_number-milestone_title - all Milestone issues will start, track and merged here.

Only `master` and `last-release` branches will be permanent ones in the repository and all other ones will be removed once they are merged.
