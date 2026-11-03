# Thessley Passkey

Passwordless WordPress sign-in with the Thessley Passkey app: a QR code or a one-tap link on `wp-login.php`, confirmed with the phone's own lock.

- **Three modes:** password or app, password then app, app only.
- **Per-user devices** with attestation (TEE, StrongBox, TPM, software) and instant revocation.
- **No external service:** QR codes are drawn locally; keys never leave the device.

## Install

Upload the `thessley-passkey` folder to `wp-content/plugins/`, activate it, then choose a login method under **Thessley Passkey**.

Reuses the tables and options of the old Passkey module, so enrolled devices carry over. Requires WordPress 6.0+ and PHP 8.3+.

**Deck:** [Thessley overview](https://netmate1234.github.io/thessley-presentations/thessley/) · **Project family:** [Thessley](https://github.com/netmate1234/Thessley)

## License

GPL-2.0-or-later.
