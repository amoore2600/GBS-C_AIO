# GBS-C-AIO
Build files for the GBS-C AIO

The GBS-C AIO is an open source add-on board for the GBS 8200 running the Gbscontrol custom open source firmware by Rama and others.

The GBS-C AIO key features are: 

* Very low lag, less than 1 frame.

* High quality upscaling for nearly all retro game systems and computers - anything pre 2000s   

* Fast resolution switching between 240p and 480i video signals - output to the display never drops sync

* Motion Adaptive deinterlacer that engages automatically and is superior to most BOB deinterlacing and BOB deinterlacing is available should you want it

* Easy to  navigate interface via web browser

* Color reproduction with auto gain and auto offset for the triple 8 bit @ 160MHz ADC

* Zero Lag bypass capability for transcoding video

* Simplified power management compared to other DYI GBS-C set ups

* Acrylic and PCB style case options 

* Inputs: SCART(RGBS), Component (YPbPr), VGA(RGBHV)

* Outputs: VGA/YPbPr 1280x960, 1280x1024, 1280x720,1920x1080, 720x480/768x576  and Source Pass-through.HDMI 720P/1080P. only one VGA or HDMI output at a time on the GBS8200 

* Fast downscaling at 240P via VGA/YPbPr 

* Built in Sync Strike that can be turned on and off



A basic BOM, Gerbers (PCB plates and AIO Board), KiCad source files and Acrylic plate files are included in this repository.

The recomeded addtions and modifications to the GBS 8200 Scaler are: 

1. Remove the pots
2. Clock mod - https://github.com/ramapcsx2/gbs-control/wiki/Si5351-Clock-Generator-install-notes use SDA and SCL pads on the AIO board for easy installation.
3. Replace c47 with a 22uf cap to compensate for the increased power draw from the clock mod.
4. Add a a resistor value in parallel with r26 to correct the ypbpr output brightness.
5. Replace the 150 ohm resistor on r26 if it is outside of 1% tolerance.

This project uses the GBScontorl firmware by Rama - https://github.com/ramapcsx2/gbs-control

Suport the GBScontrol project and Buy Rama a coffee - https://www.buymeacoffee.com/ramapcsx2 

AIO board design by Jacob Proctor (Arithmaldor) - https://twitter.com/Arithmaldor

GBS-C AIO user fourm - https://www.gbscaio.com/forum

GBS-C AIO Private Facebook Group - https://www.facebook.com/groups/gbscaio









