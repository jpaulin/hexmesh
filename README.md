#Hexagon-based fiber optics Tycoon 

## A fan of Civilization, Colonization or Big Business? Join in!

This is an open game, being developed by, hopefully, many of us
here around the world. The main theme of the game is Telecommunications
Empire: building a world-class telecomms business. Read on!

## Purpose of the game: Win!

The purpose is to build a communications empire, protect the corporation’s
assets and key people from jumping to other wagons; keep a top revenue-gathering
strategy, and crush competition.

Investments are done into infrastructure improvement, right-of-way ownership
(land and routes), buying assets from rivals and Government; negotiating
lease contracts (in and out). Sometimes you’re going to have to face
environmental protection agencies and whatnot.

## Human issues - not humane!
Key people are your most important asset, but can you make your company both
profitable enough and in good reputation enough to keep these talents in
your team?

## Stay out of lawsuits
You may face litigation (or threat of it) from many sides; from the
military to foreign nations. Can you make your case strong in politics
to persuade and fend off the litigations? If you’re going up to the court,
can you prove that you have not played dirty games? Whose portfolio of
telecommunications patents is the most valuable one? And hey, remember
that everything has a price tag. Everything. 

## Available player roles
You can play the game basically in the role of
- an angel investor
- major bank / funder
- operational fiber corporation CEO
- ground-up micromanager of societies

## The Garage - Beginning of the game
You start from humble beginnings with a little bit of land, coming
right from your distant (and past) relatives.
With the booming 1920s and electricity starting to serve in all kinds of

## Main functions in the game

Expansion
Profitability
Financial viability - negotiating with investors
Bargain acquisitions
Poison pills in corporate structure
Avoid pitfalls
Understand the legislation process
Understand reaching multiple goals simultaneously
Stay on cutting edge!
Be cost-efficient!
Take risks!
Understand how the board sees you!

## Doing a MVP version -- The simple skeleton version: "how simple?"
- a hexagon map
- three properties per hex: traffic, profit, tech
- the player can merge hex pieces that are compatible in ‘tech’
- clients’ traffic flows are modeled like watered. Bottlenecks start to irritate clients, and also their web/Internet using behaviour changes overall. 

The joining of ... <WIP> follows the idea that compatible technology
enables communication. Before the omnipotent GSM, there are many competing
technologies; they are shown in the game simply by using different icons
and colors for the items:
* base stations
* copper lines
* etc.

You start with basically geographical terrain. It provides the limitations but also possibilities for limitless richess for the witty strategist. Understanding human psychology and needs is key to winning in the game. 
People strive to live their own lives in as successful method as possible. But understanding that there’s certain, shall we say, variation of view between individuals as to “what” constitutes success and happiness is vital.   


Scenarios
- the game contains special scenarios (perks)
- completion of a perk gives both fame and also boosts the Marketing campaigns ongoing for a certain period of time


Basics
- hexagonal area in the map
- each hex (=area) is defined by control points (CPs)
- all segments between control points are linear (straight lines)
- the hexes can be connected


Cgen : city generation
- Places cities within regions
- Init the cities with 2 variables: statistics Pop, city cell use penetration cpen 
- Pop is a long integer telling the population of the city
- cpen is a long integer which tells the number of mobile phone using individuals




________________


Extra fun(ctionality)


- Live Roaming: see people use mobiles, inside cities, within country, globally. Make the roaming contracts so that you can keep customers happy, using the service, yet balance your own costs.
- Roamer is dependant on the “city generation” (cgen) module. Cgen makes cities appear within boundaries of a vectorized area, ie. a region like a country. 
- Live roamer has different levels. The individual tracking level (zoom 0) means that player gets to see one incident of actual phone usage as it happens; live tracking. A client might be happy, talking with a good connection, or he might experience intermittant breaks (disconnects) or other glitches in the connection quality. 


What keeps the player hooked?
* no single “winning strategy”
* cunningness can gain a competitive advantage
* the secret deals
* law
* understanding technology by playing (learning!)


In HexMesh you start as the newly appointed CEO of a network operator. Your mission is to deploy strategy and tactics that leave you as the sole player in the field of telecommunications - or at least as close to monopoly as legally possible. Your performance is measured every quarter by the issuing of an income statement. The Board of members evaluates your performance and decides whether you will stay or go. 

HexMesh Tycoon


Start out with a brilliant invention, which lets you create
a simple mobile network. You're lucky enough to receive
the legacy of a retired network engineer and inventor Charles
Ball. Use his advice, goodwill and patents to create a
Telecommunications empire of your own!

## Make the ball rolling: hire people!

With a cash of 1,000,000 dollars and corporate headquarters
in the city of your choice, your first steps are to hire some
crew, invest in research facilities, and make initial managerial
choices. Your company will start running a business in 
telecommunications in no time. Depending on which Era
you are playing, there are also scenario-dependant challenges
and Tasks. 


As a business manager it is also your decision how deeply
and in what ways to enter the handset markets, in addition
to core network business. Handsets may prove either to 
be a goldmine, or a catastrophy. Handsets are known to
have quite a quick turnaround and they are a wonderful
way to generate revenue, if properly marketed. However 
they may also become low-income bandwidth hogs or
otherwise incur large overhead costs as extra helpdesk resources
are needed to keep customers happy.


[Scene 1. Charles Ball's legacy]
Ball has done the ground work on your behalf, and you
start with some of the essential ingredients of a telex network...


GAMEPLAY BASICS


The game's mobile networks are built with three kinds of ingredients:


Inventions,
Implementations and
Stock. 


Inventions come from laboratories and the field. They can thus
be done in theoretical research labs (within a University or
the Research facility). The field also provides inventions of different
kind; mostly practical set ups of technology which have been
hitherto unknown.


Stock is the accumulated gear (manufactured goods) of telecom
equipment. With stock one can multiply the network's capacity. Note that “stock” 
means ‘installed capacity’, not stocks as in financial instruments. Stock supply and demand affects how well manufacturers are able to supply the gear for your company, and at what price. Both under- and oversupply situations may occur during the course of a game. 


The overall capacity, however, may not always linearly add as to stock; 
for example there are well known effects where the capital
expenditure rises sharply but the customer satisfaction does not:
then the operator is over-spending to satisfy a minority of its
most demanding super-users. 


Basic scenario: starting in the 1920s

You start out in the bright 1920s. The world has witnessed a phenomenal
growth in the use of electricity for human good; light bulbs,
radio, first television sets. The media industry is booming!
It's the era between World Wars; yet no-one can predict
the second world war yet. There's no sign of the 1929 Black Monday
stock market crash, and the big Second World War which will ravage for six years,
is yet to come far in the future. 


Mobile communications starts to take the first steps in the
form of radio operations. In 1991 the first commercial GSM network
is launched in Finland (by Radiolinja). Handset makers spring up
and the competition starts to get fierce; but consumers are the
ultimate benefactors. By 2012 there are manufacturers in 18
countries. The number of phone models is in the thousands. 


Mobile base station scenario, UC:


- grid based
- the view is based on two layers:
  ground (earth shapes)
  infrastructure layer (roads, masts, etc.)


## easy manipulation of RX/TX towers (MBS) 
 - power
 - cost
 - altitude profile
 - beam
 - maint. cost
 - placement work
 - man (how meny men needed to put up)


## Creating media buzz
  - make cashcows; SMS, network usage, MMS
  - new services for $$$

## autonomous challenges
  - grid development (electricity)
  - mobile user fashion
  - 3rd party apps
  - paranoia (big G)
  - phones development
 
## consumer disputes
  - topping (cap) the bandwidth
  - location awareness, privacy issues
  - bad credit (consumers having problem paying invoices)
  - broken devices
  