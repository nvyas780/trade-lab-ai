TRADE LAB — IPHONE HOME SCREEN APP

This is a demo-only PWA. No live broker integration or AI model is included.

INSTALL ON IPHONE
1. Upload the contents of this folder to a static HTTPS host (such as GitHub Pages or Netlify).
2. Open the resulting HTTPS website in Safari on your iPhone.
3. Tap Share > Add to Home Screen > Add.
4. Launch Trade Lab from your Home Screen.

The PWA cannot be installed reliably from a ZIP or file:// URL. Hosting is required for service-worker offline support.

FEATURES
- Synthetic price replay, explicitly labeled as not real prices
- CSV import with a 'close' column for your own historical candles
- EMA9/EMA21 + RSI14 educational rule-based signal
- Virtual UP/DOWN trades, configurable stake, payout, expiry
- Local history, CSV export, reset

LIMITATIONS
- The market dropdown is a label; it does not fetch prices. Imported CSV must correspond to the selected market.
- Synthetic price series does not model a real forex or OTC market.
- All virtual balances and trades stay in this browser's local storage.
- No Pocket Option login, order execution, live OTC feed, or trained AI model.
- This prototype is not a validated backtest. Do not infer profitability from it.
