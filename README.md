# OpenRouter Credits Dashboard

A self-contained, client-side dashboard that shows your OpenRouter account credit
balance. Private by design: you paste your OpenRouter API key into the page, it is
stored only in your browser's localStorage and sent only to OpenRouter — never stored
on any server.

## Use
Open the live page, paste an API key from https://openrouter.ai/settings/keys, and
hit **Load**. Shows available / purchased / used credits, % used, key tier & limit,
and auto-refreshes.

## Data source
- `GET https://openrouter.ai/api/v1/credits` — account balance
- `GET https://openrouter.ai/api/v1/auth/key` — key tier / limits
