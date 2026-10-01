# Open Desktop Authenticator

**Open Desktop Authenticator (ODA)** is a free, open-source Steam Guard authenticator for Windows and Linux, developed, owned, and published by [MASTERPANEL LLC](https://masterspanel.com).

ODA is an independent **Steam Desktop Authenticator (SDA) alternative** for people who want to manage Steam authentication on their desktop. It is not affiliated with Valve or endorsed by the original SDA maintainers.

## Start here

ODA has three official download sources: Microsoft Store, this project's GitHub Releases, and the Softonic listing below. The official product website links to these sources and hosts no installer.

- [Official website](https://opendesktopauthenticator.com)
- [Microsoft Store for Windows](https://apps.microsoft.com/detail/9NMM2XJ6HZ1D)
- [Source code and MIT license](https://github.com/opendesktopauthenticator/open-desktop-authenticator)
- [GitHub releases for Windows and Linux](https://github.com/opendesktopauthenticator/open-desktop-authenticator/releases)
- [Softonic for Windows x64](https://open-desktop-authenticator.en.softonic.com/)
- [Verify a download](https://opendesktopauthenticator.com/verify)

Softonic displays **Official distributor** for its developer-authorized ODA listing and includes it in the **Softonic Trusted Program**. These are Softonic's distribution and scanning labels. Check a downloaded ODA installer against its MASTERPANEL LLC publisher signature and the matching GitHub release's checksums and build provenance.

## Security and accountability

An authenticator holds sensitive account information. Read our [security policy](https://github.com/opendesktopauthenticator/open-desktop-authenticator/blob/main/SECURITY.md), [threat model](https://github.com/opendesktopauthenticator/open-desktop-authenticator/blob/main/docs/THREAT_MODEL.md), and [maintenance commitments](https://github.com/opendesktopauthenticator/open-desktop-authenticator/blob/main/MAINTENANCE.md) before deciding whether ODA fits your needs.

The project currently has one maintainer, [@The1-Master](https://github.com/The1-Master), with MASTERPANEL LLC as the accountable publisher. Our public source, release checksums, signatures, and build provenance let you inspect the project and verify downloads; they are not a substitute for an independent security audit.

Starting with v1.5.1, Windows installers and the portable executable published on GitHub are Authenticode-signed by **MASTERPANEL LLC** and timestamped using **Azure Artifact Signing**. Softonic distributes the Windows x64 installer; the same publisher-signature and release-verification checks apply to that file. The existing v1.5.0 assets are unchanged and its Windows executables remain unsigned. Signing identifies the publisher and helps detect changes to signed files; SmartScreen may still warn. Linux downloads are not platform code-signed; use the signed checksum list and build provenance to verify them. The Microsoft Store package is signed through the Store and remains a separate distribution channel. See the [download verification guide](https://opendesktopauthenticator.com/verify) for the checks available for each channel.

## Contact and contribute

- **Security vulnerabilities:** use [private vulnerability reporting](https://github.com/opendesktopauthenticator/open-desktop-authenticator/security/advisories/new) or email [security@opendesktopauthenticator.com](mailto:security@opendesktopauthenticator.com). Please do not disclose vulnerabilities in public issues.
- **Bugs and feature requests:** [open an issue](https://github.com/opendesktopauthenticator/open-desktop-authenticator/issues).
- **Code and documentation:** read the [contributing guide](https://github.com/opendesktopauthenticator/open-desktop-authenticator/blob/main/CONTRIBUTING.md).

Never post Steam passwords, authentication codes, recovery codes, or authenticator secrets in an issue or pull request.
