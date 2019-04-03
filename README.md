# UM66T Melody Generator
An UM66T generates various Melody Tunes when triggered which can be used in car/scooter reverse signals, doorbells and toys.

**Order PCB:**

## Electronic Components
| Qty | Component | Buy |
| ------------- | ------------- | ------------- |
| 1 | IC UM66T |[AliExpress](http://s.click.aliexpress.com/e/tNfC3kG) |
| 1 | 100Ω 220Ω 4.7KΩ Resistor |[AliExpress](http://s.click.aliexpress.com/e/bh4eqrQs) |
| 1 | BC547 Transistor |[AliExpress](http://s.click.aliexpress.com/e/cYm6Rss0) |
| 1 | SPDT Slide Switch |[AliExpress](http://s.click.aliexpress.com/e/cAs918wG) |
| 1 | 5mm LED |[AliExpress](http://s.click.aliexpress.com/e/wuFpLXS) |
| 1 | 100uF Capacitor |[AliExpress](http://s.click.aliexpress.com/e/c9FHzl5W) |
| 1 | 0.1uF Capacitor |[AliExpress](http://s.click.aliexpress.com/e/SX7eHuG) |
| 1 | Speaker |[AliExpress](http://s.click.aliexpress.com/e/brMJh46c) |
| 1 | 5VDC Adapter |[AliExpress](http://s.click.aliexpress.com/e/V0x0bms) |
| 1 | PCB |[AliExpress](http://s.click.aliexpress.com/e/dhgwzKY) |


| Tools | Buy |
|--|--|
|Soldering Iron|[AliExpress](http://s.click.aliexpress.com/e/E83bSJI) |
|Soldering Wire|[AliExpress](http://s.click.aliexpress.com/e/PdhB0nm) |
|Mini PCB Hand Drill + Bits|[AliExpress](http://s.click.aliexpress.com/e/b93tomjI) |

## Working
**UM66T:**

The UM66T is an CMOS LSI designed for musical applications and has an on-chip ROM
containing a musical tune. The deice has very low power consumption (around 180mW)
since it is fabricated using the CMOS process. The IC includes an inbuilt oscillation
circuit. Hence a compact melody module can be constructed with only a few additional
components.

![Pinout](https://github.com/jonathanrjpereira/UM66T-Melody-Generator/blob/master/img/pinout.png)
![Pin Description](https://github.com/jonathanrjpereira/UM66T-Melody-Generator/blob/master/img/pindescription.png)

![Block Diagram](https://github.com/jonathanrjpereira/UM66T-Melody-Generator/blob/master/img/BD.png)

An input trigger enables the tone generator unit which in turn drives an external speaker unit.
The tone generator unit consists of the Oscillator, Rhythm generator, Tempo generator and ROM.
The oscillator frequency is used as a time for tone and beat generators. Its accuracy affects the quality of the
music.

![Schematic](https://github.com/jonathanrjpereira/UM66T-Melody-Generator/blob/master/img/sch.png)

A 5VDC power adapter is used as the power supply. Since the UM66T has a maximum supply voltage of 4.5V,
a 100Ω resistor is used to reduce the supply voltage to a suitable 3.3V.
When the SPDT slide switch is turned ON, the UM66T is triggered and produces a melody signal that begins
from the first note due to the power on reset feature. An external transistor amplifies the signal and it's output is
connected to a speaker. An LED turns on whenever the circuit is triggered.

## Contributing🛠
Are you an engineer or hobbyist who has a great idea for a new feature in this project? Maybe you have a good idea for a bug fix? Feel free to grab our code & schematics from GitHub and tinker with it. Don't forget to smash ⭐️ & the Pull Request button.

[![alt text][1.1]][1] [![alt text][2.1]][2] [![alt text][3.1]][3]

[1.1]: https://github.com/jonathanrjpereira/Social-Media-README/blob/master/youtube.png (YouTube)
[2.1]: https://github.com/jonathanrjpereira/Social-Media-README/blob/master/instagram.png (Instagram)
[3.1]: https://github.com/jonathanrjpereira/Social-Media-README/blob/master/github.png (GitHub)

[1]: https://www.youtube.com/channel/UCRW-41O1vy98KKgJRQoYzdg
[2]: https://www.instagram.com/electroguruji/
[3]: https://github.com/jonathanrjpereira
