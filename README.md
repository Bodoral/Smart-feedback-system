# Smart-feedback-system
This project replaces traditional buttons in Feedback machines with smart sensors.the python codes catchs readings from PIRs (passive infrared sensors) and Raspberry Pi and then send reading to Azure cloud:
- In Smart Feedback System- Azure.py  
file: to Azure cloud IoT hub, then visualize it by Power BI.
- In Smart Feedback System- Adafruit.py  
file: to io.adafruit and disply viualizes in the dashboard.

### Notes
In System- Azure.py replace the what is between '[]' according to your Azure account as stated below:
```
# Azure IoT Hub

URI = '[your_iot_hub].azure-devices.net'
KEY = '[iothubowner Primary Key]'
IOT_DEVICE_ID = 'ID of the registered IoT device within IoT Hub'
POLICY = 'iothubowner'
```


In Adafruit.py replace the 'Client' arguments with your IO.adafruit 'Username' and 'Active Key' receptively:

```
aio=Client( '[UserName]', '[Active Key]')
```
