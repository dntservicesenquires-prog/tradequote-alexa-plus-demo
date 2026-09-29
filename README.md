# TradeQuote Alexa+ style demo

A mobile-first conversational quoting prototype for tradespeople. It demonstrates how a tradesperson could describe a job, review an itemised estimate, adjust trade stages, and save or print a draft quote.

This is a simulated Alexa+ style web experience. It is not connected to Alexa+, an Amazon account, a live AI model, RevenueCat, or a payment service. The request parser is deterministic JavaScript running in the browser. Saved drafts stay in browser local storage.

## Run it

Open `index.html` in a modern browser. No build step, server, account, or API key is required. For microphone input, use a browser that supports Web Speech recognition and serve the page from HTTPS or localhost; typing works without microphone support.

## Try the demo

1. Tap **Try a sample bathroom quote** to see the single-trade quote flow.
2. Review the customer, work, labour hours, hourly rate, materials, markup, VAT, deposit, and total.
3. Tap **Start a multi-trade project** to review an editable bathroom estimate split into plumbing, tiling, and decorating.
4. Change stage amounts and confirm the project total and deposit update.
5. Save a draft locally or use **Print / PDF**.

The sample amounts are illustrative. Confirm prices, scope, tax treatment, and terms before using any real quote.

## What this prototype adds

- Conversational input with local extraction of common quote details.
- A reviewable quote card with automatically calculated totals.
- A bespoke multi-trade project view with editable stages.
- Local draft saving and print-to-PDF output.

## Project status

This repository contains the web simulation source. It does not include an Alexa+ integration or live AI service. For hackathon judging, show the experience working in a short demo and describe the new conversational and multi-trade functionality clearly.

TradeQuote is an independent project and is not affiliated with or endorsed by Amazon or Alexa+.
