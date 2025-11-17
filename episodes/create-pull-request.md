---
title: "Submitting a Pull Request"
teaching: 10
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 

- How do you create a pull request using GitHub?
- How long should we keep a pull request open?
- How do we request a review of a pull request?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Create a pull request based on the changes we submitted to a new branch
- Describe the reasons to keep a pull request short-lived
- Request a review of your pull request from another participant

::::::::::::::::::::::::::::::::::::::::::::::::

## Creating a Pull Request

In order for someone else to take a look at our proposed change,
let's create a pull request now from this new branch.

1. First, go the `Pull requests` tab at the top of the group repository main page, and select `New pull request`
1. In the `Compare changes` page that comes up:
   - Select `compare:` and select your new branch, e.g. `readme-broken-link-fix`. You should now see a summary of the changes between the new branch and the main branch, i.e. a single commit and the fix you made earlier
   - Select `Create pull request`
1. In the `Open a pull request` page that appears:
   - Add details for pull request before creating it, including a label (e.g. `documentation`), title (if you want to change it), and brief description (if you think it's needed)
   - Select `Create pull request`

::::::::::::::::::::::::::::::::::::::::: instructor

## Checkpoint: Create Pull Request

Who's been able to create the pull request?

:::::::::::::::::::::::::::::::::::::::::

You’ll then see a summary of the pull request, including a summary of any conflicts with the base (`main`) branch, of which there should be none.
There’s also an option to merge the pull request - but don’t do this yet, since you’ll need to wait for your pull request to be reviewed!

Interestingly, even though we have created this PR to do a merge, we could continue developing our code on this new branch indefinitely if we wanted.
We could make and push new commits to this branch, which would show up here, and we then merge at a future date.
This may be particularly useful if we need to have a longer discussion about the PR as it is developing.
The discussion would be captured in the comments for the PR, and when ready, we then merge the PR.

:::::::::::::::::::::::::::::::::::::::::  callout

## How Long should PRs be Open?

Which raises the question, of how long should PRs be open, or branches for that matter?
To some degree, this depends on the nature of the changes being made.
But branches in Git are designed, and should be wherever possible, short-lived and deleted when no longer required.
The longer a branch is open, the more potential changes could be made to the main branch.
Then when it comes time to merge the branch, we may get a lot of conflicts we need to manage.
So generally, it's a good idea to keep your branches open for a day or two, a few days maximum, before creating a PR and doing a merge if you can.
Note that we can also see this PR,
as well as any others, by selecting the `Pull request` tab.

::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge

## Obtain and Add GitHub Account ID from another Participant

For the next stage, you'll be reviewing a pull request. Either:

- If you are attending a workshop with other learners,
the instructor will enable you to share your GitHub repository with another learner to review, and you'll also obtain another learner's repository in return
- If you are going through this material on your own,
ask a colleague with a GitHub account to send you their GitHub account username to review your pull request instead.

:::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::: instructor

## Checkpoint: Exchange Repository 

Who's been able to add their GitHub repository's URL to the shared document and obtain another in return?

:::::::::::::::::::::::::::::::::::::::::

First we need to add our collaborator who will do the review as a repository collaborator.
Ordinarily, as a collaborator on this repository, this would have been done a lot earlier in a project:

1. Go to the repository main page, then select `Settings` and then `Collaborators`
1. In the pop-up that appears, type in their GitHub account username, and when it appears, select `Add <username>`

You should see their username now added to the `Manage access` list with `Pending invite`.

::::::::::::::::::::::::::::::::::::::::: instructor

## Checkpoint: Add Partner as Collaborator to Repository

Who's been able to add their assigned partner as a collaborator to their own repository?

:::::::::::::::::::::::::::::::::::::::::

## Accept Repository Invite

Now, since we're also reviewing someone else's pull request,
we need to check for the invite from another participant and accept it.
Check the email account associated with your GitHub account,
and you should find an email from GitHub about the invitation.
Open the email and accept the invite,
following the instructions.
The email may not show immediately.

::::::::::::::::::::::::::::::::::::::::: instructor

## Checkpoint: Accept Invite

Who's been able to find and accept the repository invite from their assigned partner?

:::::::::::::::::::::::::::::::::::::::::

You've now been accepted as a collaborator on your partner's repository.

## Add Collaborator as Reviewer to our PR

To assign your claimed reviewer to your own pull request:

1. Go back to your repository's main page
1. Select `Pull requests`, and then select the PR you created
1. Select `Reviewers` and add the GitHub account for the reviewer

You should see an orange filled circle next to their name, indicating that you have requested their review and they have yet to submit it.
We could add as many reviewers as we want, particularly if this is a complex change that affects many aspects of the codebase.

::::::::::::::::::::::::::::::::::::::::: instructor

## Checkpoint: Add Another as a Reviewer to PR

Who's been able to add another's claimed GitHub username as a reviewer to their pull request?

:::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints 

- Try to keep pull requests short-lived to avoid them becoming outdated with other branches such as `main`
- We can request reviewers for a pull request by adding their GitHub account to a list of `Reviewers`

::::::::::::::::::::::::::::::::::::::::::::::::
