# Getting started

## Before you begin

You need Windows x64, Counter-Strike 2, an internet connection, and a DeepL API key. Read [DeepL setup](DEEPL-SETUP.md) first.

## Installation

1. Open the [GitHub Releases page](https://github.com/yrdn576-lgtm/CS2-Chat-Translator/releases).
2. Choose a release that explicitly includes the Windows x64 application ZIP. GitHub's “Source code” ZIP is **not** the application.
3. Download the application archive and verify its SHA-256 against the checksum published for that exact asset.
4. Right-click the ZIP and choose **Extract All**. Keep all extracted files together.
5. Open the extracted folder and launch `CS2ChatTranslator.exe`.
6. Complete the first-run configuration, entering your own DeepL API key and selecting the target language.
7. Start Counter-Strike 2 and use the application's overlay while playing.

The application uses CS2 chat log output; if messages do not appear, review [Troubleshooting](TROUBLESHOOTING.md). Do not assume that the overlay can capture every game or chat source.

## Everyday use

- Start the application before or while running CS2.
- Make sure the required CS2 chat log output is available to the application.
- Check the overlay for detected and translated messages.
- Adjust supported overlay settings in the application.
- Close and reopen the app to confirm settings are retained.

## Updating manually

1. Check [Releases](https://github.com/yrdn576-lgtm/CS2-Chat-Translator/releases).
2. Download and verify the newer application ZIP.
3. Close the old application.
4. Extract the new ZIP into a **new folder** rather than overwriting files in a running installation.
5. Start the new executable and verify your settings and translation behavior.
6. Retain the previous folder temporarily if you need to roll back.

The unsigned tester build does not provide an in-app automatic installation button. A notification about a newer release is not proof that an automatic update is available.

## Security

Do not send your API key to other people. Avoid sharing screenshots that show credentials. If Windows blocks an unknown download, verify its origin and checksum; do not disable Windows security protections.
