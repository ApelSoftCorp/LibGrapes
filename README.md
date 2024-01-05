# LibGrapes
LibGrapes is a compatibility layer for running MineOS Programs on OpenOS devices. It also includes the MineOS GUI libary for easy GUI development on OpenOS devices.

## Minimum Specs (GUI)
To use LibGrapes' GUI library, your device will require at least the following specs:

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| CPU       | Any*    | Tier 2      |
| GPU       | Any**   | Tier 2      |
| RAM       | ***	  | ***			|
| Diskspace | 300KB+  | N/A         |

###### \* Any CPU (Tier 1,2,3 etc. will run LibGrapes, but you will see a significant performance impact with lower tier CPUS.)
###### \** Any GPU (Tier 1,2,3 etc. will run LibGrapes, but the colors will be off on lower tiers. You may experience a lack of screen real estate when using a Tier 1 GPU.)
###### \*** LibGrapes' GUI library uses about 215kb of ram. The larger your program is, the more RAM it will use.