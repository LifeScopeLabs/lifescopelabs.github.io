# LIFESCOPE

### The Internet of You

Pretty much all internet connected software is a broken experience. 

**Does this sound familiar?**

**_"My friends and I work, play, and communicate on dozens platforms. Conversation start on texts, continue on Facebook Messenger, continue in person, then go to Skype and conclude on Slack. Retracing my history keeps me jumping from app to app."_**

The internet landscape is a vast, overwhelming, and broken terrain of data. Only the best companies in the world can tap into a tiny fraction of data's potential. People create and consume digital information without understanding what’s going on.  It is hopeless for anyone to create a complete and up to date accounting of their information, let alone search and organize their data.

The study and use of psychometircs and psychographics is the biggest hidden force in the world. Our personal data doesn't just describe who we really are, but also give others power over us by enabling them to reverse engineer our minds. Understanding and controlling our own data should be a human right.

LifeScope is an open platform for personal data designed to empower anyone with insights while preserving privacy and ownership. The platform is designed the ultimate private repository of your digital life. 

Connect anywhere and everywhere your information resides and LifeScope will automatically collect, organize, and present everything in your digital memory. Search and leverage your entire digital and social footprint, while streamlining your life online. Curate your history data into the stories you care about.

LifeScope is still in early days, but we have plans to expand this platform so it can power the next generation of software technology.

- open source
- platform
- components

#### Want to help make the LifeScope dream real? [Join the cause](https://lifescope.io/signupdev)!

# Architecture  Overview

[ ![alt text][arch]](https://lifescopelabs.github.io/assets/diagrams/LifeScope%20Architecture%20Planning%203-26-18.pdf)


### Data Source Flow

![source flow][soureflow]

![conceptdiagram][conceptdiagram]

## Frontend

App to search explorer and curate your personal data in various views. Single-page Universal web app built on Nuxt and Vue.js. Desktop/mobile reactive design interface with javascript extensions. Written with plugin framework such as location tracking, web xr and web voice. Should be containerizable inside a universal app framework like Cordova. Able to connect as many provider accounts you want. List saved searches and hashtags


#### Explorer

##### Views
* Feed
* List
* Map
* Gallery
* Virtual Reality Room
* Augmented Reality Phone
* Voice

#### Providers
* Facebook
* Twitter
* Pinterest
* Dropbox
* Steam
* Reddit
* Spotify
* FitBit
* GitHub
* Instagram
* **Google**
* **Slice**

People Management - Relate contacts together into People and relate People into Users
Settings
Published Content

## Documentation
| Repository | Priority | Status |
|--|--|--|
| [lifescope-ai](https://lifescopelabs.github.io/ai.html) | low | concept |
| [lifescope-api](https://lifescopelabs.github.io/api.html) | high | production |
| [lifescope-ai](https://lifescopelabs.github.io/ai.html) | low | concept |
| [lifescope-ai](https://lifescopelabs.github.io/ai.html) | low | concept |
| [lifescope-ai](https://lifescopelabs.github.io/ai.html) | low | concept |
| [lifescope-ai](https://lifescopelabs.github.io/ai.html) | low | concept |
| [lifescope-ai](https://lifescopelabs.github.io/ai.html) | low | concept |


[lifescope-site](https://lifescopelabs.github.io/site.html)
[lifescope-browser-extension](https://lifescopelabs.github.io/app.html)
[lifescope-voice](https://lifescopelabs.github.io/app.html)
[lifescope-xr](https://lifescopelabs.github.io/app.html)
[lifescope-api](https://lifescopelabs.github.io/app.html)
[lifescope-ai](https://lifescopelabs.github.io/app.html)
[lifescope-etl](https://lifescopelabs.github.io/etl.html)
[DB Storage](https://lifescopelabs.github.io/db.html)


[conceptdiagram]:https://lifescopelabs.github.io/assets/img/concept-diagram.png
[soureflow]:https://lifescopelabs.github.io/assets/diagrams/data-source-flow.png
[arch]: https://lifescopelabs.github.io/assets/diagrams/LifeScope%20Architecture%20PlanningNEW.jpg  "Arch" 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkxMTE0MTMxOV19
-->