# SERP API: Live Google Search Results by CrakSEO

SERP API for SEO: live Google search results and keyword rankings by location and device, with SERP features, Google AI Overview sources, Google Maps and Bing.

Live SERP data built for SEO: get the Google search results for any keyword, exactly as a searcher sees them. The SERP API returns organic keyword rankings, which SERP features appear (such as People Also Ask), Google AI Overview text and AI Overview sources, and Google Maps results, by country, city and device for local search, plus Bing search results. Check where any domain ranks for a keyword, see which pages Google AI Overviews cite, and compare results across locations. Structured SEO data at scale that web search can't provide.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/serp-api` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits |
| Docs | https://docs.crakseo.com/mcp-servers/serp-api |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `check_google_rankings` | Check Google rankings for a domain | API credits |
| `get_google_serp` | Google SERP results | API credits |
| `get_bing_serp` | Bing SERP results | API credits |
| `get_ai_overview_sources` | Google AI Overview sources | API credits |
| `check_google_maps_rankings` | Google Maps rankings | API credits |
| `get_api_credit_balance` | API credit balance | Free |

## Questions it answers

- How do I check the top Google results for a keyword?
- How do I compare Google and Bing search results?
- Which websites does Google's AI Overview cite?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-serp-api": {
      "url": "https://crakseo.com/mcp/serp-api"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/serp-api

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
