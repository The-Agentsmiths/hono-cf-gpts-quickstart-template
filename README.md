```
npm install
npm run dev
```

```
npm run deploy
```

## Helpful Links

### Localhost
- OpenAPI Doc: http://localhost:8787/doc?pretty
- Swagger UI: http://localhost:8787/ui

### Cloudflare
- Worker Limits: https://developers.cloudflare.com/workers/platform/limits/#worker-limits

### GPTs
- Create a new GPT: https://chat.openai.com/gpts/editor
- Plugins in Production: https://platform.openai.com/docs/plugins/production/plugins-in-production

### Hono
- Setup Bearer Auth in Hono: https://github.com/honojs/middleware/tree/main/packages/zod-openapi#how-to-setup-authorization

## Known Issues

Auth works when OpenAI GPTs calls it, but not locally in the Swagger UI. This is because the Swagger UI is not sending the Authorization header. Track the issue here: https://github.com/The-Agentsmiths/cf-gpts-quickstart-template/issues/10

Jest testing fails. Not sure why yet, but issue referenced here: https://github.com/honojs/middleware/issues/298
