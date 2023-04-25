```bash
curl -L \
  -X POST \
  -H 'Accept: application/vnd.github+json' \
  -H "Authorization: Bearer <TOKEN>" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/repos/ooooorobo/dispatch-test/dispatches \
  -d '{"event_type": "test_result", "client_payload": {"message":"test"}}'
```

토큰 권한
- Metadata: Read access (default)
- Contents: Read and Write
