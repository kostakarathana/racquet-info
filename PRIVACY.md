# Racquet — Privacy Policy

Effective date: October 5, 2026

This policy describes the Racquet Chrome extension maintained by [kostakarathana](https://github.com/kostakarathana).

## Solo play

Solo play works offline after installation. Solo gameplay and your best score stay on your device. Racquet has no analytics, advertising, accounts, purchases or tracking cookies. Its code, models, textures and other game assets are included in the extension.

The extension does not read your browsing history or the contents of other websites. It does not request access to your camera, microphone, contacts or device location. Game audio is generated locally; it does not record sound.

## Optional multiplayer

Multiplayer works best with both players on the same Wi-Fi. An internet connection is needed to find and connect to the other player. It starts when you choose Multiplayer, enter a display name and go online. It does not use Bluetooth or require a separate account. Both players must be online, and a player must accept an invitation before a match starts.

- **Finding a player:** your display name, the name you search for, connection identifiers and connection setup messages pass through PeerServer Cloud at `0.peerjs.com`. This lets the game find and connect to the other player. The service also receives your IP address as part of the connection.
- **Making the connection:** the browser contacts Google’s STUN service (`stun.l.google.com`) to help establish a direct connection. This service receives network addresses. Connection information, including IP addresses, may also be visible to the other player. An IP address can indicate an approximate location; Racquet does not use it to locate you.
- **Playing:** the two browsers exchange display names, invitations, racquet movements, ball and match state, scores, timing and connection status. Gameplay travels directly between players over an encrypted WebRTC connection. The developer does not operate a server that stores matches or scores.

Display names are nicknames, not verified identities. Anyone who knows your exact name can try to invite you while you are online. Choose a nickname that does not contain personal information. There is no chat, voice or video feature.

Match state is kept in memory for the session. Racquet does not save a match history, and multiplayer results do not change your solo best score. Leaving multiplayer or closing the game ends the connection. Service providers handle their own operational logs; the developer does not control or promise a retention period for those logs. See [PeerServer Cloud](https://peerjs.com/server/cloud) and [Google's Privacy Policy](https://policies.google.com/privacy).

## Information processed locally

Racquet uses pointer, touch, keyboard or gamepad input to control the game. In multiplayer, resulting game movements are shared as described above. Window dimensions and the browser's reduced-motion preference are used locally for display and visual effects.

Racquet uses the browser's local storage for:

- **Best score:** the number of successful returns in your best rally is kept under `racquet-best` until the extension's local storage is cleared.
- **Display name:** `racquet-player-name` remembers the name you chose for multiplayer until you replace it or clear local storage.
- **Help screen:** `racquet-help-opened` remembers whether you have opened How to play, so it does not automatically appear again. This flag stays on your device until local storage is cleared.
- **Moving a rally between windows:** when the toolbar popup opens a game window, a temporary record contains the score, ball and racquet positions, rally timing and other game state, together with a random transfer identifier. The destination window reads and removes it. Records older than 30 seconds are not restored. An abandoned record is removed when the extension next initializes; it is not necessarily deleted exactly 30 seconds after creation.

This information is used to provide the game. Your solo best score and window transfer records are not sent to other players or services. You can erase local information by clearing Racquet's extension storage in Chrome. The developer cannot recover your locally stored score.

## How data is used

Racquet uses and shares data only as needed for the features described here. It does not sell data, use it for advertising, or use it for credit or lending decisions. Its use and transfer of information follow the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data), including the Limited Use requirements.

## The store, these pages and support

Installing or updating through the Chrome Web Store involves Google's services and [Google's Privacy Policy](https://policies.google.com/privacy). Reading these pages or using GitHub issues involves GitHub's services and [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

If you choose to open a [support issue](https://github.com/kostakarathana/racquet-info/issues), your GitHub username and anything you post are visible to the maintainer and the public. The maintainer uses that information to respond and investigate the issue. Public issue content may remain available until edited or removed, subject to GitHub's controls and retention practices. Please do not post personal information, passwords or sensitive details.

## Changes and questions

This page will be updated if Racquet's privacy practices change, with a new effective date. For privacy questions, use the [repository's issues page](https://github.com/kostakarathana/racquet-info/issues) without including personal or sensitive information.
