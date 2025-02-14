# General Identification & Mitigation Strategies

Here’s a structured approach before diving into case studies.

## Identifying RF Noise
### Visual Clues (Waterfall Display / Spectrum Analysis)
	•	Broadband noise: A raised noise floor across a wide frequency range.
	•	Narrowband noise: Persistent or drifting carriers at specific frequencies.
	•	Harmonic patterns: Repeating peaks at regular frequency intervals.
	•	Time-variable noise: Noise that changes when equipment cycles on/off.
### Audible Clues (AM/SSB/CW Listening)
	•	Buzzing/Humming: Power line noise, poor grounding, or switching power supplies.
	•	Popping/Clicking: Arcing from bad insulators, motors, or thermostats.
	•	Whining or Warbling: Switching regulators, LED dimmers, and microprocessor clocks.
	•	Rushing/Frying Sounds: Plasma TVs, grow lights, electric fences.
### Physical & Electrical Proximity Clues
	•	Changes when moving a cable? Suspect common-mode currents or shielding issues.
	•	Noise disappears on battery power? The source is on the AC mains.
	•	Directional changes? Use a loop or Yagi to pinpoint sources.
	•	Not affected by power cycling? Could be an external source like power lines.

## Mitigation Strategies
### Shielding & Enclosures
	•	Use metal cases, ferrites, and shielded cables for noisy devices.
### Filtering
	•	Use common-mode chokes, AC line filters, and capacitor bypassing.
### Grounding & Bonding
	•	Ensure proper single-point grounding to avoid ground loops.
### Antenna & Feedline Management
	•	Use current chokes, baluns, and reposition antennas away from interference.

## A layered approach works best:
	1.	Detect the noise (waterfall, audio, directionality).
	2.	Measure its characteristics (harmonics, patterns, conducted vs. radiated).
	3.	Localize the source (power down, portable radio, ferrites).
	4.	Mitigate using filtering, shielding, grounding, and better equipment.

