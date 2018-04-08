# LIFESCOPE

### The Internet of You

> "My friends and I work, play, and communicate on dozens platforms. Conversation start on texts, continue on Facebook Messenger, continue in person, then go to Skype and conclude on Slack. Retracing my history keeps me jumping from app to app."

_Does this sound familiar?_

![dataknot][dataknot]

**Internet connected software is broken.**

The internet landscape is a vast, overwhelming, and broken terrain of data. Only the best companies in the world can tap into a tiny fraction of data's potential. People create and consume digital information without understanding what’s going on.  It is hopeless for anyone to create a complete and up to date accounting of their information, let alone search and organize their data.

The study and use of psychometircs and psychographics is the biggest hidden force in the world. Our personal data doesn't just describe who we really are, but also give others power over us by enabling them to reverse engineer our minds. Understanding and controlling our own data should be a human right.

LifeScope is an open platform for personal data designed to empower anyone with insights while preserving privacy and ownership. Master time and space with a digital memory. The platform is designed the ultimate private repository of your digital life. 

Connect anywhere and everywhere your information resides and LifeScope will automatically collect, organize, and present everything in your digital memory. Search and leverage your entire digital and social footprint, while streamlining your life online. Curate your history data into the stories you care about.

Lifescope as an open source platform for anything you want to do with your personal data. We have plans to expand this platform so it can power the next generation of software technology. 

### ***Want to help make the LifeScope dream real? [Join the cause!](https://lifescope.io/signupdev)***

## How does the Lifescope platform work?

### Data Flow

![source flow][soureflow]

![conceptdiagram][conceptdiagram]
### Architecture  Overview

[ ![alt text][arch]](https://lifescopelabs.github.io/assets/diagrams/LifeScope%20Architecture%20Planning%203-26-18.pdf)

#### Single App Architecture

LifeSope App to search explorer and curate your personal data in various views. Single-page Universal web app built on Nuxt and Vue.js. Desktop/mobile reactive design interface with javascript extensions. Written with plugin framework such as location tracking, web xr and web voice. Should be containerizable inside a universal app framework like Cordova (iOS, Android, Mac, Win). Able to connect as many provider accounts you want. List saved searches and hashtags.

- Explorer Views
  * Feed
  * List
  * Map
  * Gallery
  * Timeline
  * Virtual Reality Room
  * Augmented Reality Phone
  * Voice
- Explore People
	- Relate contacts together into People 
	- Relate People to Users
- Your Settings
- Published You

## Developer Documentation Index
| Repository | Priority | Status |
|--|--|--|
| [lifescope-ai](https://lifescopelabs.github.io/ai.html) | low | concept |
| [lifescope-api](https://lifescopelabs.github.io/api.html) | high | production |
| [lifescope-app](https://lifescopelabs.github.io/app.html) | high | development |
| [lifescope-browser extension](https://lifescopelabs.github.io/browser-extension.html) | medium | development |
| [lifescope-etl](https://lifescopelabs.github.io/etl.html) | high | production |
| [lifescope-site](https://lifescopelabs.github.io/site.html) | low | development |
| [lifescope-voice](https://lifescopelabs.github.io/voice.html) | low | concept |
| [lifescope-xr](https://lifescopelabs.github.io/xr.html) | medium | development |

- [Database Documentation](https://lifescopelabs.github.io/db.html)
- [Legacy App Documentation](https://github.com/LifeScopeLabs/lifescope-etl/tree/master/archive/tutorial)

## Supported Personal Data Sources

| Name | Source | Status | Data Collected |
|--|--|--|--|
| Facebook | API ETL | production | events, content, contacts, locations |
| Twitter | API ETL | production | events, content, contacts, locations |
| Pinterest | API ETL | production | events, content, locations |
| Dropbox | API ETL | production | events, content, locations |
| Steam | API ETL | production | events, content |
| Reddit | API ETL | production | events, content, contacts, contacts |
| Spotify | API ETL | production | events, content |
| GitHub | API ETL | production | events, content, contacts |
| Instagram | API ETL | production | events, content, contacts |
| Google | API ETL | production | events, content, contacts |
| Slice | API ETL | development | events, content, contacts |
| FitBit | API ETL | planned | events, things |
| **Browser** | Browser plugin | planned | events, content, places |
| **Native App** | Native app | planned | events, content, contacts, places |

![fractal][fractal]

## Who thought of lifescope?

Liam Broza and the team at Bitscoop Labs have been working on problems big data and quantified self for over a decade. This project started as SmokeSignal in 2009 as a Java desktop app for crawling android app data. 

https://web.archive.org/web/20141222111903/http://www.smokesignal.info/

|--|--|
| ![smokesignalss2] | ![smokesignalss1] |

In 2016, BitScoop Labs rebuilt the project as Live Explorer. This is now the legacy lifescope app.
https://web.archive.org/web/20151116131419/http://ografy.io/

[conceptdiagram]:https://lifescopelabs.github.io/assets/img/concept-diagram.png
[soureflow]:https://lifescopelabs.github.io/assets/diagrams/data-source-flow.png
[arch]: https://lifescopelabs.github.io/assets/diagrams/LifeScope%20Architecture%20PlanningNEW.jpg  
[dataknot]:https://lifescopelabs.github.io/assets/img/dataknot.png
[smokesignalss1]:https://lifescopelabs.github.io/assets/screenshots/smokesignal-io-legacy-1.png
[smokesignalss2]:https://lifescopelabs.github.io/assets/screenshots/smokesignal-io-legacy-2.png
[fractal]:https://lifescopelabs.github.io/assets/img/fractal.png
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTk0MDU0MzA3OV19
-->