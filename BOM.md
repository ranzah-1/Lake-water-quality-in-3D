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
|[Custom Turbidity Sensor PCB](#)|Measures turbidity (0–10 NTU range)| |
|[Op-Amp : TLC271ACD](https://www.digikey.se/en/products/detail/texas-instruments/TLC271ACD/374879)|Signal amplification| |
|[MOSFET : 2N7002](https://www.digikey.se/en/products/detail/onsemi/2N7002/244345)|LED current switching| |
|[100kΩ Trimmer : PVG5A104C03R00](https://www.digikey.se/en/products/detail/bourns-inc/PVG5A104C03R00/666289)|Calibration (gain adjust)| |
|[500Ω Trimmer : PVG5A501C03R00](https://www.digikey.se/en/products/detail/bourns-inc/PVG5A501C03R00/666298)|LED drive calibration| |
|[IR LED 860 nm : WP7113SF6C](https://www.digikey.se/en/products/detail/kingbright/WP7113SF6C/8591570)|Infrared light source| |
|[IR LED 850 nm : SFH 4855](https://www.digikey.se/en/products/detail/ams-osram-usa-inc/SFH-4855/5719277)|Infrared light source| |
|[IR LED 940 nm : TSAL6100](https://www.digikey.se/en/products/detail/vishay-semiconductor-opto-division/TSAL6100/1681338)|Infrared light source| |
|[Photodiode : BPW 34 S-Z](https://www.digikey.se/en/products/detail/ams-osram-usa-inc/BPW-34-S-Z/1893856)|IR receiver for turbidity| |
|[Photodiode : TEMD5110X01](https://www.digikey.se/en/products/detail/vishay-semiconductor-opto-division/TEMD5110X01/1681182)|Infrared light detector| |
|[22nF Capacitor : CL21B223KBANNNC](https://www.digikey.se/en/products/detail/samsung-electro-mechanics/CL21B223KBANNNC/3886739)|Filtering| |
|[1µF Capacitor : CL21B105KAFNNNE](https://www.digikey.se/en/products/detail/samsung-electro-mechanics/CL21B105KAFNNNE/3886724)|Filtering| |
|[Schottky Diode : BAT54](https://www.digikey.se/en/products/detail/diotec-semiconductor/BAT54/13163463)|Reverse protection| |
|[Indicator LED : APT1608SECK](https://www.digikey.se/en/products/detail/kingbright/APT1608SECK/1747518)|Power indicator| |
