# [LIFESCOPE-BROWSER-EXTENSION](https://github.com/LifeScopeLabs/lifescope-browser-extension)

## [Repository](https://github.com/LifeScopeLabs/lifescope-browser-extension)

(development phase, medium priority)

* Regularly post browser history into LIFESCOPE schema
* Capture web history on a url, site visit, or domain basis
* Scrape important info (like netflix or hulu history)
* Surface metadata (oEmbed, Embedly)
* Capture and store location data

### Requirements
- **MVP**:  Reconnect current extension

### Dependencies
- Vue/Nuxt compatible

**Opt in to browser history collection and scraping on supported sites.**

![browserextscrape]

**Review and edit your collected history.**

![browserext]

## Data Collection Sources

| Data Source | Status | Data Collected |
|--|--|--|
| URL History | beta | events, content |
| Location History | development | locations |
| **Scrape** Netflix | planned | events, content |
| **Scrape** Hulu | planned | events, content |
| **Scrape** Amazon Prime | planned | events, content |
| **Scrape** HBO GO | planned | events, content |
| **Scrape** YouTube | planned | events, content |

## Examples
- [Browser Extension Dev Example](https://www.smashingmagazine.com/2017/04/browser-extension-edge-chrome-firefox-opera-brave-vivaldi/)
- [Mozilla WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions)

## Developer Setup

1. Clone this repo
2. Install the repo's directory as an extension

[browserext]:https://lifescopelabs.github.io/assets/screenshots/browser-plugin-screenshot.png
[browserextscrape]:https://lifescopelabs.github.io/assets/screenshots/browser-extensions.png

<!--stackedit_data:
eyJoaXN0b3J5IjpbNDExMzExMDUwLC0xNTY3NjQ4OTAzLC0xNj
AxMzUzMjI0LC01Mjg2NDg3MTQsLTg1MjAzMTUwMSwxOTI3Nzc3
NDI5XX0=
-->