SKYCLAW SD TRADER - STANDALONE MOBILE VERSION 4

PURPOSE
This version is intentionally NOT connected to XM, MT5, a broker, or a trading server. You can install and explore the dashboard now and decide later whether to connect a trading account.

WHAT WORKS NOW
- Android-friendly installable web app (PWA).
- Dashboard with standalone status.
- START and STOP toggle a local preview state only.
- Supply & Demand configuration display: H1 zones, M5 entries, XAUUSD plan.
- Risk preference controls (0.5% per trade and 2% daily loss by default), stored locally on this device.
- Activity log.
- A future XM connection information panel.

WHAT DOES NOT HAPPEN
- START does not place trades.
- STOP does not manage or close trades.
- No live prices, account balance, equity, or positions are retrieved.
- No XM login, password, investor password, API token, or MT5 connection is requested or stored.
- The displayed strategy and risk preferences are planning settings only, not an operational Expert Advisor.

INSTALL ON ANDROID
1. Extract this ZIP on your phone.
2. Host the folder on an HTTPS static website (or ask a trusted web host to publish it). A PWA generally needs HTTPS to install and use its service worker.
3. Open the HTTPS page in Chrome on Android.
4. Tap Chrome menu > Install app (or Add to Home screen).
5. Open SkyClaw from your home screen.

CONNECT XM LATER (OPTIONAL)
A later connected version will require a Windows VPS or PC running XM MT5 and a separately implemented, compiled, and tested MQL5 Expert Advisor bridge. The mobile MT5 app itself cannot run Expert Advisors. Do not share broker passwords in chat. Test on an XM demo account before any live use.

SAFETY
Trading involves risk. Low risk settings do not guarantee safety or profits. Do not use this standalone preview as evidence that a trading system is ready for live trading.
