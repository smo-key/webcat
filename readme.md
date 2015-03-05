#Webcat

Catche (cache) your webpages with ease!
A system for continuous local storage of the Internet.

Development status: An idea, support it by giving stars.  Or don't.  Up to you.

##I use Webcat for
- Storing StackOverflow for coding competitions
- Making my own local Wikipedia... also for coding competitions
- Keeping Wikileaks safe and accessible

##Features
- Smart webpage caching
- Automated, continuous hashing

##Comes with
- **webcat.js**: easy and simple catching (caching) library
	- **webcat-search.js**: searching API, "what pages do I download if I only want ____?" and also searches indexed pages
	- **webcat-scrape.js**: scraping API, "what parts of pages do I keep if I only want ____?"
	- **webcat-parse.js**: parsing API, "how do I display the pages I've stored?"
	- Searcher API + Scraper API + Parser API = Webcat
- **webcat.sh**: CLI wrapper, put in your path and call `webcat` command via commandline
- **webcat-server.js**: NodeJS server with pretty GUI interface - runs in your favorite browser
- later: Chrome extension for DevTools [?]
