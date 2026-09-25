# Quartermaster privacy

Updated September 25, 2026.

## Personal records

Your manually entered cash, K/D/A, session notes, loadouts, favorites, plans, progression, profile picture and appearance settings are saved on your computer. Settings provides a data-folder control and JSON backup export/restore. Exported files contain your records; share them only when you intend to.

Profile pictures are centered, resized to 96 pixels and re-encoded as JPEG before saving or sharing. The original image filename and metadata are not uploaded. Choose **Use initials** in Settings to remove the picture. A personal JSON backup includes your saved picture.

Quartermaster does not read game memory, capture your screen, monitor game traffic or collect Steam credentials. No app analytics or telemetry is included.

## Optional squad rooms

Connecting to a relay sends your display name, selected role, loadout name/cost, readiness and your chosen profile picture. Cash and K/D/A are shared only when you opt in. Room chat, briefings, tasks and explicitly published boards are shared with the room. Personal match-review notes are not automatically published.

The relay operator can read shared content and ordinary connection metadata, including IP addresses. HTTPS protects transport; room messages are not end-to-end encrypted. Internet connections require HTTPS. Local loopback testing permits HTTP.

Invite codes grant access to a room. Share them privately. Guest authentication tokens stay in application memory. Advanced relay rooms are temporary and inactive rooms expire. When a player uses **Team server**, the host retains the briefing, objectives, shared boards and last 60 chat messages on their computer, with a previous-copy backup. The server owner key is saved using Windows encryption; guests do not acquire ownership when the host disconnects. Guest presence, authentication tokens and optional cash/K/D/A profiles are not persisted in the team file. Local personal records remain on each player’s computer. Team files are separate from personal JSON backup exports.

No always-on hosted service or account system is provided with this download. The host can stop hosting or lock new joins. Removing a member disconnects their current session; it does not permanently block that person, and an unlocked invitation can be reused. If you use someone else's relay, their hosting and logging practices also apply.

## Map detail downloads

Map overviews, reference layers and road/relief overlays are bundled for offline use. With **High-detail tiles** enabled, zooming in requests original map tiles over HTTPS from wardogs.zone. That service sees your IP address and requested tile coordinates, which describe the part of the game map being viewed. These requests do not include your profile, loadouts, squad chat or plans. Downloaded tiles are cached locally with a 200 MiB target limit; cached detail remains available offline. Turn off High-detail tiles in the map Display controls to stop new detail requests. Failed requests fall back to the bundled overview.

## External services

Optional app-managed internet hosting uses Cloudflare Quick Tunnels. Cloudflare carries and terminates HTTPS traffic for the connection; its terms and privacy policy apply. Choosing Download Cloudflare helper retrieves the Windows executable and release metadata from Cloudflare’s official GitHub repository and verifies its published SHA-256 digest. The helper runs only for hosting, and closing the app stops its server and tunnel. A new tunnel receives a new address.

Reference buttons open third-party websites in your browser. Downloads, issue reports and this product page use GitHub; page badges use Shields.io. Those services have their own privacy policies. Do not post private backups, personal information or active invite codes in public issues.
