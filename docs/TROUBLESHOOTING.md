# Troubleshooting and FAQ

## The ZIP downloaded from GitHub contains no EXE

You probably downloaded GitHub's auto-generated **Source code** archive. Open [Releases](https://github.com/yrdn576-lgtm/CS2-Chat-Translator/releases) and look for a separately attached Windows x64 application ZIP. If no such asset is present, a public download has not yet been published.

## The EXE does not start

- Confirm you use Windows x64.
- Extract the entire ZIP first; do not launch from inside the archive.
- Keep the EXE, DLLs, and runtime files in the same extracted directory.
- Check the download's SHA-256 against the checksum for that release.
- Check Windows security alerts without disabling protection.

## No CS2 messages appear

- Confirm CS2 is running and producing supported chat log output.
- Confirm the application is running and its overlay is visible.
- Test with a new ALL message and then a team message.
- If the log is missing or unavailable, check your CS2 logging configuration and app-specific settings.

## Messages appear but are not translated

- Verify the DeepL API key, subscription, and available quota.
- Check internet connectivity.
- Try a message with a different source language.
- Consult [DeepL setup](DEEPL-SETUP.md).

## The overlay is hard to read

Adjust the application's supported display settings, such as opacity, then test during a match.

## Why is there no automatic update button?

The unsigned v1.0.0 tester build uses **manual updates**. A newer release notification does not guarantee an installable signed update package.

## Is the application open source?

No. The public GitHub repository hosts documentation and release information. The application source code remains private.

## Does the app require a separate .NET installation?

The Windows x64 release package is self-contained; Visual Studio and the .NET SDK are not required.

## How do I report a bug?

Use [GitHub Issues](https://github.com/yrdn576-lgtm/CS2-Chat-Translator/issues/new) or [Discord](https://discord.gg/ExnAs6qP83). Include the app version, Windows version, steps to reproduce, and expected/actual results. Redact keys, names, chat logs, and other personal information.
