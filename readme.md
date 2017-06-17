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


CLIENT_ID='1814145905472752' CLIENT_SECRET='3162cf21c36b14511cd3b1b5524575d1' node server.js

Open a web browser and navigate to [http://localhost:3000/](http://localhost:3000/)
to see the example in action.

Do not commit the package.json file.
