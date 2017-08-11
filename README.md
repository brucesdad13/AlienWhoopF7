![IMAGE AlienWhoop F7 Flight Controller Welcome](https://scontent-iad3-1.xx.fbcdn.net/v/t1.0-9/20375760_1452516294794035_3452827763551447574_n.png?oh=ce87191ab286e5735aee62b3992636ee&oe=5A38B747)

# AlienWhoopF7 Features :alien:
AlienWhoop flight controller for Tiny Whoop, Blade Inductrix, Eachine, BetaFPV, and other micro brushed quadcopter frames. Best in class flight controller running BetaFlight 3.2 release candidate (upgradable)--surface mount soldering required.

* Choice of the top performing ARM processors: 
  * High-performance ST Microelectronics ARM Cortex-M4 core F4 168 MHz CPU
  * High-performance ST Microelectronics ARM Cortex-M7 core F7 216 MHz CPU
     *(NOTE: STM32 F7 availability has been hit or miss in 2017. Some vendors have them in stock after a 2 month drought)*
* Choice of top performing motion processors: 
  * Invensense MPU-6500 Six-Axis (Gyro + Accelerometer) low power consumption MEMS MotionTracking™ Device
  * Invensense MPU-9250 Nine-Axis (Gyro + Accelerometer + Compass) low power consumption MEMS MotionTracking™ Device
* Latest BetaFlight firmware running the ALIENWHOOPF4 or ALIENWHOOPF7 target. Capable of 32kHz gyro sampling and potentially 32kHz PID loop when overclocking for F4 is released with BetaFlight 3.2 (*32kHz gyro sampling rate has been flown on prototypes for several months now at up to 16kHz PID loop without overclocking the F4*).
* Fairchild Semiconductor FDMA410NZ MOSFET with 9.5A continuous and 24A burst brushed motor insanity (8.5mm coreless scream)
* UART4 solder pads for programmable LED strip (SUPER COOL) using WS2812B RGB or RX/TX for Micro MinimOSD
* Choice of external receivers. Officially supporting FrSky XM and XM+ and LemonRX DSM2 and DSMX satellites--FlySky iBUS undergoing testing.

## DIY Flight Controller :alien:
If you fancy doing it yourself (DIY), and have the right equipment and patience, building an AlienWhoop from scratch can be tremendously satisfying--though not for the faint of heart. After doing your homework the first step is to place an order for blank PCBs from [OSH Park](https://oshpark.com/shared_projects/m61Bc99Q):
* We recommend ordering the 2oz copper 0.8mm thickness PCB
  * *It takes about three weeks to make the thin boards which allows plenty of time to order components from the bill of materials in the resources folder.*
  * **Please note there are slight changes to the bill of materials (BOM) depending which MCU you choose (F4 vs F7). These MCUs are not 100% pin compatible.**
   * F4: components C7 and C10 place 4.7uF ceramic capacitors and C15 substitute 0 ohm resistor (0R).
   * F7: components C7 and C10 substitute 0 ohm resistor and C15 place 4.7uF ceramic capacitor.

## Official Facebook page :alien:
AlienWhoop has a Facebook page and it's our preferred way to engage with you and keep you updated. Please Like and/or Follow Us for regular updates in your status feed related to AlienWhoop, DIY electronics, and micro brushed quadcopter related posts.
* http://fb.me/alienwhoop/

## See the AlienWhoop F7 in action on YouTube :alien:

[![IMAGE AlienWhoop Race Track](https://img.youtube.com/vi/VbBsdTQpdaE/0.jpg)](https://www.youtube.com/watch?v=VbBsdTQpdaE&t=5s)

[![IMAGE AlienWhoop 7mm Disco ](https://img.youtube.com/vi/Ov4fFRiZYsI/0.jpg)](https://youtu.be/Ov4fFRiZYsI)

May this work be of benefit and bring much joy and happiness!

## Acknowledgements :alien:

Deep bows of appreciation and thanks to Lance for his original work and tremendous
generosity in releasing his labor of love for the benefit of all flight controller
enthusiasts. Check out AlienWhoop's ancestry in our preserved copy of Lance's original AlienFlight
github repository of open source hardware flight controllers: the [Classic FC aka Classic Narrow](https://github.com/brucesdad13/AlienFlightArchive/blob/master/Flight-Controllers/Classic#narrow-classic-flight-controller), [F3 Quad FC](https://github.com/brucesdad13/AlienFlightArchive/blob/master/Flight-Controllers/F3-V1/F3-Quad#f3-quad-brushed-v1-flight-controller), [F3 Hexa FC](https://github.com/brucesdad13/AlienFlightArchive/blob/master/Flight-Controllers/F3-V1/F3-Hexa#f3-hexa-brushed-v1-flight-controller), and [F3 Octo FC](https://github.com/brucesdad13/AlienFlightArchive/blob/master/Flight-Controllers/F3-V1/F3-Octo#f3-octo-brushed-v1-flight-controller).
*As of late July 2017, the original www.alienflight.com site is no longer in operation.

Equally deep bows to Jesse Perkins, creator of Tiny Whoop, and the source of inspiration and love for tiny brushed quads.
* http://www.tinywhoop.com/ ~
* https://www.facebook.com/groups/tinywhoop/ ~

Appreciation and respect also goes out to the dedicated BetaFlight software developers including @jflyper, Michael Jakob (MJ666), Michael Keller (@mikeller), Martin Budden (martinbudden), J Blackman (blckmn), and certainly Boris. Special thanks to Michael Jakob (MJ666) for clearing up confusion on the MPU-9250 magnetometer / compass driver and for updating to MPU-6500 code to work with whichever MPU you decide upon 6500 or 9250 (with compass). And a huge thanks to @jflyper for enduring endless questions about the BetaFlight source code and STM32 architecture!

Others deserving thanks for answering questions include in no specific order (and many others):
* Peter (Pedro) Newman (AW Fan Club)
* Adam Madron (AW Fan Club)
* Joel Goetze (AW Fan Club)
* Gary Baynes (AFNG)
* Leon Salisbury (AFNG)
* Dan Sheadel (OSH Park)
* Matthew Navarro (GroupGets)

~ Please note: **AlienWhoop** is not affiliated with nor endorsed by AlienFlight or forks of Lance's work such as AlienFlight NG. The use of Alien in the name and the alien head vector graphic used on the board silkscreen are nods to the lineage of this remix and to the work of Lance and others who created the conditions for this project to arise. Likewise, AlienWhoop is not affiliated with nor endorsed by Tiny Whoop. The Whoop in the name comes from Jesse Perkin's fantastic Tiny Whoop ("a small first-person-view aircraft that truly allows you to feel the gift of flight and the feeling of being tiny" [tinywhoop.com]) and is simply a nod to his efforts and the TW community worldwide.

## If you like this project and want to support further development
* https://paypal.me/AlienWhoop/ <a href="https://paypal.me/AlienWhoop/"><img src="https://camo.githubusercontent.com/bf75919b94531ffe3b83ca1249b33a6ece815232/68747470733a2f2f7777772e70617970616c2e636f6d2f656e5f55532f692f62746e2f62746e5f646f6e6174655f4c472e676966" border="0" name="user-content-submit" title="PayPal - The safer, easier way to pay online!" alt="Donate" data-canonical-src="https://www.paypal.com/en_US/i/btn/btn_donate_LG.gif" style="max-width:100%;"></a>
