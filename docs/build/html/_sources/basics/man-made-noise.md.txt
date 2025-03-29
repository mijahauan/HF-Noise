# Man-Made Noise (Electromagnetic Pollution)

Some external noise/interference sources one might control or eliminate.

## QRM 
 - One person's signal -- another person's noise.

## Power Line Noise
- Source: Arcing from faulty insulators, transformers, bad wiring.
- Characteristics: Buzzing/humming, strongest at power line harmonic frequencies (60 Hz and multiples).
- Identification: Peaks near power lines, detectable with a handheld AM radio.
- Mitigation: Report to the utility company, use directional antennas.

## Switching Power Supply Noise
- Source: Cheap AC adapters, LED lights, solar inverters, electric fences.
- Characteristics: Harmonic-rich broadband noise, often spaced at multiples of the switching frequency (e.g., 30–150 kHz).
- Identification: Peaks around 50–150 kHz intervals, disappears when suspect device is unplugged.
- Mitigation: Use better-shielded supplies, add ferrite chokes, or replace offending devices.

## Industrial & Consumer Electronics Interference
- Source: Smart meters, TVs, computer monitors, PLC (power line communication) devices.
- Characteristics: Broad or narrowband interference, varies by device.
- Identification: Can often be localized using an AM or SDR receiver.
- Mitigation: Improve shielding, use RF filters, place distance between antenna and source.

## Solar Panel & Inverter Noise
- Source: Switching inverters converting DC to AC.
- Characteristics: Continuous broadband noise, strongest at switching frequency harmonics.
- Identification: Strongest during daylight, noise drops at night.
- Mitigation: Use shielded inverters, add inline chokes, locate antennas away from panels.
