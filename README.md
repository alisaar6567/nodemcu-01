# nodemcu-01

**Hej och välkommen!**

"Här är kort förklaring på vad jag har lärt mig denna vecka."


## Blinkprogram på NordeMCU (ESP8266)

 **Översikt**
Ett blinkprogram är det första och enklaste programmet man brukar köra på en mikrokontroller. 
Det får den **inbyggda LED-Lampan** på NodeMCU att blinka med ett intervall 
Syftet är:
- testa att mikrokontrollern fungerar
- lära sig Arduion-grund: setup () och loop ()
- lära sig styra en digital utgång

## Här ett basic kodexemple 
<img width="864" height="557" alt="Screenshot 2025-11-26 at 21 33 06" src="https://github.com/user-attachments/assets/f9b0c20e-6624-413e-a31f-6b46aec37608" />

**vad koden betyder**

setup()

- körs en gång när kortet startar
- vi talar om att LED-pinnen ska vara en utgång

loop ()

- körs om och om igen
- tänder LED
- väntar 0,5 sek
- släcker LED
- väntar 0,5 sek


På ESP8266 är LED: en kopplad "omvänt".
- LOW = tända LED
- HIGH = släck LED
  
  

## Mikroprocessor ESP8266

ESP8266 är perfekt för nybörjarprojekt. En liten, billig och kraftfull mikrokontroller. en mikrokontroller är som en liten dator i ett enda chip, det kan läsa signaler, köra kod och styra elektronik.

 Vad är ESP8266:
- Wifi-mikrokontroller
- sitter på NodeMCU
- Standard för många IoT-projekt

Vad ESP8266 kan erbjuda:
- läsa digitala signaler (LOW/HIGH)
- styra LED- lampor, sensorer, motorer
- köra Arduino kord
- koppla upp sig mot Wifi och skicka data
___
Bild på nodeMCU ESP8266
<img width="900" height="800" alt="png-clipart-microcontroller-nodemcu-esp8266-arduino-wi-fi-esp8266-electronics-data" src="https://github.com/user-attachments/assets/14c6a1f6-54f7-4a2a-b15c-57170fc3bca3" />

