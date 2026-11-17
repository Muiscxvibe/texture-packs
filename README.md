# LCE Texture Packs

Texture packs for the LCE PS4 superplugin. The in-game **Mods** menu downloads
from this repository.

- `index.json`: catalog (id, name, version, files with URL, size, SHA-256).
- `index.json.sig`: Ed25519 signature of `index.json`. The plugin rejects the
  catalog if the signature does not verify, and rejects any file whose SHA-256
  does not match.
- Files are attached to GitHub releases (one release per item version).

Publish with `lce_content.py` from the lce-ps4-superplugin repository; do not
edit `index.json` by hand (the signature would no longer match).
