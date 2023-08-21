## Open energy system models are fueling the green energy transition

Our mission is to research new methodology and develop demonstration-ready energy modelling tools, that allow for <b>maximum flexibility, generality and speed while being open, secure and user-friendly</b>. This is no easy task, but to pride ourselves by saying that our tools are at the cutting edge of the field. We do this by simultanously hosting many modelling tools and research projects with similar goals, yet different focuses - and by working in close collaboration with the leading open-source energy models out there, like our friends at PyPSA and Osemosys. Of course we also work hand-in-hand with other VTT energy models, like Fleximar.

There are many open energy system models and modelling frameworks out there. We appreciate you taking the time and patience to get to know our tools, and hope they can help you in solving the novel energy system challenges of your case. Please read through our leading ideas in model design below, install our models and try them out. We do our best to provide tutorials and documentation, but please excuse when we fail to be clear and let us know on our mistakes so we can work on fixing them. 

# Our tools
<picture>
<img src="https://github.com/Tools-for-energy-system-modelling/.github/assets/112698385/65209323-fd0c-43f7-a90e-3b89e33065d2">
</picture>

## [Spine Toolbox](https://github.com/spine-tools/Spine-Toolbox)

1. Graphical user interface for maintaining repeatable workflows from input data to different modelling tools and visualizing results
2. Tools to transform data, data structures, and data formats
3. Create scenarios from alternative values and parallelize the execution
4. Easy to share workflows and operate models without touching the code

Maturity score: 3/5
Availability score: 4/5
Ease of use: 3/5
Level of flexibility: 5/5
Level of features: 4/5
   
[https://github.com/spine-tools/Spine-Toolbox](https://github.com/spine-tools/Spine-Toolbox)

## [SpineOpt](https://github.com/spine-tools/SpineOpt.jl)

1. Fully open framework for energy system optimization models from site-level to continental-scale
2. Include operational detail in investment planning
3. Highly flexible temporal, spatial and stochastic settings
4. Written in Julia, use Spine Toolbox as user interface
   
\+ SpineInterface package for quick model building using Julia JuMP

Maturity score: 3/5
Availability score: 4/5
Ease of use: 2/5
Level of flexibility: 5/5
Level of features: 4/5

[https://github.com/spine-tools/SpineOpt.jl](https://github.com/spine-tools/SpineOpt.jl)

## [Backbone](https://gitlab.vtt.fi/backbone/backbone)

1. Flexible and mature framework for energy system optimization models
2. Optimize investments and operation in multi-sectoral energy systems on local, national and continental scales
3. General in formulation, rich in features
4. Written in GAMS, no specific user interface (Excel+GDXXRW can be used), needs GAMS licence

Maturity score: 4/5
Availability score: 3/5
Ease of use: 2/5
Level of flexibility: 4/5
Level of features: 5/5

[https://gitlab.vtt.fi/backbone/backbone](https://gitlab.vtt.fi/backbone/backbone)

## [IRENA FlexTool](https://github.com/irena-flextool)

1. Fully open framework for energy system optimization models
2. Focused on system planning for high shares of variable power generation in future energy systems
3. Developed with IRENA for ease-of-use fo users with limited modelling or coding experience
4. FlexTool 3 written in AMPL+Python, can be used with Spine Toolbox or web interface (FlexTool 2 in IRENA distribution in Excel)

FlexTool 3:
Maturity score: 3/5
Availability score: 4/5
Ease of use: 4/5
Level of flexibility: 4/5
Level of features: 3/5

FlexTool 3: [https://github.com/irena-flextool](https://github.com/irena-flextool)
FlexTool 2: [https://www.irena.org/Energy-Transition/Planning/Flextool](https://www.irena.org/Energy-Transition/Planning/Flextool)


## [Predicer](https://github.com/predicer-tools)

1. "Predictive decider" - A fully open framework for real-time asset management on complex stocastic markets
2. Supports models to maximize the revenue from the operation of existing assets an industrial site, a building or an energy storage
3. Supports models to optimize the trading on multiple simultaneous energy markets while considering short-term uncertainty in weather, market prices and energy demand
4. Written in Julia

Maturity score: 2/5
Availability score: 4/5
Ease of use: 1/5
Level of flexibility: 4/5
Level of features: 3/5

[https://github.com/predicer-tools](https://github.com/predicer-tools)

## Hertta

1. Predicer-based easy-to-use home energy asset optimization software
2. In development, not published yet
3. Written in Rust with interface to Julia

Maturity score: 1/5
Availability score: -/5
Ease of use: -/5
Level of flexibility: -/5
Level of features: -/5

(Not public yet)


# Our best ideas to steal

1.	<b>Not everything in the model needs same resolution – not in space, not in time and not in probability.</b> Freedom to assign different resolution to different parts of the model makes it possible to create a TIMES-like economy model and a PLEXOS-type operational model with the same tool. As computational time is still a major issue on how wide and detailed we can make our models, being free to assign more resolution to the parts that matter expands modelling capabilities. In SpineOpt, the spatial, temporal and stochastic resolution can be freely assigned to different types of model.
2.	Invest optimizing without operational detail is like painting with the lights off. All modellers know it’s difficult to include operation detail in investment planning, but we believe it’s absolutely crucial and we have spent a lot of time on it.
3.	The model doesn’t have to care whether you model power, heat, gas or river systems. Agnostic and general representation of energy vectors allows for easy modelling of sectoral integration. When you want to model a new technology or a new sector, you don’t need to touch the model fundamentals. Of course most used constraints like power flow, heat transfer, hydrological inflow, and technologies are included in the framework for your convenience.
4.	Optimizing subsystems leads to suboptimal solutions.
5.	Maintain workflows, not models
6.	Using alternatives makes scenario building simpler.
7.	A modeller doesn’t have to be a coder.
8.	Open source is a strength.
9.	We like our models, but we are not the best at everything. So explore the open source models out there and combine the best in them.

# The Design and Operation of Energy Systems Team at VTT - who are we?

<img align="left" width=500 src="https://github.com/Tools-for-energy-system-modelling/.github/assets/112698385/10fe015a-1d59-4475-a21f-07a96653fcb4">

We operate at the sweet spot between where energy system expertize meets mathematics and programming. Our team consist of nine researchers with years of experience on creating cutting-edge energy system modelling. Our work is in research projects for the benefit of the Finnish and European public authorities, as well as the Nordic industry. Here are some of our largest ongoing projects:

- Mopo
- ELEXIA
- ...

Some of our reference work includes:

- Nordic energy system model for Backbone
- ...

For full list of our ongoing and past projects, please visit: LINK TO PURE

Want to know more? Contact team leader XX at XX.XX@vtt.fi

<img align="left" width=150 src="https://github.com/Tools-for-energy-system-modelling/.github/assets/112698385/209d39e6-4e0b-4adf-8626-12b9a45ddc4d">
