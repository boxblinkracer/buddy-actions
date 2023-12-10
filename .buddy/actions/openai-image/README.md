## Instructions

This action allows you to ask OpenAI to generate an image for you.

It requires an OpenAI API key, which you can get from https://platform.openai.com/api-keys.

If you want to use multiple of these actions, it's recommended to use a **workspace variable** in Buddy for the OpenAI key.

The result of the action is stored in a variable **OPENAI_IMAGE_URL**, which can be used in upcoming actions inside your pipeline.
So you can either process the URL, download the image or do anything else with it.