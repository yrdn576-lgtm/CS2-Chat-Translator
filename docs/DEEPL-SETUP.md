# Setting up the DeepL API

CS2 Chat Translator uses DeepL to translate supported CS2 chat messages. **Each user must supply their own DeepL API credentials.** A standard DeepL translation subscription is not necessarily the same as a DeepL API subscription.

## Step by step

1. Visit [DeepL API](https://www.deepl.com/pro-api) and review the currently available API plans and terms for your region.
2. Sign up for a DeepL API plan or sign in to an existing account that has API access.
3. Open your [DeepL account](https://www.deepl.com/account) and locate the **API Keys & Limits** section. The wording and navigation may change.
4. Create or copy an API authentication key associated with your API plan.
5. Open CS2 Chat Translator, enter the key in its first-run setup, and select the language into which chat should be translated.
6. Complete the application's connection check, if presented, and test with a CS2 chat message.

## Key safety

- Treat your API key like a password.
- Never post it in GitHub issues, Discord, screenshots, or logs.
- Do not use another person's key.
- If a key is exposed, revoke or rotate it in your DeepL account.
- API usage may incur charges or count against a quota. Review your plan, usage, and limits in your DeepL account.

## Common issues

**Invalid key or authentication failure:** Verify that you copied the entire key from an account with DeepL API access. Check whether it was revoked.

**Quota or billing error:** Review your plan's remaining quota, limits, and billing status.

**Connection failure:** Confirm internet connectivity and retry. Network filters or a DeepL service issue can also affect requests.

**No translation in CS2:** First confirm that the application receives chat log messages; see [Troubleshooting](TROUBLESHOOTING.md).

## Official resources

- [DeepL API information](https://www.deepl.com/pro-api)
- [DeepL API documentation](https://developers.deepl.com/)
- [DeepL account](https://www.deepl.com/account)

This project is not affiliated with DeepL.
