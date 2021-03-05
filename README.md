# Task-manager-API

A complete Task Manager API, using Auth and CRUD Operations.


### prerequisites

```
node  
Npm
```

### Installing

```
npm install
```


### There is a need to create a dev.env file, which should contain

```
PORT=<port number>
SENDGRID_API_KEY=<sendgrid key>
JWT_SECRET=<secret>
MONGODB_URL=<url>
```
### Running

```
npm run dev

```
### It's possible to test after creating a test.env file

```
PORT=<port number>
SENDGRID_API_KEY=<sendgrid key>
JWT_SECRET=<secret>
MONGODB_URL=<test url>
```

### Testing

```
npm run test
```
### Tools:
- nodeJS - The web framework used
- npm - Back-End package manager
- express - Routes framework
- @sendgrid/mail - Service for interaction with the mail endpoint
- jsonwebtoken - Token generator
- mongodb - API for mongodb
- mongoose - Mongodb schema
- multer - File uploader
- sharp - Image uploader
- validator - Library for string validators
