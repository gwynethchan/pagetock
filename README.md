# PageTock website

Static website for GitHub Pages. No installation or build step required.

## Publish

Create a public repository named `pagetock` under `gwynethchan`. Upload the contents of this folder to the repository root. In Settings → Pages choose Deploy from a branch, `main`, `/ (root)`.

After deployment verify:
- https://gwynethchan.github.io/pagetock/
- https://gwynethchan.github.io/pagetock/support/
- https://gwynethchan.github.io/pagetock/privacy/

These addresses are planned, not proof of publication. Check they load before adding them to the app.

## Content notes

Support describes the currently confirmed phone-lock behavior. The updated timer screenshot and support copy include the developer-supplied Dim screen feature. The privacy policy reflects the developer’s confirmed practices and includes the operator’s real name. Confirm all policy statements against the release build before publishing. No pricing or permanent entitlement promises are included pending final decisions.

Cormorant Garamond and Jost are hosted locally with their licenses; there are no external font requests. Assets are supplied app screenshots. All internal links work under the /pagetock/ project path.

## Preview

Run `python3 -m http.server 4173` from this folder and open http://localhost:4173.
