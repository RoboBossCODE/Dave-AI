# Dave AI
A standalone, rule-based JavaScript chatbot for GitHub Pages. No backend or API.

## Deploy
1. Create a public GitHub repository, e.g. `dave-ai`.
2. Upload `index.html` and `script.js` to the repository root.
3. In repository **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
4. Visit `https://YOUR-USERNAME.github.io/dave-ai/` once Pages finishes publishing.

## Notes
- Dave is a custom rule-based chatbot, **not** a generative language model.
- Chat history, name, and interests are stored in the browser's localStorage on that device.
- Voice uses the browser's speech synthesis API and depends on browser support.
- To add capabilities, extend the `answer(raw)` function in `script.js`.
- Calculations use a small expression parser, not JavaScript eval.
