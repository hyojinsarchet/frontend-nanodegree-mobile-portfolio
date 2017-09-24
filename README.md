## Website Performance Optimization portfolio project

Optimizing the critical rendering path and make this page render fast is the key of this project.


### Getting started / Tools

* Optimize pageSpeed for index.html through this link below.
(https://developers.google.com/speed/pagespeed/insights/)
* Download and install `ngrok` to make your local server accessible remotely.
(https://ngrok.com/)

#### Final pageSpeed

* Desktop: 91/100
* Mobile: 90/100

#### Optimize `idex.html`

* Minified / Inlined CSS
* Added [async] attribute on JavaScript / Moved Script end of body
* Removed Google Fonts
* Added [media = print] tag to print.css
* Reduced image size

#### Optimize `main.js`

* Minified arrays
* Made changes in some functions
* Reduced image size
