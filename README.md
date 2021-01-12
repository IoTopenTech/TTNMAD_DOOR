# TTNMAD_DOOR

En este repositorio se recopila toda la información mecesaria para poner en funcionamiento el caso de uso TTNMAD_DOOR, que es un sensor de puerta/ventana abierta y temperatura, que envía sus datos mediante tecnología inalámbrica LoRa a la red pública The Things Network, y desde allí se integran en la plataforma my IoT open Tech (en lo sucesivo, myIoT), desde la que se pueden visualizar los datos y configurar alarmas.

- **Electrónica:** Es la correspondiente a la configuración básica del nodo TTN MAD V2.3 basado en Arduino y ampliado con las extensiones Hall y NTC, cuya información está disponible en https://github.com/IoTopenTech/Nodo_TTN_MAD_V2/wiki.
- **Firmware:** Se recomienda utilizar el programa [ttn_mad_v2_3_hall_ntc_heartbeat_OTAA](https://github.com/IoTopenTech/Nodo_TTN_MAD_V2/tree/master/software/ttn_mad_v2_3_hall_ntc_heartbeat_OTAA) que se une a la red utilizando "activación por el aire". No obstante, se ofrece también el programa [ttn_mad_v2_3_hall_ntc_heartbeat_ABP](https://github.com/IoTopenTech/Nodo_TTN_MAD_V2/tree/master/software/ttn_mad_v2_3_hall_ntc_heartbeat_ABP) como alternativa para unir el nodo a la red mediante "activación por personalización".
- **Carcasa 3D:** Los STL correspondientes a los elementos del nodo están disponibles en este mismo repositorio.
- **Integración con myIoT:** En este [vídeo](https://youtu.be/PtA9cxz3UNI) se explican los conceptos básicos de myIoT y cómo crear una integración desde The Things Network; al crear el dispositivo deberá elegir como tipo "TTNMAD_DOOR".

