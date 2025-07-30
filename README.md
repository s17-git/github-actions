# github-actions

## Trigger webhook

curl -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: token your_token_key" \
  https://api.github.com/repos/s17-git/github-actions/dispatches \
  -d '{"event_type": "webhook"}'