# Noise Detection and Measurement

We recognize the presence of noise primarily as we see and hear its effect on reception -- what we hear, see on a spectrum display, and decode (e.g., wspr spots, CW, etc.).  

## Software-Defined Radios

For now, anchored in a particular HamSCI project, we will focus on the use of the RX888 which works with ka9q-radio and its supplementary software, ka9q-web, which provides a high-quality spectrum display.

Other radio systems (RTL-SDR, Airspy, HackRF, SDRplay, FobosSDR, KiwiSDR, OpenHPSDR and its descendants like FlexRadio, ApacheLabs, etc.) work or come with spectrum display software. We hope the descriptions here will prove just as useful in those environments as well. 

### Advantages:
- Provides a visual spectrum and/or waterfall display of noise patterns.
- Helps recognize constant, periodic, or intermittent interference.
- May provide dynamic noise, min and max signals per bin, SNR, and S-meter measurements, among others.
- Some deployments may enable use with directional and/or mobile antennas for noise hunting.

## Analog Receivers (AM, SSB, CW-capable radios)

These devices can provide useful information, especially in hunting for local noise.  Examples include, hand-held AM receivers, handi-talkies monitoring unsquelched 2 meters, armed with fox-hunting/RFI antennas.  

### Usage:
- AM mode is highly sensitive to impulse noise.
- SSB/CW mode helps analyze weak noise patterns.
- Portable radios help in field noise hunting.

## Oscilloscope with FFT (Fast Fourier Transform) Capability

### Usage:
- Visualizes noise signals in both time and frequency domains.
- Helps detect transient and impulse noise sources.

## Stand-alone Spectrum Analyzers

### Examples: Rigol DSA815, Siglent SSA3021X, TinySA (Ultra).

### Usage:
- Measures signal strength over a range of frequencies.
- Helps identify noise sources by their frequency signature.

## Field Strength Meters

### Usage:
- Measures RF power levels at different locations.
- Useful for determining noise intensity around potential sources.


## Current Probes & RF Clamp Meters

### Usage:
- Measures common-mode current on cables and feedlines.
- Helps detect conducted emissions from power supplies and electronics.
