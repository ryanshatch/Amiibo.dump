# Amiibo.dump

A structured collection of **Amiibo `.bin` dumps** and **NTAG215/NFC215 data**, organized by game or franchise for research, preservation, testing, and compatible NFC workflows.

> **Disclaimer:** This repository is not affiliated with, endorsed by, or sponsored by Nintendo. Amiibo, Nintendo, and related names and trademarks belong to their respective owners. Use NFC data only where you have the legal right to do so, such as backups of items you own.

## Repository Structure

```text
Amiibo.dump/
├── Bin/
│   ├── Animal Crossing/
│   ├── Fire Emblem/
│   ├── Kirby/
│   ├── Mario/
│   ├── Metroid/
│   ├── Monster Hunter*/
│   ├── Splatoon/
│   └── ...
├── NFC215/
│   ├── Animal_Crossing/
│   ├── Fire_Emblem/
│   ├── Kirby/
│   ├── Legend_of_Zelda/
│   ├── Metroid/
│   ├── Super_Mario/
│   ├── Super_Smash_Bros/
│   └── ...
└── README.md
```

### `Bin/`

Contains Amiibo dump files grouped into franchise/game folders.

These files are intended to preserve the raw data associated with compatible Amiibo/NFC tags.

### `NFC215/`

Contains data organized around **NTAG215-compatible NFC** use cases, also grouped by franchise or collection.

The repository includes folders covering a wide range of Amiibo series and related NFC-enabled products.

## About Amiibo NFC

Amiibo figures and cards use NFC technology. Standard Amiibo tags are based on **NTAG215-class NFC memory**, which is why NTAG215-compatible data and tools are commonly used when working with personal backups, NFC research, or testing.

## Typical Uses

This repository can be useful for:

- Archiving and organizing personal Amiibo backups
- NFC development and testing
- Comparing Amiibo dump structures
- Researching Amiibo/NTAG215 data organization
- Restoring data from backups you are authorized to use
- Testing compatible NFC hardware and software

## File Handling

Amiibo dump files are binary data rather than normal documents. Avoid opening and re-saving them in text editors, because doing so can corrupt the file.

When working with a dump:

1. Keep an untouched backup of the original file.
2. Verify the expected file size before use.
3. Use NFC/Amiibo software that explicitly supports the format.
4. Do not overwrite your only known-good copy.

## Compatibility

Compatibility depends on the software, NFC hardware, console, and workflow being used. A file existing in this repository does not guarantee compatibility with every reader, writer, emulator, or game.

## Contributing

Contributions that improve organization, documentation, naming consistency, or metadata are welcome.

When contributing:

- Preserve existing binary data unless a correction is necessary.
- Keep folder names descriptive and consistent.
- Avoid duplicate files where possible.
- Clearly document corrections or reorganizations in the commit message.
- Do not submit private information or unrelated files.

## Clone the Repository

```bash
git clone https://github.com/ryanshatch/Amiibo.dump.git
cd Amiibo.dump
```

Because the repository contains binary files, GitHub's web interface can also be used to browse individual folders without cloning the entire project.

## Legal / Ownership Notice

Amiibo data may contain copyrighted or otherwise protected material. Responsibility for complying with applicable law, platform rules, and ownership restrictions remains with the user.

This repository is provided for archival, interoperability, development, research, and backup-related purposes.

## Maintainer

Maintained by [ryanshatch](https://github.com/ryanshatch).

---

If you find an organizational issue, mislabeled folder, or corrupted file, open an issue or submit a pull request.
