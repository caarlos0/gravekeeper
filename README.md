<img align="right" width="200" height="200" src="https://avatars2.githubusercontent.com/u/31578685?v=4&s=200">

# Gravekeeper

Gravekeeper informs users that a repo is abandoned, commenting on new
PRs and Issues.

Example/test repository: https://github.com/caarlos0-graveyard/grave (check PRs and Issues).

## How it works

It is a simple endpoint running on AWS Lambda that comments on new issues and new pull requests.

It is managed with [apex/up](https://github.com/apex/up).

## Usage

To use it, add [this url](https://w9tfb4bspe.execute-api.us-east-1.amazonaws.com/production/)
to your repository (or even organization) webhooks. Set it up like this:

![Webhook config](https://user-images.githubusercontent.com/245435/29999664-1ea0e168-9028-11e7-9d4a-bbb2852df241.png)

It will leave a comment on new pull requests and new issues:

![example comment](https://user-images.githubusercontent.com/245435/29999797-c62e25dc-902b-11e7-9c79-0c5d6f957387.png)
