## Instructions

This action allows you to automatically send deployment notifications to a Slack channel of your team.
It also sends additional metadata.

The only thing you need to provide is the **Slack Bot Token**, the **Slack Channel** and the **Status** (Started, Success, Failed, Canceled).

Then simply place the actions you need. For example at the beginning of your pipeline with the status **Started**,
at the end of your pipeline with the status **Success** or in the On-Failure or On-Cancel section with the status **Failed** or **Canceled**.

If you use the action multiple times, it's a good idea to use a **workspace variable** for the Slack Bot Token.
Then you only have it once in your system.

### Getting Slack Bot Token

It's a bit tricky at first to get the Bot token in Slack.

Start by creating a new Slack app in your workspace: https://api.slack.com/apps

You might need the manifest from Buddy, but I don't know exactly.

But just in case, use it from here: https://buddy.works/docs/on-premises/configuration/integrations/slack


Afterwards it's important to make sure you add the scope **chat:write.public** to your app in Slack.
This allows the integration to post to any channel.

Open the section **OAuth & Permissions** and add the scope.
Then reinstall your app in your Slack workspace.

That's it, you can now use the **Bot User OAuth Token** in Buddy.
You can find it in your Slack App in the section **OAuth & Permissions**.
