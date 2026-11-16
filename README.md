# House Wren

The phone app for House Wren, Jeff's Philadelphia housing scout in the Amethyst Aviary.

- `index.html` is the whole app: a list of nests (listings) with New / All / Saved / Passed tabs. Save and Pass marks stay on the phone.
- `data/nests.json` is written by House Wren on the PC after each scheduled check (8 AM and 6 PM), through GitHub's API.
- It works offline with the last copy it loaded.

The listings are public Craigslist posts. Rejected and dismissed nests are never published.
