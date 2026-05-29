# App Lock Guides

Remote Markdown guides for App Lock.

The app downloads `manifest.json`, chooses a guide localization by the current app language, and falls back to `en` when a specific language is not available yet.

To add a new language:

1. Create a folder under `guides/<language-code>/`.
2. Add translated `.md` files with the same screenshot paths.
3. Add the language key to each guide in `manifest.json`.

Screenshots are stored in `assets/` and are referenced from Markdown as root-relative repository paths, for example `assets/home-groups.png`.
