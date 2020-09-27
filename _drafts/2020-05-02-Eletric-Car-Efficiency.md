---
layout: post
title: "How efficient are Electric Vehicles?"
categories: climate
permalink: ev
---

__TL;DR__: Electric Vehicles are __5__ times more energy efficient than fossil Fuel powered Vehicles.

Terms : 
- Electric Vehicle (EV): Vehicles powered by 100% electric.
- Internal Combustion Engine Vehicle (ICE Vehicle) : Vehicles powered by fossil fuels (Gas or Diesel).
- Hybrid Vehicle (HV) : Vehicles use more than 1 power source, often is a combination of fossil fuels and electric.
- L/100km : the unit of measurement for how many liters of fuel a vehicle consumes to travel 100km. We'll use this number to compare the efficiency of vehicles.

# Facts checking
<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/top_fuel_consumption_by_sector_2019.png" style="width:100%" class="img-center">

This chart shows the comparision between 3 cars represent for 3 vehicle types: ICE Vehicles, EVs, Hybrid Vehicles. Each of them are the most fuel effcient in their league based on data measured by [United States Environmental Protection](https://www.epa.gov). They have been keeping track fuel economy of over 42000 cars models since 1985.

Best in ICE league is the Mitsubishit Mirage, It comsumes about 6 Liters of Gasoline to travel 100km, It's __3.5__ times higher than the Tesla Model 3 which consumes just 1.7L/100km.

Even With the hybrid Toyora Prius using both electric and gasoline consumes 4.2 L/100km, still __2.5__ times higher than Tesla Model 3.

## A broader aspect[(2)](#2)

One car model is hardly be able to speak for its industry, so this chart shows the fuel economy of each Automotive Industry from 1985 to 2020.
<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" 
    src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/gas_hybrid_electric_1985-2020.html" 
    height="525" width="100%"></iframe>

As of 2020, The ICE vehicles Industry consumes 10.88 L/100km on average - __4.7__ times higher than the EVs Industry which consumes 2.29 L/100km.

It's important to note that the ICE Vehicles Industry has started with the sucessful Ford Model T in 1908, and the first EV were allowed to run on highway is Tesla Roadster in 2004.
It's almost one century ahead of development for ICE vehicles.

## Clarification

I try to write my essays in the way I deliver facts, so I want to clarify about our unit of comparision - __L/100km__.
Primarly, this unit is used to measure the fuel economy of ICE vehicles, for EVs we often use __km/kWh__.
But I'll keep using the unit __L/100km__ when discussing about fuel economy of both EVs and ICE vehicles. 

The __L/100km__ for EVs are the equivalent liters of gasoline to generate electric for an EV to travel 100km. 
The advantage of using a single unit of comparision is it helps us easily understand and visualize the difference between ICE and EV vehicles in energy consumption. 

# So, How EVs are 4.7 times more efficient than ICE vehicles?

When we say Tesla Model 3 are more energy efficient than Mitsubishi Mirage, it's just that The Tesla Model 3 waste less of its input energy than the Mitsubishi Mirage.
Touching to the heart of this question is the problem of energy, and to fully understand and answer it, we need to recall The law of conservation of energy:
> Energy can neither be created nor destroyed; rather, it can only be transformed or transferred from one form to another.

This mean there are good and bad energy based on which situation it is produced.
For example when we drive an ICE vehicle, much of our input energy were transformed to heat in the engine (or thermal energy).
Clearly there are not much use of having thermal energy while driving a car; what we need is __kinetic energy__.

So, let's dive deeper to understand where does the energy go when we drive a car and find out how much of it is being wasted?

Turns out, Most the energy are used for these 3 tasks:
- Energy transformation
- Overcome rolling and air resistant
- Warming, cooling, electric drive systems, etc...

We'll now discover each task and to have a better illustration, I'll fill ICE Vehicle with a full tank of gasoline and EV a fully charged battery.
As we go through each tasks we will fill in its proportion in energy usage.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_full_fuel.png" style="width:100%" class="img-center">

## Energy transformation[(6)](#6)
Both ICE and EV's Motor do the same thing: they take in chemical energy and transform it to __kinetic energy__. But the different is in their underlying mechanisms that lead to the different in effciency.

### Internal Combusion Engine
The working principles of an ICE vehicle consists of 2 main steps:
1. Motion generation
2. Motion transportation

The step 1) happens inside our engine - a machine consists of multiple pairs of piston-cylinder. 

Here is a short explanation of how an ICE works:
- ICE work on the principle of the ideal gas law: Raising the temperature of a gas increases the pressure that make the gas want to expand.
- Using this principle, we mix air with gasoline then compress it inside our cylinders by a piston.
- The compression enforce the mixture of gasoline and air to explode. This explosion propel the pistons in a linear motion.
- Convert the linear motion to rotational motion by connect pistons to a crankshaft.
- Ultimately, the rotational motion will be transfered to the wheels via a transmission.



One of ICE's limitations is it can only produces maximum [torque](#torque) at a small range of RPM(Revolutions per minute), but we need the car to run at various speed range. 
That's why ICE vehicles need a tranmission to adapt the output of engine with the vehicle's speed.

The side effect of ICE's powertrain is it has to generate a lot of heat from the explosion to produce work.
And by "a lot" we are talking about __74%__ of the input energy is wasted in the form of heat. Or the effiency of ICE engine is __26%__.

I need you to remember this number because it shows how ineffective the ICE is. 
Think of the engine as our digestion system, if it has the effiency of 26% that mean only 26% calories of what we eat is being used for walking, thinking, imagining... 74% is used by our digest system for converting raw food to energy. 
For a man that needs 2500 Calories a day he has to ingest 9600 Calories, which is equal to : 62 eggs or 3.84 Kg of beef or 23L of cow's milk. 

### Electric Motor
The successes of most electric vehciles are powered by the three-phase Induction Motor and Alternating-Current(AC) Power invented by Nikola Tesla.

An Induction Motor consists of: 
- A Stator, the fixed part of induction motor that is connected to the battery.
- A Rotor, the rotating part placed inside the stator and connect to the wheels.

In a three-phase Induction Motor there are 3 wires arranged in a way that they are each shifted 120° from each other, and each of them are connected to an AC power.
When an AC current is provided, the 3 wires together create a Rotating Magnetic Field(RMF) that will rotate the rotor inside it.
We then just need to connect the rotor to the wheels to have our vehicle rolling.

By principles, the induction motor can produce maximum torque even at 0 RPM. 
There for we rarely see the use of transmission in side an EV. 
This is one of the reasons why the Tesla Model S P100D can go from 0-100km/h in 2.3 seconds - on the same league with Bugatti Chiron.

<figure class='img-center' style="width:40%">
    <img src="/assets/img/posts/tesla_owner.jpg" />
    <figcaption style='text-align:center; font-size:13px; color:gray;'>This is a good one</figcaption>
</figure>

There is a missing piece, Our battery can't directly provide an AC current, we need to use a converter to convert from DC to AC. 
This converter also act as the speed controller of the motor. By changing the frequency of the AC current, it'll change the speed of RMF and result in changing rotational speed of our rotor.

Going through this process (including the loss in DC/AC converter), the Induction Motor loses less than 20% of its input energy to heat. With some systems, the induction motor even lose just 1% of its input energy.

To recap about energy transformation: ICE vehicles lose 74% of input energy and it is 20% for EVs.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_energy_conversion.png" style="width:100%" class="img-center">


## Overcome rolling and air resistant

We have made the energy reached our wheels, this is the part where we use those energy to:
- Overcome road friction
- Swirling air
- Speeding up then slowing down using brakes

### Overcome road friction

By definition, friction is the force resisting the relative motion between surfaces sliding against each others, in our case it's the vehicle's tyres and the road.
Without friction, we can't move our vehicles, and even if we can, our vehicle will slide and spin unstoppably on the road.
That's also mean we need to use energy to overcome friction in order to move.
This force is proportional to the vehicle's weight, independent of speed or vehicle's type.

How much of energy we have to use is proportional to the vehicle's weight, independent of speed or vehicle's type. The constant of proportionality is called the coeffcient of rolling resistance. For cars, this coefficient


### Swirling air

While the vehicle is moving, it makes air swirling around and leaves behind a tube of air moving with the similar speed of the car. 
That mean the faster the car move, the more energy is used to swirl air.
<figure class='img-center' style="width:40%">
    <img src="/assets/img/posts/car_swirling_air.png" />
    <figcaption style='text-align:center; font-size:13px; color:gray;'>Car swirl air while moving (Source: https://www.withouthotair.com)</figcaption>
</figure>

There are numbers of way to reduce energy usage in swirling air:
- Slower driving 
- Reduce the frontal area
- Round the edges of the frontal end
- Use less friction materials for vehicle's frame
- Install rear spoiler - like most sport cars do
- Lower the vehicle
- Use narrower tires

This is where the study of areodynamics come in, much of it is about how we design the shape of our vehicle in the way that make it easier to pass throuh air. 
There is a measure called drag coefficient that tell how efficient a vehicle passes through air or water while moving. 
Drag coefficient is often achieved by practicle measurements, and show high correlation toward fuel economy of the vehicles.

Both Swirling air and overcome road friction is classied as good use of energy while driving car, so here is its proportion in energy consumption.

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_to_wheels.png" style="width:100%" class="img-center">

### Speeding up then slowing down using brakes
When we accelerate the engine gives the car kinetic energy and braking throws that kinetic energy away. Especially in city-driving, we waste a lot of energy for this process. 

But here is an interesting but straight forward  question: Can we capture those thrown away energy?

With ICE vehicles it's not much we can do because most of the energy kinetic energy has been converted to heat on the brake already. 
But with Induction Motor we can recover up to 70% of the braking energy with regenerative braking.

The principle of Regerative braking is when you take your foot of the pedal, you cut power to the motors, this make the motor slow down. 
Now the wheels are rotating faster than the motor, when this happens, the motor turn itself into a generator and re-charge energy to the battery.

With the re-generative braking system we can now recover about up to 34% for city driving and about 17% for both city and highway driving combined

<img src="https://qnkhuat.github.io/plotly-charts/ev-vs-ce/plots/where_is_the_energy_go_power_to_wheels_with_rb.png" style="width:100%" class="img-center">

## Power Auxiliary systems

ruxiliary systems is a term refered to 


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

https://www.edmunds.com/fuel-economy/improving-aerodynamics-to-boost-fuel-economy.html

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



