<p align="center">
   <img width="400px" src="/assets/buddy.png">
</p>
<h1 align="center">Custom Actions for Buddy CI/CD</h1>

![Build Status](https://github.com/boxblinkracer/buddy-actions/actions/workflows/ci_pipe.yml/badge.svg)

This repository contains ready to use **custom actions** for [Buddy](https://buddy.works) that will help you to automate your pipelines with custom workflows and actions.

If you want to learn more about building your custom actions, please see this page: https://buddy.works/docs/pipelines/custom-actions

# Actions

Here is the list of included actions:

* **Ask OpenAI**: Provide a prompt and use the answer in your subsequent pipeline actions
* **Create AI Image**: Create an image using OpenAI and a custom prompt, and use the generated image ULR in your pipeline
* **Slack Deployment Notification**: Easily send out deployment notifications (started, success, failure, canceled) to your Slack team

# Installation

## Add Github Integration in Buddy

Start by adding a new integration for Github in Buddy.
The easiest approach to use a **Personal Access Token**, the downside is that updates need to be manually fetched in Buddy.

For a better integration, please create a **Github App** for your Buddy installation
and configure it accordingly as described here: https://buddy.works/docs/integrations/github/github 


## Clone this repository

To install the custom actions in your Buddy workspace, add a new project in Buddy
and clone this repository using your Github integration.

# Usage

Once cloned, the custom actions will automatically appear in your **action list**.
You can use them in your pipelines just like any other action.

For more information about each action, please see the README.md in the corresponding folder.
These README files will also be visible directly inside Buddy.

## Use specific version

It's recommended to use a specific version of the custom actions within your pipelines.
By default, always the "default" branch and therefore the latest (unreleased) version of GIT is used.

You can also use a specific (tagged) version of an action.

Open the pipeline of your project and click on the custom action.
There you should see a button where you can easily decide which available branch/tag and therefore version you want to use.

<p align="center">
   <img width="400px" src="/assets/set-version.png">
</p>


# Reliability

Please note, that I usually try to create high quality products.
However, I cannot guarantee that these actions will always work as expected.

In this case you might want to create your custom actions based on these examples.

There will be no guarantee, reliability or high priority support for these actions.
