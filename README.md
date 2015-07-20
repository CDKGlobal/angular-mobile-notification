# AngularJS module for mobile notification

Angular Service to send mobile notification. This depends on Mobile Notification API https://github.com/CDKGlobal/mobile-notification-api

## Demo
http://jayeshgangadharan.github.io/angular-mobile-notification/

## Dependencies
- required:
	Mobile notification api https://github.com/CDKGlobal/mobile-notification-api
- optional


See `bower.json` and `index.html` in the `gh-pages` branch for a full list / more details

## Install
1. download the files
	1. Bower
		1. add `"angular-mobile-notification": "latest"` to your `bower.json` file then run `bower install` OR run `bower install angular-mobile-notification`
2. include the files in your app
	1. `mobile-notification.min.js`
3. include the module in angular (i.e. in `app.js`) - `jayeshgangadharan.angular-mobile-notification`

See the `gh-pages` branch, files `bower.json` and `index.html` for a full example.


## Documentation
See the `mobile-notification.js` file top comments for usage examples and documentation
https://github.com/jayeshgangadharan/angular-mobile-notification/blob/master/mobile-notification.js


## Development

1. `git checkout gh-pages`
	1. run `npm install && bower install`
	2. write your code then run `grunt`
	3. git commit your changes
2. copy over core files (.js and .css/.less for directives) to master branch
	1. `git checkout master`
	2. `git checkout gh-pages mobile-notification.js mobile-notification.min.js mobile-notification.less mobile-notification.css mobile-notification.min.css`
3. update README, CHANGELOG, bower.json, and do any other final polishing to prepare for publishing
	1. git commit changes
	2. git tag with the version number, i.e. `git tag v1.0.0`
4. create github repo and push
	1. [if remote does not already exist or is incorrect] `git remote add origin [github url]`
	2. `git push origin master --tags` (want to push master branch first so it is the default on github)
	3. `git checkout gh-pages`
	4. `git push origin gh-pages`
5. (optional) register bower component
	1. `bower register angular-mobile-notification [git repo url]`
