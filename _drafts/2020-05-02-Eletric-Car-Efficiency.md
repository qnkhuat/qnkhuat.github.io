---
layout: post
title: "How efficient are Electric Vehicles?"
categories: climate
permalink: ev
---

__TL;DR__ : Electric Vehicles are __5__ times more energy efficient than fossil Fuel powered Vehicles.

Terms : 
- Electric Vehicle (EV): Vehicles powered by 100% electric.
- Internal Combustion Engine Vehicle (ICE Vehicle) : Vehicles powered by fossil fuels (Gas or Diesel).
- Hybrid Vehicle (HV) : Vehicles use more than 1 power source, often is a combination of fossil fuels and electric.
- L/100km : the unit of measurement for how many liters of fuel a vehicle consumes to travel 100km. We'll use this number to compare the efficiency of vehicles.

# Facts checking
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/top_fuel_consumption_by_sector_2019.png" style="width:100%" class="img-center">

This chart shows the comparision between 3 cars represent for 3 vehicle types: ICE Vehicles, EVs, Hybrid Vehicles. Each of them are the most fuel effcient in their league based on data from [United States Environmental Protection](https://www.epa.gov). They have been keeping track fuel economy of over 42000 cars models since 1985.

Best in ICE league, The Mitsubishit Mirage comsume about 6 Liters of Gasoline to travel 100km, It's __3.5__ times higher than the Tesla Model 3 which consumes just 1.7L/100km.

Even With the hybrid Toyora Prius using both electric and gasoline consumes 4.2 L/100km, still __2.5__ times higher than Tesla Model 3.

## A broader aspect[(2)](#2)

One car model is hardly be able to speak for its industry, so this chart shows the fuel economy of each Automotive Industry from 1985 to 2020.
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
Touching to the heart of this question is the problem of energy, and to fully understand and answer the question, it's necessary to recall The law of conservation of energy:
> Energy can neither be created nor destroyed; rather, it can only be transformed or transferred from one form to another.

There are good and bad energy based on when and why. 
For example when we drive an ICE vehicle, much of its input energy were transformed to heat in the engine (or thermal energy). 
Clearly there are not much use of having thermal energy while driving a car, what we want is __kinetic energy__.

So, the real question is where does the energy go when we drive a car? and how much of it is being wasted?

Turns out, Most the energy are used for these 3 tasks:
- Energy transformation
- Overcome rolling and air resistant
- Power Auxiliary systems

We'll now discover each task and its proportion in energy usage.
To have a better illustration I'll fill ICE Vehicle with a full tank of gasoline and EV a fully charged battery.
As we go through each tasks we will fill out its proportion in energy usage.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_full_fuel.png" style="width:100%" class="img-center">

## Energy transformation[(6)](#6)
Both ICE and EV's Motor have the same purpose: they take in energy in the form of chemical and transform it to __kinetic energy__. But the different is in their underlying mechanisms that lead to the different in effciency.

### ICE
ICE work on the principle of the ideal gas law, meaning by raising the temperature it'll increases the pressure and cause the gas to expand. 

Here is a short (thougth still complexed) explanation of how an ICE works: The powertrain starts by compressing gasoline and ignite it to generate an explosion within the cylinders. 
The explosion proppel pistons in a linear motion then being converted to rotational motion by connect pistons with a crankshaft.
The rotational motion of crankshaft is then being passed through a transmission.
Ultimately, this motion drives the vehicle's wheels.

Because ICE can only produce maximum torque at a small range of RPM(Revolutions per minute), so we have to use a transmission to keep the engine operates at its most effectie RMP while allowing the wheels to rotate at various speed.

The side effect of ICE's process is it has to generate a lot of heat from the explosion in order to produce work.
And by "a lot" we are talking about __68-80%__ of the input energy has been wasted in the form of heat.

### Electric Motor
The successes of most electric vehciles are powered by the three-phase Induction Motor and Alternating-Current(AC) Power invented by Nikola Tesla.

An Induction Motor consists of: 
- A Stator, the fixed part of induction motor that is connected to the battery.
- A Rotor, the rotating part placed inside the stator and connect to the wheels.

In a three-phase Induction Motor there are 3 wires arrange in a way that they are each shifted 120° from each other, and each of them are connected to an AC power. 
Interestingly as it is when an AC current is provided, the 3 wires create a Rotation Magnetic Field(RMF) that will rotate the rotor inside it. 
We then just need to connect the rotor to the wheels to have our vehicle rolling.

Because the induction motor can produce maximum torque at 0 RPM. 
There for, we rarely see the use of transmission in side an EV. 
This is one of the reason why the Tesla Model S P100D can go from 0-100km/h in 2.3 seconds - on the same league with Bugatti Chiron.

<figure class='img-center' style="width:40%">
    <img src="/assets/img/posts/tesla_owner.jpg" />
    <figcaption style='text-align:center; font-size:13px; color:gray;'>This is a good one</figcaption>
</figure>

There is a missing piece, Our battery can't directly provide an AC current, we need to use a converter to convert from DC to AC. 
This converter also act as the speed controller of the motor. By changing the frequency of the AC current, it'll change the speed of RMF which will change the speed of our rotor.

Going through this process (including the loss in DC/AC converter), the Induction Motor lose less than 20% of its input energy to heat. With some systems, the induction motor even lose just 1% of its input energy.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_energy_conversion.png" style="width:100%" class="img-center">

## Overcome rolling and air resistant

We have make the energy reached our wheels, this is the part we use those energy to:
- Swirling air
- Overcome road friction
- Speeding up then slowing down using brakes

### Swirling air

While the vehicle is moving, it makes air swirling around and leaves behind a tube of air moving with the similar speed of the car. 
That mean the faster the car move the more energy is used to swirl air.
<figure class='img-center' style="width:40%">
    <img src="/assets/img/posts/car_swirling_air.png" />
    <figcaption style='text-align:center; font-size:13px; color:gray;'>Car swirl air while moving</figcaption>
</figure>

In automotive design there is a measure called drag coefficient that basically tell how good a vehicle passes through air while moving.
And to reduce the energy of car in swirling air, it's the study of aerodynamics, not about whether the vehicle is powered by electric or fossil fuel. 
Therefor we'll not discuss further about this topic in this essay.

### Overcome road friction

Without friction, we can't move our vehicles, and even if we can, our vehicle will slide and spin unstoppably on road. The only way to stop is crashing to an object that are sticked to ground( we can't crash to a rock though because without the friction the car and the rock will continue to slide together ).

That's also mean we need to use energy to overcome friction in order to move, and how much of energy we have to use is proportional to the vehicle's weight, independent of speed or type of vehicles.

Both Swirling air and overcome road friction is classied as good use of energy while driving car, so here is its proportion in energy consumption.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_to_wheels.png" style="width:100%" class="img-center">

### Speeding up then slowing down using brakes
When we accelerate the engine gives the car kinetic energy and braking throws that kinetic energy away, this is why high-way drive consumes less energy than city-driving.

But here is an interesting idea: why don't we capture that thown away kinetic energy?

With ICE vehicles it's not much we can do because most of the energy kinetic energy has been converted to heat on the brake already. 
But with Induction Motor we can recover up to 70% of the braking energy with regenerative braking.

The principle of Regerative braking is when you take your foot of the pedal, you cut power to the motors, this make the motor slow down. 
Now the rotational speed of the wheels is faster than the rotational of the motor, when this happens, the motor turn into a generator and charge energy back to the battery.

It is curicial especially for city-driving, because the we have the cycle of speeding up and slowing down is very short. With the re-generative braking system we can now recover about 17% of our input energy.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_to_wheels_with_rb.png" style="width:100%" class="img-center">

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
As of 2010, Transportation is accounted for 14% of the total Greenhouse Gas(GHG) Emissions globally and it's heavily depends on burning fossil fuels. 
So if we can find a more effience way of transportation that mean will can still keep our our need to transport but reduce our GHG emissions.

# Is electric vehicles the final answer?
I believe, it's not.

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

##### (8)
[Combustion Engine Basic](https://www.energy.gov/eere/vehicles/articles/internal-combustion-engine-basics)


#### a
[How Does An Electric Motor work](https://www.saveonenergy.com/how-does-electric-car-motor-work/)


https://www.tesla.com/blog/magic-tesla-roadster-regenerative-braking

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



