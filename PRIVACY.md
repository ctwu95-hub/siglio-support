# Privacy Policy for Siglio

**Effective date:** June 3, 2026
**Last updated:** June 3, 2026

This Privacy Policy describes how Siglio ("we," "us," "the app") handles information when you use the Siglio iOS application. Siglio is built and operated by an independent developer ("the developer"). It is a privacy-respecting crypto news reader designed to keep your data on your device.

## Summary

- We do **not** operate any backend server for Siglio.
- We do **not** maintain user accounts.
- We do **not** collect, store, sell, or share your personal information.
- We do **not** use any analytics, telemetry, advertising, or crash-reporting SDKs.
- We do **not** track you across apps or websites.

## Information Siglio Stores On Your Device

Siglio stores the following entirely on your device, in the app's sandboxed local storage (`UserDefaults`). This information never leaves your device through Siglio:

- Third-party API keys you enter in **Settings → API Keys** (CryptoPanic, GNews, Firecrawl, NewsAPI, CoinMarketCap).
- The list of RSS feed URLs you add in **Settings → News Sources**.
- UI preferences such as your selected news-category filters.
- Articles you bookmark for later (stored via SwiftData on-device).

You can remove any of this at any time by clearing the corresponding field in Settings or by deleting the app from your device.

## Information Sent to Third Parties

When you use Siglio, your device makes direct network requests to the following third-party services. We do not see, log, or proxy these requests — they go from your device straight to the provider.

| Provider | What is sent | Why |
|---|---|---|
| **CoinGecko** (api.coingecko.com) | Standard request metadata only (IP address, User-Agent string `Siglio/1.0`) | Fetch market prices, trending coins, and category data |
| **Alternative.me** (api.alternative.me) | Standard request metadata only | Fetch the Fear & Greed Index |
| **Blockchain.info** (blockchain.info) | Standard request metadata only | Fetch on-chain Bitcoin transaction activity |
| **CoinDesk, CoinTelegraph, Decrypt, The Block, Bitcoin Magazine** | Standard request metadata only | Fetch their public RSS feeds |
| **Any RSS source you add** | Standard request metadata only | Fetch the feed you specified |
| **CryptoPanic** (only if you provide a key) | Your CryptoPanic API key, search query | Fetch crypto headlines |
| **GNews** (only if you provide a key) | Your GNews API key, search query | Fetch crypto-filtered news |
| **Firecrawl** (only if you provide a key) | Your Firecrawl API key, search query | Fetch scraped news cards |
| **NewsAPI** (only if you provide a key) | Your NewsAPI key, search query | Fetch mainstream news |
| **CoinMarketCap** (only if you provide a key) | Your CoinMarketCap API key | Fetch CMC editorial feed |

Each of those providers has its own privacy policy that governs what they do with the request. Siglio does not control or monitor that processing.

## Data We Do Not Collect

Siglio does not collect, transmit, or store on any server we control:

- Your name, email address, phone number, or any other identifier
- Your device identifiers (IDFA, IDFV, advertising identifiers)
- Your precise or approximate location
- Your contacts, photos, calendar, or other on-device content
- Your browsing or app-usage activity
- Crash reports or usage analytics

## Children's Privacy

Siglio is not directed to children under 13. Siglio does not knowingly collect any information from anyone. If you are a parent or guardian and have questions, please contact us at the email address below.

## Security

API keys and saved data are stored in the iOS app sandbox, which is protected by the operating system's standard sandboxing and (when device passcode is set) data protection. We recommend you keep your device protected by a passcode and the latest version of iOS. Future versions of Siglio may move third-party API keys to the iOS Keychain for additional protection.

## Changes to This Policy

If we make material changes to how Siglio handles data, we will update this policy and increase the "Last updated" date above. Because Siglio does not have a user account or notification system, we recommend you re-read this policy when a significant new version of the app is released.

## Contact

Questions about this policy? Email: **ctwu95@gmail.com**

---

*This policy applies only to the Siglio iOS application. It does not cover any third-party services Siglio interacts with on your behalf.*
