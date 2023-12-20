# RABARBARO
USB PD powered ultra-low noise ultra-low distortion condenser microphone preamplifier

This repo holds all the files about this project, LTSpice simulation schematics and ECAD files.

RABARBARO is an ultra-low noise and ultra-low distortion condenser microphone preamp with a standard balanced XLR input connector (with of course the option for switchable Phantom Power, 48VDC 10mA MAX), variable gain, high power phones output (6.35mm jack stereo) and a balanced XLR line output. RABARBARO can easily drive 10V RMS onto 600Ohm trough line out and effortlessly power 4W of headphones (32Ohm, 250mA MAX per channel).

The main PCBA is the preamp itself with the phantom power DC/DC converter, phones output driver and balanced line out driver, while the secondary PCBA is the power supply: it provides positive and negative 18VDC from a USB-C connector (15VDC USB PD) through a low noise slew rate limited isolated DC/DC converter (switched pulse transformer) + output LDOs.

--**PROJECT STILL WORK IN PROGRESS**--
