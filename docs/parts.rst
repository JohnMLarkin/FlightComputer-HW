Standard Parts
==============

Assembly of a Flight Computer requires the following electronic components and connection hardware.



..  list-table:: Common components for either Flight Computer
  :header-rows: 1
  :widths: auto

  * - Description
    - Manufacturer
    - Part Number
    - Quantity
    - Link
  * - 20 pin header socket (for mbed)
    - Sullins
    - PPPC201LFBN-RC
    - 2
    - `Digi-Key <https://www.digikey.com/product-detail/en/sullins-connector-solutions/PPPC201LFBN-RC/S7053-ND/810192>`__
  * - XBee socket (2 mm, 10 pin, set of 2)
    - Adafruit
    - 366
    - 1
    - `Digi-Key <https://www.digikey.com/product-detail/en/adafruit-industries-llc/366/1528-1392-ND/5629440>`__
  * - 2x5 IDC connector receptacle (female sockets)
    - Wurth Electronics
    - 61201023021
    - 2
    - `Digi-Key <https://www.digikey.com/product-detail/en/wurth-electronics-inc/61201023021/732-2102-ND/2060598>`__
  * - 2x5 IDC connector header (male pin)
    - Wurth Electronics
    - 61201021621
    - 2
    - `Digi-Key <https://www.digikey.com/product-detail/en/wurth-electronics-inc/61201021621/732-2094-ND/2060590>`__
  * - 2-pin screw terminal block, 3.5 mm pitch
    - Wurth Electronics
    - 691214110002
    - 18
    - `Digi-Key <https://www.digikey.com/product-detail/en/wurth-electronics-inc/691214110002/732-2747-ND/2508516>`__
  * - 220 |ohm|, 1/4 W resistor
    - 
    -
    - 3
    - `Digi-Key <https://www.digikey.com/product-detail/en/stackpole-electronics-inc/CF14JT220R/CF14JT220RCT-ND/1830334>`__
  * - LED, 5 mm, red
    - Cree
    - C503B-RCN-CW0Z0AA1
    - 1
    - `Digi-Key <https://www.digikey.com/product-detail/en/cree-inc/C503B-RCN-CW0Z0AA1/C503B-RCN-CW0Z0AA1-ND/1922930>`__
  * - LED, 5 mm, green
    - Cree
    - C503B-GCS-CY0C0791
    - 1
    - `Digi-Key <https://www.digikey.com/product-detail/en/cree-inc/C503B-GCS-CY0C0791/C503B-GCS-CY0C0791-ND/1922941>`__
  * - LED, 5 mm, blue
    - Cree
    - C503B-BCN-CV0Z0461
    - 1
    - `Digi-Key <https://www.digikey.com/product-detail/en/cree-inc/C503B-BCN-CV0Z0461/C503B-BCN-CV0Z0461-ND/1922945>`__
  * - Slide switch, SPDT
    - NKK Switches
    - AS13AP
    - 1
    - `Digi-Key <https://www.digikey.com/product-detail/en/nkk-switches/AS13AP/360-2124-ND/1014820>`__
  * - mbed LPC1768 microcontroller
    - NXP
    - OM11043
    - 1
    - `Digi-Key <https://www.digikey.com/product-detail/en/nxp-usa-inc/OM11043,598/568-4916-ND/2138502>`__
  * - XBee 3 radio module
    - Digi
    - XB3-24Z8PT
    - 1
    - `Digi-Key <https://www.digikey.com/product-detail/en/digi-international/XB3-24Z8PT/602-2191-ND/8130937>`__
  * - microSD breakout
    - SparkFun
    - BOB-00544
    - 1
    - `Digi-Key <https://www.digikey.com/product-detail/en/sparkfun-electronics/BOB-00544/1568-1345-ND/5824094>`__
  * - 7.4 V, 800 mAh LiPo battery with PCB
    - Tenergy
    - 31145
    - 1
    - `Tenergy <https://power.tenergy.com/search.php?search_query=31145>`__
  * - Male Tamiya connector, 20 AWG silicon wire
    - Tenergy
    - 80001-5
    - 1
    - `Tenergy <https://power.tenergy.com/standard-male-tamiya-connector-battery-side/>`__ 


A charger for the battery is also required. For the battery pack specified, an appropriate choice is the Tenergy TLP-2000 (`Tenergy <https://power.tenergy.com/tenergy-tlp-2000-smart-charger-for-li-ion-lipo-battery-packs-3-7v-14-8v/>`__). This charger can be shared among multiple Flight Computers.

Connecting the Flight Computer PCB to the external interface also requires flat ribbon cable (10 conductors).  We buy this by the meter (`Digi-Key <https://www.digikey.com/product-detail/en/wurth-electronics-inc/63911015521CAB/732-11801-ND/8324551>`__) and cut an appropriate length.

We also use standard perf board (like `this <https://www.digikey.com/product-detail/en/vector-electronics/64P44XXXP/V1043-ND/37918>`__) in the assembly of the external interface. You just need a 2 hole by 5 hole piece so this might easily be scrap from some other project.

Additions for Standard Flight Computer
--------------------------------------

If you are assembling a **standard** Flight Computer, you will also need female header sockets in various lengths (with 2.54 mm pitch).  Those lengths and the number required are:

* 16 pins (2)
* 7 pins (1)
* 3 pins (1)
* 2 pins (9)

We use breakaway female header strip and cut it to length. Cutting always sacrifices one pin and then the edges are smoothed. We have had good success with Adafruit's 598 (5 pack of 36-pin strips) and the price is less than many other options (`Digi-Key <https://www.digikey.com/products/en?keywords=1528-2537-ND>`__).

The breadboard clip on the standard Flight Computer (one of the custom 3D printed components) is designed for a half-size solderless breadboard (for example, Adafruit's `64 <https://www.digikey.com/product-detail/en/adafruit-industries-llc/64/1528-2182-ND/7241427>`__). If you want something more permanent than a solderless breadboard, Adafruit makes a `perma-proto half-sized breadboard PCB <https://www.digikey.com/products/en/prototyping-fabrication-products/prototype-boards-perforated/636?k=adafruit%20571>`__ that has the same mounting hole spacing as our breadboard clip.

Addition for Mini Flight Computer
---------------------------------

If you are assembling a **mini** Flight Computer, you will also need a 3-pin screw terminal block (with 3.5 mm pitch). We use Wurth Electronics part 691214110003 (`Digi-Key <https://www.digikey.com/product-detail/en/wurth-electronics-inc/691214110003/732-2748-ND/2508517>`__).

.. |ohm| unicode:: U+03a9 ..  capital omega
