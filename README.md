# goodsplit

A tiny, no-sign-up expense splitter. Describe a shared expense in plain English and goodsplit calculates each person's equal share and who needs to pay whom.

## Use it

Open [`index.html`](./index.html) in a modern browser. No install, build step, account, or server is needed.

Try an example:

> Dinner 1200, Ravi paid, split with Anu and me

The app shows the total, each person's share, and the minimum payments needed to settle up. Use one amount, say who paid, and list the people after “split with” or “split between.” “I paid” and “me” refer to you. Amounts are interpreted as INR.

## Features

- Plain-English expense input with example shortcuts
- Equal splits with cent-accurate rounding
- Consolidated payer-to-recipient settlement suggestions
- Responsive layout for desktop and mobile
- Works locally in the browser without external services

## Limitations

Splits are equal only; custom shares and multiple expenses are not supported. The input is parsed with lightweight browser-side rules, so use the examples as a guide.
