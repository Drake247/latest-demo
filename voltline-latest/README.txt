VOLTLINE — latest build (this zip is updated with every new version)

CONTENTS
  index.html   - the entire game, currently v4.7.44 (single file)
  render.yaml  - Render Blueprint config (static site, no build step)

UPDATE YOUR LIVE SITE (Render + GitHub)
  1. Unzip this file.
  2. In your GitHub repo, open the folder that holds index.html and
     replace it with the new one (delete old, upload new, same name).
  3. Render redeploys automatically — same URL, new version.

FRESH DEPLOY
  Upload index.html + render.yaml to a GitHub repo, then in Render:
  New + -> Blueprint -> connect repo -> Apply.
  (Publish Directory = the folder that directly contains index.html.)
