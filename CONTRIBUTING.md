# Contributing to waydlp

Thank you for helping make waydlp better! This guide applies to every repository in the organisation. Each repository's own `CONTRIBUTING.md` explains how to build, test and lint it.

## Ways to contribute

* **Report a bug.** Use the issue templates. Include your platform, the waydlp and yt-dlp versions, the steps to reproduce, and the *Technical details* from the error view (secrets are redacted automatically, but please check).
* **Suggest a feature.** Describe the problem you want solved, who it helps and how it fits waydlp's principles.
* **Improve documentation.** User docs live in [waywhy-website/content/docs](https://github.com/waywhywhy/waywhy-website/tree/main/content/docs).
* **Test packages.** Try the Linux packages on your distribution, the Windows installers, or the APK on your phone, and report what works.
* **Write code.** Pick an issue labelled `good first issue` or `help wanted`, or discuss your idea in an issue first.

## Principles every change must respect

1. **No fake functionality.** Controls must work. Progress and metadata must come from yt-dlp/FFmpeg.
2. **Privacy:** no telemetry, ads, trackers or required accounts, and no network requests the user didn't ask for.
3. **Security:** never run user input through a shell, validate everything user-controlled, verify downloaded binaries, and never log secrets.
4. **Honesty:** document limitations, and don't claim something is tested or published unless it is.
5. **Consistency:** keep the AMOLED-black and purple design and the shared terminology across apps and website.
6. **Respect package managers:** never modify files owned by apt, dnf, pacman, Flatpak and so on.
7. **No DRM circumvention,** ever.

## Workflow

1. Fork the repository and create a branch (`fix/…`, `feat/…`, `docs/…`).
2. Make focused commits with clear messages (imperative mood: "Add playlist numbering option").
3. Run the repository's formatter, linter and tests.
4. Open a pull request using the template. Describe what changed, how you tested it and any screenshots for UI changes.
5. A maintainer reviews it. CI must pass before merging.

Add a line to the repository's `CHANGELOG.md` under *Unreleased* for user-visible changes.

## Licensing of contributions

By contributing, you agree that your contribution is licensed under the license of the repository you contribute to (GPL-3.0-or-later for the apps, MIT for the website and this repository).

## Conduct

Everyone participating is expected to follow the [code of conduct](CODE_OF_CONDUCT.md).
