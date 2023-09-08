## Interact with the API
`curl http://localhost:8080/TianMiao/api/users`

`curl -X POST -H 'Content-Type: application/json' -d '{"username": "test"}'  http://localhost:8080/TianMiao/api/users`

`curl http://localhost:8080/TianMiao/api/users/1`

`curl -X PUT -H 'Content-Type: application/json' -d '{"username": "newUser"}' http://localhost:8080/TianMiao/api/notes/`


based on https://github.com/joe-elliott/tempo-springboot-example