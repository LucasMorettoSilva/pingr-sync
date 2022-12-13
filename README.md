# pingr-sync

Pingr system implemented in synchronous communication pattern. This system contains two microservices:
`sync-ms-connection` and `sync-ms-chat`.

### Run the system

To run the system inside containers you can do:

```sh
docker-compose up
```

Once the system is up and running, each microservice will expose its API through a Swagger Client.
The Connection API can be accessed through [http://localhost:8080](http://localhost:8080). The Chat
API can be acessed through [http://localhost:9086](http://localhost:9086).
