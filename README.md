# Test Deploy to Chrome

A fake extension to test auto deploying to Chrome Web Store with grunt via Travis CI.

# Replicating the Process in Another Project
1. Go to the [Google Developers Console](https://console.developers.google.com/) to create the CLIENT_ID and CLIENT_SECRET you'll need to deploy. Start with the "Before You Begin" section here https://developer.chrome.com/webstore/using_webstore_api and make sure you have a `CLIENT_ID`, `CLIENT_SECRET`, and `REFRESH_TOKEN` following those instructions.
2. Create a new Google Extension via the [Dashboard](https://chrome.google.com/webstore/developer/dashboard) as usual. You need to start the app this way.