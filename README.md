# IF down converter, 455kHz to 12kHz.
This converter allow a shortwave radio to decode DRM (Digital Radio Mondiale) broadcast using a SDR software.  
  
The circuit use a LA1186N or TA7358AP as mixer, and a analog television chrominance crystal as source to local oscillator.  
The crystal frequency are divide by IC301, and need to selected between 74HC4017 or 74HC4040, depending on choosen crystal frequency.  
To get 12kHz output use 4.433619MHz (PAL) crystal and 74HC4017.  
Using the 74HC4040 and 3.579545MHz (NTSC) or 3.575611MHz (PAL-M) crystal, the output frequency are centered near 8kHz.  
The input impedance of converter are great that 6k.  
Total gain is 12dB.  
  
On the radio, FI signal need to tapped after last IF stage of after 455kHz ceramic filter. Use a 47pF (or lowwer) to decouple the signal.  
  
...





