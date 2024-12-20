### This is a demo of using docker compose for Home Assistant + MQTT Broker (mosquitto)
```bash
cp -r ./etc /etc   # copy config from project to host

docker compose down
docker compose up --force-recreate
docker compose restart
```
