# github-actions

## Trigger webhook

curl -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: token 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" \
  https://api.github.com/repos/s17-git/github-actions/dispatches \
  -d '{"event_type": "webhook"}'