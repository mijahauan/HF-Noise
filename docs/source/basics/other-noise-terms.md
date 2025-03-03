
# Other Basic Noise Types

## Common Mode Noise
- Description: Common mode noise refers to noise that appears equally on both conductors of a differential pair or across a shared ground. This noise does not affect the differential signal but can create problems in systems that are sensitive to common mode signals.
- Relation to Types of Noise: Common mode noise can be considered a type of "interference noise." This noise often originates from external electromagnetic fields, such as those generated by nearby electronics, power lines, or radio frequencies. It's particularly relevant in balanced signaling systems.
- Mitigation: To reduce common mode noise, use twisted pair cables, differential signaling, and common mode chokes. Good grounding practices and shielding can also help minimize its impact.

## Propagated Noise
- Description: Propagated noise is noise that travels through the air or along the transmission medium (such as cables) and affects signal integrity. This can include RF interference from other transmitting devices or unwanted signals picked up by antennas and feed lines.
- Relation to Types of Noise: This noise is often categorized as "radio frequency interference (RFI)" or general environmental noise. Propagated noise can also be considered a form of interference that degrades the quality of the received signal.
- Mitigation: To mitigate propagated noise, implement shielding, use filters to attenuate unwanted frequencies, and properly position antennas away from noise sources. Directional antennas can also help focus reception on the intended signal while rejecting noise from other directions.

## Ground Loop Noise
- Description: Ground loop noise occurs when there are multiple grounding paths in a system, leading to differences in ground potential. This can create unwanted current flow in the ground connections, resulting in voltage differences that manifest as noise on the signal lines.
- Relation to Types of Noise: Ground loop noise can be categorized as a type of "power supply noise" or "interference noise." It often affects low-frequency and analog signal systems, degrading performance due to unwanted voltage changes.
- Mitigation: To prevent ground loop noise, design the system with a single ground point to eliminate multiple ground paths. Use isolation transformers or differential inputs to minimize the effects of ground loops. Additionally, careful attention to grounding practices during installation can help avoid this issue.

