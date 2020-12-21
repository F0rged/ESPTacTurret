# ESPTacTurret

This project aims to create an automated turret capable of engaging targets on its own. The main components of the solution's architecture will consist of:

* A 2 axis ceiling mounted turret built using a Wemos D1 mini clone (ESP8266 12-E), stepper motors, and 3d printed parts.

* Home Assistant & ESPHome This will handle the majority of the solution's logic. Home assistant will consume the RTSP stream from the Unifi NVR, route images through Deepstack and then control the camera via ESPHome.

* Deepstack AI This will handle the image analysis from the cameras and seek out people.

* Unifi G3 Flex & Unifi NVR The camera will be mounted to the turret and will be used to capture the video feed for the camera

* External IR Illuminator For additional IR light to help the camera.
