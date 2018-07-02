# Restaurant Reviews: Stage 1

This website is a project made for Nanodegree Program by Udacity&Google in Front-end Path.

The goal was to turn static, unresponsive site to the one that:

* displays well and correctly on every screen size (RWD)
* is optimazed in the terms of accessibility (screen reader friendly, proper semantics and afforances)
* has implemented service worker, so it is available offline (content cache)

### Setup instructions

1. Clone (using git) or download this repository (ZIP file)
2. Navigate to the new directory and run from there a simple HTTP server to serve, for example using Python. If You don't have it installed on your computer, go to [Python official website](https://www.python.org) and download it. If You do, just run the server from your terminal with command:
Python 2: `python -m SimpleHTTPServer 8000` 
Python 3: `python3 -m http.server 8000`
3. Open site in the browser at `http://localhost:8000`

### Page content

Website contains of main page with restaurant info cards. Provided filters let You choose neighborhood and cuisine type. 
View details button links to proper restaurant detail page with address, opening hours and some client's reviews.

### Responsiveness 

RWD is based on flex-box layout and setting breakpoints with media-querries to provide clean layout that suits diverse range of display sizes.

### Accessiblilty

Implementation of ARIA best practices and semantic HTML. Lighouse audit score: 94%.

### Offline first

Service worker provides offline accessibility - implemented by content cache. To audit that - switch to Chrome DevTools panel, navigate the Network tab and check the offline checkbox to force dissconnected from network.

### DEPENDENCIES:

* starter code from Udacity: https://github.com/udacity/mws-restaurant-stage-1
* service-worker inspiration: https://www.youtube.com/watch?v=BfL3pprhnms
* flex-box overview: https://css-tricks.com/snippets/css/a-guide-to-flexbox/