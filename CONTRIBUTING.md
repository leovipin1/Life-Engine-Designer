# Welcome to Life Engine Designer contributing guide

Thank you for investing your time in contributing to the program.

In this guide, you will get an overview of the contribution workflow for opening an issue, creating a PR and merging the PR.

Use the table of contents on the top left corner of this document to get to a specific section of this guide quickly.

## New contributor guide

To get an overview of the project, read the **[README](README.md)**. Here are some resources to help you start the Life Engine Designer program.

- **`[Program's initial setup steps](update the link for the initial steps document)`**

- **`[Program's documentation](update the link for program's documentation landing page)`**

## Getting started

Check to see what types of contributions we accept before making changes.

### Label types

1. **https://github.com/leovipin1/Life-Engine-Designer/labels/Category%3A%20Issue** - *Applied automatically to a new issue when submitted*.

2. **https://github.com/leovipin1/Life-Engine-Designer/labels/Category%3A%20PullRequest** - *Applied automatically to a new pull request when submitted*.

3. **https://github.com/leovipin1/Life-Engine-Designer/labels/Status%3A%20Backlog** - *Applied automatically to a new issue or pull request when submitted and removed automatically when an assignee is assigned to the issue or pull request*.

4. **https://github.com/leovipin1/Life-Engine-Designer/labels/Status%3A%20Closed** - *Applied automatically to an issue or pull request when they are closed and removed automatically when a closed issue or pull request is reopened*.

5. **https://github.com/leovipin1/Life-Engine-Designer/labels/Status%3A%20Developing** - *Applied automatically to an issue or pull request when an assignee is assigned to it and removed automatically when an issue or pull request is closed*.

6. **https://github.com/leovipin1/Life-Engine-Designer/labels/Status%3A%20Incomplete** - *Applied automatically to a new issue when submitted and removed automatically when an assignee is assigned to the issue*.

7. **https://github.com/leovipin1/Life-Engine-Designer/labels/Status%3A%20Reopened** - *Applied automatically when an issue or pull request is reopened*.

8. **https://github.com/leovipin1/Life-Engine-Designer/labels/Status%3A%20Wont%20Do%2FFix** - *To be applied to an issue or pull request when it cannot be either implemented or fixed or merged*.

9. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20Bug** - *Applied automatically to a new issue(whose title begins with **`[Bug]:`**)*.

10. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20BugFix** - *Applied automatically to a new pull request(whose commit message title begins with **`bf:`**)*.

11. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20Documentation** - *Applied automatically to a new issue(whose title begins with **`[Documentation]:`**) or new pull request(whose commit message title begins with **`dc:`**)*.

12. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20Epic** - *Applied automatically to a new issue(whose title begins with **`[Epic]:`**) or new pull request(whose commit message title begins with **`ep:`**)*.

13. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20Feature** - *Applied automatically to a new issue(whose title begins with **`[Feature]:`**) or new pull request(whose commit message title begins with **`ft:`**)*.

14. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20HotFix** - *Applied automatically to a new pull request(whose commit message title begins with **`hf:`**)*.

15. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20Miscellaneous** - *Applied automatically to a new issue(whose title begins with **`[Misc]:`)** or new pull request(whose commit message title begins with **`ms:`**). To be applied to an issue or pull request which cannot be categorised in any of the **`Type:`** labels*.

16. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20Repo** - *Applied automatically to a new issue(whose title begins with **`[Repo]:`**) or new pull request(whose commit message title begins with **`rp:`**)*.

17. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20Task** - *Applied automatically to a new issue(whose title begins with **`[Task]:`**) or new pull request(whose commit message title begins with **`tk:`**)*.

18. **https://github.com/leovipin1/Life-Engine-Designer/labels/Type%3A%20UserStory** - *Applied automatically to a new issue(whose title begins with **`[User Story]:`**) or new pull request(whose commit message title begins with **`us:`**)*.

***Note:***
1. The labels **`must not`** be added to an issue or pull request when submitting or closing. The respective labels will be applied once submitted as per the issue's title or commit message of the pull request.

2. An issue or pull request **`must not`** be added to any project at the time of submission. It will automatically be added to the **`Life Engine Designer Plan`** project.

3. An issue or pull request **`must not`** be assigned to any person at the time of submission.

4. Once an assignee is assigned to an issue or pull request, it is automatically moved from the **`Backlog`** to the **`Developing`** status in the project.

5. Once an issue or pull request is closed, it is automatically moved from the **`Developing`** to the **`Finished`** status in the project.

### Issues

Below are the types of issue templates. Kindly use the specific issue template as per your requirement.

#### Epic

This type of issue must be used to submit a high-level idea for the program's functionality. You can open a new epic issue using a **[Epic relevant issue form](https://github.com/leovipin1/Life-Engine-Designer/issues/new?assignees=&labels=&template=issue-epic.yml&title=%F0%9F%8F%94%EF%B8%8F+%5BEpic%5D%3A+)**. The title of the issue must begin with **`🏔️ [Epic]:`**.

#### Feature

This type of issue must be used to submit the break up of the high-level idea of a functionality ***`(Epic)`***. You can open a new feature issue using a **[Feature relevant issue form](https://github.com/leovipin1/Life-Engine-Designer/issues/new?assignees=&labels=&template=issue-feature.yml&title=%E2%9C%A8+%5BFeature%5D%3A+)**. The title of the issue must begin with **`✨ [Feature]:`**.

#### User Story

This type of issue must be used to submit the break up of the functionality based on user persona ***`(Feature)`***. You can open a new user story issue using a **[User Story relevant issue form](https://github.com/leovipin1/Life-Engine-Designer/issues/new?assignees=&labels=&template=issue-userstory.yml&title=%F0%9F%93%87+%5BUserStory%5D%3A+)**. The title of the issue must begin with **`📇 [User Story]:`**.

#### Task

This type of issue must be used to submit the work needed for developing the user story-based functionality ***`(User Story)`***. You can open a new task issue using a **[Task relevant issue form](https://github.com/leovipin1/Life-Engine-Designer/issues/new?assignees=&labels=&template=issue-task.yml&title=%F0%9F%93%9D+%5BTask%5D%3A+)**.The title of the issue must begin with **`📝 [Task]:`**.

#### Bug

This type of issue must be used to submit the flaws found in the program during development or operation. You can open a new bug issue using a **[Bug relevant issue form](https://github.com/leovipin1/Life-Engine-Designer/issues/new?assignees=&labels=&template=issue-bug.yml&title=%F0%9F%90%9E+%5BBug%5D%3A+)**.The title of the issue must begin with **`🐞 [Bug]:`**.

#### Documentation

This type of issue must be used to submit the updation of the program's documentation. You can open a new documentation issue using a **[Documentation relevant issue form](https://github.com/leovipin1/Life-Engine-Designer/issues/new?assignees=&labels=&template=issue-documentation.yml&title=%F0%9F%93%84+%5BDocumentation%5D%3A+)**.The title of the issue must begin with **`📄 [Documentation]:`**.

#### Repository

This type of issue must be used to submit any changes to the repository that need a pull request. You can open a new repository issue using a **[Repository relevant issue form](https://github.com/leovipin1/Life-Engine-Designer/issues/new?assignees=&labels=&template=issue-documentation.yml&title=%F0%9F%93%84+%5BDocumentation%5D%3A+)**. The title of the issue must begin with **`🗃️ [Repo]:`**.

#### Miscellaneous

This type of issue must be used to submit any task which cannot be categorised in any of the above issue types. You can open a new miscellaneous issue using a **[Miscellaneous relevant issue form](https://github.com/leovipin1/Life-Engine-Designer/issues/new?assignees=&labels=&template=issue-miscellaneous.yml&title=%F0%9F%A4%94+%5BMisc%5D%3A+)**. The title of the issue must begin with **`🤔 [Misc]:`**.

### Make changes

#### Make changes via UI.

First, it is **`not recommended`** to make any changes via the UI. Always use a code editor like **`VS Code`**. If any changes are being made via UI, ensure the commit title follows the **[commit message title convention](#commit-message-title-convention)**.

#### Make changes locally

1. Fork the repository.
- Using GitHub Desktop:
  - **[Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop)** will guide you through setting up Desktop.
  - Once Desktop is set up, you can use it to **[fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)**.

- Using the command line:
  - **[Fork the repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository)** so that you can make your changes without affecting the original project until you're ready to merge them.

2. Create a working branch and start with your changes

#### Branching convention

Every branch that is created for the development of the program must follow the below guidelines.

1. The branching method for this repository must follow the **`GitHub branch flow strategy`**, where every work done must be created from the **`main`** branch as its base.

2. Before starting work on any issues, a new branch must be created from the **`main`** branch with the naming convention below.

3. **`type/#issueno-title-of-the-issue`** - *This is the branch naming convention, where the **`type`** must be the type of issue for which this branch is being created, **`#issueno`** is the number of the issue that is being worked and **`title-of-the-issue`** is the title of the issue that is being worked on*.

4. Once the work is completed, the work must be committed, and the branch must be published to GitHub by creating a pull request.

5. Once the pull request is merged on GitHub Desktop, move back to the **`main`** branch and pull from GitHub.

6. Once the pull is done into the **`main`** branch, the merged branch must be deleted locally, as the branch on GitHub is automatically deleted after the merge. The below command must be used to delete the merged branch locally.

    **`git branch -vv | grep ': gone]' | grep -v '\*' | awk '{ print $1; }' | xargs -r git branch -d`**

#### Commit your update

Commit the changes once you are happy using the **[commit message title convention](#commit-message-title-convention)**.

### Pull Request

When you're finished with the changes, create a pull request known as a PR.
1.  Fill the **`Pull Request`** template. This template helps users understand your changes and the purpose of your pull request.

2.  Don't forget to **[link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)** if you are implementing/solving one.

3. Only merge the pull request once all the status checks are complete, as they manage the labels and project status movement.

#### Your PR is merged

Congratulations! Once your PR is merged, your contribution will be publicly visible.

### Commit message title convention

Every commit message title must follow the below convention.

**`xx:#[##] [issue title]`**

The break up of the convention is as below.

- **`xx:`** - *The beginning of the commit message*.

As we use automatic labelling for pull requests, every commit message must begin with the following.

1. **`ep:`** - *The commit message beginning with this indicates that the commit is for completing an Epic issue*.

2. **`ft:`** - *The commit message beginning with this indicates that the commit is for completing a Feature issue*.

3. **`us:`** - *The commit message beginning with this indicates that the commit is for completing a User Story issue*.

4. **`tk:`** - *The commit message beginning with this indicates that the commit is for completing a Task issue*.

5. **`bf:`** - *The commit message beginning with this indicates that the commit is for fixing a bug issue during program development*.

6. **`hf:`** - *The commit message beginning with this indicates that the commit is for fixing a bug issue during program production*.

7. **`dc:`** - *The commit message beginning with this indicates that the commit is for completing a Documentation issue*.

8. **`rp:`** - *The commit message beginning with this indicates that the commit is for updating the Repository structure*.

9. **`ms:`** - *The commit message beginning with this indicates that the commit is for completing a Miscellaneous issue*.

- **`#[##]`** - *The issue number for which this commit is begin done*.

- **`[issue title]`** - *The title of the issue for which this commit is being done*.