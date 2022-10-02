---
title: "HOWTO"
date: 2021-09-15T20:14:13Z
draft: false
---



## Hacktoberfest is now opt-in and on GitHub and GitLab.  Make sure you have opted in.
PRs for Hacktoberfest count if:

- Submitted during the month of October AND
- Submitted in a public repo AND
    + The PR is on either GitHub or GitLab AND
    + The PR is labelled as `hacktoberfest-accepted` by a maintainer OR
    + Submitted in a repo with the `hacktoberfest` topic AND
      - The PR is merged OR
      - The PR has been approved

Not familiar with repository topics?  I wasn't, either.
- Go to your repo and click "About", then add any useful topics, along with `hacktoberfest` if you want contributors.
![giving your repo topics](https://user-images.githubusercontent.com/876146/96199831-04dd9c80-0f1e-11eb-9100-f111453f12c4.gif)


## Making a good Hacktoberfest issue:
The secret to getting pull requests from Hacktoberfest participants is trying to put yourself in the shoes of a first time contributor.
_A first-time contributor may have some of these characteristics:_
* This may be their first time using Github, or their first time using source control out of a work or school context.
* They have zero to many years of experience in this programming language.
* They may have previously worked on projects alone or in very small groups, always starting from the beginning of the project.
* They have limited free time, and are using Hacktoberfest as a trial run in spending free time working on open source code.
* They like free t-shirts and stickers.

Keeping aware of these characteristics, we want to have as little friction as possible between creating an issue, having a stranger read that issue, decide to work on the project, bring down your repo and get it to run, make the needed changes, and put in a pull request, have their code reviewed, and get those changes accepted.

### Introduce the part of the program that needs attention and how it works in general.
If someone has never seen your repo before, they probably don't know how your stuff works.  Help them out. Give a general overview of what is currently happening in the application.

### Use a Descriptive Title for Easy to Understand Directions
Many folks won't open the issue if they don't think they can help you with the solution.

### Define the problem or enhancement you want.
Make a permalink to the line numbers, or refer to particular parts of code that are relevant.  Here is how to create a permalink to a line or lines of code that can be used inside of an issue: https://help.github.com/en/articles/creating-a-permanent-link-to-a-code-snippet
You can do the normal user story stuff here. Example: As a _someone_, I want _a thing_ so that I can _do something_.

### When it's useful to do so, include screenshots or images.
GitHub makes it really easy to add images to your issues, and a picture can be very descriptive, so consider using a screenshot to help explain what you're looking for.

Gifs and diagrams can be very helpful, too! You can use free software like [LICEcap](https://www.cockos.com/licecap/) or [ScreenToGif](https://www.screentogif.com/) to make these relatively easily.
![example](https://user-images.githubusercontent.com/876146/88444298-20834c00-cde2-11ea-822f-960329388719.gif)


### Split work into small chunks.
One big hurdle that keeps people from putting in that first pull request is looking at the issue, not knowing where to start, then closing everything without making any contributions. Splitting up work into smaller, but still meaningful, bits. Create issues that fit between "Add your name to a text file" and "Reinvent quantum computing and create order from chaos".

### Do you know the lines of code you want changed?  Include them with a code snippet!
In 2017, GitHub added the ability to [embed code snippets into your issues](https://github.blog/2017-08-15-introducing-embedded-code-snippets/). To include your code, you're going to need to create a permanent link to a code snippet, and GitHub has put some documentation on how to do so [here](https://docs.github.com/en/github/managing-your-work-on-github/creating-a-permanent-link-to-a-code-snippet).  Generally, if you go to the code in question on the GitHub website, there's a little context menu on the left side that lets you select the code and make a permalink.  You can also create an issue directly from this menu, if you haven't already created the issue. Giving the additional code context can really help get someone more familiar with the code in your project.

### Consider making your repo "ready to code"
There are a variety of services that allow you to open your repo inside of a container with an online IDE, which greatly I've had good luck using [GitPod](https://gitpod.io/) to do so on some of my repos, but other alternatives exist, such as [Glitch](https://glitch.com/) and the upcoming [GitHub Codespaces](https://github.com/features/codespaces), so feel free to make your own decisions based on programming language or other factors.

### Give suggestions on a possible path to pursue to accomplish the task.
Consider giving some architectural advice on the sort of change you're looking to see.

### Tags, Tags, Tags!
There are websites that help people find Hacktoberfest tickets to do, and many of them allow the potential coder to filter by tags/labels.  If you want your ticket to be found, use tags in your labels section that will make your issues appear in these lists!
Here are some tags to consider using in your issue labels:
 * up-for-grabs
 * first-timers-only
 * trivial
 * beginner
 * "easy pick"
 * "good first issue"
 * "help wanted"
 * newcomers
 * jump-in
 * easy
 * documentation
 * tests
 
Aim to be truthful with your tags. Don't tag everything with trivial if you don't think it will be.

### Be communicative when people offer to help.
Folks will often reach out in the issue comments before getting into the code. Be supportive.

### Was their PR helpful?  Add the `hacktoberfest-accepted` tag!
Did you appreciate their work? Help them get credit for it by either merging the PR, adding the `hacktoberfest-accepted` tag, or both!
![hacktoberfest-accepted](https://user-images.githubusercontent.com/876146/96200885-be3d7180-0f20-11eb-930f-700d7a21f04c.png)

### Use templates and guidelines to help communicate what you expect.

#### CONTRIBUTING.md files
The standard way to provide guidelines on contributions to your repository is to create a CONTRIBUTING.md file. 
That file should contain your expectations for contributors, and any background information that those contributors should go through if they wish to participate in your repository.
What should you put in it? [Embedded Artistry has a good checklist](https://embeddedartistry.com/blog/2017/12/11/get-others-involved-in-your-project-with-a-contributing-guide/) and [Mozilla has an article about how to create one](http://mozillascience.github.io/working-open-workshop/contributing/).
Borrowing is the sincerest form of flattery, so you could always look at the [more than 7 million references to CONTRIBUTING.md on GitHub](https://github.com/search?q=contributing.md&type=Code).

#### Pull Request templates
Do you want something included in your pull requests? Create a template, and you can auto-populate your pull request with the information that you're looking for.
[Github has some good documentation about it](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/creating-a-pull-request-template-for-your-repository), but there are a few rules of thumb.
* If you want the template to be easily viewable, make it in pull_request_template.md or docs/pull_request_template.md
* If you want it to be in a hidden directory, make it in .github/pull_request_template.md
* To create multiple pull request templates, get ready to read some more documentation, as that seems to be a bit more complicated. 

# Advice for Hackertoberfest First Timers and Noobs:
## Welcome!
Thanks for choosing to work on open source code.  You may be motivated by personal development, a career in programming, or a really comfy t-shirt.  All of these are valid reasons. There are other reasons too, including "because I felt like it", and that's OK, too.

## Looking for issues:
There are a variety of places to look for new issues, but they aren't always friendly.
* [Awesome for Beginners](https://github.com/mungell/awesome-for-beginners)
* [Up For Grabs](https://up-for-grabs.net/#/)
* [Up For First Timer and Noobs](https://www.firsttimersonly.com/)
* [Good First Issues](https://goodfirstissues.com/)
* [Good First Issues](https://goodfirstissue.dev/)

### Looking for additional swag?
Some companies will post additional swag opportunities, but you may have to work a little bit extra to get those benefits.
A good place to look for places that are offering additional stuff is the [Hacktoberfest Swag List](https://hacktoberfestswaglist.com/).  Feel free to check that out if you're feeling adventurous.


It can be useful to define what level of commitment you're looking to make in picking up an issue.
Possible places you spend time working on an issue include:
* Reading the issue itself
* Understanding what the heck they want.
* Asking clarifying questions in the issue discussion
* Communicating that you intend to work on this issue to the repo owner(s)
* Figuring out which file or files need to be opened to figure out the solution.
* Trying, potentially failing, trying again, lather, rinse, repeat.
* Creating the solution.
* Testing your solution.
* Committing your changes and giving the commit a descriptive name
* Opening up a pull request
* Discussing your pull request
* Potentially make changes to your pull request.
* Doing a happy dance if your pull request is accepted.

The more you do the above actions, the more quickly you can accomplish these things. For your first issue, plan on at least a couple minutes to accomplish each task in the above list in order to keep from getting too discouraged.  If you already know the solution to the issue, make sure you still plan on spending time communicating with the repo owners about the work you plan to do.

Depending on the level of programming experience you have, it might be good to set a goal of spending approximately 1 hour per Hacktoberfest Pull Request, not including wading through all of the issues.  Hopefully, you find a cool repo with a helpful owner that makes this process smooth and empowering, not painful and toxic. If you don't find issues right away, don't fret!  You CAN make your repositories, and create your own issues.  Then, you can use the valuable experience of having looked through a bunch of GitHub issues to write clearly defined, achievable issues that you and others can work on.

## You can do this!
Remember, contributing to open source should be fun and fulfilling, so if you're discouraged, take a break.  Go and take a walk, play a game, or interact with people you care about, and come back to it when you're feeling recharged and motivated.
