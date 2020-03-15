# The Annoy-a-tron

This is a simple circuit using an Attiny85 (with socket), CR2032 Battery (with holder), and a piezo speaker on a piece of PCB about 1-1/4" square. 

The circuit is very straight forward. You just wire:

- The positive end of the battery holder to the positive pin on the ATtiny85 (the solder tail).
- The negative end of the battery holder to:
  - The negative pin on the ATtiny85
  - The negative pin on the piezo speaker
- The chosen out pin (I chose pin 1) of the ATtiny85 to the positive end of the piezo speaker.

If you want, you can throw a surface mount switch in there on the negative side of things so you can turn it off and on.
