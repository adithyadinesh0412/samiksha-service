# Shikshalokam School Assessment APIs version: 0.0.1

## Environment variables:

### Hostname

```
HOST = localhost
```

### Port number

```
POST = 3000
```

### Mongo DB connecting string

```
MONGODB_URL = mongodb://localhost:27017
```

### Database name

```
DB = dbname
```

### Log level

- 0 EMERGENCY system is unusable
- 1 ALERT action must be taken immediately
- 2 CRITICAL the system is in critical condition
- 3 ERROR error condition
- 4 WARNING warning condition
- 5 NOTICE a normal but significant condition
- 6 INFO a purely informational message
- 7 DEBUG messages to debug an application

```
LOG = debug
```

### port Define environment

```
NODE_ENV = development
```

## Environment:

### production

```
NODE_ENV=production node app.js
```

### stage

```
NODE_ENV=stage node app.js
```

### qa

```
NODE_ENV=qa node app.js
```

### development

```
NODE_ENV=development node app.js
```

"mongoose": "^5.13.20",
"mongoose-autopopulate": "^0.6.1",
"mongoose-delete": "^0.4.0",
"mongoose-timestamp": "^0.6.0",
"mongoose-ttl": "0.0.3",

"@azure/storage-blob": "^12.0.2",
"@elastic/elasticsearch": "^7.7.1",
"@google-cloud/storage": "^2.0.3",
"aws-sdk": "^2.580.0",
"body-parser": "^1.18.2",
"bunyan": "^1.8.12",
"cache-manager": "^2.9.0",
"cli-table": "^0.3.1",
"commander": "^2.20.0",
"cookie-parser": "^1.4.3",
"cors": "^2.8.4",
"csvtojson": "^2.0.8",
"dotenv": "^6.1.0",
"express": "^4.16.3",
"express-cassandra": "^2.3.2",
"express-fileupload": "^0.4.0",
"express-validator": "^5.3.1",
"extendify": "^1.0.0",
"fn-args": "^4.0.0",
"form-urlencoded": "^3.0.0",
"fs": "0.0.1-security",
"fs-extra": "^7.0.1",
"glob": "^6.0.4",
"json2csv": "^4.3.1",
"jsonwebtoken": "^8.5.1",
"jwt-decode": "^2.2.0",
"kafka-node": "^4.1.3",
"keycloak-auth-utils": "^3.3.0",
"log": "^1.4.0",
"mathjs": "^5.2.3",
"mkdir": "0.0.2",
"moment-timezone": "^0.5.23",
"mongodb": "^3.2.3",
"mongoose": "^7.4.5",
"mongoose-autopopulate": "^1.0.1",
"mongoose-delete": "^1.0.1",
"mongoose-timestamp": "^0.6.0",
"mongoose-ttl": "^0.0.3",
"morgan": "^1.9.0",
"p-each-series": "^2.1.0",
"path": "^0.12.7",
"request": "^2.88.0",
"require-all": "^2.2.0",
"uuid": "^3.3.2",
"yaml-js": "^0.1.3"
