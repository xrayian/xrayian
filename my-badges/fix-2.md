<img src="https://my-badges.github.io/my-badges/fix-2.png" alt="I did 2 sequential fixes." title="I did 2 sequential fixes." width="128">
<strong>I did 2 sequential fixes.</strong>
<br><br>

Commits:

- <a href="https://github.com/Injabin/fintech-ai-swe-proj-next-js/commit/afb9749f53916725e533615ed0de093f0df70fa7">afb9749</a>: fix: correct Finnhub fundamentals field names, add merge-based provider fallback with Roic AI and sector ETFs

Finnhub /stock/metric field names were wrong — roeTTM, revenueGrowthTTMYoy, netProfitMarginTTM, totalDebt/totalEquityQuarterly used instead of non-existent keys. Percentage values divided by 100 for scorecard-utils.

Orchestrator fetchFundamentals now merges Roic AI data into Finnhub results (fills ROE/margin/DE gaps) and cascades on null returns.

Roic AI provider fetches profitability/credit ratios (no key required).
Sector performance replaced broken Finnhub endpoint with 11 SPDR ETF quotes.
Fallback function cascades on null (not just thrown errors).
- <a href="https://github.com/Injabin/fintech-ai-swe-proj-next-js/commit/7cb3d2d7cfe9bf5437572245f45dedada61d4515">7cb3d2d</a>: fix: correct news sentiment mapping, unicode escapes in JSX, sector empty state, and ScoreCard zeros

- Fix Finnhub news sentiment to match positive/negative/neutral labels (was bullish/bearish)
- Fix \u2014/\u00d7 unicode escapes in JSX text to render as em dash/multiply symbols
- Return proper N/A state in sector heatmap instead of stale loading
- Return null from providers when all fundamentals are zero (so fallback logic kicks in)
- Handle zero metrics gracefully in ScoreCard AI coach (shows N/A)
- Add searchable filter to copilot scorecard panel
- Replace hardcoded quick prompts with dynamic context-aware suggestions


Created by <a href="https://github.com/my-badges/my-badges">My Badges</a>