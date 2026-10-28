<div align="center">

<img src="assets/avian-network-brand.webp" alt="Avian Network" width="720">

# Avian Wallet

**A self-custody, full-node desktop wallet for Avian (AVN) on Windows, macOS and Linux.**

[![Website](https://img.shields.io/badge/Website-avianwallet.com-16a6a1?style=for-the-badge)](https://avianwallet.com) [![Guides](https://img.shields.io/badge/Guides-39%20articles-27364b?style=for-the-badge)](https://github.com/avian-network/avian-network-docs) [![License](https://img.shields.io/badge/License-MIT-2f855a?style=for-the-badge)](COPYING)

</div>

---

## Downloads

[![Download Windows](https://img.shields.io/badge/Windows-Download-16a6a1?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-win64-setup.exe) [![Download macOS](https://img.shields.io/badge/macOS-Download-16a6a1?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-apple.dmg) [![Download Linux](https://img.shields.io/badge/Linux-Download-16a6a1?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-linux.zip)

| Platform | File | Requirements |
|---|---|---|
| Windows | [avian-wallet-v5.0.4-win64-setup.exe](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-win64-setup.exe) | Windows 10 or 11, 64-bit |
| macOS | [avian-wallet-v5.0.4-apple.dmg](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-apple.dmg) | Apple silicon or Intel |
| Linux | [avian-wallet-v5.0.4-linux.zip](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-linux.zip) | 64-bit desktop distribution |

<!-- SHA256:START -->
### SHA-256 checksums

| File | SHA-256 |
|---|---|
| [avian-wallet-v5.0.4-win64-setup.exe](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-win64-setup.exe) | `d14cbb6839a1f6abeeef5564b1bdb2cae2a6a4f64d5e4a095557e12cf361c324` |
| [avian-wallet-v5.0.4-apple.dmg](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-apple.dmg) | `a3cf1ceb765cf71880ff484cd30709556a7fe1bd4be5d049270b545df1e47fa4` |
| [avian-wallet-v5.0.4-linux.zip](https://github.com/avian-network/Avian-Wallet/releases/download/v5.0.4/avian-wallet-v5.0.4-linux.zip) | `0ed72061d438371600c2fc8fd1270757d5769e562574d284fcf40b226e28da35` |

<!-- SHA256:END -->

> [!TIP]
> Compare every checksum character before opening an installer. The [Avian Wallet download page](https://avianwallet.com/download) also explains verification for each platform.

---

## Install.

| Platform | Safe start |
|---|---|
| Windows | Download the `.exe`, verify SHA-256, run the installer, then allow the initial sync to finish. |
| macOS | Download the `.dmg`, verify SHA-256, open it and move Avian Wallet to Applications. |
| Linux | Download the `.zip`, verify SHA-256, extract it to a dedicated folder and launch the included wallet program. |

Do not bypass operating-system security controls for an unverified file. See the [full installation guide](https://avianwallet.com/guides/how-to-install-avian-wallet).

---

## Features

- Self-custody: private keys remain on the user's computer.
- Full-node blockchain verification with visible peer and synchronization status.
- Guided backup and restore using wallet.dat or a recovery phrase.
- RavencoinLite wallet import with rescan progress.
- Receive-address, asset and mining-information views.
- Network-upgrade notices, readable errors and anti-scam guidance.
- Windows, macOS and Linux installers.

---

## Guides

| Task | Guide |
|---|---|
| Install safely | [Download Avian Wallet for your desktop](https://github.com/avian-network/avian-network-docs/blob/main/docs/download-avian-wallet-windows.md) |
| Fix synchronization | [Avian Wallet not syncing checklist](https://github.com/avian-network/avian-network-docs/blob/main/docs/avian-wallet-not-syncing.md) |
| Protect recovery data | [Back up Avian wallet.dat](https://github.com/avian-network/avian-network-docs/blob/main/docs/backup-avian-wallet-dat.md) |
| Move from RavencoinLite | [Import RavencoinLite into Avian Wallet](https://github.com/avian-network/avian-network-docs/blob/main/docs/import-ravencoinlite-wallet.md) |
| Browse all help | [39 Avian Wallet guides](https://github.com/avian-network/avian-network-docs) |

The website also provides the [RavencoinLite migration guide](https://avianwallet.com/migration) and [Avian Wallet troubleshooting](https://avianwallet.com/troubleshooting).

---

## Security

> [!WARNING]
> **Never share your recovery phrase, private key or wallet.dat. Avian Network support does not need them.**

Download only from the tagged Release or [avianwallet.com](https://avianwallet.com/). Verify the installer checksum and keep protected backups in more than one place.

---

## Development

Avian Wallet is C++ software built with CMake. Confirm platform prerequisites in the repository's `doc/` directory, then use the project presets and tests appropriate to your environment. Contributions should follow [CONTRIBUTING.md](CONTRIBUTING.md). Report security-sensitive issues without publishing wallet secrets or private user data.

## Support

- [Report a reproducible issue](https://github.com/avian-network/Avian-Wallet/issues) without attaching wallet secrets.
- [Read Avian Wallet FAQs](https://avianwallet.com/faq).
- [Review the tagged v5.0.4 Release](https://github.com/avian-network/Avian-Wallet/releases/tag/v5.0.4).

## License

Avian Wallet is released under the MIT License. See [COPYING](COPYING).
