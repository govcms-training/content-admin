# Contributing Guide 

First of all, thank you for taking the time to provide feedback and/or contribute to the training manuals! 
We’re continually working on improving these documents with community input and we appreciate any feedback, whether it's helping to contribute to further documentation or code, grammar issues, or simply a suggestion or improvement.

If you want to read the manual you can do so with the following link: 
https://salsa-digital.gitbook.io/govcms-content-administration. 

If you want to contribute and make changes to the manuals, this page will guide you through the contribution process, outlining which tools we use and the steps you need to follow to contribute. 


## Providing Feedback

There are a few ways you can provide feedback: 

* You can email your feedback to govcms.training@salsadigital.com.au.
* You can submit an issue via the GitHub issue queue: https://github.com/govcms-training/content-admin/issues/new.


## Overview and basics

* The source code for this manual is hosted on Github and uses a service called Gitbook for publishing its documentation. 
* The manuals are written using Markdown mark up language.
* The GovCMS content administration manual is part of the [govcms-training](https://github.com/govcms-training) distribution which also includes the [GovCMS site builder manual](https://github.com/govcms-training/site-builder).
* Both these manuals share a [public Roadmap](https://github.com/orgs/govcms-training/projects/1) which lists out issues and feature requests on a kanban board. 
* [Click here](https://github.com/govcms-training/content-admin/issues) to view the current issue queue for the GovCMS content administration manual. 
* All contributions must be licensed under [CC BY-SA 3.0 AU](https://creativecommons.org/licenses/by-sa/3.0/au/). 


## Getting started and prerequisites

For contributing to the manual, the following is needed to get started:

* a [GitHub account](https://github.com/join).
* Some basic knowledge of GitHub. Please see [Beginner Github guide](https://guides.github.com/activities/hello-world/) to get started. 
* Some knowledge of Markdown, 
  * The following [Markdown Cheatsheet](https://guides.github.com/features/mastering-markdown/) may be helpful. 
  * You can also use a visual WYSIWYG editor for Markdown such as [Stack Edit](https://stackedit.io/app#).


## Gitbook & GitHub integration <a name="contributing-github" />

This repo has two branches: 


* `master`: reserved for production only. The `master` branch is synced with the [Gitbook page for this manual](https://salsa-digital.gitbook.io/govcms-content-administration/) and is only editable by maintainers of this repo. 
  * Any changes merged in to `master` will automatically be reflected on Gitbook. 
* `develop`: the default branch used for development and content changes. 


## How to contribute

Trying to edit or create a file in this repository will create your fork automatically. You can then edit pages or create new pages, and commit your changes and file a pull requests one document/issue at a time. 


For content changes or new pages, you can use the GitHub online editor:

* Open the page you want to edit on your forked version of the repo on GitHub and press the Edit icon (pen icon).
* When have finalised your changes, scroll to the bottom of the page and write a description of the changes you're proposing under the "Commit changes" ection. Then select `Create a new branch for this commit and start a pull request` and click on `Propose file change`. This will direct you to the Pull request page
* On the Pull request page, write a short comment explaining why are proposing those changes and publish your pull request clicking on Create pull request.


Any pull request should be based on the `develop` branch. We will not consider pull requests made to `master`.

For more information, please see see [Using Pull Request](https://help.github.com/articles/using-pull-requests/) and [Fork a Repo](https://help.github.com/articles/fork-a-repo/) if you're not familiar with Pull Requests.

## Code review process

Moderators will review and comment on pull requests. We may suggest changes, improvements, or alternatives, in which case the original contributor will be tagged directly so follow-up instructions are clear. There may be times where moderators will make commits to your fork directly for clarity. 


## Community 

If you have any other questions about contributing to our documentation, please reach out to govcms.training@salsadigital.com.au or join the online [GovCMS Community Discourse](https://community.govcms.gov.au/).