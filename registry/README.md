# Is this really from Mishkah?

**Mishkah's signing key fingerprint: `5D3D-8774-D2E3-8E25-AAA7`**
(public key, Ed25519, base64: `6vlPP01NyLzrHwaDfmEquBfP2igX1C7TvVlWQrCOEZ8=`)

Everything Mishkah publishes or sends (posts, kit updates, lists of scholars and reciters) is signed with this key.
If someone shows you a kit, a list or a "Mishkah" post signed with a different key, it is not from Mishkah.

**Check a file** you downloaded from Mishkah's links: work out its SHA-256 (Mac: `shasum -a 256 <file>`;
Windows: `certutil -hashfile <file> SHA256`) and look for it in [`posts.json`](posts.json). The list is signed with
the key above (field `signed`). Copies saved from Instagram, TikTok or YouTube are re-encoded by those apps and will
not match: for those, check that the post is on Mishkah's own accounts.
