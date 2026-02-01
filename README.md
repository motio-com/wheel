# Standup Wheel

A "Wheel of Fortune" style spinner for selecting team members during standup meetings. Each person is removed from the wheel after being selected, ensuring everyone gets a turn.

## Usage

Open `docs/index.html` in a browser, or host it on any static file server.

### URL Parameters

Pre-populate the wheel with names using the `names` parameter:

```
https://yoursite.com/?names=Alice,Bob,Charlie,David
```

Bookmark this URL to save your team's lineup.

### Controls

- **Spin** - Click the wheel or the "Spin!" button
- **Add** - Type a name and click "Add" or press Enter
- **Remove** - Click the X next to any name

The URL updates automatically as you add or remove names.

## Hosting on GitHub Pages

1. Push this repo to GitHub
2. Go to Settings > Pages
3. Set source to "Deploy from a branch"
4. Select `main` branch and `/docs` folder
5. Save

Your wheel will be available at `https://username.github.io/repo-name/`

## License

MIT
