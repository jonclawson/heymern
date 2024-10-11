# heymern
A MERN Generation Script

Creates a fullstack MERN app housed inside 3 containers, React Container, Express Container and Mongo.

Installation:

Run the script.
`$ ./heymern.sh `

Generates a file structure that looks like this.

```
mern-docker-app/
├── client/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── App.js
│   │   └── index.js
│   ├── Dockerfile
│   └── package.json
├── server/
│   ├── src/
│   │   └── index.js
│   ├── Dockerfile
│   └── package.json
├── docker-compose.yml
├── docker-compose.prod.yml
└── .dockerignore
```

`$ cd mern-docker-app`
`$ docker comose up`

Serves at localhost:3000
