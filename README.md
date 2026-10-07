# Windows Chewing Custom

Personal GPL-3.0-or-later fork of [Windows Chewing TSF](https://github.com/chewing/windows-chewing-tsf), maintained by [5unny6oy](https://github.com/5unny6oy). Upstream development has moved to [Codeberg](https://codeberg.org/chewing/windows-chewing-tsf).

## Project status

The initial public fork contains upstream source and project setup. Local custom changes are being reviewed for publication. Planned features include configurable initial input mode, closing input on focus loss, restricting activation to text input, and customizable Ctrl symbol shortcuts. They are not yet included in this public branch.

PUBG compatibility is under investigation. A signed official 26.7.2.0 build composed Chinese in a controlled lobby test. An unsigned diagnostic copy was explicitly blocked by BattlEye. This does not prove that any independently signed fork will be accepted.

## Code signing policy

This fork has NOT been approved for SignPath Foundation signing and currently has no signed fork release. The upstream project's signing sponsorship and credentials do not apply to this fork. We intend to apply independently.

- Source maintenance and signing approval: [5unny6oy](https://github.com/5unny6oy).
- Changes must be reviewed before release. Signing, if granted, will use source-built GitHub CI artifacts and manual release approval.
- Both architectures of the TIP DLL inside the installer must be signed before the enclosing MSI.
- No release will claim PUBG compatibility until actual lobby composition and mode switching are tested.

## Privacy

Local user dictionaries, input history, ETW traces, personal screenshots, account credentials and signing keys must not be committed to this repository. Upstream components include update and component-download facilities. Their behavior and defaults must be reviewed before custom releases are published.

## Building

See the upstream development documentation. The first signing comparison is planned against a source-built 26.7.2.0 baseline, before reintroducing custom behavior. The signature-removal diagnostic binary is not a production release or a signing submission.

## License

GPL-3.0-or-later; see [COPYING.txt](COPYING.txt). Retain upstream copyright and license notices.
