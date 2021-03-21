# A Robot Mole to Tackle Climate Change


Developing technologies and shifting human activities to carbon-free alternatives while maintaining a high standard of living is the key to successfully tackling climate change. One of the best examples of this challenge is heating our homes - an essential activity for anyone living in northern climates or high altitudes, a human activity so old it predates our species. It is also, rightly, one of the biggest anxieties people express when discussing climate change - if we have to stop burning fossil fuels, how will we heat our houses?



## Summary

* Heating is a large source of emissions in northern climates.
* Unlike EVs, fossil fuels are very efficient for heating.
* Geothermal systems are the only climate-friendly option, but very expensive.
* Cheap goundloop installation can make geothermal systems cheaper than gas furnaces.
* A robotic mole can tackle this challenge.

## Background
Heating is a very stubborn and intractable problem when it comes to climate change. While there are other ways to produce heat, burning fossil fuels, particularly natural gas, is a simple, cheap and efficient way to do it. The recent success of electric vehicles offers a stark contrast. EVs are inherently efficient, as an electric motor is able to convert upwards of 90% of the energy supplied to useful mechanical work. Combustion engines found in cars have much lower efficiencies - only around 25-30% of the energy contained in the fuel is converted to useful mechanical work, and the rest wasted as heat, friction, and noise. Cheap batteries have allowed manufacturers to take advantage of this natural efficiency and offer superior cars that are vastly cheaper to operate.

While fossil fuels are inefficient for mechanical work, they are very efficient when it comes to producing heat. A regular household furnace is easily more than 90% efficient in extracting heat from its fuel. None of the recent climate-related developments, from cheap solar panels to cheap batteries to carbon taxes, can help us overcome this natural advantage.

 ![Ground Temperatures from https://doi.org/10.4224/40000712](/heating/robot-mole-chart-2.png)
## Options
There are three ways to heat a house: 

1. Burn fossil fuels.

2. Convert electrical energy to heat using a resistor.

3.  Use electricity to power a heat pump, which transfers heat from the outside to the inside. 

Fossil fuels take a variety of forms, including wood, coal, heating oil, and natural gas. While the prices, availability and efficiency of these fuels vary, natural gas is the best and the benchmark against which fuels should be compared. For example, in Ontario, widely available, inexpensive, and highly efficient (95%+) furnaces cost $3000-$5000. Operating costs are fairly low, at $0.12 per m^3 or ~10kWh, compared to $1.20 per 10kWh of electricity.

The second way to heat homes is by running electricity through a resistor to produce heat, similar to an electric oven . This is a simple and cheap setup, however it is usually costly to operate. While resistive heating is technically very efficient, in that 100% of the electrical energy is turned into heat, it does not account for losses from the actual source of electricity production. It also requires a lot of electricity. Given the prices for electricity, resistive heating often ends up costing several times more than a natural gas furnace. This makes it suitable for niche applications, such as mild climates that require only occasional heating, but not ideal as a general solution for cold climates. 

The final method is using an electrically powered heat pump to move heat from outside the house to the inside. Because heat pumps merely move heat, it is possible for 1 unit of electrical energy to effectively produce up to 4.5 units of heating energy. This efficiency is driven largely by the temperature difference between the outside and the inside - the greater the difference, the more work the pump has to do to move heat, and the less efficient it is. 

There are two types of heat pumps - air source and geothermal. Air source heat pumps get their heat from the outside air. This makes them cheaper and easier to install, as they are basically a reverse-AC. However, they are not able to work in colder climates, as there simply isn’t enough heat in the air to transfer inside the house during winter.

## Geothermal Is The Only Way
Geothermal systems (ground-source heat pumps) have a coolant-filled heat-exchange loop buried under the ground to take advantage of the fact that a few metres underground, the temperature stays near constant year-round. Heating systems have to be able to handle the minimum outside temperature a house is likely to encounter, but the average is typically much higher. For example, Southern Ontario temperatures can occasionally drop to -25C in the winter, but the average yearly temperature is about 15C. Thus, the temperature of the ground 3-5 metres below the surface will always be 15C and a geothermal system will have a much lower gradient to overcome than an air-source heat pump. This makes geothermal systems very efficient and suitable for cold climates, and thus the only choice to replace fossil fuels.

Geothermal systems have one massive problem that keeps them from being widely adopted - installing the ground loop is prohibitively expensive. In order to harvest enough heat from the ground, an average 2000sq ft house requires around 1500-1800f of piping running through the ground. All this piping not only requires an above-average sized yard, but installing this piping involves a construction crew digging up the entire yard 2-3 meters deep. All told, the cost to install the ground loop can easily cost $20,000, so the superior efficiency and lower running costs still cannot compete against natural gas furnaces. Therefore, to make geothermal systems the financially lucrative choice, we must solve this equation:

```
cost of furnace + cost of gas > cost of heat pump + cost of ground loop + electricity. 
```

The cost of heat pumps and furnaces can be thought of as constant - they are mature, well developed technologies, and the cost of a heat pump is broadly comparable to that of a furnace. There are no big improvements possible there. Likewise, there is not much to be done about the cost of electricity and gas. 

## The Gound Loop
The key to making geothermal systems work then, and the only variable within our control, is to radically bring down the cost of installing the ground loop. This is broadly analogous to what happened in the EV industry over the last decade - by aggressively bringing down the cost of batteries, manufacturers were able to take advantage of natural efficiencies and give people an economic incentive to ditch fossil fuels for transportation. By focusing on bringing down the cost of installing a ground loop, we can take advantage of the natural efficiencies of geothermal systems and give people an economic incentive to ditch fossil fuels for heating. This incentive will also likely not require great mental leaps or encounter significant social and cultural barriers, unlike choosing a car, which is far more a reflection of personal identity and cultural affiliations. 

The objective is to develop a way of installing the ground loop for around $2000. This would compete adequately with the price ranges of furnaces and heat pumps, incentivizing homeowners to switch for savings on operating costs.

To help us develop this low-cost way of installing the ground loop, we can consider how installations are done today. A medium sized house of around 2000sq ft will require about 1500-1800ft of piping. This piping is buried at least 2m below ground with enough space to adequately exchange heat. It is made out of commodity polyethylene, which is affordable, withstands pressures, has good heat conducting properties, and is widely available at about $0.25 per foot. To meet our aggressive price targets, our solution has to meet these criteria:
* Can retrofit existing houses.
* Install 1800 ft of polyethylene piping.
* Cannot disrupt the landscaping.
* Requires minimal human labour
* Takes no more than 1-2 days of human operator time.
* Fits within a small yard.

To put it another way, we need about $400 worth of polyethelene and $350 worth of operator time, leaving only $1250 for the amortized research and production of the solution.

## The Robot Mole

The most elegant and efficient way to tacke this problem is to develop a robot mole. This would be a small, tunnel boring machine which is able to make unobtrusive 4cm/1.5" tunnels through which we can run the required piping. Ideally the robot mole would be launched by an operator from a customer's basement, it would drag and install the piping along with it and be able to make turns and complete an entire loop. Multiple robot moles can be launched at different heights or angles in order to take advantage of smaller yard and complete the job quickly, minimizing the operator's time.

There would be a number or challengest with building such a machine - mapping and navigating the terrain, dealing with very heterogeneous environments, miniturizing drilling technolgies etc. Nevertheless, it seems very doable


In [Market Opportunity](market.md), we'll explore the financial and emissions savings opportunities for this technology.