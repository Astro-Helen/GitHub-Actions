# GitHub-Actions -09/03/2023


What Is GitHub_Actions?

#Github Actions is a platform that automates the build, test, and deployment of software

The developer can automate their workflows across issues, pull requests, and more—plus native CI/CD functionality. 

The Github Actions brings automation directly into the software developer the software development lifecycle on GitHub via event-driven triggers

Explain the concepts of Events and Actions?

GitHub Event 

The github  event allowes to  triggers a workflow. it  can be configured to look for one or more triggers and qualified asbneeded by a developer. They can also be set to run on specific coding branches within a given repository on GitHub.

GitHub Actions

GitHub Actions can be automate any webhook on GitHub. This makes github  a powerful and flexible platform feature that’s able to handle complex workflows and operations 

GitHub Actions used: 

Build, test, and deploy within the GitHub flow: Continuous Integration (CI) and continuous deployment (CD) (aka CI/CD) automations are typically the easiest way for someone to understand the full functionality of GitHub Actions. From automating tests to deploying code, Actions enables you to run CI/CD workflows in containers and virtual machines directly from your repository. You can also integrate your preferred tools third-party CI/CD tools directly into your repositories with Actions.


Automate repetitive tasks: GitHub Actions can be used to automate an almost endless number of steps in the software development lifecycle. Whether it’s the creation of a pull request, a new contributor joining your repository, a pull request being merged, or a web hook from a third-party application that is integrated with a
given repository, you can introduce an automated response including sorting an issue, or assigning a reviewer to a pull request

Manage users easily at scale: Maintainers often use GitHub Actions to set organization rules including assigning developer permissions, notifying reviewers of new pull requests, and more. This makes it easier to manage a repository and all of the contributors in a given project.

Keep track of your projects: You can use GitHub Actions to monitor application builds, measure performance, track errors and more via integrations with third-party tools. GitHub Actions also produces live logs, which lets you watch your workflows run in real time. Live logs also give you the ability to copy a link from a failed tep to identify and solve potential issues (they support color and emojis, too).

Quickly review & test code on GitHub: GitHub Actions lets you integrate any number of third-party testing tools directly into yourworkflow in your repo—at any step. Moreover, GitHub Actions enables multi-container testing and “matrix builds,” which lets you run multiple tests on Linux, Windows, and macOS at the same time

How does Github actions Automation developer workflows?

workflow consists of several different core concepts.

Events: Events are defined triggers that kick off a workflow. They can be configured to look for one or more triggers and qualified as needed by a developer. They can also be set to run on specific coding branches within a given repository on GitHub.

Jobs: Jobs are a set of steps that execute on the same runner. Each runs in its own VM and parallel to other jobs, unless otherwise specified.

Steps: Steps are individual tasks that run commands in a job. These can be an action or a shell command. All steps in a job execute on the same runner.

Actions: An action is a command that’s executed on a runner—and the core element of GitHub Actions, which is named after it.

Runners: A runner is a GitHub Actions server. It listens for available jobs, runs each in parallel, and reports back progress, logs and results. Each runner can be hosted by GitHub or self-hosted on a localized server. 
