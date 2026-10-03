# x4-sec-action

**GitHub Action that runs the X4 AI agent security scanner** and uploads SARIF results.

Scans skills, hooks, MCP servers, and agent configs for common risks: over-permissive tools, missing allow-lists, secrets in prompts, and unsafe defaults.

## Usage

```yaml
- uses: dhe-cruzer69/x4-sec-action@v1
  with:
    path: '.'
    sarif: true
```

## Marketplace intent

This repo is the Action packaging layer for the scanner logic that lives in `x4-sec` / `x4-ai-security-scanner`.

## License

Apache-2.0
