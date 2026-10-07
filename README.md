# Tessera Realms

A turn-based strategy game that runs from one HTML file. Hosted on GitHub Pages, it plays inside an X post through a player card.

## Put it online (GitHub Pages)

1. Create a new public repository on GitHub called `tessera-realms`.
2. Upload `index.html`, `preview.png` and `.nojekyll` to the root of the repository.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, pick `main` and `/ (root)`, and save.
4. After a minute the game is live at `https://YOUR-USERNAME.github.io/tessera-realms/`.

## Fill in your details

Open `index.html` and replace, in the `<head>`:

- `YOUR-USERNAME` with your GitHub username (it appears in 6 tags).
- `@YOUR-X-HANDLE` with your X handle.

If you name the repository something other than `tessera-realms`, change that part of the URLs too. Commit the change.

## Share it on X

Post the bare link `https://YOUR-USERNAME.github.io/tessera-realms/`. X reads the `twitter:card="player"` tags and shows the game in an iframe inside the post. Where the inline player is not supported (some apps and clients), X shows `preview.png` with the link instead.

## Notes

- Every URL in the card tags must be an absolute `https://` link, which GitHub Pages provides.
- X caches cards. If you change the tags after posting, it can take a while before a new post picks up the update.
- Solo and hotseat modes work everywhere. Online rooms only work in the claude.ai version, so that button is hidden here.
- Saved games use the browser's local storage. Inside the X iframe the browser may block that, in which case the game still plays but won't resume later.
