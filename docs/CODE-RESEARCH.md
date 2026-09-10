# Source Code & Code Research

## Current status

A complete original Methodus Toolz / Methodus 3 Visual Basic project tree has **not** yet been recovered, but the source-code evidence is now much stronger than a language guess.

## Verified original-site development evidence

The preserved Methodus2000 site provides direct evidence that Methodus development used **Visual Basic** and references **Visual Basic 6.0 Professional**.

The recovered original `vb/sources.htm` page is especially important. It lists source-code downloads and explicitly identifies several items as Methodus-related:

- **Pin The Donkey** — described by the original site as a game made from Methodus Toolz with its source code being given away.
- **Bambi Kill** — described as a game from Methodus Toolz and the first game the author made.
- **Chat Clear** — explicitly described as the source to the Chat Clearer from Methodus Toolz.
- **Key Logger** — described as an example of a key logger like the one in Methodus Toolz.
- **Room Buster** — described as source for a room buster like the one in Methodus.
- **Firewall** — described as the same concept as Hack Protector in Methodus.
- **Chat Scan** — described as source to a Chat Scan control similar to Methscan.
- **Anonymailer** — identified as the first version of the author's Anonymailer.
- **CD Writer**, **API Spy**, **FontMacro**, **PicMacro**, web-server examples and other developer resources also appear on the page and likely document technologies/components used in or adjacent to Methodus.

The preserved page is archived at:

`archive/site/vb/sources.html`

This is `ORIGINAL-SITE` evidence that Methodus-specific or Methodus-derived source code was publicly distributed by the creators/site, even though the actual referenced source ZIPs/files still need to be recovered.

## Crapster source evidence

A surviving Methodus2000 Gnutella/Crapster research page states that Crapster was created in the **Visual Basic 6 environment** and that a research/source package once included VB6-compatible Crapster source code and related network-analysis tools.

This is another high-priority recovery target.

## What to search for

Priority filename/extensions:

- `.vbp`, `.vbw`, `.frm`, `.bas`, `.cls`, `.ctl`, `.res`, `.frx`
- `.dsr`, `.dob`, `.pag`
- source ZIP/RAR/ACE archives
- `.ini`, `.cfg`, `.dat` files containing Methodus paths or component names

High-priority source-page names and likely archive leads now include:

- `pindonkey`
- `bambikill`
- `chatclear`
- `chatscansource`
- `keylogger`
- `roombuster`
- `firewall`
- `anonymail`
- `cdwritersrc`
- `api`
- `apispy`
- `fontmacro`
- `picmacro`
- `webserver`
- `advwebserver`
- `crapster`

## Useful string searches

When scanning recovered archives, search case-insensitively for:

- `Methodus Toolz`
- `Methodus 3`
- `Methodus2000`
- `ChiefDreegFleer`
- `Jump0ffABuilding`
- `Fungus Eye`
- `Crapster`
- `Methscan`
- `Hack Protector`
- `Chat Clear`
- `Pin The Donkey`
- `Bambi Kill`
- `methodus.bizland.com`
- `downloadmethodus.bizland.com`
- `methimages.hypermart.net`

## Website code preservation

Original-site HTML is valuable because it reveals:

- filename conventions
- directory structure
- screenshots and asset names
- download endpoints
- source-code filenames/pages
- third-party mirrors
- developer/tutorial pages
- legacy ActiveX/component dependencies
- product/version names that can be searched elsewhere

Preserved HTML should remain as close to the recovered original as practical in `archive/site/`; cleaned summaries belong in `docs/`.

## Binary-analysis boundaries

For recovered executables, safe archival research can include static metadata such as hashes, PE headers, imported DLLs, strings, embedded URLs, resource names, icons, and version information. Unknown binaries should not be executed on a normal host. Use an isolated offline VM/emulator for screenshots or runtime observations.

## Evidence labels

Use these labels in notes:

- `ORIGINAL-SITE` — from Methodus2000.com or an archived capture of it
- `ORIGINAL-FILE` — recovered file whose provenance is tied to the original distribution
- `MIRROR` — copy from a later archive or third-party site
- `CATALOG` — metadata-only evidence
- `RETROSPECTIVE` — later recollection/article/post
- `UNVERIFIED` — claim or file not yet corroborated
