---
layout: post
title: "How efficient are Electric Cars?"
categories: climate
permalink: ev
---

__TL;DR__ : Electric cars are __5__ times more energy efficient than fossil fuel powered cars.


Terms : 
- Electric cars : Cars powered by 100% electric.
- Combustion engine cars : Cars powered by fossil fuels (__Gas__ or __Diesel__).
- Hybrid cars : Cars use more than 1 power source, often is a combination of fossil fuels and electric.
- L/100km : the unit of measurement for how many liters of fuel a car consumes to travel 100km. We'll use this number a lot to compare the efficiency of cars.

__Facts checking__
<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" 
    src="https://qnkhuat.github.io/ploty-charts/ev-vs-ce/plots/top_fuel_consumption_by_sector_2019.html" 
    height="525" width="100%"></iframe>

Using data form [United States Environmental Protection](https://www.epa.gov) contains measurements of 42231 car models since 1985, I've picked the 3 most fuel-efficient sedan cars in 3 categories.

Eventhough Electric Cars don't use fuel directly, The number L/100km for electric cars indicate the equivalent liters of gas to generate electric for a car to run 100km.

Looking at the chart we have the Mitsubishi Mirage consumes 6 L/100km - __3.5__ times higher than the Tesla Model 3 which consumes just 1.7 L/100km.

Even with the hybrid Toyora Prius which are very popular in the US consumes 4.2 L/100km, still __2.5__ times higher than Tesla Model 3.

__How about the whole industry?__[(2)](#2)
<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" 
    src="https://qnkhuat.github.io/ploty-charts/ev-vs-ce/plots/gas_hybrid_electric_1985-2020.html" 
    height="525" width="100%"></iframe>

As of 2020, The Combusion Engine Cars Industry consumes 10.88 L/100km on average - __5__ times higher than the Electric Cars Industry which consumes 2.29 L/100km.

Let's not forget the Combustion Engine Cars Industry has started with the sucessful Ford Model T in 1908, And The first Electric Car that allowed to run on highway is Tesla Roadster in 2004, About 100 years gap of development.

# How do Electric cars achieve this efficiency?
Whenever we talk about energy, we need to remember the Law of conservation of energy : 
> Energy can neither be created nor destroyed; rather, it can only be transformed or transferred from one form to another.

What that means is when we consider a closed system like : a phone with 100% battery. That 100% battery is the fixed amount energy of the system existing in the form of checmical energy. As we use our phone, The phone transformed checmical energy to electrical energy to power the processors, light up the screen and part of it is transformed to heat.

Overtime time your battery will ran out but all the transformed energy in form of electrical, light, heat still add up to the original 100% battery exist in chemical form.

With that being said, not all form of energy are useful to us. So, At the end of this section, we will find fuel efficiency ratio ($$\eta_{e}$$) of Combustion Engine and Electric Cars. 

This ratio reflect how effective the cars use the input energy(in the form of gas or electric), for example if $$\eta_{e} = 30\%$$ means just 30% of the input energy are converted to kinetic energy which put our car to move, 70% are wasted energy like heat or swirling the air.

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
$$E_{in}$$ are the energy that we input to the car. For combustion engine cars It's gasoline/Dielse. For electric cars it's, well, Electric. 
</div>

To measure this ratio, we need to understand where the energy wasted in a car. There are 3 major sources of energy waste:
- Energy conversion
- Power to wheels
- Auxiliary systems

## Energy conversion

|              | Combustion Engine Cars | Electric Cars |
|--------------|------------------------|--------------|
| $$\eta_{e}$$ | 12-30%[(4)](#4) | 60-73%[(5)](#5)   |

The Combustion Engine are an ineffective machine, most of the energy are converted to thermal energy which basically means heat.

## Power to Wheels



# Less maintanace
Due to its much simpler design, Electric cars don't have the complicated engine with 6, 8 or 12 pistons; No more manual or automatic transmission [(3)](#3). As the result, the car don't need spark plugs, fuel injector, filters, exhaust ...

Instead electric cars have a battery and motors which are more durable and easier to repair or fix.

There are not much data on the cost to maintain an Electric car, but as pointed out in "Clean Disruption" by Tony Seba: Electric cars need 90-percent fewer reparis and maintaince works than combustion engines cars.

# Is it possible for a combustion engine to have 90% effiency?
No. 

Combustion engines are heat engines, therefor it's subjected to the laws of thermodynamics. The engines has to generate heats in order to generate kinetic engine, and there is an upperbound of how much heat can be turned to useful work. With gasoline the bound is 30%. That means, even at its theorerical best, a gasoline engine will still waste 70% of the input energy.
# Funfact about the development of fossil fuel cars
There is an inevitable future that Electric cars will replace Combustion Engine Cars just like how smart phones replace "stupid" phones for a greater good.


# Is electric cars the final answer?
No, of course not. 

It'd be much better if we have a car powered bysolar energy. In fact, we've had it, but the efficiency are low and range is too short to meet our need. When the solar energy are mature enough, we'd have the transition from electric cars to solar cars. 

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
