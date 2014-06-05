# Basic Auth Middleware for Express
### http://zip-tax.com

<a href="https://nodei.co/npm/basicauth/"><img src="https://nodei.co/npm/basicauth.png?downloads=true"></a>

## Download
The source is available for download from GitHub. Alternatively, you can install using Node Package Manager (npm):

`npm install basicauth`

## Example
```coffeescript
basicAuth = require 'basicauth'

app.use(basicAuth({
	'skoop' : 'Skoopin!100'
	'mattnull' : 'test'
}))
```

## Development
### Dependencies

This command needs to be ran first if CoffeeScript is not installed on your system

* run `sudo npm install -g coffee-script`

### Setup

Install all of the dependencies

* run `npm install`

The following command will watch and compile Coffeescript
* run `gulp`

