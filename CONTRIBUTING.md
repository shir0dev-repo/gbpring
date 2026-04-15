# Contributing to CS Webring

If you've studied any CS course at George Brown Polytechnic, you can add yourself to the webring.

## How to join

1. Fork this repository
2. Open `sites.json` and add your entry at the bottom:

```json
{ "name": "Your Name", "year": 2026, "website": "https://yoursite.com" }
```

3. Commit and submit a pull request

Once merged, your node will appear on the maple leaf and in the members list.

### Or edit directly (no git needed)

1. Go to [`sites.json`](sites.json) on GitHub
2. Click the pencil icon to edit
3. Add your entry at the bottom
4. Click "Propose changes" - GitHub handles the rest

## While you're here

Give the repo a star - it helps more GBP students find the ring.

## Rules

- **`name`** - your real name
- **`year`** - your graduation year
- **`website`** - your personal portfolio or site (must be live and accessible)
- Only add yourself, not other people
- One entry per person
- Only edit `sites.json` - do not modify any other files
- Your site must actually exist and load

## Adding the webring to your site

Once you're merged, add the GBP Huskies logo somewhere on your portfolio. It links back to gbp-ring.com so visitors can discover other members.

<img src="assets/husky.svg" alt="GBP CS Webring" width="40" height="40" />

Paste this anywhere in your HTML:

```html
<a href="https://gbp-ring.com" target="_blank">
  <img src="https://gbp-ring.com/assets/husky.svg" alt="GBP CS Webring" width="40" height="40" />
</a>
```

If your portfolio uses React/JSX:

```jsx
<a href="https://gbp-ring.com" target="_blank" rel="noopener noreferrer">
  <img src="https://gbp-ring.com/assets/husky.svg" alt="GBP CS Webring" width={40} height={40} />
</a>
```

That's it - a small husky icon that links to the ring. Footer, sidebar, wherever you want.

## Questions?

Open an issue or reach out to the dev team.
