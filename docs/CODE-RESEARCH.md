# Source Code & Code Research

## Current status

No verified original Methodus Toolz source-code tree has been recovered in the material reviewed so far.

The archive does contain original website HTML and references to program-development material, including a preserved `makeprogz.html` page and Methodus-related Visual Basic-era context. These are useful leads, but they are **not** proof that Methodus source code itself has been recovered.

## What to search for

Priority filename/extensions:

- `.vbp`, `.vbw`, `.frm`, `.bas`, `.cls`, `.ctl`, `.res`, `.frx`
- `.dsr`, `.dob`, `.pag`
- `.sln`, `.dsp`, `.dsw`, `.vcxproj`
- `.c`, `.cpp`, `.h`
- `.ini`, `.cfg`, `.dat` files containing Methodus paths or component names
- source ZIP/RAR/ACE archives containing `methodus`, `dreeg`, `jump0ff`, `fungus eye`, `crapster`, or distinctive tool names

## Useful string searches

When scanning recovered archives, search case-insensitively for:

- `Methodus Toolz`
- `Methodus 3`
- `Methodus2000`
- `ChiefDreegFleer`
- `Jump0ffABuilding`
- `Fungus Eye`
- `Crapster`
- `methodus.bizland.com`
- `downloadmethodus.bizland.com`
- `methimages.hypermart.net`

## Website code preservation

Original-site HTML is valuable because it can reveal:

- filename conventions
- directory structure
- screenshots and asset names
- download endpoints
- third-party mirrors
- developer/tutorial pages
- legacy ActiveX/component dependencies
- product/version names that can be searched elsewhere

Preserved HTML should remain unchanged in `archive/site/`; cleaned summaries belong in `docs/`.

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
