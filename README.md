# passport-local-token-auth

Authenticate via a username/password and get back a token

## Synopsis

This app logs in a user with a username / password pair using Passport's `passport-local` strategy for session-based authentication. It also uses `passport-http-bearer` strategy for token-based authentication.

Notes: I use Git Bash for Windows, thus the package.json file uses windows paths. Please update accordingly for other environments. Also mongoDB is required to store both the session and the registered users.

To test in Windows:

```
node ./node_modules/jasmine/bin/jasmine
```

To run the web server:

```
node app
```

To access from the browser:

```
localhost:3000
```

:coffee:
