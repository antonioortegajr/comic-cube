## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:antonioortegajr/comic-cube
$ cd comic-cube
$ npm install
```

The example uses environment variables to configure the consumer key and
consumer secret needed to access Facebook's API.  Start the server with those
variables set to the appropriate credentials.

```bash
$ CLIENT_ID=__FACEBOOK_CLIENT_ID__ CLIENT_SECRET=__FACEBOOK_CLIENT_SECRET__ node server.js
```

Open a web browser and navigate to [http://localhost:3000/](http://localhost:3000/)
to see the example in action.
