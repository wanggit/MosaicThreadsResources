# MosaicThreadsResources

Public web resources for **Mosaic Threads** (`com.wanggang.mosaicthreads`),
served via GitHub Pages.

| Page | File | Used for |
| --- | --- | --- |
| Resources index | `index.html` | Landing page |
| Technical Support | `support.html` | App Store Support URL |
| Privacy Policy | `privacy.html` | App Store Privacy Policy URL, App Privacy report |
| Terms of Use | `terms.html` | App Store EULA URL (required for in-app purchases) |
| About the game | `marketing.html` | Product description, press, partners |

## Local preview

    open index.html

## Deploying

Pages is served from the repository root. `.nojekyll` is present so the files are
published verbatim rather than run through Jekyll.

## Notes for maintainers

* The privacy policy states that no advertising SDK is present and that analytics
  is disabled unless configured. **If Firebase Analytics is ever enabled in a
  release, section 1 and section 7 must be updated first**, and the App Store App
  Privacy report must be updated to match.
* The support page documents a strict linear unlock and per-device storage. Both
  are load-bearing claims: changing either without editing this page makes the
  published policy wrong.
