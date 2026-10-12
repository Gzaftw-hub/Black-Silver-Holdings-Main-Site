# Black Silver Holdings Main Site

Static site for Black Silver Holdings. Deploy via Cloudflare Workers static assets (`public/`), Worker name `black-silver-holdings-demo`.

```bash
python3 -m http.server 4174 --directory public
npx wrangler deploy
```
