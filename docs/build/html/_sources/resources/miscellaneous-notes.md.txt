
# Miscellaneous Notes

## From Glenn Elmore N6GN:
"If one starts with a video+audio of the fundamental of a leaking SMPS, say a bipolar one switching at 30 kHz but having the residual imperfectly filter 120 Hz riding on the DC it is chopping, along with imprecise chop rate, it isn't CW it's spread with noise, say 1 kHz wide 'bump' at 30 kHz  so angular modulation index, beta = deviation/rate so maybe .01 or so, then shows that the chopper is essentially a frequency multiplier, I think many could understand it.   Then go up to 30 MHz and listen in FM with a 10 kHz BW.  Up there  each of the ~1000th+- harmonics in the region now has its line but because its an FM signal the deviation is now 1 MHz. Both it and neighbors within 500 kHz contribute to energy there.  There is no longer any relatively narrow bump to look at or even recognize, just spread noise due to 30 similar lines - each of which is coherently switched at exactly the same instant.

The result is a spread noise floor that can look flat but is actually due to the noise spectrum around the original 30 kHz line summed a whole lot of times.  It may look like noise, and someone might mistakenly think it's normal BUT if you listen to it even in a 10 kHz wide AM BW the 120 Hz component due to the residual jumps out at you.  It isn't necessarily noticed in SSB mode.

This is a tool for discovering a noise impairment you didn't know you had.

Related to that, recognize that propagated noise, our goal, has a different characteristic from near-Gaussian or "white" noise. 75 years ago before the age of SMPS if one listened from a quiet location to 20m the propagated noise had distinctive qualities. This due to the impulse nature of the finite nature of the less-than-a-jillion T-storm strikes that contributed to it.  It sounded "crackly". That's not what one hears at a site that is limited by spread SMPS noise.  Until you listen (and look for diurnal variations characteristic of propagated mostly-Tstorm noise  you may not recognize the difference.

If the video played AM from a SMPS fundamental and then went up to, say, the high end of HF where things are spread as described above, the 120 Hz (FW rectification) component due to the residual will show the effect and hum/buzz/growl that is its signature. Then go to KPH or some other quiet site with high diurnal variations which indicate that it is not limited by spread SMPS noise and let the viewer/listener compare the demodulated noise.

Oldtime geezers will immediately get the distinction. Newer amateurs will get it when they see/hear it
Try it on your own system where there is a bump visible at ~2.6 MHz. Listen to 2600 in AM mode then add a zero and listen at 26000."

## From Philip Barnard VK7JJ

Nothing revolutionary here, just evolutionary via trial and error


### mains EMI filter
	- a two stage EMI filter placed in metal case has outlets for all mains powered computers and were noticeably worthwhile
	- filter eg: https://www.ebay.com.au/sch/i.html?_nkw=two+stage+EMI+filter&_sacat=0&_from=R40&_trksid=p2332490.m570.l1313
	- the same filters work nicely inline with other mains-noise injecting devices at other locations in the home
	
### ethernet
	- using a router that came in a metal case and supported islanding of RX888 radiod traffic
	- all ethernet leads attach to the router via HF EMI toroids with 6 or so windings of flat ethernet cable
	- no clip on ferrites, only HF EMI toroids with 6 or so turns of all SMA joining cables
	(each extra turn through a toroid gives #turns x impedance increase)
	- typical cheap local toroids eg https://www.jaycar.com.au/l15-35x21x13mm-toroid-or-ring-cores-pack-of-2/p/LO1238
	- tubes eg https://www.jaycar.com.au/large-ferrite-suppression-sleeves-pack-of-6/p/LF1260
	
### power supplies
	- all power supplies are home brew well filtered linear except for the mains powered computers
	- all mains powered computers are fed from a single mains EMI filter as above
	- 12V battery bank as below powers all low current 5 volt devices eg LNAs via homebrew linears
	- 5V higher current supplies are homebrew linear using low voltage multi-tapped surplus electric blanket mains transformers
	(ie. minimum AC-DC voltage differential keeps losses and heat low)
	
### shack's 12V 600AH battery bank
	- normally solar powered but has mains linear backup auto-switch
	- battery bank powers all 12V devices and low current 5V linear homebrew supplies
	- the PWM solar inverter has an option to switch at < slow 1 second rate which is great for RFI reduction
	
### common "grounding" point on shack wall
	- all relevant devices have their own "earth" or chassis wire to the grounding point
	eg. the antenna current balun's coax, cases of radios, computers didn't seem to matter
	- the grounding point's earth wire exits shack to good grounding system
	
### antennas and their feedlines
	- my balanced horizontal loop antennas are noticeably less noisy than my verticals
	- my balanced feedlines are noticeably quieter than coax
	- my balanced feedlines have current baluns of multiturned coax through 6 x large ferrite tubes inside shack
	
### comments
	- my RX888s radiate badly and push the shack's noise floor up noticeably and so far no complete solution has been found
	- Kiwis also radiate some sort of switching very annoyingly at the ethernet connector but are more easily suppressed with ether toroids as mentioned above
	- 8 band Kiwis with splitters to 2 x AirSpy HF+ on 60m and 12m via SparkSDR give better performance than RX888s at this location
	
	- The most rewarding improvements in reducing shack noise in descending order of magnitude have been
		- linear power supplies
		- preventing shack noise injection into the mains wiring and suppression of externally induced mains noise
		- earthing and grounding layout
		- ethernet suppression
		
		Note:  galvanic isolation using wideband miniature RF transformers at various points in the coax didn't do much for me.
		DO NOT BUY the below they don't isolate either the RF or shield and in fact connect both inner and shield together DC electrically
		eBay:  "RF Double Head Mini Antenna Galvanic Isolator"


	

