# MQTT-broker

Installing Mosquitto broker

```python
sudo apt-get install mosquitto
sudo apt-get install mosquitto-clients
```

MQTT is based on publish subscribe messaging pattern

Subscribe to topic "temperature"

```python
mosquitto_sub -t "temperature"
```
