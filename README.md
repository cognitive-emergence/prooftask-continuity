# ProofTask continuity mirror

This repository holds everything needed to verify a stored ProofTask result record without reaching prooftask.com:

- the offline verifier (`verifier/`);
- the issuer keys, the trust bundle and its full history (`keys/`, `history/`);
- `manifest.json` and `SHA256SUMS`, which list the SHA-256 of every file.

Open the guide at https://cognitive-emergence.github.io/prooftask-continuity/. It is also in `index.html`, with one page per language.

ProofTask commits to keeping these materials available, on hosting independent of ProofTask, for at least 10 years. If ProofTask stops operating, it will give at least 90 days' notice. Each release refreshes this mirror. The git history is a public, append-only record of every mirrored key and verifier.

Check the files: `shasum -a 256 -c SHA256SUMS`

Licence: the verifier files are Apache-2.0 (`LICENSE`). Keys and trust bundles are published data.
