# LIFESCOPE

**The Internet of You** 

This GitHub.io Site contains LIFESCOPE Developer documentation and serves as planning workbook for each lifescope code repository.

> "My friends and I work, play, and communicate on dozens platforms. Conversation start on texts, continue on Facebook Messenger, continue in person, then go to Skype and conclude on Slack. Retracing my history keeps me jumping from app to app."

_Does this sound familiar?_

![dataknot]

**Internet connected software is broken.**

The internet landscape is a vast, overwhelming, and broken terrain of data. Only the best companies in the world can tap into a tiny fraction of internet data's potential. People create and consume digital information without understanding the complex truth of what’s going on.  Where is your data? A database? File system? Somewhere else? It is hopeless for anyone to create a complete and up to date accounting of their information, let alone search and organize their data.

The study and use of psychometrics and psychographics are the biggest hidden forces in the modern world. Our personal data doesn't just describe who we really are, but also give others power over us by enabling them to reverse engineer our minds. Understanding and controlling our own data should be a human right.

LIFESCOPE is an open platform for personal data designed to empower anyone with insights while preserving privacy and ownership. Access and control of your data is a human right. The platform is designed the ultimate private repository of your digital life. Master time and space with a digital memory.

![conceptdiagram]

Connect anywhere and everywhere your information resides and LIFESCOPE will automatically collect, organize, and present everything in your digital memory. Search and leverage your entire digital and social footprint, while streamlining your life online. Curate your history data into the stories you care about.

LIFESCOPE as an open source platform for anything you want to do with your personal data. We have plans to expand this platform so it can power the next generation of software technology.

- [LIFESCOPE Main Site](https://lifescope.io)
- [LIFESCOPE Legacy App](https://app.lifescope.io)
- [LIFESCOPE Documentation](https://lifescope.io/learn)
- [LIFESCOPE GitHub](https://github.com/LifeScopeLabs)

# Want to help?
We are currently looking for designers, creators, developers, and data scientists to help build and grow LIFESCOPE.

## **[Join the team!](https://lifescope.io/open-source/)**

# Documentation Index

Developer documentation serves as a roadmap planning workbook for each repository.

| Repository Documentation | Priority | Status |
|--|--|--|
| **[LIFESCOPE-AI](https://lifescopelabs.github.io/ai.html)** | low | concept |
| **[LIFESCOPE-API](https://lifescopelabs.github.io/api.html)** | high | production |
| **[LIFESCOPE-APP](https://lifescopelabs.github.io/app.html)** | high | development |
| **[LIFESCOPE-BROWSER-EXTENSION](https://lifescopelabs.github.io/browser-extension.html)** | medium | development |
| **[LIFESCOPE-ETL](https://lifescopelabs.github.io/etl.html)** | high | production |
| **[LIFESCOPE-SITE](https://lifescopelabs.github.io/site.html)** | low | beta |
| **[LIFESCOPE-VOICE](https://lifescopelabs.github.io/voice.html)** | low | concept |
| **[LIFESCOPE-XR](https://lifescopelabs.github.io/xr.html)** | medium | development |

- [Database Documentation](https://lifescopelabs.github.io/db.html)
- [Legacy App Documentation](https://github.com/LifeScopeLabs/lifescope-etl/tree/master/archive/tutorial)

**Note**: Each repository has a seperate list of Status

# How does it work?

The core of LIFESCOPE is an automated set of tools to collect personal data (via [API ETL Scripts](https://lifescopelabs.github.io/etl.html), [Browser Plugin](https://lifescopelabs.github.io/browser-extension.html), [App](https://lifescopelabs.github.io/app.html) repositories) and organize everything a standard format. All of the collected data is organized into a [database](https://lifescopelabs.github.io/database.html) and presented with the [API](https://lifescopelabs.github.io/api.html).

The LIFESCOPE platform is designed to be completely pluggable. Easily add data sources, change data organization, change database technologies, and create apps on the API.

The [LIFESCOPE App](https://lifescopelabs.github.io/app.html) is a suite of experiences letting you explore your entire digital life.

## Data Collection
LIFESCOPE collects personal information from three places. When you create connections in the App or API, [API ETL Scripts](https://lifescopelabs.github.io/etl.html) will run. The [Browser Plugin](https://lifescopelabs.github.io/browser-extension.html) allows for opting into recording url and visits. The plugin can also scrape webpages. The native and web JavaScrip [App](https://lifescopelabs.github.io/app.html) can pull information on the device such as locations and contacts.

![soureflow]

## Data Organization and Storage

[LIFESCOPE API](https://lifescopelabs.github.io/api.html) uses GraphQL and REST to signup, login, manage connection sources, and access all your data. LIFESCOPE's API will eventually allow for pluggable [Database Support](https://lifescopelabs.github.io/database.html).

**LIFESCOPE Schema** Replicated in MongoDB and the GraphQL API.

![gqlschema]

## Single App Architecture

The [LIFESCOPE App](https://lifescopelabs.github.io/app.html) is a full viewer of the API allowing users to search, explore, and curate your personal data in various views. Explore data with various views (Feed, List, Map, Gallery, Timeline, [Virtual Reality, Augmented Reality](https://lifescopelabs.github.io/xr.html).  Let the app look and [listen to you](https://lifescopelabs.github.io/voice.html). Speak questions about yourself or record and automatically respond.

Curate your data with saved searches and hashtags. See [reports and data visualizations](https://lifescopelabs.github.io/ai.html). Get smart notifications with machine learning. Explore people from your history. People are represented as related contacts and history across services.

Th eapp is a Single-page Universal web app built on Nuxt and Vue.js. Desktop/mobile reactive design interface with javascript extensions. Written with plugin framework with modules of features such as location tracking, WebXR and Web Speech. Designed to be containerizable inside a universal app framework like Cordova (iOS, Android, Mac, Win).

The current LIFESCOPE codebases are hosted on Amazon Web Services to power the web platform hosted on lifescope.io. 

**AWS Developer Stack**

![arch]

#  Data Collection Sources

**Current status of data source support.**

## API ETL

| Data Source | Status | Data Collected |
|--|--|--|
| Facebook | production | events, content, contacts, locations |
| Twitter | production | events, content, contacts, locations |
| Pinterest | beta | events, content, locations |
| Dropbox | production | events, content, locations |
| Steam | production | events, content |
| Reddit | production | events, content, contacts, contacts |
| Spotify | production | events, content |
| GitHub | production | events, content, contacts |
| Instagram | production | events, content, contacts |
| Google | production | events, content, contacts |
| Slice | development | events, content, things |
| FitBit | planned | events, things |
| TV Time | planned | events, content |

## Browser Plugin

**Opt in to browser history collection and scraping on supported sites.**

![browserextscrape]

| Data Source | Status | Data Collected |
|--|--|--|
| URL History | beta | events, content |
| Location History | development | locations |
| **Scrape** Netflix | planned | events, content |
| **Scrape** Hulu | planned | events, content |
| **Scrape** Amazon Prime | planned | events, content |
| **Scrape** HBO GO | planned | events, content |
| **Scrape** YouTube | planned | events, content |

## App

**Native app for iOS, Android, Windows, and Mac.**

![nativeapp]

| Data Source | Support | Status | Data Collected |
|--|--|--|--|
| Location History | Universal | development | locations
| **Scrape** Calls | Native app | planned | events, content |
| **Scrape** Messages | Native app | planned | events, content |
| **Scrape** Media | Native app | planned | events, content |
| **Scrape** Files | Native app | planned | events, content |

![fractal][fractal]

# History

[Liam Broza](httos://liambroza.com) and the team at [BitScoop Labs](https://bitscoop.com) have been working on problems in big data and quantified self for over a decade. This project started as SmokeSignal in 2009. SmokeSignal was originally written as a Java desktop app for crawling android app data.  [Original SmokeSignal LifeLogger Site](https://web.archive.org/web/20141222111903/http://www.smokesignal.info/) In 2016, BitScoop Labs rebuilt the project as Live Explorer (and is now the legacy LIFESCOPE app). In 2018, LIFESCOPE was released open source by the BitScoop team to help give people control of their digital identity.

**Original SmokeSignal LifeLogger Site (2**

![smokesignalss2]

**Original SmokeSignal LifeLogger Sources**

![smokesignalss1]

[conceptdiagram]:https://lifescopelabs.github.io/assets/img/concept-diagram.png
[soureflow]:https://lifescopelabs.github.io/assets/diagrams/data-source-flow.png
[arch]: https://lifescopelabs.github.io/assets/diagrams/LifeScopeArchitecturePlanningNEW.jpg  
[dataknot]:https://lifescopelabs.github.io/assets/img/dataknot.png
[smokesignalss1]:https://lifescopelabs.github.io/assets/screenshots/smokesignal-io-legacy-1.png
[smokesignalss2]:https://lifescopelabs.github.io/assets/screenshots/smokesignal-io-legacy-2.png
[fractal]:https://lifescopelabs.github.io/assets/img/fractal.png
[ografy]:https://lifescopelabs.github.io/assets/screenshots/ografy.png
[gqlschema]:https://lifescopelabs.github.io/assets/diagrams/LifeScopeSchema.png
[browserextscrape]:https://lifescopelabs.github.io/assets/screenshots/browser-extensions.png
[nativeapp]:https://lifescopelabs.github.io/assets/screenshots/ss-savedsearches.png
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjc4MDAxMjUxLDg1MTkxNjQwNywyOTQ1OD
E1NDYsLTE2NTcyMzI5ODcsLTE2NTcyMzI5ODcsLTI0ODAxNTI3
OCw1OTgzNzAzMjIsLTk4NDAyMzU1MCwtOTM4NTg2Nzk5LC0xMj
kyMjE3MjQwLC0xMTQ2MzgwNjQyLDE2NDQ0MDQ3ODhdfQ==
-->