# esynth-lost-sampler
this is a non-working code, written in 2023, in microchip's mikroC, for controlling a PIC16F1784, interfaced with 2 512kb 24LC512: microchip's EEPROMs, via I2C. The goal is to being able to record 10 seconds of mono sound at 12bit-50kHz, store into the memory and be able to replay it, using the stock PIC's ADC and DAC. Other informations, schematics, and the old original code are in the .pdf file.
--> UPDATE: the problem are the 2 EEPROMS: too small and too slow. Check the possible solution from ChatGpt Go analysis 
