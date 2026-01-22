# To Run This Application

1. Login to AWS Managment console and create an AWS Cognito SPA client application

2. Note the cognito domain and client id and update the file ui/.env, replacing the values below:

```
VITE_COGNITO_DOMAIN='https://eu-west-2azp1ieq4o.auth.eu-west-2.amazoncognito.com'
VITE_COGNITO_CLIENT_ID='1ctvlmhfehrj0dumbmb2tv1shp'
```

3.  Build and Run the UI

```bash
cd ui
npm install
npm run dev
```

4. Select "Login" and create a new user login ...
