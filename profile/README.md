<img align="left" width=150 src="https://github.com/Tools-for-energy-system-modelling/.github/assets/112698385/209d39e6-4e0b-4adf-8626-12b9a45ddc4d">

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
4. Easy to share workflows with non-coders

[https://github.com/spine-tools/Spine-Toolbox](https://github.com/spine-tools/Spine-Toolbox)

## [SpineOpt](https://github.com/spine-tools/SpineOpt.jl)

1. Fully open framework for energy system optimization models
2. Include operational detail in investment planning
3. Highly flexible temporal, spatial and stochastic settings
4. Written in Julia, use Spine Toolbox as user interface
+ SpineInterface package for quick model building using Julia JuMP

[https://github.com/spine-tools/SpineOpt.jl](https://github.com/spine-tools/SpineOpt.jl)

## [Backbone](https://gitlab.vtt.fi/backbone/backbone)

1. Energy system optimization framework in GAMS
2. Optimize investments and operation in multi-sectoral energy systems on local, national and continental scales
3. Flexible and general formulation, rich in features
4. Written in GAMS, no specific user interface (Excel+GDXXRW can be used)

[https://gitlab.vtt.fi/backbone/backbone](https://gitlab.vtt.fi/backbone/backbone)

## [IRENA FlexTool](https://gitlab.vtt.fi/backbone/backbone)

1. Energy system optimization framework in GAMS
2. Optimize investments and operation in multi-sectoral energy systems on local, national and continental scales
3. Flexible and general formulation, rich in features
4. Written in GAMS, no specific user interface (Excel+GDXXRW can be used)

[https://gitlab.vtt.fi/backbone/backbone](https://gitlab.vtt.fi/backbone/backbone)

## [Predicer](https://gitlab.vtt.fi/backbone/backbone)

1. Energy system optimization framework in GAMS
2. Optimize investments and operation in multi-sectoral energy systems on local, national and continental scales
3. Flexible and general formulation, rich in features
4. Written in GAMS, no specific user interface (Excel+GDXXRW can be used)

[https://gitlab.vtt.fi/backbone/backbone](https://gitlab.vtt.fi/backbone/backbone)

## [Hertta](https://gitlab.vtt.fi/backbone/backbone)

1. Energy system optimization framework in GAMS
2. Optimize investments and operation in multi-sectoral energy systems on local, national and continental scales
3. Flexible and general formulation, rich in features
4. Written in GAMS, no specific user interface (Excel+GDXXRW can be used)

[https://gitlab.vtt.fi/backbone/backbone](https://gitlab.vtt.fi/backbone/backbone)

| [Spine Toolbox](https://github.com/spine-tools/Spine-Toolbox) | SpineOpt | Backbone | IRENA FlexTool  | Predicer |
| :---------------- | :------ | :---- | :------ | :---- | 
| DATA & WORKFLOW MANAGEMENT | Fully open ENERGY SYSTEM OPTIMIZATION | ENERGY SYSTEM OPTIMIZATION in GAMS | ENERGY SYSTEM OPTIMIZATION for developing countries | SINGLE-ACTOR MULTI-MARKET OPTIMIZATION |
| 1. Maintain repeatable workflows to supply data to different modelling tools | 1. Include operational detail in investment planning | Optimize investments and operation in multi-sectoral energy systems on local, national and continental scales | Planning for high shares of variable power generation in future energy systems | |
| 2. Tools to transform data, data structures, and data formats  | 2. Highly flexible temporal, spatial and stochastic settings  | Flexible and general formulation, rich in features | Developed with IRENA for the developing countries | ----: | 
| 3. Create scenarios from alternative values and parallelize the execution  | 3. Written in Julia, use Spine Toolbox as user interface   | Written in GAMS, no user interface (Excel + GDXXRW can be used)  | Written in AMPL+Python, can be used with Spine Toolbox or web interface  | ----: | 
|    | + SpineInterface package for quick model building using Julia JuMP   |  | |  | 

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
