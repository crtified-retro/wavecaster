# Wavecaster
## Summary

It's been a couple of years since I began building and using versions of the milestone [WavetablePi project](https://github.com/scrapcomputing/WavetablePi) designed by Scrap Computing, which ports Dale Whinham's renowned [mt32-pi project](https://github.com/dwhinham/mt32-pi) onto the 'Waveblaster' daughterboard form factor used by legacy soundcards.

Over that time, various little tweaks and changes came to mind, streamlining Scrap Computing's work into a particular version to suit myself. 

Main changes -

- **Adoption of the WavetablePiHoriz's horizontal format**  
Reason : fits more legacy soundcards; and higher center-of-gravity (the vertical WP can lean a little!)

- **Incorporating the PCM510x DAC circuitry directly onto the board**  
Reason : keeps the profile thin; and avoids the QA issues the DAC modules sometimes have

- **Resistors and capacitors to SMD**  
Reason : saves space and cost

- **Removal of the Pi Audio option (J1,J2, & associated C's and R's)**  
Reason : the Pi Audio selection is redundant with the higher-quality DAC onboard; saves space and cost

- **Adoption of the breakout connector for screen and controls, as used by Serdaco's mt32-pi products**  
Reason : enables the user to locate an external screen and buttons anywhere; keeps the profile thin

* **Silkscreen updates**  
Reason : visuals

---
## Status

I will release the project files here in the near future.

---
### Licence 
My work in this repository is free and open source.
