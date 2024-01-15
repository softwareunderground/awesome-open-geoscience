# Maintainer Role

This document provides an overview of how to be a maintainer for this repository.

## Maintainer goals

_The goal for maintainers should be for contributors to have a good experience 
adding to the Awesome list._ 

New potential contributors should be able to look at the 
record of past experiences in closed pull requests and be encouraged by what 
they see to add their own contributions.
If a contribution is lacking in some manner that leads to it falling short 
of being "AWESOME", clear feedback should be given 
with a pleasant and positive framing. Often this can lead to improvements 
in projects, additional documentation that helps users, etc. All good things.
Rarely, a contribution will not be merged due to sustained shortcomings. 
This is okay too. Maintaining the minimum bar helps ensure the consumers of 
the list find value in it and some of them eventually add their own 
contributions.

## Who, How, and Why be a maintainer of this repository?

### Who can be a maintainer?

Anyone who has any participation in the Software Underground 
Slack/Mattermost discussions or has made contribution(s) to this repository
can become a maintainer if they want.

### How to become a maintainer?

Anyone added to the 
[awesome GitHub team](https://github.com/orgs/softwareunderground/teams/awesome) 
will have effectively have permissions that let them do maintainer tasks
like approve pull requests. 

To join that list of maintainers, add an issue to this repository. 
Select the issue template called "maintainer_application"
and ping all the members of the 
[awesome GitHub team](https://github.com/orgs/softwareunderground/teams/awesome)
like ` @justinGOSSES , @leouieda, etc.` after you submit the issue in a secondary 
comment to the issue.
One of them will reach our and/or add you to the
[awesome GitHub team](https://github.com/orgs/softwareunderground/teams/awesome).

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

While the stakes are low, the impact is high.
This repository is one of the most starred repositories on GitHub 
under the 'geoscience' topic, Being a maintainer on this resume 
is something that one can list on 
their resume as evidence of contributing to the open source geoscience 
community and evidence of their experience solving merge conflicts, 
working with external contributors, etc. 

#### Work with a net

If you have questions as a new maintainer, there are
experienced people you can reach out to for advice. 
For example, you can send a private message to JustinGOSSES
in the Software Underground [mattermost channel](https://softwareunderground.org/mattermost)
if you have a question.

## Maintainer tasks

### Approving Pull Requests

The most common maintainer tasks is evaluating and approving pull requests. 

#### When to approve an item as "Awesome" that has been submitted in a pull request

The characteristics that are required to be an "awesome" open source geoscience
resource is described in the [contributing.md](/contributing.md) 
and [awesome.md](/awesome.md) files. A checklist gets 
generated via 
the [.github/PULL_REQUEST_TEMPLATE.md](.github/PULL_REQUEST_TEMPLATE.md).

Most of the process of evaluating a 
contribution to the awesome list is just checking 
off that all these criteria are satisfied.
Many pull request approvals are straight forward and takes 5-12 minutes.

In some cases, a maintainer may want to attempt to 
run a program mentioned in a pull request themselves. This takes more time. 
A maintainer might want to do this if there are signs in the
the installation instructions or files that the application
might only run on the originators computer or operating system.
In the past, these sorts of problems have been identified 
and fixed.

#### Debugging pull request conflicts

Rarely there are multiple pull requests in the que that 
impact the same lines in some file causing a merge conflict.
For instructions on how to "fix merge conflict" on the web interface for 
GitHub see 
[GitHub's fixing merge conflict guidelines](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)

#### CI/CD Automation test failture

Please read the ["How to fix automation problems"](contributing.md/#how-to-fix-automation-problems) for instructions on how to fix 
previously seen problems related to the TravisCI continuous improvement 
tooling that runs with each pull request. 

The most common reason for a pull request to not be immediately 
mergable is a failure in the Travis CI (continuous integration) 
script related to links in the README.md.
Links that used to work can 404 or redirect from their original 
URL to a new URL. In both cases, this will cause the CI to fail.
To fix these issues, use a search engine
to look for a new link address. If a new URL exists, then edit 
the README.md file directly in the pull request with the new link address.  
If that resource being linked to has disappeared entirely, it 
may mean it is time to delete the previous contribution that includes the link. 
It is often easiest to do these types of fixes using the 
"edit this file" button as described in 
the [contributing.md](/contributing.md) file.

### Handling new feature requests and vision clarification

Rarely, the maintainers also discuss new feature requests. 
This has included new sections, like datasets, as well as a request 
for a DOI for the awesome list repository. 
These conversations mostly take place in issues. For longer conversations 
or for expanding the scope of who is included, it can also be useful
to post a question on the "Open Geoscience" channel in the 
Software Underground [mattermost channel](https://softwareunderground.org/mattermost). 

### Maintainers should respond to new issues and pull requests

Maintainers should make a good faith effort to 
respond to new issues and pull requests on this repository.
Once you are a maintainer, it is recommended that you click the 
watch button right next to the fork button the main page of the 
[repository](https://github.com/softwareunderground/awesome-open-geoscience)
This will put any new issues or pull requests you haven't already visited
in your GitHub noticiations que. 
A direct link to new issues and pull requests limited to 
this repositories is [https://github.com/notifications?query=repo%3Asoftwareunderground%2Fawesome-open-geoscience](https://github.com/notifications?query=repo%3Asoftwareunderground%2Fawesome-open-geoscience)
If you don't visit the GitHub notifications page often in the normal course
of your life, you might want
to set a reminder to double check notifications page so nothing gets missed.

#### How responsive do maintainers need to be?

Faster is better as it makes people who submit an issue or pull requests 
feel more included when they get a fast response. 
In practice, this repository has been managed in a very asynchronous manner 
with pull requests often getting responses in 1-2 week range and sometimes unfortunately significantly longer. We should probably try to reduce this time to first response.