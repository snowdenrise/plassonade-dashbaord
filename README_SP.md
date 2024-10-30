# Dashboard de Plassonade
El padre de la Inteligencia Ambiental (AmI), Mark Weiser, dijo:
> Las tecnologías más profundas son aquellas que desaparecen. Se entrelazan en el tejido de la vida cotidiana hasta que son indistinguibles de ella.

La intención detrás de este dashboard es mostrar solo la información necesaria (no datos crudos) de manera concisa y comprensible para el usuario final del "Hogar Inteligente / Smart Home".

En un "Hogar Inteligente / Smart Home" ideal, los dashboards no serían necesarios. Sin embargo, hay momentos en los que todavía necesitas tomar tu teléfono inteligente para ajustar algunas cosas. 

¡Así que hagamos un dashboard genial!

🚧 Esto es un trabajo en progreso, actualizaré este repositorio regularmente a medida que el dashboard cambie 🚧

## Disclaimer

This dashboard's code is provided as-is. It is up to you to modify the entities' names (sensors and devices) to make it work.

## Requirements
- [HACS] (not forcefully needed but it's gonna help you install most of the following requirements automatically)
- [Mushroom cards]
- [Stack in cards]
- [Simple thermostat]
- [Mini graph card]
- [Card Mod]

[HACS]: <https://hacs.xyz/>
[Mushroom cards]: <https://github.com/piitaya/lovelace-mushroom>
[Stack in cards]: <https://github.com/custom-cards/stack-in-card>
[Simple thermostat]: <https://github.com/nervetattoo/simple-thermostat>
[Mini graph card]: <https://github.com/kalkih/mini-graph-card>
[Card  Mod]: <https://github.com/thomasloven/lovelace-card-mod>

## Want to replicate my setup?

I've put all the items I'm using in my Smart Home on my Amazon page.

Select the appropriate marketplace:<br />
[🇺🇸 Amazon USA]<br />
[🇫🇷 Amazon France]<br />
[🇮🇹 Amazon Italia]<br />
[🇩🇪 Amazon Deutschland]<br />

[🇺🇸 Amazon USA]: <https://amazon.com/shop/plassonade>
[🇫🇷 Amazon France]: <https://amazon.fr/shop/plassonade>
[🇮🇹 Amazon Italia]: <https://amazon.it/shop/plassonade>
[🇩🇪 Amazon Deutschland]: <https://amazon.de/shop/plassonade>


If you order from here, it won't cost you anything more but I will receive a small commission from your purchases. Thanks for your support!

## Room card

![Room card](room_card/room_card.jpg)

The intention was to have a functional and minimal card to check the status of each room at a glance.
It is also a shortcut to a more detailed view (dashboard) for each room, which is perfect for a small screen (smartphone) display.
I've designed a small card, that I duplicated for each room, and all put together in a grid component.

Each card displays:
- The light state of the room (if any light is on, the room logo will be lit up to the color of the lights);
- The temperature of the specific room;
- If presence is detected or not in that room.

Controls:
- By clicking on the room you can turn on/off the lights inside it;
- Clicking on the arrow will redirect you to the approriate dashboard.

To make this work, you just need to replace the entities for each of your rooms and copy/paste the card in the grid if you have more rooms to manage.
Also, you need to create a dashboard for each room that you will navigate to when tapping on the arrow.


## Climate control and Weather card

![Climate control and Weather card](climate_card/climate_card.png)

The goal was to concatenate a few things into a single card:
- Air conditioning control and status (on/off/heat/cold/dry/temperature);
- Air conditioning presets (none/eco/boost);
- Inside temperature vs. outside temperature;
- Local weather: temperature and conditions;
- Possibility to turn on/off an automation*

*This automation allows me to turn on and off the A/C if presence is detected, and automatically adjust the temperature depending on how far residents are from the A/C.

## Media control

Work in progress...

## Lights control

Work in progress...

## Tech stats, server metrics

Work in progress...

## Residents status and location

Work in progress...


## Shades, Roller shutters control

Work in progress...




## Need help?

Feel free to ask your questions on our Discord community, The Smart Playground.
[You can join it for free here].

[You can join it for free here]: <https://plassonade.com/links>
