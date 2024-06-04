
# Auth0 Integration With Node.js - ExpressJS

This is a simple guide to demonstrate backend Auth0 integration.


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`CLIENT_ID` -> Go to Auth0 -> Applications -> Settings -> Client ID

`AUTH0_TENANT` -> Go to Auth0 -> Applications -> Settings -> Domain

`CLIENT_SECRET` -> Run this command to generate the secret value -> openssl rand -hex 32
    
- If you are running on Windows: Try to run this in Git Bash it should work without you needing to install Win64 OpenSSL

--------------------------------------------------------

Also make sure to setup this in Settings tab in Auth0:

Allowed Callback URLs: http://localhost:3000

Allowed Logout URLs: http://localhost:3000

--------------------------------------------------------    
    


## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
  npm start
```
    
## References

https://auth0.github.io/express-openid-connect/index.html

## Feedback

If you have any feedback, please reach out to me at jarvisfranklinthaker@gmail.com



## Authors

- [Franklin Thaker](https://www.github.com/FranklinThaker)

