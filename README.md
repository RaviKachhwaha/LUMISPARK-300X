<h1 align="center">
  <br>
  <img src="https://github.com/RaviKachhwaha/LUMISPARK-300X/blob/main/docs/images/LUMISPARK-300X_schematic.png" alt="docs/images/LUMISPARK-300X_schematic.png">

  <br>
  LUMISPARK-300X
  <br>
</h1>
<h3 align="center">
A hand-wired Zero PCB power conditioner and 3-mode driver for 220V LED strips 
</h3>

Note :- At top cover image I will replace it with the completed Zero PCB after build.

| Front Render | Back Render | 
| --- | --- |
| ![](https://github.com/RaviKachhwaha/LUMISPARK-300X/blob/main/docs/images/LUMISPARK-300X_front_image..png) | ![](https://github.com/RaviKachhwaha/LUMISPARK-300X/blob/main/docs/images/LUMISPARK-300X_back_image..png) | 

Note:- The Image will come after build due to this will built on Zero PCB, So when I solder all components on PCB then the image is taken and uploaded to here!!

## Schematics  

Here are the schematic design,

![](https://github.com/RaviKachhwaha/LUMISPARK-300X/blob/main/docs/images/LUMISPARK-300X_schematic.png)

## Features
- **Multi-Stage AC Grid Armour** - A 1A 250V fast cartridge fuse paired with a 07D471K MOV for transient overvoltage surge clamping.
- **Thermal Inrush Soft-Start** - A 10D-9 NTC thermistor to suppresses turn on current spikes into the high-voltage capacitor bank.
- **Phase-Angle Dimming Engine** - BT136-600E TRIAC and DB3 DIAC to provide smooth 20% to 100% manual brightness control via a 500kohm's rotary photometer.
- **Dusk to Dawn Ambient Sensor** - A 5mm LDR with dedicated bypass rocker switch for automated sunset turn-on and dawn shutoff.
- **147µF 450V Dual Capacitive Hold-Up Bank** - This will delivers a 3 to 4 second cinema fade out and also bridges inverter switchover brownouts.
- **Switchable Output Modulation** - A dedicated SPST toggle selects between ripple free filtered DC and 50Hz festive sparkle shimmer.
- **Integrated High-Voltage Safety Bleeders** - The dual 470kohm's 1W resistors provide safe, automatic capacitor discharge upon AC disconnection.
- **Zero PCB Hand wireable Topology** - A laid out for single-sided 7.5×10cm prototyping boards with safe 5mm high-voltage creepage spacing.
- **Precision Dusk Sensitivity Calibration** - The dedicated 500kohm's trimmer potentiometer with a 4.7kΩ safety limiter to enable fine-tuning of the ambient sunset switching thresholds.

### The PCB is 4 layers with dimensions 75.00 x 100.00 mm, made to be easily useable for anyone.  

### PCB Schematic Design files are [here](https://github.com/RaviKachhwaha/LUMISPARK-300X/blob/main/hardware) 

## Pinout  

This is a general pinout 

| ![](https://github.com/RaviKachhwaha/LUMISPARK-300X/blob/main/docs/images/Pin_Outs..png) | 
| --- | 

Note :- This image will come after building the board over Zero PCB.

(Credits to KiCad EDA for KiCad 10, WeEn Semiconductors for the BT136 TRIAC, SAMWHA for the 450V hold-up capacitor, and Hack Club for funding to make this possible.)

## Why was it made?  

While using the normal old LED strip lights for many years for my many fetevials and in some times need, I realised it doesn't have safty, some control, watterprof and quality and I couldn't use it in rainfall, unfortunately I had to think to buy a different high power LED Light Strip with this board built-in then I see that those have waterprof and my board like board built-in but cost is very high and not have my needed full control over every thing and use very low price components which give low quality, but now I designed one with many simplicity's and have full control ever it and the top most need of safty.
It will also build my soldering skills more best and perfect.

## How you can get one for yourself? 

That is pretty easy, you have all the files you will need in the hardware folder, order the compoents and BOM list items and solder them by your self on Zero PCB and BINGO! You will have it to use for any purpose you want!  

## How do you use it?  
You can use it as any normal LED Strip light with board but first you want to connect the board output wires to the LED input pins and then plug the board input wire to your wall plug and set the LDR sensitivity using the RV3 potentiometer according to your need and you are good to go!
It doedn't require any firmware.

## BOM  
|Name|Purpose          |Quantity|Total Cost (USD)|Link               |Distributor|
|----|-----------------|--------|----------------|-------------------|-----------|
|General Purpose Printed Mini Zero PCB Board |To place every component over it and hand solder them using soldering Iron|1       |1.85           |[Zero PCB](https://www.amazon.in/dp/B0CJJJLB2P)|Amazon India     |
|Components|Needed components to place over Zero PCB and build the working board|1       |31.22           |[Amazon India](https://www.amazon.in)|Amazon India     |
|LED Rope Light 30 Meter |The board is build for this LED lighting so this is needed to test the board is working or not|1       |9.96          |[LED Rope Light](https://www.amazon.in/dp/B0HH3TVCW8)|Amazon India     |
|Soldering Wire and Flux |To solder the components over the board and flux to make soldering perfect and strong|1       |4.26           |[Soldering Wire with Flux](https://www.amazon.in/VMTRONIX-Solder-Welfix-Soldering-Rosin-Rich/dp/B0D7ZB2H93)| Amazon India     |
|Wire|Wire is needed to joint the board input to wall plug and the output to the LED input|1       |6.81           |[Wire](https://www.amazon.in/CabONE-Insulated-Electrical-Household-Industrial/dp/B0F2N6WNSW)| Amazon India     |
| | | Total | 54.10 |

LCSC & DigiKey BOM for the components on board is [here](https://github.com/RaviKachhwaha/LUMISPARK-300X/blob/main/components_bom.csv)

!!Thanks to ALL!!
