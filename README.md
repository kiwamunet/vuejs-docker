# vuejs-docker 


## Usage

```
$ docker-compose up -d --build
$ docker-compose exec vue_app sh

/app # vue init webpack
/app # npm install


vim config/index.js
//host: 'localhost', // can be overwritten by process.env.HOST
//port: 8080, // can be overwritten by process.env.PORT, if port is in use, a free one will be determined
host: '0.0.0.0', // can be overwritten by process.env.HOST
port: 9000, // can be overwritten by process.env.PORT, if port is in use, a free one will be determined

/app # npm run dev
```

## access web

[http://localhost:9000](http://localhost:9000)
