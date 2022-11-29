<h1 align="center">
  <br>
  <img src="https://github.com/Ks89/air-conditioner/blob/master/docs/icons/logo512.png?raw=true" alt="ks89/home-anthill" width="220">
  <br>
  <br>
Home Anthill
  <br>
</h1>

home-anthill is a project to control your home remotely with ESP32 devices.

There are 2 types of devices that I call in this way:
- `devices`: ESP32 devices to control something, like Air Conditioners.
- `sensors`: ESP32 devices to read physical phenomenons like temperature, humidity, air quality.

At the moment, the only supported `device` is the one to control `Beko air conditioner (Remote type: RG52A9/BGEF)`,
but you can modify the firmware changing the protocol to control you specific model, if supported by [`crankyoldgit/IRremoteESP8266`](https://github.com/crankyoldgit/IRremoteESP8266).

`Sensors` can read temperature, humidity, light (lux), air quality, motion, air pressure.
Feel free to extend this project to match your requirements.


## **Full documentation [HERE](https://github.com/home-anthill/docs)**
