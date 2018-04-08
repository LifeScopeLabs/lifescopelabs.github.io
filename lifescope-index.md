# LIFESCOPE
### The Internet of You


"My friends and I work, play, and communicate on dozens platforms. Conversation start on texts, continue on Facebook Messenger, continue in person, then go to Skype and conclude on Slack. Retracing my history keeps me jumping from app to app without any control. Pretty much all software is like this; it's a broken experience."

 -- Liam Broza, Founder of LIFESCOPE

The internet landscape is a vast, overwhelming, and broken terrain of data. Only the best companies in the world can tap into a tiny fraction of data's potential. People create and consume digital information without understanding what’s going on.  It is hopeless for anyone to create a complete and up to date accounting of their information, let alone search and organize their data.

The study and use of psychometircs and psychographics is the biggest hidden force in the world. Our personal data doesn't just describe who we really are, but also give others power over us by enabling them to reverse engineer our minds. Understanding and controlling our own data should be a human right.

LifeScope is an open platform for personal data whereby ownership is returned to the user. The platform is designed the ultimate private repository of your digital life. Connect anywhere and everywhere your information resides and LifeScope will automatically collect, organize, and present everything in your digital memory. Search and leverage your entire digital and social footprint, while streamlining your life online. Curate your history data into the stories you care about.

LifeScope is still in early days, but we have plans to expand this platform so it can power the next generation of software technology.

- open source
- platform
- components

#### Want to help make the LifeScope dream real? [Join the cause](https://lifescope.io/signupdev)!


# Architecture

### Overview

[ ![alt text][arch]](https://lifescopelabs.github.io/assets/diagrams/LifeScope%20Architecture%20Planning%203-26-18.pdf)


### Data Source Flow

![source flow][soureflow]

![conceptdiagram][conceptdiagram]


## Frontend
### [lifescope-site](https://lifescopelabs.github.io/site.html)
* Backups of all site content /documentation for lifescope.github.io
* lifescope.io served by SquareSquare
### [lifescope-app](https://lifescopelabs.github.io/app.html)
* App to search explorer and curate your personal data in various views
* Single-page Universal web app built on Nuxt and Vue.js
* Desktop/mobile reactive design interface with javascript extentions
* Written with plugin framework such as location tracking, web xr and web voice
* Should be containerizable inside a universal app framework Cordova
#### Login
* Able to sign up and login with any provider
#### Homepage
* List saved searches and hashtags
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
#### People Management
Relate contacts together into People and relate People into Users

#### Settings

#### Published Content

### [lifescope-browser-extension](https://lifescopelabs.github.io/app.html)
* Regularly post browser history into Lifescope schema
* Capture web history on a url, site visit, or domain basis
* Scrape important info (like netflix or hulu history)
* Surface metadata (oEmbed, Embedly)
* Capture and store location data

### [lifescope-voice](https://lifescopelabs.github.io/app.html)
* voice search
* voice response
* capture voice data

### [lifescope-xr](https://lifescopelabs.github.io/app.html)
* AR/VR views

## Backend

### [lifescope-api](https://lifescopelabs.github.io/app.html)
* GraphQL-based for CRUD operations on data schema
* REST api for login/logout/signup and OAUTH workflow

### [lifescope-ai](https://lifescopelabs.github.io/app.html)
* Reporting
* Visualization
* Behavior modeling
  * correlation
  * prediction
  * suggestion

### [lifescope-etl](https://lifescopelabs.github.io/etl.html)
* Pull data from source apis through BitScoop SDK
* Syncs on a scheduled basis
* Transform data into lifescope schema
* Keep a copy of original data

### [DB Storage](https://lifescopelabs.github.io/db.html)
* Common Schema (schema.org)
* User level encryption
* Whole DB backups
* Eventually pluggable (Local/OBDC/JBDC/Etc)

[conceptdiagram]:https://lifescopelabs.github.io/assets/img/concept-diagram.png
[soureflow]:https://lifescopelabs.github.io/assets/diagrams/data-source-flow.png
[arch]: https://lifescopelabs.github.io/assets/diagrams/LifeScope%20Architecture%20PlanningNEW.jpg  "Arch" 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjI0NTg3ODA5XX0=
-->