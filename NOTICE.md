# Tiger Browser - copyright and licence notice

Publisher and copyright holder of Tiger Browser: **Cell Play Studio** (cellplaystudio@gmail.com).

## Tiger Browser original work

Copyright (c) 2026 Cell Play Studio. All rights reserved.

This applies to everything written or designed for Tiger Browser:

* the dashboard (logo block, search bar, Quick access, free-site chips, neon search-bar light, Customize sheet, gradient editor),
* onboarding animations and copy,
* the media saver, downloads card, Wi-Fi / mobile-data fallback and site rules (`tiger_features/`),
* default search and engine-list handling (`com.tiger.search`),
* the Tiger widgets and their previews,
* Tiger's interface design, colours, typography settings and brand artwork,
* the build, rebrand and audit tooling (`tiger_tools/`) and the project documents.

Every such source file carries this header:

```
Copyright (c) 2026 Cell Play Studio. All rights reserved.
Tiger Browser original work. See NOTICE.md for the licences of the third-party software it builds on.
```

**Tiger Browser licence:** Cell Play Studio grants users a personal, non-exclusive, non-transferable licence to use Tiger Browser under its Terms of Service (`legal/TERMS_OF_SERVICE.md`). The same wording is shown in the app at `tiger://credits`, above the notices of the software below. The tools that stamp this holder are `tiger_tools/add_copyright.py` (source headers) and `tiger_tools/restore_credits.py` (credits page).

## Software Tiger Browser is built on (not Tiger's copyright)

Tiger Browser is derived from open-source software. Their notices stay exactly as their authors wrote them and are listed in
the app at `tiger://credits`:

| Software | Licence | Notes |
|---|---|---|
| Brave Browser (brave-core) | Mozilla Public License 2.0 | Files of this project that were modified from Brave's (for example the small hooks added to its code) stay under MPL 2.0; their source is available on request. |
| Chromium and its components | BSD 3-Clause and the licences on the credits page | Unchanged. |
| Inter typeface | SIL Open Font License 1.1 | `assets/tiger_font_OFL.txt`. |

**Served by Tiger's backend, not inside the app** (downloaded by the browser as signed ad-block components; each component
carries a `LICENSES.txt` with these credits, written by `tiger_backend/build_lists.py`):

| Content | Licence | Notes |
|---|---|---|
| EasyList, EasyPrivacy | GPLv3+ or CC BY-SA 3.0+ | joined into Tiger's filter list |
| uBlock filters, uBlock Origin scriptlets and stand-in resources | GPLv3 | from an official uBlock Origin release (source: github.com/gorhill/uBlock); converted unchanged by `ubo_resources.mjs` |
| Peter Lowe's ad server list | free for use with credit | |
| URLhaus malware list | CC0 1.0 and MIT | |
| adblock-resources helper scripts | MPL 2.0 | 24 site-fix scripts, unchanged |

Calling the whole application Tiger's own work would be inaccurate: Tiger's copyright covers what Tiger added.

## Trademarks

"Brave", "Chrome" and "Chromium" belong to their owners. Tiger Browser is an independent product and is not affiliated with or
endorsed by Brave Software, Inc., Google LLC or the Chromium project.
