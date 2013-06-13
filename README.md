service_alternatives [![Stories in Ready](http://githubkanban.herokuapp.com/huboard/notbenh/service-alternatives.png)](http://huboard.com/notbenh/service-alternatives/board)
====================

_Alternatives to existing services that you find yourself using_

Apparently 2013 is the year of shitting on your customers, and I've had
enough. If I were to make a serious attempt to rewrite every service that does
not already have an open alternative what would that world look like?

This started out as a [pirate pad](http://piratepad.net/NTi3s7kHmv)
between [@vmbrasseur](http://github.com/vmbrasseur) and myself. It was suggested (by someone far brighter than I) that this would make a better git repo so we can
better point to it and collect an even wider audience. Thus here it
lives! Feel free to file issues, supply support requests or even move
this all over to the wiki. For now all is fair game!

email
-----

Currently I am using Gmail, though shifting to a provided email system should
be easy. IMAP is an open standard, it's just a matter of having a server that
plays MX.

Requirements:

  * [IMAP](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol "IMAP Wikipedia page")

Suggested options:

* [pobox.com](http://pobox.com)
	* Pros:
		* Reliable
		* Friendly service
		* Stable company
		* Proven commitment to keep the service ad-free
		* Great spam filter and reporting
	* Cons:
		* Has a webmail option but it's fairly clunky (atmail)
		* Not free
* [Fastmail](https://www.fastmail.fm/)
	* Pros:
		* Very good webmail UI
		* Service of Opera Software (read: open standards FTW)
	* Cons:
		* Not free
* Self-hosted
		* Pros:
		* Infinitely flexible
		* Potentially low monetary outlay
	* Cons:
		* [PITA](http://www.urbandictionary.com/define.php?term=PITA)
		* Potentially unreliable

chat
----

Fuck [Hangouts](http://www.google.com/+/learnmore/hangouts/). Google effectively
has [dropped support](http://tech.slashdot.org/story/13/05/20/2315216/google-drops-xmpp-support) for XMPP. As it's an open standard, finding a way to continue in this vein would ~should~ be
simple. It also might be time to just lean in and go email/IRC only.

Requirements

* XMPP?  

Suggested options:

* [DuckDuckGo XMPP](https://dukgo.com/blog/xmpp-services-at-duckduckgo)
	* Pros:
		* XMPP
		* Free
		* DuckDuckGo is committed to ad-free services which respect user privacy
	* Cons:
		* DDG is still a relatively new company. Does it have staying power?
* Self-hosted
	* Pros:
		* Infinitely flexible
		* Potentially low monetary outlay
	* Cons:
		* [PITA](http://www.urbandictionary.com/define.php?term=PITA)
		* Potentially unreliable

calendar
--------

There are currently no known decent web-based alternatives for [Google Calendar](https://www.google.com/calendar).

Requirements:

* Sync with [iCal-enabled](http://en.wikipedia.org/wiki/Calendar_%28application%29) systems
* Repeatable events
* Invite others to an event
* Sharable calendars
* Multiple calendars
* Event notifications
* Accessible on web

Suggested options:

* Uh...I got nuthin'
* Self-hosted?

twitter
-------

Currently it's free enough that I have no real issues with continue with it
but it might be time to get back on [Identi.ca](http://identi.ca) or some self hosted solution.

Requirements

* ?

Suggested options:

* [Indenti.ca](http://identi.ca)
* [App.net](http://app.net)

google reader
-------------

Requirements:

* syndicate [RSS](http://en.wikipedia.org/wiki/RSS) feeds
* dedupe feeds
* keyboard navigation of feeds
* un-minimize snipped contents from a feed
* ability to track what has been seen and has yet to be seen
* categorization/filing
* tagging/saving of articles  

Nice to haves:

* sharing is caring  

Suggested options:

* [NewsBlur](http://newsblur.com/)
	* Pros:
		* It's up and running
		* There's a free option
		* Others are using it
	* Cons:
		* Keyboard shortcuts are inconsistent
		* Updates are inconsistent
		* Fails to process all content correctly
		* UI's a mess
		* Sharing is extra clunky (i.e. only w/in NewsBlur community?)
		* Subscriptions are limited without a paid account
* [The Old Reader](http://theoldreader.com/)
	* Pros:
		* It's up and running
		* It's still free
	* Cons:
		* Idea of 'read' seems shaky
		* Share seems to be TOR only?
* Self-hosted
	* [Tiny Tiny RSS](http://tt-rss.org/redmine/projects/tt-rss/wiki)
		* Pros:
			* Under active development
			* Active community of contributors
		* Cons:
			* SLOW
			* Project lead is a jerk to the community and is proud of it

Photos
------

The current go-to online service is [Flickr](http://flickr.com), but some of the recent moves by its parent company [Yahoo!](http://yahoo.com) have some people nervous.

Requirements:

* Ease of upload
	* Android/iOS app(s) 
		* easy to take pictures
		* easy to upload content
* Create thumbnail versions of any uploaded content with the possibility of other sizes
* Organization options for content
* Metadata
* Auto-extracted from [Exif](https://en.wikipedia.org/wiki/Exchangeable_image_file_format)
* User contributed
* Content accessible via permalink
* Auto-rotate images based on Exif data
* Search based on metadata
* Access control to view images
* Image licensing options (in metadata?)  

nice to haves:

* ?

Suggested options:

* [500px](http://500px.com)
    * Pros:
        * Good interface
        * Organization options
        * Creative Commons image licensing available
    * Cons:
        * Relatively new, no reputation yet
* Self-hosted  


personal cloud
-------------

* [Owncloud](http://owncloud.org/)
	* Pros:
		* Open source
	* Cons:
		* ???

hosting
-------

Here's the big one, currently I am on [Dreamhost](http://dreamhost.com/). 
Nice service for somethingsimple but I'm currently at the $7-ish a month and 
they don't allow for anything exciting... Well guess what? Everything that 
I want to do is just exciting enough get in the way of the DH TOS... so where 
to put everything?

Requirements:

* Command-line access
* *NIX  

Suggested options:

* Self-hosted
* [dotCloud](https://www.dotcloud.com/) 
	* Pros:
		* Allows for node.js hosting which opens up SFW, etherpad, etc.
	* Cons:
		* ???
* [Heroku](https://www.heroku.com/)
* [Linode](https://www.linode.com/)
* [OpenShift](https://www.openshift.com/) (from Red Hat)
* [DigitalOcean](https://www.digitalocean.com/)
   

### wiki testing

Attempt to see if the Readme parser speaks enough wiki to make links: 

* [News](https://github.com/notbenh/service_alternatives/wiki#news)

