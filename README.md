# GitHub HTML Viewer — Privacy Policy

_Last updated: 16 November 2026_

GitHub HTML Viewer is a Chrome extension published by Pepr for use inside the Pepr Google Workspace. It renders `.html` files stored in GitHub repositories as live pages in the browser.

## What the extension accesses

- **GitHub pages and files you choose to render.** When you click **Render** on a github.com file page, the extension fetches that file and the files it references (stylesheets, scripts, images, data) from `github.com` and `githubusercontent.com`, using your existing GitHub sign-in in the browser. It fetches only files from the same repository and commit as the page you opened.
- **Its own settings.** The list of GitHub organizations it renders for, and whether to render automatically, are saved with Chrome's `storage.sync`. If you have Chrome sync turned on, Chrome syncs these settings across your signed-in browsers.

## What the extension does not do

- It does not send any data to Pepr or to any server other than GitHub.
- It does not collect analytics, track browsing, or read pages other than github.com file pages.
- It does not sell, share, or transfer any data to third parties.
- It does not save GitHub content itself. Rendered files are held only by the open viewer tab.

A rendered page runs its own code in an isolated sandbox, without access to the extension or your GitHub cookies. Any requests that page makes to other websites come from the page's own content, the same as opening the file locally.

## Contact

Questions about this policy: open an issue in this repository.
