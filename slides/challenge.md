# The Coding Challenge

-

## What are we doing?

* Building a renewable energy "auto-bidder"
  * How much energy the site can sell to the grid in the next 24 hours?
  * What is the most profitable price that this can be sold for? 
    * This relies on knowing the wholesale price of electricity
  * Produce a regular report on:
    * Amount of electricity generated and exported/imported
    * Profitability
    * Money saved vs just using it from the grid CO<sub>2</sub> saved vs using the grid

-

## Context

* Last year, three teams were hired to do this
* All produced workable solutions, but none quite satisfied the Customer's needs
* Presentations on each of the solutions this afternoon
* You will take on their solutions and build on them
* There will be additional features needed

-

## The (fictitious) AIMLAC HQ

![AIMLAC HQ Location](images/aimlac-hq-map1.png)
![AIMLAC HQ Location wide](images/aimlac-hq-map2.png)

* 2.5km west of Llanwrtyd Wells railway station in mid Wales
* Mountaintop location, 470m above sea level, 200m above valley floor
* Approximate centre point of the 5 universities

-

## Renewable Energy at AIMLAC HQ

![E3120 Wind Turbine](images/e3210.jpg)

* 6x Endurance E3120 50 kW wind turbines
* 1400x LG 335 W Mono Neon2 A5 solar panels
  * Tilted at 45 degrees
  * South facing
* 50 amp/11,000 volt (550 kW) grid connection
* No battery storage

-

## On-site Electricity Usage

* Heating - up to 120kW
  * 0 kW on warm days (>15C outside)
  * 30kW at 10C
  * 60kW at 5C
  * 90kW at 0C
  * 120 kW at -5C
* Computers in data centre: 200 kW
* PCs and office equipment: 10 kW
* Lighting + Misc: 20kW
* Building typically occupied 9:00am to 5:30pm, Monday to Friday
  * Excluding bank holidays and December 22nd to January 3rd.

-

## Renewable energy 101&mdash;Units

<!-- TODO: add images -->


* Amps = number of electrons moving per second
* Volts = electrical “Pressure” moving electrons
* Watts = amps * volts
  * Instantaneous measure of power
* Kilowatt Hours
  * 1 kWh = 1000 watts sustained for 1 hour
  * Electricity is bought and sold in kilowatt hours.

-

## Renewable Energy 101&mdash;Wind Turbines

![Wind Turbine power curve](wind_powercurve.png)

* Wind turbines generate electricity proportionally to wind speed.
  * Cuts off at maximum speed
  * Might even drop off slightly
  * Really strong winds might require stopping the turbine
* Find the data sheet of the wind turbine for exact relationship.

-

## Renewable Energy 101&mdash;Solar Power

<!-- TODO: add images -->
![Solar Panel Power Curve](solar_powercurve.png)

* Generate electricity in proportion to the amount of sunlight hitting them.
* Power output reduced when sun isn't directly pointed at the panel
  * Forms a sine curve across the day
* Cloudy days have much lower output.
  ** 10-25% of sunny output

-

## How we will be working

* Teams of 5-6 people
  * We will allocate you
* Monthly customer meeting
  * One RSE acting as the customer, it might change who
  * Agree a work plan for the following month
  * Customer might have new requirements as things go along
* Technical support
  * Other RSEs providing technical support
  * Recommendations on software development process

-

## Team allocation

* We're trying to even out skills across the teams
* Quick Google Form <!--TODO: LINK -->

-

## Teams Icebreaker

* Join up with your team now
  * If any are remote, loop them in with a Zoom call
* Go around the group and introduce yourselves
  * Name, University, PhD topics
* Let the group know what programming languages/technologies you have knowledge/experience office
* Suggest a name for your group

-

## First task

* Before seeing the existing code, think about how you might build a solution
  * What data would you need? Where would you get it from?
  * What models would you need to make?
  * What AI/ML/Modelling techniques would you use?
  * What programming languages?

-

## Deliverables

* Produce a 2-page project proposal by November 1st
  * See document for more details
  * Include costings for your team (note: we aren't really paying you!**
  * Reviewer's comments returned mid-November
* Present this to the customer $\sim$ 1 week after reviewer's comments

-

## Set up your teams

* Choose somebody to lead the first task
* Responsibilities will include:
  * Arranging and chairing meetings
  * Submitting the proposal document
* Setup some co-working resources:
  * Slack
    * Make a private channel/workspace for yourselves and a channel on AIMLAC Slack for customer interaction
  * Trello
  * Github
  * Anything else you think you might need
