# Grok Imagine 2.0 Ext — リバース route (日本語)

> **1K $0.015** · model ID `grok-imagine-2.0-ext` · **リバース/逆解析** route.

**[料金を見る](https://go.apimart.ai/k-b5f7df)** · **[APIキーを取得](https://go.apimart.ai/k-2e8900)**

grok-imagine-2.0-ext-reverse-api-ja は **リバース** の Grok Imagine 2.0 Ext ルートです。呼び出し ID は `grok-imagine-2.0-ext`、公式ルート（`grok-imagine-image-2.0`）と並行提供で単価が低くなります。

## Pricing (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.015 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"grok-imagine-2.0-ext","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **リバース** | `grok-imagine-2.0-ext` | 1K $0.015 |
| 公式転送 | `grok-imagine-image-2.0` | official list price, billed at ×0.8 group ratio |


## Keywords

`grok-imagine-2.0-ext` · `リバース` · `逆解析` · `AI API ゲートウェイ` · `API 中継` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

