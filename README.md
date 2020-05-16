# gfont-installer
Interactive script to install fonts from Google Fonts, selected through fzf.

Requires an API key, see https://developers.google.com/fonts/docs/developer_api
Requires `jq` (for json parsing) and `fzf` (for fuzzy selection)

Downloads fonts to `~/.fonts/`
