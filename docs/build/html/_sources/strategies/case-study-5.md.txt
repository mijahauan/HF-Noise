# Case Study 5: Noise Floor from DC to 60MHz is Higher than ITU Models Predict

## Symptom:
- The receiver’s noise floor does not follow the expected ITU noise model.
- Instead of gradually decreasing, it remains elevated across the HF spectrum.

## Analysis:
- This suggests broadband noise pollution from multiple sources, possibly from local electronics, solar inverters, or poor grounding.

## Mitigation Steps:
1.	Determine Internal vs. External Sources:
- Power the station from batteries only to isolate internal noise.
- Use a portable receiver outdoors to compare local vs. environmental noise.
2.	Reduce Local Noise:
- Install ferrites on power cords and data cables.
- Use shielded network cables to reduce Ethernet leakage.
- Ensure that LED lights and smart devices aren’t contributing noise.
3.	Improve Antenna Placement:
- Move antennas away from structures and noisy equipment.
- Use a loop antenna or a high-pass filter to eliminate low-frequency noise.
