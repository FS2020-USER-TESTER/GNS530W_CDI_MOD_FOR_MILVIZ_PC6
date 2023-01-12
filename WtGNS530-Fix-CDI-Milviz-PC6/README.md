# GNS530W_CDI_MOD_FOR_MILVIZ_PC6 VERSION 1.0.1

This mod patches the Blackbird PC-6 Porter Analog panel versions to improve compatibility with early release WT GNS530W including split CDI.
The GNS530W is currently available optionally in Marketplace but will become the standard GPS implementation in 2023.
The GTN530W upgrade has many advanced features including RNAV approaches. 
All aircraft config changes recommended by WT document are included.

This mod is not supported by Blackbird. 

## Prerequisite

At the time this mod is published the Working Title Simulations upgrade of GNS530/GNS430 is available for optional download/install in the Marketplace replacing the default sim version. The current name is "GARMIN GNS 430/530".  The same update is installed in the AAU1 beta.  This information is subject to change as this code moves from expirmental to production.

## Install

1. Unzip WtGNS530-Fix-CDI-Milviz-PC6.zip placing WtGNS530-Fix-CDI-Milviz-PC6 into community folder
2. This mod is only functional while flying the three Blackbird PC6 analog-panel airplanes.
3. Sim user wishing to use GTN750 should NOT install this mod and install mod from JayDee instead.  You will see malfunction if GTN750 mod installed in community folder with this mod.

## Support

You may report issues or ask questions here: https://github.com/FS2020-USER-TESTER/GNS530W_CDI_MOD_FOR_MILVIZ_PC6/issues

## Using External Controls for GNS530:

1. Users that map GNS530/430 to external buttons need to assign the CDI button to a script. Here are suggested scripts:

* 1 (>H:AS530_CDI_Push, Number)
* 1 (>H:AS430_CDI_Push, Number)

## Features provided by the mod:

1. There is a GNS530 and a GNS430 available in the Milviz PC-6 analog panels. With this mod the units can be in unmatched CDI states - one in VLOC and one in GPS
2. The HSI and NAV2 CDI behavior code has been improved to use latest simvars and to provide correct indicator flags.
3. The TO/FROM flag for HSI and CDI are correctly calculated in GPS operation and match GPS status.
4. The latest core fix for autopilot startup PID reset is enabled. This can provide smoother autopilot startup. It is suggested that pilot trim the aircraft before engaging the AP for smoothest transition.

## NOT Usable with GTN750 mods:

1. The target of this add-on mode is users with WT GNS530W mod installed from marketplace or AAU1 Beta.
2. No support of GTN750 is provided. 

