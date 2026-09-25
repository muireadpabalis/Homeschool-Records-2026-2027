# Homeschool Records 2026–2027

This repository is the durable GitHub record store for the Brody and Rory homeschool portals.

The portals save each child's browser records to a separate JSON file:

- `records/brody/latest.json`
- `records/rory/latest.json`

Every successful save creates a Git commit, so earlier versions remain available in the file history. The repository is intentionally public at the parent's direction. Do not place GitHub access tokens, passwords, recovery keys, or other credentials in this repository.

The record files are created by the portals after the parent connects a fine-grained GitHub token limited to this repository with **Contents: Read and write** permission. A new or empty browser loads the existing GitHub copy before allowing any upload, and stale revisions stop with a conflict instead of silently overwriting newer work.

GitHub Pages must remain disabled for this repository; it stores records and does not host a website.
