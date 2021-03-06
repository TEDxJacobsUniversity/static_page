TEDxJacobsUniversty Static Page
===============================

To run:
-------
- run `python --vesion` and check python version
- For Python 2.7, run `python -m SimpleHTTPServer`
- For Python 3.x, run `python -m http.server`
- Goto `http://localhost:8000` on your browser


Signup Form:
------------

	The signup form won't actually do anything (other than report back with a "thank you" message)
	until you tie it to either a third party service (eg. MailChimp) or your own hosted solution.
	In either case, there are two ways to go:

	1. The conventional (non-AJAX) way, which pretty much comes down to pointing the form's "action"
	attribute to your service/script URL. If you go this route, remove the entire "Signup Form" code
	block from assets/js/main.js (since it's not needed for this approach).

	-or-

	2. The AJAX way. How you set this up is largely dependent on the service/solution you're using
	so you'll need to consult their/its documentation. However, I have included some basic code
	(under "Signup Form" in assets/js/main.js) that will at least let you interact with the
	form itself.


Slideshow Background:
--------------------

	This is pretty straightforward, but there are two JS settings you'll want to be aware of
	(found under "Slideshow Background" in assets/js/main.js):

	images

		The list of images to cycle through, given in the following format:

			'url': 'alignment'

		Where 'url' is the image (eg. 'images/foo.jpg', 'http://somewhere.else/foo.jpg'), and
		'alignment' is how the image should be vertically aligned ('top', 'center', or 'bottom').

		Note: Browsers that don't support CSS transitions (like IE<=9) will only see the first image.

	delay

		How long to wait between transitions (in ms). Note that this must be at least twice as long as
		the transition speed itself (currently 3 seconds).


Credits:
--------

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
