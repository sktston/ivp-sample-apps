# React-oidc-client-js

> OpenID Connect (OIDC) client with React and typescript

- This is sample application, full credit to [Jan Škoruba](https://github.com/skoruba/react-oidc-client-js)

- It contains [oidc-client-js](https://github.com/IdentityModel/oidc-client-js) and `React` with `Typescript`.

- The application is based on `create-react-app` - [Create React App](https://github.com/facebook/create-react-app)

- You will need access to the Initial Platform.

# Project status
The sample app is ready to be installed locally for trying out the connection to Initial Identity Verification Provider.

# Installation

## Cloning the sample-apps repo

``` sh
git clone https://github.com/sktston/ivp-sample-apps
```

## Change to the dir and install dependencies

- Install dependencies
``` sh
cd oidc-client-react
yarn install
```

## Update the .env file
Rename the `.env-template` file to `.env` and add your variables

```
REACT_APP_STSAUTHORITY=https://dev-console.myinitial.io/kc/auth/realms/vc-authn
REACT_APP_CLIENTID=oidc-client-react
REACT_APP_CLIENTROOT=https://localhost:3000/
REACT_APP_CLIENTSCOPE='profile vc_authn'
```

## Running app

- `yarn start` - start the web server 

