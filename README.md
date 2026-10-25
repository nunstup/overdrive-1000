# OVERDRIVE 1000

Mobile-friendly Phaser 3 cascading cluster slot **demo**. No real money, deposits, or withdrawals.

## Play
Open `index.html` through GitHub Pages. Phaser loads from jsDelivr, so internet access is required.

## Mechanics
- 6 × 5 grid, clusters of 5+ orthogonally connected matching symbols
- Cascades, increasing multipliers, Scatter-triggered free spins
- Client-side demo credits and browser cryptographic random values
- 5,000× single-spin payout cap

## Math status
**Not calibrated or certified.** RTP 96.2% is a design target, not a verified property. The engine is client-side and must not be used for real-money wagering.

To simulate, load `simulate.js` after `engine.js` and run `await OverdriveMath.simulate(100000)` in the browser console.
