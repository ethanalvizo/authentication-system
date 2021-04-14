# Authenthication System

A React + Firebase app that acts as a proper authentication/login system. This allows users to signup with their own credentials and even update it later if needed. The application is also using Firebase hosting.

[Live Demo](https://auth-dev-27e8b.web.app/).

## Getting Started
```
git clone https://github.com/ethanalvizo/authenthication-system.git
cd dev
```
Create a '.env.local' file in the root directory with this inside and fill in the variables with the info from your firebase config
```
REACT_APP_FIREBASE_API_KEY=
REACT_APP_FIREBASE_AUTH_DOMAIN_KEY=
REACT_APP_FIREBASE_PROJECT_ID=
REACT_APP_FIREBASE_STORAGE_BUCKET=
REACT_APP_FIREBASE_MESSENGER_SENDER_ID=
REACT_APP_FIREBASE_APP_ID=
```

```
npm install
npm start
```
## Built With
* [React](https://reactjs.org/)
* [react-router](https://reactrouter.com/)
* [react-bootstrap](https://react-bootstrap.github.io/)
* [Firebase](https://firebase.google.com/)

## Resources used to troubleshoot deployment
* [Medium Article](https://medium.com/@bensigo/hosting-your-react-app-with-firebase-hosting-add1fa08c214)
* [StackOverflow](https://stackoverflow.com/questions/52939427/react-router-doesnt-route-traffic-when-hosted-on-firebase)

