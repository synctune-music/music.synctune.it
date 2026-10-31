# Content and assets

## Edit the page

The complete branch site lives in `index.html`. Edit its project entries,
descriptions, availability labels and links directly. There is no content API,
JavaScript or generator.

Keep this page focused on this branch's work. Do not name or promote sibling
branches here; `synctune.it` is the only site with the branch-family overview.
A simple link back to the company can remain.

`assets/styles.css` contains the shared layout. `assets/brand.css` contains
this branch's approved accent and visual motif. Each branch repository ships
its own files; no website depends on another website's CSS or assets.

## Project links and confidentiality

The catalog is based on the branch's public GitHub profile and Matteo's public
project directory. Public source links use verified current repositories,
including projects still under `mbianchidev`. Some organization-profile links
describe planned transfers and must not be copied without checking them.
Update the company directory on `synctune.it` when changing branch entries.

Keep private projects unlinked and label their availability. Do not invent
release dates, store listings, testimonials or product screenshots.
Keep archived work and partner projects distinct from current releases and
company-owned projects.

Customer identities, logos, private repositories and delivery details must not
be added without authorization.

Matteo's personal site is linked at `mbianchi.dev`. Open Playlist and Open
Playlist Engine belong to the Synctune Music portfolio and keep their own
websites at `open-playlist.synctune.it` and `op-engine.synctune.it`. This
repository links to those sites; it does not build or deploy them.

## Brand source and rights

Synctune family artwork and unmodified font files come from
[synctune-io/branding](https://github.com/synctune-io/branding),
approved snapshot `55764ef`. Use the branch's outlined SVGs without changing
their colors, proportions, padding or orientation.

Ink is `#111214` and paper is `#F5F2E9`. The branch accent in `brand.css` matches
its approved palette. Use accent on ink, paper on ink or ink on paper for text;
ink on an accent has the same contrast ratio as the approved reverse pair.
Do not use the bright accent as body text on paper.

The display face is Bricolage Grotesque, body text uses Work Sans, and metadata
uses DM Mono. Unmodified fonts are bundled in `assets/fonts/`; their original
SIL Open Font License notices are in `assets/fonts/licenses/`. Keep those
notices. No new license or trademark clearance is implied for brand artwork.

No scripts, CDN resources, analytics, cookies, embedded media, forms or booking
widgets load on this site. Linked services have their own policies. Update the
page's privacy note if this behavior changes.

## Studio Duo logo

The Studio Duo showcase uses `assets/projects/studio-duo.svg`, an unmodified
copy of `assets/branding/studio-duo-icon.svg` from `mbianchidev/studio-duo` at
commit `bf853019806303eaadd1c179dca4c1fa8bc49286`. Keep the editable SVG and
the supplied license in `assets/projects/licenses/studio-duo-AGPL-3.0.txt`.
The icon has no external font or script dependency. The Synctune Music symbol
still identifies the branch itself.

## Before publishing a change

Describe what the music tools and artist projects do, without explaining branch
focus or website independence. Use their verified marks, not branch-symbol or
framework-icon placeholders. `assets/projects/provenance.json` records local
artwork, original source revisions, checksums and notices. Keep asset copies
inside this repository; wide artist wordmarks need enough room to be legible.

Preview narrow and wide screens. Check local assets, anchors, outbound
destinations and keyboard focus. Open the privacy disclosure with the keyboard.
Keep `CNAME`, canonical URLs, `robots.txt` and `sitemap.xml` consistent if the
hostname changes. No install or build step is required.
