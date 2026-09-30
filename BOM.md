# Bill of materials

Prices are in USD, checked on 30 Sep 2026, and do not include shipping or tax. Several of these parts are only sold in packs. **For one build** is that pack price divided by how many pieces are in it. **Listing** is what you actually pay if you buy the linked item.

One of each part comes to about **$58**. Buying the listings as they are sold (the ESP board is a pair, the charger is a 10-pack) comes to about **$72**.

| Qty | Part | Role | Where | Listing | For one build |
| --- | --- | --- | --- | --- | --- |
| 1 | [TETRIX MAX continuous-rotation servo](https://www.pitsco.com/products/tetrix-continuous-rotation-servo) (39177 / HSR-1425CR) | Spins the printed hand. 4.8–6 V. Signal on D7. | [Pitsco](https://www.pitsco.com/products/tetrix-continuous-rotation-servo) | $20.75, clearance | $20.75 |
| 1 | HW-625B, or the same class of board: NodeMCU ESP-12 with CH340, D7 = GPIO13 | ESPHome controller. USB for the first flash. | [MakerFocus, 2-pack](https://www.makerfocus.com/products/2pcs-esp8266-nodemcu-lua-ch340-esp-12e-internet-wifi-development-board-for-arduino) | $13.99 for 2 | $7.00 |
| 1 | [MT3608 boost module](https://www.icstation.com/mobile/icstation-step-converter-module-boost-converter-power-supply-module-icsa004a-p-3448.html) | Steps the cell up. Set the trim pot to 6 V before connecting anything else. | [ICStation](https://www.icstation.com/mobile/icstation-step-converter-module-boost-converter-power-supply-module-icsa004a-p-3448.html) | $0.90 | $0.90 |
| 1 | [TP4056 1S charger with protection](https://www.amazon.com/HiLetgo-Lithium-Battery-Charging-Protect/dp/B00LTQU2RK) | Charges the 18650 from 5 V USB. | [HiLetgo on Amazon, 10-pack](https://www.amazon.com/HiLetgo-Lithium-Battery-Charging-Protect/dp/B00LTQU2RK) | $7.79 for 10 | $0.78 |
| 1 | [Samsung INR18650-30Q](https://imrbatteries.com/products/samsung-30q-18650-3000mah-15a-battery) | Single lithium-ion cell. 3000 mAh, 15 A, enough for this servo. | [IMR Batteries](https://imrbatteries.com/products/samsung-30q-18650-3000mah-15a-battery) | $5.99 | $5.99 |
| 1 | [Polymaker Panchroma PLA, black, 1.75 mm, 1 kg](https://www.amazon.com/Panchroma-Filament-Printing-Compatible-Miniatures/dp/B0FC1RT6M8) | Case (one print) and servo hand (three prints). A spool is far more than this project uses. | [Polymaker on Amazon](https://www.amazon.com/Panchroma-Filament-Printing-Compatible-Miniatures/dp/B0FC1RT6M8) | $14.49 | $14.49 |
| 1 | [Gorilla Super Glue Gel, 15 g](https://www.amazon.com/dp/B01GWD35YQ) | Holds the hand on the servo axle. | [Amazon](https://www.amazon.com/dp/B01GWD35YQ) | $8.02 | $8.02 |

The servo is also listed by part number at [Techno-Tek](https://techno-tek.com/product/tetrix-max-continuous-rotation-servo-39177-hsr-1425cr/) for $22.00. The Pitsco price above is a clearance listing.

This build used an HW-625B. That is a NodeMCU-style ESP-12 board: CH340 USB serial, and D7 on the silkscreen is GPIO13, which is the pin in the ESPHome config. The MakerFocus pair is that same board.

The cell in the photos sits in a single 18650 holder with leads. Any leaded one-cell holder fits. The 30Q above is a flat-top unprotected cell, so the TP4056 module's protection circuit is the protection on this build.

Electrical tape, hookup wire, and solder are what pack the boards into the case. They are not in the total.
