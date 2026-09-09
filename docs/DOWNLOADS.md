# Methodus Download & Recovery Index

This is a preservation index for historical Methodus files and mirrors. Links are recorded for provenance and recovery research. Old binaries may be unsafe; inspect only in an isolated VM/emulator and verify hashes before use.

## Confirmed catalog/mirror lead

A preserved AOL program catalog records:

- **Methodus Toolz 3.0**
- Archive filename: `methodus toolz 3.0 for aol 5.0-7.0.zip`
- Approximate catalog size: **4.7 MB**
- Catalog label: `methodus3b2`
- Mirror: https://github.com/ssstonebraker/aolunderground-proggies/blob/main/programs/AOL/proggies-sorted-deduped/proggies-by-version/unknown/methodus%20toolz%203.0%20for%20aol%205.0-7.0.zip
- Raw mirror: https://raw.githubusercontent.com/ssstonebraker/aolunderground-proggies/main/programs/AOL/proggies-sorted-deduped/proggies-by-version/unknown/methodus%20toolz%203.0%20for%20aol%205.0-7.0.zip

## Original / historical Methodus URLs

| File / label | Original URL | Archive lead |
| --- | --- | --- |
| Methodus Toolz | `http://www.methodus2000.com/methodustoolz/methodus.exe` | https://web.archive.org/web/20001109201900/http://www.methodus2000.com/methodustoolz/methodus.exe |
| Methodus mirror #1 | `http://methimages.hypermart.net/methodus.exe` | https://web.archive.org/web/20001109201900/http://methimages.hypermart.net/methodus.exe |
| Methodus mirror #2 | `http://methodus.bizland.com/methodus.exe` | https://web.archive.org/web/20001109201900/http://methodus.bizland.com/methodus.exe |
| Methodus ZIP | `http://www.oogle.net/downloads/progs/methodus.zip` | https://web.archive.org/web/20010424150235/http://www.oogle.net/downloads/progs/methodus.zip |
| Methodus ZIP | `http://www.cybernyse.com/downlowdz/methodus.zip` | https://web.archive.org/web/20010613064806/http://www.cybernyse.com/downlowdz/methodus.zip |
| Methodus ZIP | `http://lenshellarchive.com/Progs/aolprogs/methodus.zip` | https://web.archive.org/web/20110904003253/http://lenshellarchive.com/Progs/aolprogs/methodus.zip |
| Methodus 3 Build 2 | `http://lenshellarchive.com/Progs/aolprogs/methodus3b2.zip` | https://web.archive.org/web/20111002120811/http://lenshellarchive.com/Progs/aolprogs/methodus3b2.zip |

## Methodus 3 beta/build filename leads

Recovered research notes reference old `downloadmethodus.bizland.com` executable names such as:

- `methodus3b1.exe`
- `methodus3b2.exe`
- later numbered Methodus 3 beta/build executables, including a Build 8 lead

These should be treated as filename evidence until the actual archived binaries are recovered and hashed.

## Recovery status conventions

- **verified** — file recovered, hash recorded, content inspected safely
- **mirrored** — file exists in a known public archive/mirror but has not yet been independently verified here
- **archive-lead** — Wayback or historical link exists but replay may return HTML/404 rather than the original binary
- **filename-only** — filename/source mention recovered but no file yet
- **missing** — known file could not currently be recovered

## Recommended metadata for every recovered binary

Record at minimum:

- Original filename
- File size
- SHA-256
- MD5 (historical matching only)
- PE compile timestamp, if present
- Version strings / embedded URLs
- Archive/source URL
- Date recovered
- Antivirus/malware-scan notes without treating a single engine as definitive
- Screenshot of the application in an isolated environment

Do not modify original binaries. Preserve originals read-only and place analysis output separately.
