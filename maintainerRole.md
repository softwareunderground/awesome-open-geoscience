# Maintainer Role

This document provides an overview of how to be a maintainer for this repository.

## Goals

The goal for maintainers should be for contributors to have a good experience 
adding to the list. New potential contributors should be able to look at the 
record of past experiences in closed pull requests and be encouraged by what 
they see to add their own contribution.

If a contribution is lacking in some manner that leads to it falling short 
of being "AWESOME", clear feedback should be given 
with a pleasant and positive framing. Often this can lead to improvements 
in projects, additional documentation that helps users, etc. All good things.

Rarely, a contribution will not be merged due to sustained shortcomings. 
This is okay too. Maintaining the minimum bar helps both the consumers of 
the list and the contributions to the list.


## Tasks

Maintainers tasks for this repository are either approving pull requests, 
submitting their own contributions like everyone else, and handling 
questions about new features. 

### Approving Pull Requests

The bulk of the maintainers task is about approving pull requests. 

#### When to approve

What to check for is described in the contribuging.md and awesome.md files.

Additionally, there are cases where a maintainer will want to attempt to 
run the program themselves. This is not always required, but 
sometimes seems appropriate if the "installation" or "how to use" 
instructions are unusually sparse. In the past, this has caught
issues that prevented new users from using the project who work on a different
operating system than the contriutor. 

#### Debugging pull request conflicts

Sometimes there are competing pull requests that conflict with one another. 
This can require a maintainer to resolve the merge conflict. 
For instructions on how to "fix merge conflict" on the web interface for 
GitHub see 
[GitHub's fixing merge conflict instructions](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)

#### CI/CD Automation test failture

Please read the ["How to fix automation problems"](contributing.md/#how-to-fix-automation-problems) for instructions on how to fix problems
related to the TravisCI continuous improvement tooling that runs with
each pull request. 

The most common issue here is just that some link that used to work 
either 404s or redirects now. To fix these issues, use a search engine
to find the new link address. 
If that resource being linked to has disappeared, it may mean its time to 
delete a previous contribution. It is often easiest to do this using the 
"edit this file" button as described in the contributing.md file.

### Handling new feature requests and vision clarification

Rarely, the maintainers also discuss new feature requests. 
This has included new sections, like datasets, as well as a request 
for a DOI for the awesome list repository. 

These conversations mostly take place in issues. For longer conversations 
or for expanding the scope of who is included, it can also be useful
to post a question on the "Open Geoscience" channel in the Software Underground mattermost channel. 

## How response do maintainers need to be?

Faster is always better as it makes people feel more included, 
but traditionally this repository has been
managed in a very asynchronous manner with pull requests often getting 
responses in 1-2 weeks and sometimes unfortunately longer.
We should probably try to reduce this time to first response.


## Who, How, and Why be a maintainer of this repository?


### Who can be a maintainer?

Anyone how has a record of participation in the Software Underground 
Slack/Mattermost discussions or has made contributions to this repository
can become a maintainer if they want.

### How to become a maintainer?

Anyone added to the 
[awesome GitHub team](https://github.com/orgs/softwareunderground/teams/awesome) 
has maintainer permissions that let them approve pull requests. 

To become a maintainer, add an issue to this repository. 
Select the issue template called "maintainer_application"
and ping all the members of the 
[awesome GitHub team](https://github.com/orgs/softwareunderground/teams/awesome)
like ` @justinGOSSES , @leouieda, etc.` after you submit the issue.

#### Keeping track of new issues and pull requests
To be a maintainer, you just need to make a good faith effort to 
respond to new issues and pull requests on this repository.
Once you are a maintainer, it is recommended, you click the 
watch button right next to the fork button the main page of the 
[repository](https://github.com/softwareunderground/awesome-open-geoscience)

You'll also likely want to make use of the GitHub notification page if you 
don't already. A direct link to new issues and pull requests limited to 
this repositories is [https://github.com/notifications?query=repo%3Asoftwareunderground%2Fawesome-open-geoscience](https://github.com/notifications?query=repo%3Asoftwareunderground%2Fawesome-open-geoscience)

### Why be a maintainer?

Historically, most of the maintainers who approve issues on this repository
where involved in setting up the repository. 
We would like to broaden the participation. 

#### Gain maintainership skills
Being a mainter on a repository like this is a great opportunity to 
learn maintainer skills and to do so in a low risk situation. 
Solving merge conflicts, managing community members, and lowering friction 
for developers are all important skills for working on open source 
code repositories. This repository is merely a list, so the stakes 
are low. There is no production service to break or be "down".

#### Put it on your resume

This repository is one of the most starred repositories on GitHub 
under the 'geoscience' topic, Being a maintainer on this resume 
is something that one can list on 
their resume as evidence of contributing to the open source geoscience 
community and evidence of their experience solving merge conflicts, 
working with external contributors, etc. 