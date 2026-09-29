# Chi Rho Studio DLC

Optional downloads and catalog files for Chi Rho Studio. The HTML packages are
separate from the application and can be installed from ZIP files.

The catalog admin app generates catalog JSON for supported automatic downloads.
Media packages are manual downloads and do not need catalog entries.

## Media packages

| Package | Version | Download |
| --- | --- | --- |
| Announcements en-US | 1.0.2 | [Announcements ZIP](https://github.com/OSHGP/Chi-Rho-Studio-DLC/raw/main/packages/media/announcements/Announcements-en-US-v1.zip) |
| Prayer List en-US | 1.0.1 | [Prayer List ZIP](https://github.com/OSHGP/Chi-Rho-Studio-DLC/raw/main/packages/media/prayer-list/Prayer-List-en-US-v1.zip) |
| Tithes & Offerings en-US | 1.0.1 | [Tithes & Offerings ZIP](https://github.com/OSHGP/Chi-Rho-Studio-DLC/raw/main/packages/media/tithes-offerings/Tithes-Offerings-en-US-v1.zip) |

Select a package link to download its ZIP directly. If GitHub shows the file
page instead, choose **⋯ → Download** (or use GitHub's **Ctrl+Shift+S** shortcut
while viewing that file).
In Chi Rho Studio, open **Libraries → Media** and import the ZIP as Custom HTML.
The README inside each ZIP explains its controls. Churches may also unzip a
package to study or adapt it as an authoring example.

The [SHA-256 checksums](SHA256SUMS) cover these exact ZIPs. After cloning this
repository, run `sha256sum -c SHA256SUMS` from its root to verify all three.
Checksums must be regenerated when a ZIP changes; the release downloads must
match the same bytes. These packages do not update automatically after import.
