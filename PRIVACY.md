# Racquet — Privacy Policy

Effective date: October 1, 2026

This policy describes the Racquet Chrome extension maintained by [kostakarathana](https://github.com/kostakarathana).

## The game stays on your device

Racquet runs locally after installation. It does not send gameplay data or personal information to its developer or to third-party services. It has no analytics, advertising, accounts, purchases, tracking cookies or remotely loaded code. Its models, textures and other game assets are included in the extension.

The extension does not read your browsing history or the contents of other websites. It does not request access to your camera, microphone, contacts or location. Game audio is generated locally; it does not record sound.

## Information processed locally

Racquet uses pointer, touch, keyboard or gamepad input to control the game. It uses window and screen dimensions to size the display, and the browser's reduced-motion preference to adjust visual effects. These inputs and settings are processed on your device and are not transmitted by the game.

Racquet uses the browser's local storage for two purposes:

- **Best score:** the number of successful returns in your best rally is kept under `racquet-best` until the extension's local storage is cleared.
- **Moving a rally between windows:** when you expand the toolbar popup, a temporary record contains the score, ball and racquet positions, rally timing and other game state, together with a random transfer identifier. The destination window reads and removes it. Records older than 30 seconds are not restored. An abandoned record is removed when the extension next initializes; it is not necessarily deleted exactly 30 seconds after creation.

This local information is used only to provide gameplay and continue the current rally between windows. Racquet does not sell it, share it, use it for advertising, or sync it to a developer server. You can erase it by clearing Racquet's extension storage in Chrome. The developer cannot access or recover your locally stored score.

## The store, these pages and support

Installing or updating through the Chrome Web Store involves Google's services and [Google's Privacy Policy](https://policies.google.com/privacy). Reading these pages or using GitHub issues involves GitHub's services and [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). These services operate separately from the offline game.

If you choose to open a [support issue](https://github.com/kostakarathana/racquet-info/issues), your GitHub username and anything you post are visible to the maintainer and the public. The maintainer uses that information to respond and investigate the issue. Public issue content may remain available until edited or removed, subject to GitHub's controls and retention practices. Please do not post personal information, passwords or sensitive details.

## Changes and questions

This page will be updated if Racquet's privacy practices change, with a new effective date. For privacy questions, use the [repository's issues page](https://github.com/kostakarathana/racquet-info/issues) without including personal or sensitive information.
