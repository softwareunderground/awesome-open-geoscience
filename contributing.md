# Contribution Guidelines

Please note that this project is released with a
[Contributor Code of Conduct](code-of-conduct.md). By participating in this
project you agree to abide by its terms.

## Adding something to an awesome list

If you have something awesome to contribute to an awesome list, this is how you do it.

You'll need a [GitHub account](https://github.com/join)!

1. Access the awesome list's GitHub page. For example: https://github.com/sindresorhus/awesome
2. Click on the `README.md` file: ![Step 2 Click on README.md](https://cloud.githubusercontent.com/assets/170270/9402920/53a7e3ea-480c-11e5-9d81-aecf64be55eb.png)
3. Now click on the edit icon. ![Step 3 - Click on Edit](https://cloud.githubusercontent.com/assets/170270/9402927/6506af22-480c-11e5-8c18-7ea823530099.png)
4. You can start editing the text of the file in the in-browser editor. Make sure you follow guidelines above. You can use [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/). ![Step 4 - Edit the file](https://cloud.githubusercontent.com/assets/170270/9402932/7301c3a0-480c-11e5-81f5-7e343b71674f.png)
5. Say why you're proposing the changes, and then click on "Propose file change". ![Step 5 - Propose Changes](https://cloud.githubusercontent.com/assets/170270/9402937/7dd0652a-480c-11e5-9138-bd14244593d5.png)
6. Submit the [pull request](https://help.github.com/articles/using-pull-requests/)!

## Updating your PR

A lot of times, making a PR adhere to the standards above can be difficult.
If the maintainers notice anything that we'd like changed, we'll ask you to
edit your PR before we merge it. There's no need to open a new PR, just edit
the existing one. If you're not sure how to do that,
[here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md)
on the different ways you can update your PR so that we can merge it.

## How to fix automation problems

We have an automatic link checker in place to help us detect broken links.
Your pull request will be checked by our bot that is running on TravisCI.
If everything is OK (all checks at the bottom of the PR page are green), there's nothing
to worry about.
It may however fail for the following reasons:

* Duplicate entry: Your link already exists in the file. In this case, please close your
  PR or let us know if there's a mistake.
* Redirection of link: Your link redirects somewhere else. In  this case, please use the
  final link after redirection.

Clicking on the failing build (a red x) will take you to the TravisCI website. 
You probably want to right click, so it opens in a new tab otherwise it can be difficult to go backwards.
Look at the log to see what went wrong and what needs fixing. What is wrong is usually at the very bottom of the log.
If none of this makes sense to you, let us know and we'll come in and guide you along to
make the contribution a success.

##### Fixing 301 Link Redirection Error
Fixing a 301 link redirection error usually means (1) following the link to the TravisCI logs 
(2) finding which link has changed. The logs will usually have both the old link and the new link 
(3) going back to the README and selecting edit. (4) and searching for the old link 
(5) replacing the old link with new link that TravisCI suggests. 

If this is done within a pull request that exists and just ran a short time ago, 
your changes will automatically trigger a new run of TravisCI, which should now pass all the tests.
However, if it has been a while since last running TravisCI there could now be additional link changes to address.

##### Edit Someone Else's Pull Request as an Admin
It is fairly common for pull requests to get stopped due to the submitter not understanding how to deal with TravisCI issues. In this case, the easiest way to edit their pull request to make corrections is to (1) go to the pull request (2) click on the `files changed` tab on the right (3) click on the three dots in the upper right corner of a file's window (4) select edit file. After you make edits, the changes will appear as commits by you in their pull request. This will also usually trigger the TravisCI job to run again. Although you could technically clone their pull request, this method is usually easier.

##### Getting TravisCI to Run Again
If you need TravisCI to run again but can't figure out how. Go to a file that doesn't matter, add an extra line. 
Go back to that file and then edit away that line. This will trigger the pull request to run TravisCI again.

## Contributing as a maintainer

For information on contributing as a maintainer for this 
see the [maintainerRole.md](/maintainerRole.md) file for a description 
of the role. We are looking for more maintainers.