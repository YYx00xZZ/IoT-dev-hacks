# IoT-dev-hacks
different way for the same

[ hook-to-ch340-nodemcuV3](/hook-to-ch340-nodemcuV3)
Записваме празна скица на NodeMCU v.3 с Arduino IDE;
(виж приложената схема)
Качваме код на ESP-12N по обичайния начин

Това което правим е, че изключваме(EN -> GND) wiFi модула на NodeMCU и на негово място "прикачваме" целевия модул. На практика използваме серийния чип от NodeMCU-то (и още няколко елемента,например voltage regulator,бутоните RST и FLASH.. т.н.) за да програмираме втори чип.
