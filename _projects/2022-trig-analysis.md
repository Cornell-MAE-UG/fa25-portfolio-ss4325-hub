---
layout: project
title: ENGRD 2210 Project
description: Extra Credit Assignment for Devices
technologies: [Control Volume Analysis]
image: /assets/images/Dry_Steam_Power_Plant.jpg.jpg
---


This project analyzes a direct dry steam geothermal power plant, used at the Geysers geothermal field in California. In this system, naturally occurring steam from a geothermal reservoir is routed directly to a turbine to generate electricity.

##### Simplified Schematic of a Direct Dry Steam Power Plant
![Photo of plant]({{ "/assets/images/Dry_Steam_Power_Plant.jpg" | relative_url }}){: .block-image}

### Overview

Water at high temperature and pressure is extracted from deep underground geothermal reservoirs . It is then run through a separator that only allows the steam to pass through and leaves the heavier liquid behind. Because the steam is separated as saturated vapor or superheated steam, it can be sent directly to a steam turbine. The steam expands through the turbine, producing shaft work that drives an electric generator.

After expansion, the low-pressure steam enters a condenser, which is not shown on the simplified diagram. It is cooled and condensed into liquid water using ambient cooling (through cooling towers). The condensed water is then reinjected into the geothermal reservoir for environmental and economical reasons.

This is an open system operating continuously, with both mass and energy crossing the system boundary.

Below you can see the full schematic of the cycle modeled as a control volume. The blue dashed lines signify the system boundary, and the red arrows show the work and heat inputs and outputs.

##### Annotated Schematic of a Direct Dry Stream Power Plant

![Photo of plant]({{ "/assets/images/annotated.jpg" | relative_url }}){: width="500px" height="300px"}

### Energy and Mass Balance Equations:

#### Assumptions 
1. The turbine is adiabatic
2. Neglect the work done by pumps and the mass out from the cooling towers as they are much smaller than the turbine work and the mass reinjected
3. Neglect kinetic and potential energy

#### Energy and Mass Balance for the Entire System

{% raw %}
$$
\dot{m}_{\mathrm{steam}} = \dot{m}_{\mathrm{condensate}} \\
\dot{Q}_{\mathrm{in}} - \dot{Q}_{\mathrm{out}} = \dot{W}_{\mathrm{turbine}}
$$
{% endraw %}


#### Turbine





