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