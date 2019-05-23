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

Open another terminal and publish to the topic "temperature"

```python
mosquitto_pub -m "temperature exceeds 50 deg C" -t "temperature"
```

Secure MQTT server with a password

