# Methodus Source-Code Leads

This page tracks source-code evidence connected to Methodus2000, Methodus Toolz, Methodus 3, and related Fungus Eye Entertainment software.

## Confirmed development language

Original Methodus2000 site material states that Methodus Toolz was created in **Visual Basic**, and the site specifically referenced **Visual Basic 6.0 Professional** for distributable programs.

A surviving Methodus2000 Gnutella research page goes further: it states that **Crapster**, the decentralized file-sharing component included in Methodus 3, was created in the **Visual Basic 6 environment**, and that a research package included VB6-compatible source code for Crapster and related network-analysis tools.

Historical page:
- https://www.methodus2000.com/gnutella/

## Original Methodus2000 VB source index

The recovered original `vb/sources.htm` page is preserved in this repository at `archive/site/vb/sources.html`. It identifies several source releases tied directly to Methodus or its components.

### Pin The Donkey — concrete source ZIP lead

The original source index describes **Pin The Donkey** as a game made from Methodus Toolz and says the source code was being given away.

Recovered HTTrack logs expose the underlying source ZIP URL:

- `https://www.methodus2000.com/vb/pindonkey.zip`

A later mirror attempt returned HTTP 404, but an older archive log records the same URL and local intended path. This makes `pindonkey.zip` a concrete original-source recovery target rather than a reconstructed filename.

### Other Methodus-linked source targets

The original source index also identifies or describes source for:

- **Bambi Kill** — described as a game from Methodus Toolz.
- **Chat Clear** — described as the source to the Chat Clearer from Methodus Toolz.
- **Room Buster** — source for a room buster like the one in Methodus.
- **Key Logger** — example described as being like the one in Methodus Toolz.
- **Firewall** — described as the same idea as Hack Protector in Methodus.
- **Chat Scan** — source to a Chat Scan control similar to Methscan.
- **Anonymailer** — source for an early Anonymailer version.
- **CD Writer** — source demonstrating the CD Writer control.
- **API Spy / code-generator utilities**, macro tools and related Visual Basic examples.

Each linked wrapper/page and its underlying ZIP filename should be recovered from Wayback, old site mirrors, local HTTrack trees, or other AOL-program archives.

## Planet Source Code lead

A preserved Planet Source Code index contains an entry attributed to **Jump0ffabuilding** dated **January 17, 2001**:

> Make a form a cool shape with using masks and BitBlt as shown in Methodus Toolz

This is a particularly valuable lead because the title explicitly connects the submitted Visual Basic technique to Methodus Toolz.

Preserved indexes:
- https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/PAGE06.md
- https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md

### Recovery target

Search Planet Source Code mirrors and archival ZIP collections for the corresponding submission package. Likely useful contents would include `.vbp`, `.frm`, `.bas`, `.cls`, `.frx`, `.res`, screenshots, README files, API declarations, and BitBlt/mask routines.

This does **not** prove that the submission contains the full Methodus Toolz source tree. It is evidence of Methodus-related code published by a named project contributor and therefore a high-priority recovery lead.

## Crapster research-source lead

The Methodus2000 Gnutella page describes a package containing:

- Crapster source code.
- Source for an advanced search-request monitoring tool embedded in a research edition of Crapster.
- Source for a statistical research application.
- Raw monitoring logs.
- A roughly 20-page Gnutella research paper.

The page says the code was VB6 compatible. Locating a surviving copy of this package is now one of the archive's highest-priority source-code recovery targets.

## Search identifiers

Useful strings for archive, disk, ZIP, GitHub, FTP and Wayback searches:

- `ChiefDreegFleer`
- `Jump0ffabuilding`
- `Methodus Toolz`
- `Methodus 3`
- `Fungus Eye Entertainment`
- `Crapster`
- `pindonkey.zip`
- `methodus3b1.exe` through `methodus3b9.exe`
- `methodus.exe`
- `methodus.zip`
- `BitBlt`
- `CreateCompatibleDC`
- `MaskBlt`
- `VB6`
- `.vbp`
- `.frm`
- `.bas`
- `.cls`

## Evidence policy

Files are labeled **recovered source** only when actual source artifacts are obtained. Web descriptions, catalog entries and source-code references remain leads until the files themselves are preserved and reviewed.
