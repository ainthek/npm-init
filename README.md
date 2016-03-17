# npm-init

set of tools to setup your npm project quicker

See also <https://github.com/gratex/node-boilerplate> for another approach.

## Usage

Assuming you already have node project (`npm init`)
	
	# for consumers 
	npm install --save-dev npm-init # path to git, or local folder of this repo

	# for contributors
	cd ..
	git clone git@gitlab01.hq.gratex.com:dojo/npm-init.git

	
	npm install --save-dev ../npm-init

From now you can easily add new feature to your project:

	./node_modules/.bin/npm-init-babel
	./node_modules/.bin/npm-init-mocha

	...
For easier workflow when developing init scripts 
you may run bins directly from npm-init folder:

 	../npm-init/bin/npm-init-mocha

That is all.

## Links

- <http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/>	
- <https://github.com/gratex/node-boilerplate>
