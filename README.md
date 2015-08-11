# jQuery Plugin for Listing accounts and Sharing page 

* Both example: http://threenugroho.heck.in/files/social/index.html
* For sharing example: http://tolgaergin.com/files/social/social-share.html
* For listing social profiles: http://tolgaergin.com/files/social/social-profiles.html

## Usage

	<link rel="stylesheet" href="/assets/stylesheets/arthref.min.css">

#### If you use the plugin in order to link to your profiles, you need to load jQuery first then arthrefSocialProfiles.js
	<script src="/assets/javascripts/socialProfiles.min.js"></script>

Then initialize the variables

	$('#clickable').socialProfiles({
		email: 'trenzoalgenre07@gmail.com',
		facebook: 'tri adi nugroho',
		twitter: 'trinugroho',
		pinterest: 'three',
		dribbble: 'bbb',
		skype: 'threenugroho.heck.in',
		linkedin: 'tr.linkedin.com/in/threenugroho'
	});

(When listing your social accounts,
for some websites such as LinkedIn, Evernote, Paypal, Windows, Flud, AIM, Yahoo
you need to write url address without "http://" or "https://"
Because, these websites doesnt have regular url.)

#### If you use the plugin in order to share pages, you need to load jQuery first then arthrefSocialShare.js
	<script src="/assets/javascripts/socialShare.min.js"></script>

Then initialize the variables

	$('#clickable').socialShare({
		social: 'blogger,delicious,digg,facebook,google,linkedin,myspace,reddit,stumbleupon,tumblr,twitter,windows,yahoo'
	});

## Directory and files

	/assets
		/stylesheets
			arthref.min.css
		/images
			social-sprite.png
		/javascripts
			socialProfiles.min.js
			socialShare.min.js

## Authors

**Three nugroho**

+ http://twitter.com/trinugroho http://threenugroho.heck.in

**trinugroho**

+ http://twitter.com/trinugroho http://threenugroho.heck.in

