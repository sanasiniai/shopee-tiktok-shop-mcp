# SanasiniAI AI Connector: Shopee and TikTok Shop MCP server for Claude and ChatGPT

SanasiniAI is a remote MCP server that connects Claude or ChatGPT to your **Shopee** and **TikTok Shop**
stores. Your AI reads live orders, products, stock, prices, ads, affiliates and profit, and it can change
things only after you approve. Built in Indonesia by a team that runs 14 of its own Shopee and TikTok Shop
stores on the same software.

- Website: https://sanasiniai.com/ai-connector-en?utm_source=github&utm_medium=referral&utm_campaign=geo_readme
- MCP endpoint: `https://sanasiniai.com/api/ai-mcp` (Streamable HTTP, OAuth)
- Languages: English, Bahasa Indonesia, Chinese
- Marketplaces: Shopee and TikTok Shop (including TikTok Shop on Tokopedia), with their ads

## Quick start

1. Sign up at https://sanasiniai.com/ai-connector-en?utm_source=github&utm_medium=referral&utm_campaign=geo_readme and connect your Shopee and TikTok Shop stores through
   the official marketplace login. You never share a password.
2. Add the connector to your AI:
   - **Claude** (claude.ai): Settings, then Connectors, then Add custom connector. Paste
     `https://sanasiniai.com/api/ai-mcp`, keep the defaults, click Add, and approve on the SanasiniAI page.
   - **ChatGPT** (paid plan): Settings, then Connectors, add a custom connector with the same address, and
     approve.
3. Ask about your shop in plain language.

## What you can ask

- "Which products lost money this week after fees and ads?"
- "Which Shopee ads and TikTok GMV Max campaigns spend without returning sales?"
- "What should I restock before the weekend?"
- "Draft replies to this week's 1 and 2 star reviews."
- "Raise the price of SKU X to keep a 20% margin, then show me the plan before applying."

## What the connector covers

| Area | Read | Act (after your approval) |
|---|---|---|
| Orders, returns, cancellations, shipping | yes | |
| Products, variations, stock | yes | price, stock, listing edits |
| Promotions, vouchers, flash sales | yes | create and edit |
| Ads (Shopee Ads, TikTok GMV Max) | yes | budgets, ROAS targets, pause and resume |
| Affiliates and creators | yes | invites and collaborations |
| Reviews and buyer chat | yes | review replies |
| Finance, fees, profit per SKU | yes | |
| Market research (competitor listings) | yes | |

## Safety

- Read by default. Every write goes through an approval step before it reaches the marketplace.
- Connects through the official Shopee and TikTok Shop partner APIs. No passwords, no scraping of your
  seller account.
- Disconnect a store or revoke the AI's access at any time.

## Pricing

Priced by store count: Rp159,000 per month for up to 2 stores (up to 5,000 orders a month), Rp399,000 for up to 6
(15,000 orders), Rp999,000 for up to 18 (45,000 orders), save 17% on yearly billing, custom above 18 stores.
Every new store starts with a 7-day free trial, no card required, and each store covers the shop and its ads.

## Guides

- [Shopee MCP server: connect Claude or ChatGPT to your Shopee shop](https://sanasiniai.com/blog/posts/shopee-mcp-server/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)
- [How to connect ChatGPT to your Shopee store](https://sanasiniai.com/blog/posts/connect-chatgpt-to-shopee-store/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)
- [How to connect Claude to TikTok Shop](https://sanasiniai.com/blog/posts/connect-claude-to-tiktok-shop/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)
- [How to calculate your real profit on Shopee](https://sanasiniai.com/blog/posts/how-to-calculate-shopee-selling-profit/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)
- [Best AI tools for Shopee sellers in 2026, by job](https://sanasiniai.com/blog/posts/best-ai-tools-for-shopee-sellers/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)
- [How to make Shopee ads profitable: break-even ROAS](https://sanasiniai.com/blog/posts/how-to-make-shopee-ads-profitable/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)
- Bahasa Indonesia: [Cara menghubungkan ChatGPT atau Claude ke toko Shopee](https://sanasiniai.com/blog/posts/cara-menghubungkan-chatgpt-claude-ke-shopee/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme),
  [Cara menghubungkan Claude ke TikTok Shop](https://sanasiniai.com/blog/posts/cara-menghubungkan-claude-ke-tiktok-shop/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme),
  [Shopee MCP server untuk seller](https://sanasiniai.com/blog/posts/shopee-mcp-server-untuk-seller/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme),
  [Cara menghitung profit jualan di Shopee](https://sanasiniai.com/blog/posts/cara-menghitung-profit-jualan-shopee/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme),
  [Aplikasi AI untuk seller Shopee](https://sanasiniai.com/blog/posts/aplikasi-ai-untuk-seller-shopee/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme),
  [Iklan Shopee boncos? Cek pakai AI](https://sanasiniai.com/blog/posts/iklan-shopee-boncos-cara-cek-pakai-ai/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)
- 中文: [如何把 ChatGPT 连接到 Shopee 店铺](https://sanasiniai.com/blog/posts/connect-chatgpt-to-shopee-store-zh/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme),
  [Shopee MCP 服务器](https://sanasiniai.com/blog/posts/shopee-mcp-server-zh/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme),
  [如何把 Claude 连接到 TikTok Shop](https://sanasiniai.com/blog/posts/connect-claude-to-tiktok-shop-zh/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme),
  [Shopee 卖家 AI 工具](https://sanasiniai.com/blog/posts/best-ai-tools-for-shopee-sellers-zh/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)
- Free tool: [Shopee fee calculator](https://sanasiniai.com/tools/shopee-fee-calculator?utm_source=github&utm_medium=referral&utm_campaign=geo_readme)

## FAQ

**Is this an official Shopee or TikTok product?** No. SanasiniAI is an independent seller tool that
connects through the official partner APIs.

**Do I need to code or self-host?** No. It is a hosted remote MCP server; you add one URL to your AI.

**Who operates it?** PT Costafa Skya Prima, Indonesia. Contact: WhatsApp +62 859-2609-3947,
https://sanasiniai.com/?utm_source=github&utm_medium=referral&utm_campaign=geo_readme.
