# LIFESCOPE

**The Internet of You**

> "My friends and I work, play, and communicate on dozens platforms. Conversation start on texts, continue on Facebook Messenger, continue in person, then go to Skype and conclude on Slack. Retracing my history keeps me jumping from app to app."

_Does this sound familiar?_

![dataknot][dataknot]

**Internet connected software is broken.**

The internet landscape is a vast, overwhelming, and broken terrain of data. Only the best companies in the world can tap into a tiny fraction of data's potential. People create and consume digital information without understanding what’s going on.  It is hopeless for anyone to create a complete and up to date accounting of their information, let alone search and organize their data.

The study and use of psychometircs and psychographics is the biggest hidden force in the world. Our personal data doesn't just describe who we really are, but also give others power over us by enabling them to reverse engineer our minds. Understanding and controlling our own data should be a human right.

LIFESCOPE is an open platform for personal data designed to empower anyone with insights while preserving privacy and ownership. Master time and space with a digital memory. The platform is designed the ultimate private repository of your digital life. 

![conceptdiagram]

Connect anywhere and everywhere your information resides and LIFESCOPE will automatically collect, organize, and present everything in your digital memory. Search and leverage your entire digital and social footprint, while streamlining your life online. Curate your history data into the stories you care about.

LIFESCOPE as an open source platform for anything you want to do with your personal data. We have plans to expand this platform so it can power the next generation of software technology. 

- [LIFESCOPE Main Site](https://lifescope.io)
- [LIFESCOPE Legacy App](https://app.lifescope.io)
- [LIFESCOPE Documentation](https://lifescope.io/learn)
- [LIFESCOPE GitHub](https://github.com/LifeScopeLabs)

# Want to help? 
We are currently looking for designers, creators, developers, and data scientists to help build and grow LIFESCOPE.

### **[Join the team!](https://lifescope.io/signupdev)**

# Repository Documentation Index

Here is the repository documentation and development status of all project components.
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

- [Database Documentation](https://lifescopelabs.github.io/database.html)
- [Legacy App Documentation](https://github.com/LifeScopeLabs/lifescope-etl/tree/master/archive/tutorial)

# How does it work?

The core of LIFESCOPE is an automated set of tools to collect personal data (via [API ETL Scripts](https://lifescopelabs.github.io/etl.html), [Browser Plugin](https://lifescopelabs.github.io/browser-extension.html), [App](https://lifescopelabs.github.io/app.html) repositories) and organize everything a standard way. All of the collected data is organized into a [database](https://lifescopelabs.github.io/database.html) and presented with the [API](https://lifescopelabs.github.io/api.html).

The LIFESCOPE platform is designed to be completely pluggable. Easily add data sources, change data organization, change database technologies, and create apps on the API.

The [LIFESCOPE App](https://lifescopelabs.github.io/app.html) is a suite of experiences letting you explore your entire digital life.

## Data Collection
LIFESCOPE collects personal information from three places. When you create connections in the App or API, [API ETL Scripts](https://lifescopelabs.github.io/etl.html) will run. The [Browser Plugin](https://lifescopelabs.github.io/browser-extension.html) allows for opting into recording url and visits. The plugin can also scrape webpages. The native and web JavaScrip [App](https://lifescopelabs.github.io/app.html) can pull information on the device such as locations and contacts.

![soureflow]

## Data Organization and Storage

[LIFESCOPE API](https://lifescopelabs.github.io/api.html) uses GraphQL and REST to signup, login, manage sources, and access all your data. LIFESCOPE's API will eventually allow for pluggable [Database Support](https://lifescopelabs.github.io/database.html).

**LIFESCOPE Schema** Replicated in MongoDB and the GraphQL API.

![gqlschema]

## Single App Architecture

The [LIFESCOPE App](https://lifescopelabs.github.io/app.html) is to search, explore, and curate your personal data in various views. Explore data with various views (Feed, List, Map, Gallery, Timeline, [Virtual Reality, Augmented Reality](https://lifescopelabs.github.io/xr.html).  Let the app look and [listen to you](https://lifescopelabs.github.io/voice.html). Speak questions about yourself or record and automatically respond.

Curate your data with saved searches and hashtags. See [reports and data visualizations](https://lifescopelabs.github.io/ai.html). Get smart notifications with machine learning. Explore people from your history. People are represented as related contacts and history across services. 

Single-page Universal web app built on Nuxt and Vue.js. Desktop/mobile reactive design interface with javascript extensions. Written with plugin framework such as location tracking, WebXR and Web Speech. Should be containerizable inside a universal app framework like Cordova (iOS, Android, Mac, Win). 

The current LIFESCOPE codebases are hosted on Amazon Web Services to power the web platform.

**AWS Developer Stack**

![arch]

# Data Sources

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

| Data Source | Support | Status | Data Collected |
|--|--|--|--|
| Location History | Universal | development | locations
| **Scrape** Calls | Native app | planned | events, content |
| **Scrape** Messages | Native app | planned | events, content |
| **Scrape** Media | Native app | planned | events, content |
| **Scrape** Files | Native app | planned | events, content |

![fractal][fractal]

# History

[Liam Broza](httos://liambroza.com) and the team at [BitScoop Labs](https://bitscoop.com) have been working on problems big data and quantified self for over a decade. This project started as SmokeSignal in 2009 as a Java desktop app for crawling android app data.  [Original SmokeSignal LifeLogger Site](https://web.archive.org/web/20141222111903/http://www.smokesignal.info/) In 2016, BitScoop Labs rebuilt the project as Live Explorer (and is now the legacy LIFESCOPE app). In 2018, LIFESCOPE was released open source by the BitScoop team to help give people control of their digital identity.  

**Original SmokeSignal LifeLogger Site**

![smokesignalss2]

**Original SmokeSignal LifeLogger Sources**

![smokesignalss1] 

[conceptdiagram]:https://lifescopelabs.github.io/assets/img/concept-diagram.png
[soureflow]:https://lifescopelabs.github.io/assets/diagrams/data-source-flow.png
[arch]: https://lifescopelabs.github.io/assets/diagrams/LifeScope%20Architecture%20PlanningNEW.jpg  
[dataknot]:https://lifescopelabs.github.io/assets/img/dataknot.png
[smokesignalss1]:https://lifescopelabs.github.io/assets/screenshots/smokesignal-io-legacy-1.png
[smokesignalss2]:https://lifescopelabs.github.io/assets/screenshots/smokesignal-io-legacy-2.png
[fractal]:https://lifescopelabs.github.io/assets/img/fractal.png
[ografy]:https://lifescopelabs.github.io/assets/screenshots/ografy.png
[gqlschema]:https://lifescopelabs.github.io/assets/diagrams/LifeScopeSchema.png
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3NDU3NDUyNzFdfQ==
-->