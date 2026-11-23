# Zoomfolio: a CV you zoom into

**[▶ Live demo](https://kheleey.github.io/zoomfolio/)** · Free to use under the [MIT License](LICENSE)

<p align="center"><img src="preview.gif" width="300" alt="Preview"></p>

### 🎬 Video tour

<a href="https://kheleey.github.io/zoomfolio/tour.mp4"><img src="screenshot-1.jpg" width="260" alt="Watch the video tour"></a>

**[▶ Watch the full video tour](https://kheleey.github.io/zoomfolio/tour.mp4)**

### Screenshots

<table><tr><td align="center"><img src="screenshot-1.jpg" width="200" alt="The whole CV"><br><sub>The whole CV</sub></td><td align="center"><img src="screenshot-2.jpg" width="200" alt="Zoomed into the profile"><br><sub>Zoomed into the profile</sub></td><td align="center"><img src="screenshot-3.jpg" width="200" alt="Collage layout"><br><sub>Collage layout</sub></td><td align="center"><img src="screenshot-4.jpg" width="200" alt="Playful layout"><br><sub>Playful layout</sub></td><td align="center"><img src="screenshot-5.jpg" width="200" alt="AI summary"><br><sub>AI summary</sub></td></tr></table>

The whole CV on one floating page. Tap any section and the view gently zooms into it, where that section has its own design:

- **Profile:** an editorial layout
- **Experience:** a timeline
- **Skills:** gauges
- **Projects:** a gallery
- **Education:** certificates
- **Contact:** a letter

Move to the next section with the dropdown, the arrows, a swipe or the arrow keys.

- **Formal layouts:** Classic, Sidebar, Editorial and Bento.
- **Creative layouts:** Collage, Poster and Playful.
- **Colour themes:** Ivory, Noir and Sage.
- **Sound:** an optional whoosh.

## ✦ AI summary

<p align="center"><img src="ai-summary.gif" width="260" alt="The AI summary writing itself"></p>

A short AI-written summary of the CV sits beside it, or behind the ✦ button on smaller screens. Out of the box it shows a sample (`aiSample`). To have an AI write it live from your CV, add a key to the `ai` settings in the `window.CV` block:

```js
// Anthropic
ai: { provider: 'anthropic', apiKey: 'sk-ant-…', model: 'claude-haiku-5-5', baseURL: '' },

// or any OpenAI-compatible service (OpenAI, DeepSeek, …)
ai: { provider: 'openai', apiKey: 'sk-…', model: 'your-model-name', baseURL: 'https://api.openai.com/v1' },
```

**Keep your key private.** A key written into this file can be seen by anyone who opens the page. Never commit a real key to a public repository. Only add one in your own local copy, or use a key with a strict spending limit.

## Make it yours

Edit the `window.CV` block near the top of `index.html`: name, role, contact, experience, projects, skills, education, awards and languages.

## Built with

A single HTML file of plain HTML, CSS and JavaScript, with fonts from Google Fonts.

## Use it for your own

1. Click **Fork** at the top of this page, or **Code → Download ZIP**.
2. Open `index.html` in any text editor and change the content block near the top.
3. Publish it with GitHub Pages (below), or open `index.html` in a browser.

Free to use, change and share, including commercially. Please keep the `LICENSE` file.

## Publish it as a website (GitHub Pages)

1. Upload this folder's files to a new **public** GitHub repository.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then click **Save**.
3. After a minute or two it's live at `https://<your-username>.github.io/<repo-name>/`.

You can also just open `index.html` in a browser.

## License

MIT. See [LICENSE](LICENSE).
