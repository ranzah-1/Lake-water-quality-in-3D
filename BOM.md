# Bill of Materials

|Component|Use|Draw|
|-|-|-|
[Raft micro computer](https://docs.arduino.cc/hardware/due/)||
|[Arduino Due](https://www.amazon.se/Arduino-AG-utvecklingskort-Due-A000062/dp/B08933P95J?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=ANU9KP01APNAG)|Microcontroller for underwater|7V-12V|
[Turbidity sensor](https://www.rikasensor.com/rk500-07-ss-turbidity-sensor.html) [(alt2)](https://www.electrokit.com/grumlighetssensor-analog) [Farnells](https://se.farnell.com/seeed-studio/101020752/turbidity-sensor-board-arduino/dp/4007740)|Measure water clarity||
[Temperature sensor](https://www.elbutik.se/product.html/shelly-ds18b20-temperatursensor?msclkid=df07bc15ebfb17916f10d4d63b7faed5&utm_source=bing&utm_medium=cpc&utm_campaign=Viva+-+Shopping&utm_term=4587574838336733&utm_content=Ad+group+%231) [Farnell](https://se.farnell.com/dfrobot/dfr0198/temp-sensor-probe-6mm-x-35mm-ss/dp/3517904)|Measure water temperature||
[Dissolved oxygen](https://se.farnell.com/dfrobot/sen0237-a/dev-kit-analog-dissolved-oxygen/dp/3517931)|Ammount of oxygen available to life||
[PH sensor](https://se.farnell.com/dfrobot/sen0169/anal-ph-sensor-meter-pro-kit-arduino/dp/3517876)||
|[TDS (Total Dissolved Solids)](https://se.farnell.com/dfrobot/sen0244/analogue-tds-sensor-meter-kit/dp/3517934)|Measure water cleanness||
|[Hall effect sensor](https://www.electrokit.com/tlv49645-sip-3-hall-effektsensor-digital?gad_source=1&gad_campaignid=17338847491&gbraid=0AAAAAD_OrGN7ekLvdRKENoxCQ38xOgkfL&gclid=CjwKCAjwiY_GBhBEEiwAFaghvvtc5-3xuZx12bOuwTdUgIruGaBNhWvSB5BtiQO6VNAnJ_LaX2MxmBoCMSQQAvD_BwE) |Calculate depth of sensor platform||
|Pulley|Lower sensor platform||
|[DC motor](https://www.biltema.se/bil---mc/lasta-och-dra/transporttillbehor/elektriska-vinschar/elvinsch-12-v-907-kg-2000042426?utm_source=google&utm_medium=cpc&utm_campaign=p-shopping-LIA-mid&gad_source=1&gad_campaignid=1603792037&gbraid=0AAAAADowiYi8V4ggsYYD4R_vxDRMR9FQR&gclid=Cj0KCQjwoP_FBhDFARIsANPG24PgOhgRuM1j2egWvMcDXaO6lrkzRsuYV2femD6pD6_SUT8Prufzs9IaAtKREALw_wcB)|Motor for pulley||
|[Water Proof Casing](https://bluerobotics.com/store/watertight-enclosures/wte-vp/)|Can handle up to 1000m depth||
|[Bulkhead Seal](https://bluerobotics.com/store/cables-connectors/penetrators/wlp-vp/)|To expose sensor to water, can handle 1000m depth||
# Turbidity Sensor - Bill of Materials (BOM)

Active Components
| Qty | Part Number | Description | Digi-Key Link |
|-----|-------------|-------------|---------------|
| 4 | TLC271ACD | Op-Amp SOIC-8 | [Link](https://www.digikey.se/en/products/detail/texas-instruments/TLC271ACD/374879) |
| 2 | 2N7002LT1G | N-MOSFET SOT-23 | [Link](https://www.digikey.se/en/products/detail/onsemi/2N7002/244345) |

 Potentiometers
| Qty | Part Number | Value | Digi-Key Link |
|-----|-------------|-------|---------------|
| 2 | PVG5A104C03R00 | 100kΩ | [Link](https://www.digikey.se/en/products/detail/bourns-inc/PVG5A104C03R00/666289) |
| 2 | PVG5A501C03R00 | 500Ω | [Link](https://www.digikey.se/en/products/detail/bourns-inc/PVG5A501C03R00/666298) |

 Resistors (0603)
| Qty | Part Number | Value | Digi-Key Link |
|-----|-------------|-------|---------------|
| 4 | RC0603FR-074K7L | 4.7kΩ | [Link](https://www.digikey.se/en/products/detail/yageo/RC0603FR-074K7L/727212) |
| 4 | RC0603FR-071K2L | 1.2kΩ | [Link](https://www.digikey.se/en/products/detail/yageo/RC0603FR-071K2L/726852) |
| 2 | RC0603FR-07100RL | 100Ω | [Link](https://www.digikey.se/en/products/detail/yageo/RC0603FR-07100RL/726888) |
| 2 | RC0603FR-0720RL | 20Ω | [Link](https://www.digikey.se/en/products/detail/yageo/RC0603FR-0720RL/727039) |
| 2 | RC0603FR-07270RL | 270Ω | [Link](https://www.digikey.se/en/products/detail/yageo/RC0603FR-07270RL/727103) |
| 2 | RC0603FR-0713K7L | 13.7kΩ | [Link](https://www.digikey.se/en/products/detail/yageo/RC0603FR-0713K7L/726933) |

 Capacitors (0805)
| Qty | Part Number | Value | Type | Link |
|-----|-------------|-------|------|------|
| 2 | CL21B223KBANNNC | 22nF | X7R | [Link](https://www.digikey.se/en/products/detail/samsung-electro-mechanics/CL21B223KBANNNC/3886739) |
| 2 | CL21B105KAFNNNE | 1µF | X7R | [Link](https://www.digikey.se/en/products/detail/samsung-electro-mechanics/CL21B105KAFNNNE/3886724) |
| 1 | C0805C339DCGACTU | 3.3pF | C0G | [Link](https://se.farnell.com/kemet/c0805c339dcgactu/cap-3-3pf-500v-c0g-np0-0805/dp/2821038) |
| 1 | C0805C101J5GACTU | 100pF | C0G | [Link](https://www.digikey.se/en/products/detail/kemet/C0805C101J5GACTU/411121) |

 Diodes
| Qty | Part Number | Description | Digi-Key Link |
|-----|-------------|-------------|---------------|
| 1 | BAT54,235 | Schottky SOD-323 | [Link](https://www.digikey.se/en/products/detail/diotec-semiconductor/BAT54/13163463) |

 LEDs - Indicator
| Qty | Part Number | Color | Package | Digi-Key Link |
|-----|-------------|-------|---------|---------------|
| 1 | APT1608SECK | Orange | 0603 | [Link](https://www.digikey.se/en/products/detail/kingbright/APT1608SECK/1747518) |

LEDs - Infrared
| Qty | Part Number | Wavelength | Angle | Digi-Key Link |
|-----|-------------|------------|-------|---------------|
| 2 | WP7113SF6C | 860nm | 20° | [Link](https://www.digikey.se/en/products/detail/kingbright/WP7113SF6C/8591570) |
| 1 | SFH 4855 | 850nm | 16° | [Link](https://www.digikey.se/en/products/detail/ams-osram-usa-inc/SFH-4855/5719277) |
| 1 | LiteOn E2871 | 940nm | 16° | [Datasheet](https://optoelectronics.liteon.com/upload/download/DS-50-92-0005/E2871.pdf) |
| 2 | TSAL6100 | 940nm | 20° | [Link](https://www.digikey.se/en/products/detail/vishay-semiconductor-opto-division/TSAL6100/1681338) |

 Photodiodes
| Qty | Part Number | Peak λ | Photocurrent | Digi-Key Link |
|-----|-------------|--------|--------------|---------------|
| 2 | BPW 34 S-Z | 850nm | 80µA | [Link](https://www.digikey.se/en/products/detail/ams-osram-usa-inc/BPW-34-S-Z/1893856) |

---


