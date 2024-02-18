---
title: Taser Russian Roulette
publishDate: 2022-11-10 19:42:55
img: /assets/work/trr.jpg
img_alt: Arduino with a shocking gum attached to it.
description: |
  As a university project, Taser Russian Roulette is a game that I made using an Arduino Pro Micro, a shocking gum, a button, and an RFID module. The game is as fun as the real deal, but without the risk of dying... 👀
tags:
  - Arduino
  - PlatformIO
  - RFID
  - Taser
  - Game
---

Russian Roulette, but nobody dies!

Taser Russian Roulette is, as the name implies, a game of Russian Roulette, but with a taser rather than pistols.

## Project description

I made the Roulette using the popular ["chewing gum"](https://www.amazon.com/Shot-Electric-Chewing-Shocking-Gadget/dp/B00T60U5YQ) some of us had as kids and I chose to use RFID cards and tags as _"the bullets"_.

## How 2 build

For this project, the following components were used:

- Arduino Pro Micro development board
- RC522 RFID Reader module
- Chewing shocking gum
- Push Button
- LED

Following are the circuit diagram and two photos of my "build".

## How 2 play

Gather 'round and shuffle the RFID cards and tags. Each player gets a card or a tag. Then, one scans the card/tag, grips the conductive pad and presses the button. Should the card be a __bullet card__, the player _dies_. If the card is a __safe card__, the player _lives_.

The LED stays on as long as the card is valid. If the button is not pressed, the LED goes off and the previously scanned card is discarded.

`-> GL HF!`

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](https://github.com/TudorRadoni/taser-russian-roulette/blob/main/LICENSE) file.
