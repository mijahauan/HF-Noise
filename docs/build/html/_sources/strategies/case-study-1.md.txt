# Case Study 1: Waterfall Changes When Moving a Feedline

## Symptom:
- The SDR waterfall display shows fluctuations in noise levels when a coax feedline is repositioned.
- The noise is broadband but follows the motion of the cable.

## Analysis:
- This suggests common-mode noise, where the feedline is acting as an unintended antenna.
- Possible sources: Poor shielding, improper grounding, or lack of a common-mode choke.

## Mitigation Steps:
1.	Test Isolation: Insert a common-mode choke (ferrite on coax, Mix 31 for HF) near the antenna and near the receiver.
2.	Check Grounding: Ensure the feedline shield is grounded at a single point.
3.	Re-route the Cable: Keep coax away from noise sources (AC lines, routers, computers).
4.	Improve Shielding: Use higher-quality coax like LMR-400 or clamp ferrites on both ends.
