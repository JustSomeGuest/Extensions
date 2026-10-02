# Extensions

Browser extensions made by me.

## Setup

First, check which manifest version the extension uses. It’s usually **Manifest V2** for Firefox and Firefox-based browsers, and **Manifest V3** for Chrome and Chromium-based browsers.

## Manifest V2

Firefox extensions use `.xpi` files.

1. Go to `about:addons`.
2. Click the **Settings** icon below the search bar.
3. Select **Install Add-on From File...**
4. Select your `.xpi` file.

Done.

## Manifest V3

Chrome extensions use `.crx` files.

1. Go to `chrome://extensions`.
2. Enable **Developer mode**.
3. Drag and drop your `.crx` file onto the page.

Done.

## Why does the extension say it can read my browsing history?

I don't know lmfao.

**The code does not read or access your browsing history.** The permission may be required by the browser or included in the extension's manifest, but the extension itself does not use it.

Your secrets are safe.
