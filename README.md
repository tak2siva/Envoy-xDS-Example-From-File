This example is using Envoy-Pilot xDS Server (https://github.com/tak2siva/Envoy-Pilot) to load config from file

This docker compose setup contains:

    - Envoy (port: 10000)
    - App1 (port: 8123)

To start 
```
docker-compose up
```

Verify by 

```
curl http://localhost:10000
this is app --ONE--
```
