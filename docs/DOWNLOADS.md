# Methodus Download & Recovery Index

This is a preservation index for historical Methodus files and mirrors. Links are recorded for provenance and recovery research. Old binaries may be unsafe; inspect only in an isolated VM/emulator and verify hashes before use.

## Repository download policy

Primary public download links should point only to binaries physically stored and integrity-checked in `rice2k/Methodus2000`. Third-party links below are research/provenance sources used to recover the files, not the preferred final download location.

## Confirmed catalog/mirror lead

A preserved AOL program catalog records:

- **Methodus Toolz 3.0**
- Archive filename: `methodus toolz 3.0 for aol 5.0-7.0.zip`
- Approximate catalog size: **4.7 MB**
- Catalog label: `methodus3b2`
- Mirror: https://github.com/ssstonebraker/aolunderground-proggies/blob/main/programs/AOL/proggies-sorted-deduped/proggies-by-version/unknown/methodus%20toolz%203.0%20for%20aol%205.0-7.0.zip
- Git object SHA reported by the surviving mirror: `2edf3edd2f4189d12e3a05e06346ff6c6eeff78f`

The connected GitHub interface confirms the file exists at that mirror, but it does not expose its binary bytes through the text fetch operation. The archive therefore still treats local transfer as pending rather than pretending this is already stored under `downloads/`.

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

Official/recovered research material supports the Build 1–9 history. Filename leads include:

- `methodus3b1.exe`
- `methodus3b2.exe`
- `methodus3b3.exe`
- `methodus3b4.exe`
- `methodus3b5.exe`
- `methodus3b6.exe`
- `methodus3b7.exe`
- `methodus3b8.exe`
- `methodus3b9.exe`

### Build 9 sample/hash lead

A 2026 Hybrid Analysis search result contains an uploaded PE32 sample under the exact filename `methodus3b9.exe` with SHA-256:

`662bcecbe228032757fd594fa0fdf662d9d2fec1ba858a57bb1011278f1550f9`

This is valuable corroborating evidence that a file under the historical filename survives. It is **not yet labeled an authentic original distribution** because the sample still needs provenance matching against the official Methodus URL, file size/version resources, embedded strings, or another independently preserved copy. The analysis service labels the sample malicious/high risk, so it must not be executed on a normal machine.

## Source-code download lead

Recovered Methodus2000 mirror logs expose the concrete source ZIP:

- `https://www.methodus2000.com/vb/pindonkey.zip`

The original VB source index describes Pin The Donkey as a game made from Methodus Toolz and says its source was being given away. A later mirror attempt recorded a 404, so Wayback/old-archive recovery is still required.

## Recovery status conventions

- **verified** — file recovered, hash recorded, content inspected safely
- **mirrored** — file exists in a known public archive/mirror but has not yet been independently verified here
- **archive-lead** — Wayback or historical link exists but replay may return HTML/404 rather than the original binary
- **sample-hash-lead** — a matching filename/sample survives in an analysis or malware corpus, but original provenance is not yet established
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
