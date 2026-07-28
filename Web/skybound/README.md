# Skybound world images

Images loaded at runtime by the Skybound world's slideshow frames (`SlideshowFrame`
/ VRCImageDownloader). One folder per source imgur album; filenames are the original
imgur image hashes.

| Folder | Source imgur album |
|---|---|
| `vertical-ads/` | [imgur.com/a/4mPKZIC](https://imgur.com/a/4mPKZIC) — "Omegascape Vertical Ads" |
| `friend-ads/` | [imgur.com/a/3WBhuUi](https://imgur.com/a/3WBhuUi) — "Omegascape Friend Ads" |
| `friend-pictures-horizontal/` | [imgur.com/a/Yh8j8oY](https://imgur.com/a/Yh8j8oY) — "Friend Pictures Horizontal" |

`RThuADc.png` in this folder was referenced by the world directly and belonged to
no album.

Pushing changes to `main` republishes the site via the "Publish Web Folder"
workflow; images are then served at
`https://omegascape-productions.github.io/image-loading/skybound/<folder>/<hash>.png`.
