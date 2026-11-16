# CS2 Chat Translator

**Real-time Counter-Strike 2 chat translation for Windows.**

CS2 Chat Translator monitors supported CS2 chat log output, translates detected messages using the DeepL API, and displays translations in an on-screen overlay.

> **Release status:** v1.0.0 has been validated for limited testing. The downloadable Windows package is not yet attached to a public GitHub Release. Do not download GitHub's auto-generated “Source code” ZIP expecting the application.

## Quick links

- [Releases](https://github.com/yrdn576-lgtm/CS2-Chat-Translator/releases) — check for a Windows ZIP asset when published
- [Installation and usage](docs/GETTING-STARTED.md)
- [DeepL API setup](docs/DEEPL-SETUP.md)
- [Troubleshooting and FAQ](docs/TROUBLESHOOTING.md)
- [Privacy and security](docs/PRIVACY-SECURITY.md)
- [Report a bug](https://github.com/yrdn576-lgtm/CS2-Chat-Translator/issues/new)
- [Discord community](https://discord.gg/ExnAs6qP83)

## Requirements

- Windows x64
- Counter-Strike 2 for in-game chat translation
- Internet access for translation requests
- Your own DeepL API credentials and available API quota

The Windows package is self-contained and does not require a separate .NET SDK or Visual Studio installation.

## Features

- Reads supported CS2 chat log messages, including ALL, CT, and T channels
- Supports dead-player chat markers and Unicode messages
- Translates through DeepL
- Displays translated messages in an overlay
- Saves supported application settings between launches
- Checks for new release information; **updates are manual in the current unsigned build**

## Download and install

1. Visit [Releases](https://github.com/yrdn576-lgtm/CS2-Chat-Translator/releases).
2. Download the **Windows x64 application ZIP asset**, when one is published. Do **not** select GitHub's auto-generated source-code archives.
3. Verify the checksum published with the release.
4. Extract all files into a dedicated folder; do not run the EXE from inside the ZIP.
5. Launch `CS2ChatTranslator.exe`.
6. Configure your own DeepL API key and target language, then launch CS2 and confirm chat messages appear.

See the [full setup guide](docs/GETTING-STARTED.md).

**Important:** The initial tester build is not digitally signed. Windows may identify it as an unrecognized publisher. Do not disable security protections to run software. Only use files from a source you trust and verify the published checksum.

## Verify a release download

In PowerShell, run:

```powershell
Get-FileHash -Algorithm SHA256 -Path ".\CS2ChatTranslator-v1.0.0-tester-win-x64.zip"
```

For the previously validated v1.0.0 tester archive, the expected SHA-256 is:

```text
750DDFAF1F7706DF289A6718976E2AE39C9398426083F338349494EE69DB5050
```

Only use that checksum for the exact file with that name; later builds will have different hashes.

## Updates

This unsigned build supports **manual updates**. Check the project's Releases page for a newer compatible download. Do not assume an in-app update installer is available. Back up important settings before replacing your extracted application directory.

## Support

Open a [GitHub issue](https://github.com/yrdn576-lgtm/CS2-Chat-Translator/issues/new) or join [Discord](https://discord.gg/ExnAs6qP83). When reporting a bug, include your Windows version, app version, steps to reproduce, expected and actual behavior, and redacted screenshots or logs. **Never share DeepL API keys or personal chat logs.**

## About and distribution

CS2 Chat Translator is an independently developed Windows application for translating CS2 chat. It is not affiliated with, endorsed by, or sponsored by Valve, Counter-Strike, or DeepL.

**Closed-source distribution:** This public repository is for product documentation, release information, and support. The application's source code is not published here. No open-source license is granted for the application. Third-party runtime and dependency notices shipped with the binary remain applicable.
