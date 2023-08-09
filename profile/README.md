<img align="left" src="https://user-images.githubusercontent.com/112698385/232780070-da828220-9ab4-405b-aef5-8387993d260a.png">

## Open energy system models are fueling the green energy transition

Our mission is to research new methodology and develop demonstration-ready energy modelling tools, that allow for <b>maximum flexibility, generality and speed while being open, secure and user-friendly</b>. This is no easy task, but to pride ourselves by saying that our tools are at the cutting edge of the field. We do this by simultanously hosting many modelling tools and research projects with similar goals, yet different focuses - and by working in close collaboration with the leading open-source energy models out there, like our friends at PyPSA and Osemosys. 

There are many open energy system models and modelling frameworks out there. We appreciate you taking the time and patience to get to know our tools, and hope they can help you in solving the novel energy system challenges of your case. Please read through our leading ideas in model design below, install our models and try them out. We do our best to provide tutorials and documentation, but please excuse when we fail to be clear and let us know on our mistakes so we can work on fixing them. 

# Get to know our tools:

| [Spine Toolbox](https://github.com/spine-tools/Spine-Toolbox) | SpineOpt | Backbone | IRENA FlexTool  | Predicer |
| :---------------- | :------ | :---- | :------ | :---- | 
| DATA & WORKFLOW MANAGEMENT | ENERGY SYSTEM OPTIMIZATION fully open | ENERGY SYSTEM OPTIMIZATION in GAMS | ENERGY SYSTEM OPTIMIZATION for developing countries | SINGLE-ACTOR MULTI-MARKET OPTIMIZATION |
| 1. Maintain repeatable workflows to supply data to different modelling tools | 1. Include operational detail in investment planning | Optimize investments and operation in multi-sectoral energy systems on local, national and continental scales | Planning for high shares of variable power generation in future energy systems | |
| 2. Tools to transform data, data structures, and data formats  | 2. Highly flexible temporal, spatial and stochastic settings  | Flexible and general formulation, rich in features | Developed with IRENA for the developing countries | ----: | 
| 3. Create scenarios from alternative values and parallelize the execution  | 3. Written in Julia, use Spine Toolbox as user interface   | Written in GAMS, no user interface (Excel + GDXXRW can be used)  | Written in AMPL+Python, can be used with Spine Toolbox or web interface  | ----: | 
|    | + SpineInterface package for quick model building using Julia JuMP   |  | |  | 


<img align="right" src=https://user-images.githubusercontent.com/112698385/232751058-070d3b05-b338-4e36-b85b-e0ceaf6361b7.png>

# Our best ideas to steal

1.	<b>Not everything in the model needs same resolution – not in space, not in time and not in probability.</b> Freedom to assign different resolution to different parts of the model makes it possible to create a TIMES-like economy model and a PLEXOS-type operational model with the same tool. As computational time is still a major issue on how wide and detailed we can make our models, being free to assign more resolution to the parts that matter expands modelling capabilities. In SpineOpt, the spatial, temporal and stochastic resolution can be freely assigned to different types of model.
2.	Invest optimizing without operational detail is like painting with the lights off. All modellers know it’s difficult to include operation detail in investment planning, but we believe it’s absolutely crucial and we have spent a lot of time on it.
3.	The model doesn’t have to care whether you model power, heat, gas or river systems. Agnostic and general representation of energy vectors allows for easy modelling of sectoral integration. When you want to model a new technology or a new sector, you don’t need to touch the model fundamentals. Of course most used constraints like power flow, heat transfer, hydrological inflow, and technologies are included in the framework for your convenience. 
4.	Maintain workflows, not models
5.	Using alternatives makes scenario building simpler.
6.	A modeller doesn’t have to be a coder.
7.	Open source is a strength.
8.	We like our models, but we are not the best at everything. So explore the open source models out there and combine the best in them.
