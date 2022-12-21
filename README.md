# Chytrý ovladač pro RobZone Roomy Gold

## Informace
> Chytrý ovladač, který běží na ESP8266. Ovládá "hloupý" robotický vysavač pomocí IR a přijímá příkazy skrze MQTT. Vytvořeno na vysavač RobZone Roomy Gold.

## Použitý hardware
> ESP8266 Wemos D1 mini
> IR Přijímač
> IR Vysílač
> Step down konvertor (ze 14.4V na 3.3V || 5V)

## Zapojení
![schéma](https://user-images.githubusercontent.com/23415613/208913927-9d9c9d64-9128-4449-93c8-446be5c132db.png)

## Postup řešení - WIP
> - Pomocí IR vysílače získat data, která posílá klasický ovladač k robotovi
> - Naprogramovat IR vysílač, který bude získané kódy posílat robotovi
> - Naprogramovat MQTT, aby byla lehká integrace do Home Assistenta
> - Propojit chytrý ovladač s baterii co má robot, umístení ovladače bude na robotovi směrem k jeho IR příjmači
