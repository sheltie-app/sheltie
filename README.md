# Sheltie

Sheltie is a native macOS remote desktop connection manager powered by FreeRDP.
It keeps saved connections, display options, credential prompts and session controls together.

This public repository hosts downloads, release notes and the issue tracker.
The Sheltie launcher application's source repository is private.

## Download and install

Downloads require **Apple Silicon and macOS 26 or newer**.

1. Open [Releases](https://github.com/klinki/sheltie-app/releases) and download the DMG from a release.
2. Open the DMG and drag **Sheltie.app** into **Applications**.
3. Launch Sheltie from Applications. The enhanced FreeRDP client and its libraries are included; Homebrew is not required.

The first download will appear when a validated release is published.
Development releases are ad hoc signed and unnotarized. If macOS blocks launch, attempt
to open the app, then use **System Settings → Privacy & Security → Open Anyway**,
where available under your Mac's security policy.

## Feedback

Use [Issues](https://github.com/klinki/sheltie-app/issues) for bug reports and feature requests.
Include your Sheltie version, macOS version and steps to reproduce the problem.
Review diagnostic logs before sharing them; they can contain host and account information.

## Runtime sources and licenses

Sheltie uses the [FreeRDP project](https://www.freerdp.com/) and other open-source runtime dependencies.
Each release includes the matching runtime source archive, build metadata and SHA-256 checksums.
Dependency license texts are included inside the app at `Contents/Resources/Licenses`.
The runtime source archive includes FreeRDP and dependency sources and their runtime build recipes;
it does not contain Sheltie's Swift launcher application source.
