Analyze dump1090 output

This notebook is designed to analyize the bulk output from the dump1090 program.dump1090 can generate volumious data for a Raspberry Pi system - I have a large flash drive mounted via usb and on occasion copy the output via netcat. This notebook is designed to poke around at that data. 

I am doing some rough calculations for bearing and speed and using these to identify interesting tracks, then plotting them. 

I am planning to add a running curvature calculation to better automatically identify aircraft that were maneuvering. This is an academic exercise and there is no real point in doing this other than it is fun to do.
