Repository: eagle-world-updates
Purpose: public, read-only release manifest for Eagle Craft.

This repo is the public release surface for updates.eagleworlds.com.
It contains NO secrets and NO staff data. It is safe to be public.

Served by GitHub Pages from the repo root:
  /CNAME                                  custom domain (updates.eagleworlds.com)
  /eagle-craft/manifest.json              public release manifest (read by the website)
  /eagle-craft/update-1-public-online/…   frozen Update 1 artifact + .sha256 sidecar

Do NOT edit files here by hand. The Command Center publishes this content with
deploy/sync-public-host.sh, which verifies the artifact SHA-256 before publishing
and writes the manifest last.
