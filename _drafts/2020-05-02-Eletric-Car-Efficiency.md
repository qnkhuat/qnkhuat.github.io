---
layout: post
title: "How efficient are Electric Cars?"
categories: climate
permalink: ev
---

__TL;DR__ : Electric cars are __5__ times more energy efficient than fossil fuel powered cars.

Terms : 
- Electric cars : Cars powered by 100% electric.
- Combustion engine cars : Cars powered by fossil fuels (Gas or Diesel).
- Hybrid cars : Cars use more than 1 power source, often is a combination of fossil fuels and electric.
- L/100km : the unit of measurement for how many liters of fuel a car consumes to travel 100km. We'll use this number a lot to compare the efficiency of cars.

# Facts checking
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/top_fuel_consumption_by_sector_2019.png" style="width:100%" class="img-center">

This chart shows the comparision between 3 cars represent for 3 car types: Combustion engine, Electric and Hybrid. Each of them are the most fuel effcient in their league based on data from [United States Environmental Protection](https://www.epa.gov). They have been keeping track fuel economy of over 42000 car models since 1985.

Form the data we have Mitsubishit Mirage comsume about 6 Liters of Gasoline to travel 100km, It's __3.5__ times higher than the Tesla Model which consumes just 1.7L/100km.

With the hybrid Toyora Prius using both electric and gasoline consumes 4.2 L/100km, still __2.5__ times higher than Tesla Model 3.

## A broader aspect[(2)](#2)

One sample is hardly be able to speak for its industry, so this chart shows the fuel economy of each car industry from 1985 to 2020.
<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" 
    src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/gas_hybrid_electric_1985-2020.html" 
    height="525" width="100%"></iframe>

As of 2020, The Combusion Engine Cars Industry consumes 10.88 L/100km on average - __4.7__ times higher than the Electric Cars Industry which consumes 2.29 L/100km.

It's important to note that the Combustion Engine Cars Industry has started with the sucessful Ford Model T in 1908. And the first Electric Car were allowed to run on highway is Tesla Roadster in 2004.
It's almost one century ahead of development for Combustion Engine Cars.

# How do Electric cars achieve this efficiency?

##### TODO : add an explnation about kinetic energy

When we say Tesla Model 3 are more energy efficient than The Mitsubishi Mirage, it's just that The Tesla Model waste less of its input energy than the Mitsubishi Mirage.

Touching to the heart of this question is the problem of energy, and to tackle this problem it's necessary to recall The law of conservation of energy:
> Energy can neither be created nor destroyed; rather, it can only be transformed or transferred from one form to another.

Because there are good and bad energy based on the circumstances. For example when we drive a combustion engine car, much of its input energy were transformed to heat in the engine or thermal energy. There are no use of having thermal energy while driving a car, especially in a hot day.

So, the real question is where does the energy go when we drive a car? and how much of it are being wasted?

Most our energy are being used for these 3 tasks:
- Energy transformation
- Roll the wheels 
- Power Auxiliary systems

We'll now discover each task and its proportion in energy usage. To have a better illustration I'll fill Combustion Engine Car with a full tank of gasoline and Electric Car a fully charged battery. As we go through each tasks we will fill out its proportion in energy usage.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_full_fuel.png" style="width:100%" class="img-center">

## Energy transformation[(6)](#6)
Both Combustion engine and Electric Car Motor have the same purpose : It takes in energy in the form of chemical, transform it to kinetic energy. But there are a big different in how they do it.

Combustion engine work on the principle of the ideal gas law: it compresses gasoline then ignite it in order to generate an explosion inside the cylinder. The explosion propel the piston which is connected to the wheels through a crankshaft. A side effect of this process is it generates a lot of heat from the explosion and frictions between the piston and cylinder.
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_energy_conversion.png" style="width:100%" class="img-center">


## Roll the wheels 
A lot of our input energy are used to fight against the wind, that's why Elon Musk trying to build a hyperloop because there is no wind there baby.
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_to_wheels.png" style="width:100%" class="img-center">
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_to_wheels_with_rb.png" style="width:100%" class="img-center">

This is where the energy being used to do the real work including :
- Slow dow down using brakes
- Winning the traction between the cars and the road.
- Air resistance 


## Power Auxiliarary Electrical 
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_left_over.png" style="width:100%" class="img-center">


# Is it possible for a combustion engine to have 90% effiency?
No. 

Combustion engines are heat engines, therefor it's subjected to the laws of thermodynamics. The engines has to generate heats in order to generate kinetic engine, and there is an upperbound of how much heat can be turned to useful work. With gasoline the bound is 30%. That means, even at its theorerical best, a gasoline engine will still waste 70% of the input energy.

## Less maintainance
We need to take maintainance into account because there are a lot of energy being used for maintainance purposes. 

Thanks for its much simpler design, Electric cars don't have the complicated engine with 6, 8 or 12 pistons; No more manual or automatic transmission [(3)](#3). As the result, the car don't need spark plugs, fuel injector, filters, exhaust ...

Instead electric cars just have a battery and motors which are more durable and easier to repair or fix.

There are not much data on the cost to maintain an Electric car, but as pointed out in "Clean Disruption" by Tony Seba, it's safe to say Electric cars need 90-percent fewer repairs and maintaince works than combustion engines cars.


# Why do we care about fuel efficiency anyway?

# Is electric cars the final answer?
Luckily, it's not.

It'd be much better if we have a car powered by solar energy. In fact, we've had it, but the efficiency are low and range is too short to meet our need. When the solar energy are mature enough, we'd have the transition from electric cars to solar cars. 

Hopefully, It'd happen in my lifetime so I can write a post with title "How efficient are Solar Cars?".
# Footnotes
##### (1)
The numbers were estimated by [United States Environmental Protection](https://www.epa.gov) for 55% city and 45% highway driving.

The number of L/100km estimated for electric cars are the equivalent liters of gas to generate electric to power the car to travel 100km.
##### (2)
All the data used in this post are available [here](https://www.fueleconomy.gov/feg/download.shtml).
##### (3)
A motor delivers its maximum torque even at zero RPM, so it doesn't need a transmission to keep the engine operate at the peak range of torque like combustion engine cars.

This is one of the reason why the Tesla Model S P100D could go from 0-100km/h in 2.3 seconds, the same league with Bugatti Chiron or Lamborghinis.
##### (4)
[Where the Energy Goes: Gasoline Cars](https://www.fueleconomy.gov/feg/atv.shtml)
##### (5)
[Where the Energy Goes: Electric Cars](https://www.fueleconomy.gov/feg/atv-ev.shtml)

##### (6)
[Energy Conversion Effiency](https://en.wikipedia.org/wiki/Energy_conversion_efficiency)


#####(7)
[Principles of Combustion engine](https://energyeducation.ca/encyclopedia/Internal_combustion_engine)


This ratio tell how effective the cars use the input energy(in the form of gas or electric). For example if $$\eta_{e} = 30\%$$ means just 30% of the input energy are converted to useful energy which put our car to move, 70% are wasted energy like heat or swirling the air.
<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" 
    src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_conversion.html" 
    height="525" width="100%"></iframe>
<div class='image-latex' style="overflow:auto">
<figure style="width:30%; float:left; margin-right:10px">
    <img src="/assets/img/posts/energy_efficiency.png" />
    <figcaption style='text-align:center; font-size:13px; color:gray;'>Fuel efficiency</figcaption>
</figure>

The formula is simple : $$\eta_{e} = {E_{out} \over E_{in}}$$
<br>
<br>
In which $$E_{out}$$ are the actual energy that push our car to move, we call this kinetic energy in physic .
<br>
<br>
$$E_{in}$$ are the energy that we input to the car. For combustion engine cars It's gasoline/dielse. For electric cars, well, It's Electric. 
</div>

|              | Combustion Engine Cars | Electric Cars |
|--------------|------------------------|--------------|
| $$\eta_{e}$$ | 12-30%[(4)](#4) | 60-73%[(5)](#5)   |




To be able to answer this question we need to review the Law of conservation of energy:
> Energy can neither be created nor destroyed; rather, it can only be transformed or transferred from one form to another.

In the physics world, driving a car is about transfomring energy from one from to another:
- Acceleration : Chemical to Kinetic energy and thermal energy as loss 
- Slowing Down : Kinetic Energy to heat on the brakes


## Clarification

It might be confused to some when we use the L/100km unit for electric cars. The use of this unit is to have a

Even though Electric Cars don't use fuel directly, The number L/100km for electric cars is the equivalent liters of gas to generate electric to run 100km.



NOTE For the graph
- the last graph text are too small
    - don't use text - {percentage} people might mistaken it is a minus sign
