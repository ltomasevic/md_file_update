---
title: "Sprint 73: V1.68.6.1"
date: 23.11.2023

product_name: EcoStruxure Machine Expert V2.0.3
git_branch: releases/V2.0.3
git_commit: abc123defg456
git_tag: ESME_2.0.3_Sprint73
packages: 
    - https://sources-svn.electric.com/svn/se-controls-releases/ESME%20V2.0.3/ESME%20V2.0.3_Release/Sprint%2073/LMC_Pro2_1.68.6.1_21.9.8.1226.seco
    - https://sources-svn.electric.com/svn/se-controls-releases/ESME%20V2.0.3/ESME%20V2.0.3_Release/Sprint%2073/LMC_Pro_1.68.6.1_21.9.8.1221.seco
    - https://sources-svn.electric.com/svn/se-controls-releases/ESME%20V2.0.3/ESME%20V2.0.3_Release/Sprint%2073/LMC_Eco_1.68.6.1_21.9.8.1223.seco
    - https://sources-svn.electric.com/svn/se-controls-releases/ESME%20V2.0.3/ESME%20V2.0.3_Release/Sprint%2073/AddonMulticarrier_1.66.1.1_21.9.8.1227.seco
    - https://sources-svn.electric.com/svn/se-controls-releases/ESME%20V2.0.3/ESME%20V2.0.3_Release/Sprint%2073/SercosDevice_TM5CSLC100FS_1.66.0.2_21.07.01.257.seco
    - https://sources-svn.electric.com/svn/se-controls-releases/ESME%20V2.0.3/ESME%20V2.0.3_Release/Sprint%2073/SercosDevice_TM5CSLC200FS_1.66.0.2_21.07.01.257.seco
    - https://sources-svn.electric.com/svn/se-controls-releases/ESME%20V2.0.3/ESME%20V2.0.3_Release/Sprint%2073/SercosDevice_TM5NS31_1.66.0.2_21.07.01.279.seco
versions:
    DevDesc Pro/Pro2: "V1.68.6.2"
    DevDesc Eco: "V1.68.6.2"
    Firmware: "V1.68.6.1"
    CoDeSys: "V3.5 SP16 Patch 6"
    VxWorks: "7.0 21.03"
    CoSeMa 4: "V1.4.008"
    CoSeMa 5: "V3.021"
    OPC UA Server: "1.7.4"
tickets:
    Official:
        New Functions:
        Closed Bugs:
        Restrictions:
    Company Internal:
        New Functions:
            - "LMCFW-5564: Sercos phase up should be stopped if segment geometry does not fit"
            - "LMCFW-5565: Reset Segment and Carrier State Parameters"
            - "LMCFW-5497: Create CarrierWorking(Mode|State) \"deactivated\""
        Closed Bugs:
            - "LMCFW-5446: Variables are not reset after online Reset Cold"
            - "LMCFW-5247: Position of Device Addressing node changed in Classic perspective"
            - "LMCFW-3414: Incorrect error message after deleting Device Adressing"
        Restrictions:
    Team Internal:
        New Functions:
            - "LMCFW-5579: Update reference to submodule ModiPac in V2.0.3"
        Closed Bugs:
        Restrictions:
---

!!! note "Important!"
    This delivery includes also all the changes from [Sprint 73 hotfix 1: V1.66.5.1](../EcoStruxure Machine Expert V2.0.1/Sprint 73.md).

    On this page only tickets are listed, which were introduced from exactly this version.
