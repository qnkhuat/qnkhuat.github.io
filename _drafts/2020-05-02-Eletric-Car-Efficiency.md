---
layout: post
title: "How efficient are Electric Vehicles?"
categories: climate
permalink: ev
---

__TL;DR__ : Electric Vehicles are __5__ times more energy efficient than fossil Fuel powered Vehicles.

Terms : 
- Electric Vehicle (EV): Vehicles powered by 100% electric.
- Internet Combustion Engine Vehicle (ICE Vehicle) : Vehicles powered by fossil fuels (Gas or Diesel).
- Hybrid Vehicle (HV) : Vehicles use more than 1 power source, often is a combination of fossil fuels and electric.
- L/100km : the unit of measurement for how many liters of fuel a vehicle consumes to travel 100km. We'll use this number to compare the efficiency of vehicles.

# Facts checking
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/top_fuel_consumption_by_sector_2019.png" style="width:100%" class="img-center">

This chart shows the comparision between 3 cars represent for 3 vehicle types: ICE Vehicles, EVs, Hybrid Vehicles. Each of them are the most fuel effcient in their league based on data from [United States Environmental Protection](https://www.epa.gov). They have been keeping track fuel economy of over 42000 cars models since 1985.

The Mitsubishit Mirage comsume about 6 Liters of Gasoline to travel 100km, It's __3.5__ times higher than the Tesla Model which consumes just 1.7L/100km.

With the hybrid Toyora Prius using both electric and gasoline consumes 4.2 L/100km, still __2.5__ times higher than Tesla Model 3.

## A broader aspect[(2)](#2)

One car is hardly be able to speak for its industry, so this chart shows the fuel economy of each Automotive Industry from 1985 to 2020.
<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" 
    src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/gas_hybrid_electric_1985-2020.html" 
    height="525" width="100%"></iframe>

As of 2020, The ICE vehicles Industry consumes 10.88 L/100km on average - __4.7__ times higher than the EVs Industry which consumes 2.29 L/100km.

It's important to note that the ICE Vehicles Industry has started with the sucessful Ford Model T in 1908. And the first EV were allowed to run on highway is Tesla Roadster in 2004.
It's almost one century ahead of development for ICE vehicles.

## Clarification

I try to write my essays in the way I deliver facts, In order to achieve this I need to clarify about our unit of comparision - __L/100km__. Primarly, this unit is used to measure the fuel economy of ICE vehicles, For EVs we often use __km/kWh__.
But I'll keep using the unit __L/100km__ when discussing about fuel economy of EVs. 

The __L/100km__ for EVs are the equivalent liters of gasoline to generate electric for an EV to travel 100km. 
The advantage of using a single unit of comparision is it helps us easily understand and visualize the difference between ICE and EV vehicles in energy consumption. 

# How do EVs achieve this efficiency?

When we say Tesla Model 3 are more energy efficient than Mitsubishi Mirage, it's just that The Tesla Model 3 waste less of its input energy than the Mitsubishi Mirage.
So, Touching to the heart of this question is the problem of energy, and to tackle this problem it's necessary to recall The law of conservation of energy:
> Energy can neither be created nor destroyed; rather, it can only be transformed or transferred from one form to another.

There are good and bad energy based on circumstances. For example when we drive an ICE vehicle, much of its input energy were transformed to heat in the engine (or thermal energy). There are no use of having thermal energy while driving a car, what we need is kinetic energy.

So, the real question is where does the energy go when we drive a car? and how much of it is being wasted?

Turns out, Most the energy are used for these 3 tasks:
- Energy transformation
- Roll the wheels 
- Power Auxiliary systems

We'll now discover each task and its proportion in energy usage. To have a better illustration I'll fill ICE Car with a full tank of gasoline and Electric Car a fully charged battery. As we go through each tasks we will fill out its proportion in energy usage.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_full_fuel.png" style="width:100%" class="img-center">

## Energy transformation[(6)](#6)
Both ICE and EV's Motor have the same purpose: It takes in energy in the form of chemical, transform it to kinetic energy. But the a different is its underlying mechanism.

### ICE
ICE work on the principle of the ideal gas law, meaning by raising the temperature of a gas it'll increases the pressure and make the gas want to expand. 

Here is a short(thougth still complexed) explanation of how an ICE works: By compressing gasoline and ignite it the engine generate an explosion inside the cylinders.
The explosion then propel the pistons which connected to a crankshaft to generate a rotation motion.
The Rotation motion is then passed through the tranmission. Finally the wheels are connected to the transmission to move the vehicle.

The purpose of having a tramission is to keep the engine perform at it most effiecny RPM (Revolutions per Minute) range so that the engine is not overloaded and wasted too much fuel.

The side effect of this process is it generates a lot of wasted heat from the explosion and frictions between the piston and cylinder. By "a lot" we are talking about 68-80% of our input energy has been turned to heat. 

### Electric Motor
The successives of Tesla cars is powered by the three-phase Induction Motor technology and Alternating-Current(AC) Power transmission invented by Nikola Tesla.

An Induction Motor consists of 2 parts : 
- A Stator is a fixed part of induction motor that connected to the battery.
- A rotor is a rotating part that placed inside the stator.

When the stator is passed with an AC current, It'll create a Rotation Magnetic Field(RMF) that will rotate the rotor inside. We then just need to connect the rotor to the wheels.
Since the induction motor work at effectively at a wide range of RPM, there for, in a typical EV we are not going to see any transmission.

Going through this process, the Induction Motor just lose less than 20% of its input energy to heat. With some systems, the induction motor even lose just 1% of its input energy.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_energy_conversion.png" style="width:100%" class="img-center">

## Roll the wheels 
NOTE: Skim through what air resistance, rolling resistance is and that is not actually the matter of machien technology to improve this but it's about the arodynamic of the cars and tire effiency.

What make it different is the regen braking system.

So, our input energy has reached our wheels, This is the part where the energy are being used to:
- Winning the friction between the tires and road
- Moving the air


As interesting as these 2 topics are, there are no
A lot of our input energy are used to fight against the wind, that's why Elon Musk trying to build a hyperloop because there is no wind there baby.
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_to_wheels.png" style="width:100%" class="img-center">
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_to_wheels_with_rb.png" style="width:100%" class="img-center">

This is where the energy being used to do the real work including :
- Slow dow down using brakes
- Winning the traction between the vehicles and the road.
- Air resistance 

But there are an important factor that makes EVs awesome: Regenerative brake technology.
By principles, when ever the rotor rotate faster than the Rotation Magnetic Field, the Induction Motor will turn to be a generator that can re-charge the battery. So when ever we slowing down or going down hill, the car will re-charge itself.

This is very effieciece especially for city-driving when we use energy to accelerate then waste that energy with break repeatedly. Now with the re-generative braking system we can recover about 17% of our input energy. And the cool thing is we could go mostly with the the pedal in EVs.

## Power Auxiliarary Electrical 
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_left_over.png" style="width:100%" class="img-center">


# Is it possible for a ICE to have 90% effiency?
No. 

ICE are heat engines, therefor it's subjected to the laws of thermodynamics. The engines has to generate heats in order to generate kinetic engine, and there is an upperbound of how much heat can be turned to useful work. With gasoline the bound is 30%. That means, even at its theorerical best, a gasoline engine will still waste 70% of the input energy.

`Cite references`

## Less maintainance
We need to take maintainance into account because there are a lot of energy being used for maintainance purposes. 

Thanks for its much simpler design, EVs don't have the complicated engine with 6, 8 or 12 pistons; No more manual or automatic transmission [(3)](#3). As the result, we no longer need spark plugs, fuel injector, filters, exhaust...

Instead EVs just have a battery and motors which are more durable and easier to repair or fix.

There are not much data on the cost to maintain an EV, but as pointed out in "Clean Disruption" by Tony Seba, it's safe to say EVs need 90-percent fewer repairs and maintaince works than ICE vehicle.


# Why do we care about fuel efficiency anyway?

# Is electric vehicles the final answer?
I hope, it's not.

It'd be much better if we have vehicles powered by solar energy. In fact, we've had it, it's just that the efficiency are low and the range is too short to meet our need. But when the solar energy are mature enough, we'd have the transition from EVs to solar powered vehicles. 

Hopefully, It'd happen in my lifetime so I can write a post with title "How efficient are Solar Vehicles?".
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

##### (7)
[Principles of Combustion engine](https://energyeducation.ca/encyclopedia/Internal_combustion_engine)

https://matter2energy.wordpress.com/2013/02/22/wells-to-wheels-electric-car-efficiency/

This ratio tell how effective the cars use the input energy(in the form of gas or electric). For example if $$\eta_{e} = 30\%$$ means just 30% of the input energy are converted to useful energy which put our car to move, 70% are wasted energy like heat or swirling the air.

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



