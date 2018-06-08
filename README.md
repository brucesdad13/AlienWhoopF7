![IMAGE AlienWhoop F7 Flight Controller Welcome](https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/245f7ece5088c1945b2ad2335f7d4530.png)

# AlienWhoopF7 Features :alien:
AlienWhoop flight controller for Tiny Whoop, Blade Inductrix, Eachine, BetaFPV, and other micro brushed quadcopter frames. Best in class flight controller running BetaFlight or Butterflight--surface mount soldering required.

* Choice of the top performing ARM processors: 
  * High-performance ST Microelectronics ARM Cortex-M4 core F4 168 MHz CPU
  * High-performance ST Microelectronics ARM Cortex-M7 core F7 216 MHz CPU
* Choice of top performing motion processors: 
  * Invensense MPU-6500 Six-Axis (Gyro + Accelerometer) low power consumption MEMS MotionTracking™ Device
  * Invensense MPU-9250 Nine-Axis (Gyro + Accelerometer + Compass) low power consumption MEMS MotionTracking™ Device
* Latest BetaFlight firmware running the ALIENWHOOPF4 target
* Butterflight firmware supported (iNav under final testing)
* Overkill power MOSFETs capable of extreme brushed motor insanity (6mm, 7mm, 8mm, 8.5mm, and 10mm coreless scream)
* Multiple UARTs for receivers and other devices (e.g. LED strip, beeper)
* Dedicated UART with inverter for FrSky and Futaba SBUS
* UART pads on top conveniently located for SmartAudio VTX control
* Blackbox logging via onboard dataflash chip
* Note: pilots must supply external receiver. Officially supporting FrSky XM, XM+, R-XSR (SBUS,F.PORT), LemonRX DSM2 and DSMX (SBUS), and FlySky FS-A8S (iBUS) satellites.
* 0.8mm 2oz Copper ENIG (gold) finish purple PCBs from OSH Park recommended

## DIY Flight Controller :alien:
If you fancy doing it yourself (DIY), and have the right equipment and patience, building an AlienWhoop from scratch can be tremendously satisfying--though not for the faint of heart. After doing your homework the first step is to place an order for blank PCBs from [OSH Park](https://oshpark.com/shared_projects/p4hs6DbI):
* We recommend ordering the 2oz copper 0.8mm thickness PCB
  * *It takes about three weeks to make the thin boards which allows plenty of time to order components from the bill of materials in the resources folder.*
  * **Please note there are slight changes to the bill of materials (BOM) depending which MCU you choose (F4 vs F7). These MCUs are not 100% pin compatible.**
   * F4: components C7 and C10 place 4.7uF ceramic capacitors and C15 substitute 0 ohm resistor (0R).
   * F7: components C7, C10, and C15 place 4.7uF ceramic capacitor.

## Official AlienWhoop pages :alien:
AlienWhoop has many ways for you to stay engaged. Please Like and/or Follow Us for regular updates in your status feed related to AlienWhoop, DIY electronics, and micro brushed quadcopter related posts.
* http://fb.me/alienwhoop/ Facebook
* http://alienwhoop.us/ News and products
* http://alienwhoop.us/git-config CLI diff files for Betaflight and Butterflight
* http://alienwhoop.us/discord Join our Discord chat and hang out with the community or ask questions

## See the AlienWhoop in action on YouTube :alien:

[![IMAGE VelcroFPV Tinywhoop Invitational 2018 Best Run](https://img.youtube.com/vi/_v07IYvKqXY/0.jpg)](https://www.youtube.com/watch?v=_v07IYvKqXY)

[![IMAGE VelcroFPV AlienWhoop Build ](https://img.youtube.com/vi/SfvL05S8X-s/0.jpg)](https://www.youtube.com/watch?v=SfvL05S8X-s&t=30s)

May this work be of benefit and bring much joy and happiness!

## Acknowledgements :alien:

AlienWhoop V2.1 Dev Team:
* Charles Stevenson (brucesdad13)
* Travis Schrock (NotFastEnuf)
* Brian Pichardo (VelcroFPV)
* Michael Montiverdi (MontiFPV)

Deep bows of appreciation and thanks to Lance for his original work and tremendous
generosity in releasing his labor of love for the benefit of all flight controller
enthusiasts. Check out AlienWhoop's ancestry in our preserved copy of Lance's original AlienFlight
github repository of open source hardware flight controllers: the [Classic FC aka Classic Narrow](https://github.com/brucesdad13/AlienFlightArchive/blob/master/Flight-Controllers/Classic#narrow-classic-flight-controller), [F3 Quad FC](https://github.com/brucesdad13/AlienFlightArchive/blob/master/Flight-Controllers/F3-V1/F3-Quad#f3-quad-brushed-v1-flight-controller), [F3 Hexa FC](https://github.com/brucesdad13/AlienFlightArchive/blob/master/Flight-Controllers/F3-V1/F3-Hexa#f3-hexa-brushed-v1-flight-controller), and [F3 Octo FC](https://github.com/brucesdad13/AlienFlightArchive/blob/master/Flight-Controllers/F3-V1/F3-Octo#f3-octo-brushed-v1-flight-controller).
*As of late July 2017, the original www.alienflight.com site is no longer in operation.

Equally deep bows to Jesse Perkins, creator of Tiny Whoop, and the source of inspiration and love for tiny brushed quads.
* http://www.tinywhoop.com/ ~
* https://www.facebook.com/groups/tinywhoop/ ~

~ Please note: **AlienWhoop** is not affiliated with nor endorsed by AlienFlight or forks of Lance's work such as AlienFlight NG. The use of Alien in the name and the alien head vector graphic used on the board silkscreen are nods to the lineage of this remix and to the work of Lance and others who created the conditions for this project to arise. Likewise, AlienWhoop is not affiliated with nor endorsed by Tiny Whoop. The Whoop in the name comes from Jesse Perkin's fantastic Tiny Whoop ("a small first-person-view aircraft that truly allows you to feel the gift of flight and the feeling of being tiny" [tinywhoop.com]) and is simply a nod to his efforts and the TW community worldwide.

## If you like this project and want to support further development
* https://paypal.me/AlienWhoop/ <a href="https://paypal.me/AlienWhoop/"><img src="https://camo.githubusercontent.com/bf75919b94531ffe3b83ca1249b33a6ece815232/68747470733a2f2f7777772e70617970616c2e636f6d2f656e5f55532f692f62746e2f62746e5f646f6e6174655f4c472e676966" border="0" name="user-content-submit" title="PayPal - The safer, easier way to pay online!" alt="Donate" data-canonical-src="https://www.paypal.com/en_US/i/btn/btn_donate_LG.gif" style="max-width:100%;"></a>
* http://shop.alienwhoop.us/ for t-shirts and gear
