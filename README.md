I have added the retained flag for the MySensors MQTT Gateway.
You have to replace the file Arduino/libraries/MySensors/core/MyGatewayTransportMQTTClient.cpp with this one and add the following line into the Arduino Gateway ino file:
# #define MY_MQTT_RETAINED true
If you do not want to enable the retain flag, do not insert this line or set the value to "false"
