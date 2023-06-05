# printed parts

resin print vat mold files
FDm or resin print cooler base

# electronic parts

40x40 mm TEC1-12706 Peltier element, 12V, 60W:
https://www.amazon.com/DAOKI-TEC1-12706-Heatsink-Thermoelectric-Cooling/dp/B00XT0OZY0

40x40 mm heatsink:
https://www.amazon.com/40x40x20mm-Aluminium-TEC1-12706-Thermoelectric-40mmx40mmx20mm/dp/B08CN1SXQ6/

40x40 mm 12V fan:
https://www.amazon.com/40x40x10mm-Cooling-Blower-Brushless-Printer/dp/B07RZF5W75/
(or fancy noctua if you want silence)

Buck converter / step down:
https://www.amazon.com/10Gtek-Voltage-Regulator-Converter-Step-Down/dp/B09LCNVB22/
If you don't have a multimeter, pick one with a voltage display - but it won't fit as neatly on the cooler
https://www.amazon.com/Diitao-Converter-1-25-37V-Regulator-Adjustable/dp/B0B2L4WMS3

Thermal adhesive or sticky thermal pads

12V, 2A power supply, wires, connectors

epoxy glue to fix the step down board to the housing and secure the heatsink onthe fan

4x M3x24 (or longer) + nuts for the three part mold box

# wiring / assembly

Snapfit or epoxy glue the fan into the base, orientated to push air downwards.

Mount heatsink on the hot side of the peltier element (usually the not printed side, but check your manual). I recommend not using the crappy double sided sticky tape that comes with most heatsinks and use proper thermal adhesive instead.

Epoxy glue the heatsink onto the fan.

Run the fans on 12V, adjust stepdown to ~5V and use that to power the peltier element. Adjust voltage to adjust temperature, but be careful to not overpower the heatsink or cause condensation on the resin
