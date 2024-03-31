## Custom 4x SATA Backplane for home-nas and servers
If you are interested in the design process behind this pcb, take a look at [this accompanying blog post.](https://blog.hirnschall.net/custom-4x-sata-backplane)

### Why use a backplane
Using a backplane allows multiple disks to be connected to a single power-supply cable. For this a 4-pin molex connector is used as it can sustain the spinup current of 4 disks.

### How to order    
Download the the latest gerber-files from the release tab. Order then on e.g. jlcpcb.com.     
Use the following settings when ordering:
- PCB thickness: 1.6mm
- Layers: 4
- Impedance Control: yes, JLC04161H-7628
- Material type: FR4-Standard TG 135-140
- Copper weight: 1oz outer, 0.5oz inner
- Remove Order Number: Specify a location (remove if you want to)
