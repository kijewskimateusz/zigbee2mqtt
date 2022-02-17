# Zigbee2mqtt


In order to start project, please rename example.env file to .env file and provide required parameters:
```commandline
ZIGBEE2MQTT_CONFIG_MQTT_USER=user
ZIGBEE2MQTT_CONFIG_MQTT_PASSWORD=pass
ZIGBEE2MQTT_CONFIG_MQTT_SERVER=mqtt://1.1.1.1:1883
FRONTEND_PORT=8080
```

Docker-compose command: 
```commandline
docker-compose -p zigbee2mqtt -f docker-compose.yml -f example.docker-compose.dev.yml up -d
```

Git checkout to latest release tag: 
```commandline
git fetch --all --tags

Fetching origin
From git-repository
   98a14be..7a9ad7f  master     -> origin/master
 * [new tag]         v1.0       -> v1.0
```

```commandline
git checkout tags/<tag> -b <branch>

Switched to a new branch 'v1.0-branch'
```
[Source](https://devconnected.com/how-to-checkout-git-tags/)