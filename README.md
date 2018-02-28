# beckiheartsjosh
Mockup of vanilla site for @beckibuddin

## Local development
* Clone the repo (either this one or your own fork)
* Set up Compass to build style.css from the scss folder --> `compass watch` using the config.rb file I've included
* Open file `index.html` in your browser  
* Play with things
* Use Developer mode in Chrome a lot
* Push changes back to this repo: `git push origin master`

## Deployment
* Files are hosted on @DeckOfPandas's private server  
* Log in, and go to correct folder  
* Get the changes: `git pull origin master`  
* Admire in self-congratulatory manner

## Things that might be useful to know
* The template site as-sold is here: http://www.wiselythemes.com/html/lilac/
* @DeckOfPandas hasn't changed much text, and there are numerous typos etc from the template
* Styling from the template is in scss/theme/ -- don't change these (not all of them are in there yet, but _base.scss is the main one and that's done)
* If you want to change the base template, you should overwrite the classes with new scss rather than changing the theme's files (so it's easy to update the theme in the future)
* Some parameters such as colors have been pulled out of the template, and are in scss/_variables.scss
* The scss setup works like this:
  * The file style.scss just has @imports in for the other files. This will make things easier to keep track of. You can create and import more files in exactly the same way.
  * Compass will compile the file scss/style.scss into css/style.css
  * The browser reads css/style.css (this is imported in the <head> section of index.html)
* @DeckOfPandas's work in progress is in scss/_sandbox.scss, and this could eventually be split out into e.g. _titles.scss, _dividers.scss etc, or possibly even the 'proper' way (i.e. according to the Sass documentaion)
* The RSVP form isn't supposed to work yet
* The Google maps API isn't supposed to work yet
* The instagram and twitter feed in the gallery aren't supposed to work yet

## Helllllp
* Force-refresh a lot 
* Turn Compass off and on again 
* Google
* Ask @DeckOfPandas (totally totally fine)
