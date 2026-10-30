QueueSwap Match

A prototype web app for swapping places in a service queue. It runs on a simulated queue (a passport office), so no real tickets or money are involved.

Live demo: https://queuswap.netlify.app

What it does

You tell the app your situation:

your ticket number
how many minutes until you must leave
the most you will pay, in credits
what matters most: make my deadline for the lowest cost, save the most time, or pay the least
an optional note

The app checks every open listing against fixed rules and suggests who to swap with. Only you can send a request, and the other person must confirm.

The page also shows:

Suggestions: ranked swap options with the time saved and the credits asked
What the assistant did: a plain-language explanation of the result
Audit log: a record of each request and decision
Open listings: tickets that patient users have offered, with a form to add a listing
Help guide: a built-in chat box with scripted answers about the page (it is not an AI model)
How it is built
One HTML file with CSS and JavaScript. There is no build step and nothing to install.
Ticket checks, locking and the swap itself run as fixed rules.
The assistant can suggest a swap, but it cannot request, confirm or complete one.
In this version the app runs in rule-based mode. The optional AI explanation is turned off.
Try it
Open the live demo.
Choose Try a scenario, then Find swaps.
Read the suggestion and the audit log.

You can also download index.html and open it in a browser.

Notes
This is a prototype. The queue is simulated and credits are not real money.
