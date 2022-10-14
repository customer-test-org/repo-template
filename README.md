# Repo Template

Use this repo as a reference if you need it when setting up a new Repository.
Make sure when creating a new repo that you enable a README.md file and follow
the guidelines below to make a well documented file.

## What is a README.md file?

A README file is a document in the top level of a project repository that
introduces and explains a project. It contains information required to
understand and use the repository. Gitlab will automatically display the README
content when viewing a project in the web interface. It is typically a markdown
file.

Start a README right away. It can even be the first file you create.
Most README files should have the same key sections.
Use the template below to start a new README or adjust an existing one.

## Length

How long should a README be? That depends, but keep the README easy to
reference and don't overwhelm users or expect them to scan a huge amount of
instructions to find the piece of information that they need. Imagine
yourself as a new user of the repository code and explain where to start.

If it seems like it is getting too long, split the README into smaller
sections or consider adding to the Wiki of the Repo.

## README Template

Use this template to start or adjust any project README.

```md
# Name

Choose a clear self-explanatory name.

## Description

Briefly tell people what the project is for. Provide context and link to any
important references someone new might be unfamiliar with.

## Visuals

It is helpful to include screenshots, short GIFS and diagrams. Gitlab supports
using mermaidjs for a variety of helpful maps and flowcharts. Visual
descriptions early in the readme help new users understand the project.

## Installation

Explain the standard way to install things. Don't assume users have all
prerequisites already installed or even know how to find them. List specific
steps and requirements so that a novice user can begin using the project as
quickly as possible. If necessary add a Requirements section.

## Usage

Provide specific examples of common things or first steps that someone may
need to do in order to use the repository.

### Production Deployment

If applicable, briefly explain steps for production deployment or reference
the location of additional, more detailed, documentation.

## Support

Tell people where to go for help. It can be an issue tracker, email, Redmine
project or Teams channel as examples.

## Contributing

Explain how someone can do local development and contribute changes

### Local development setup

Explain how to use `docker-compose`, `kind` or other tools to allow easy local
testing

```

## Notification settings

Ensure that you have enabled notifications in your Repo.
Check out the follwoing references:

 1. Enable notification on the GitHub App. [doc](https://github.blog/2021-03-30-new-push-notifications-scheduling-releases-github-mobile/)
 2. Setup notifications for mentions [doc](https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/configuring-notifications)

## CODEOWNERS File

## References

* [Make a README](https://www.makeareadme.com/#suggestions-for-a-good-readme)
