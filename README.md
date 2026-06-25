# nonperson.ai

Static placeholder for `nonperson.ai`, deployed with Cloudflare Pages Direct Upload.

GitHub repo: `https://github.com/deshitifai/nonperson.ai`
Pages project: `nonperson-ai`
Pages URL: `https://nonperson-ai.pages.dev/`
Custom domain: `https://nonperson.ai/`

## Deploy

```sh
set -a
source /Users/russ/projects/cats/.env
set +a
wrangler pages deploy public --project-name nonperson-ai --branch main --commit-dirty=true
```
