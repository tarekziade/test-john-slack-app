Testing the slack bot
---------------------

1. Add the following secrets in GitHub repo/org secrets.

- SLACK_BOT_TOKEN
- SLACK_CHANNEL_ID (look for the channel id at the bottom of the channel details page)

2. Add a GH action in your repo, like https://github.com/tarekziade/test-john-slack-app/blob/main/.github/workflows/slack-notify.yml

3. invite @ai-platform-pr-poster to the channel

4. add a label "pr-ready" to the pull request, it will send a message



 
