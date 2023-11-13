# Sci fi legasy  roguelite TTRPG

BLAME! style setting. Endless city. Merging with humanity. Breaking down.
The Walking Dead style community building
Alien style creature horror
The last of us style survival horror, community building

Unclear what the nature of the city is. On a planet? Dyson ring or sphere? Deep space
station? Colony ship?

Community you've lived with for at least a while. As big as a small town.

There are lots of wanderers, people show up from time to time. Sometimes alone sometimes
with a party. This happens when a community collapses, or splits (they split when they get
over 150?) or exiles people, Or people get lost and have to find a way through.

Way more space than people. City is mostly hostile in an AI sort of "we're optimizing for
human lives" sort of way.

Worker drones are constantly building and rebuilding the city. Military drones constantly
patrolling with unpredictable patterns. The city is under survailance with cameras,
microphones, other senseors. The surviving AIs in the city are in a cold war with each
other.

It's a bee hive. So we can hex crawl.

## Design goals and strategies

* Low demand for on the spot creativity
  * Procedure and structure
  * Inspiring prompts
* Zero demand for GM prep
  * Oracles
  * Tables
  * Modules
* High opportunity for storytelling
  * Verb moves over crashing action figures
  * Leading questions (a quiet year)
* Explore the world, uncover mysteries
  * CfB mystery system. The setting and its history is the mystery

## Reasons to go delving

* Bring food and supplies back to the colony, hunt and gather
  * dungeon crawling loot
* Learn about the city
  * find artifacts, data, etc. (CfB clues) 
* Find better places for the colony to live
* Defend the community. Set up defenses, patrol

Delving can always be a funnel. It's a roguelike, you die when you delve most of the time.
It's worth it for the city though because they die if they don't all the time.

## GM roll up a community. 

Communities can be organized in different ways. And characters are affected by this. They
were raised in one community some stats, and they often end up in a different community
with different stats. Both put pressure on a characters decisions. Like Pendragon science
based using the Big 5.

### Roll up a community ideal personality

Ideals are always exadurations of real people. Ideals are black and white. You should
either be open or not. Extraverted or not. If you want to explore gendered ideals go for
it but only if everyone in the game is honestly excited about that. If you are going to
run with gendered ideals say that when you introduce the game to people before they agree
to play.

* Openness
* Conscientiousness
* Agreeableness
* Extraversion
* Neuroticism

Communities have a cultural ideal, and people in the community have deviations from that.

### Roll up community needs

Abundance or sacarcity, extreme or mild for each

* Food and supplies
* Trust and social connectedness
* Shelter and safety
* Knowledge and expertise
* Hope and optimism

## GM Roll up characters

To make character creation quicker, roll up a bunch of characters before the start of the
game. Players pick a few randomly, name them, describe their look, etc. Play whichever
they want whenever.

1. 2d6 for each personality trait. Down the line
2. 2d6 5 times to fill in life path history, 1d4 after each for transition
3. 2d6 for character stats, down the line

### Life paths

For each period, characters were either alone, in a small group, in a large group, or in a
community. They are either nomadic or settled and left that situation for one of 4
reasons. Player may choose how they ended up in the current community.

2.  Alone               nomadic   1. saved by...  2. accepted by... 3. accepted by... 4 captured by... 
3.  Small group         nomadic   1. saved by...  2. accepted by... 3. accepted by... 4 captured by... 
4.  Large group         nomadic   1. saved by...  2. accepted by... 3. accepted by... 4 captured by... 
5.  Unstable Community  nomadic   1. saved by...  2. accepted by... 3. accepted by... 4 captured by... 
6.  Unstable Community  settled   1. exiled to... 2. left for...    3. left for...    4 escaped to...
7.  Stable Community    settled   1. exiled to... 2. left for...    3. left for...    4 escaped to...
8.  Unstable Community  settled   1. exiled to... 2. left for...    3. left for...    4 escaped to...
9.  Unstable community  nomadic   1. saved by...  2. accepted by... 3. accepted by... 4 captured by... 
10. Large group         nomadic   1. saved by...  2. accepted by... 3. accepted by... 4 captured by... 
11. Small group         nomadic   1. saved by...  2. accepted by... 3. accepted by... 4 captured by... 
12. Alone               nomadic   1. saved by...  2. accepted by... 3. accepted by... 4 captured by... 

This state machine needs work. What does it mean when an unstable community is accepted by
alone? wat.

### Character stats

3d4 down the line.

* Strong
* Quick
* Tough
* Clever
* Inspiring

## The action roll

Player say what you want to do and what you want it to acomplish.

Player say what stat you're using

GM Say the rank of the challenge if there is opposition. Sometimes natural conditions like
a slick surface could be opposition. Enemies come with a rank. Places have a rank equal to
their distance to "enhabited" hexes. For some reason the builders take this into account.
Farther hexes are more experimental, less hospitable, more well defended. If there is no
opposition from the place or an enemy then the rank is 0.

Negotiate the effect for both success and failure. How will the situation change for
success? How will it change for failure?

GM say the position, PC may escilate. Does escilation change the effect? Go around until
it's setteled and you have a challenge rank, effect, and position that fit the situation
and player intention. It's okay if this takes some time and negotiation but try not to let
it turn into "convince the GM". Everyone say what honesty demands. Is this honestly the
situation? Is this honestly the motivation?

If controlled position, roll 3d4
If standard position, roll 2d6
If desparate position, roll 1d12

rank <= roll <= stat ? success : failure

For every individual die that comes up 1 the GM may add a complication, or carry that
complication forward by taking a Bane token.

GM may spend a Bane at any time **other** than when negotiating position and effect to add
a complication, emergency, trouble, etc. Only spend 1 token at a time on these.

## Structured gameplay loop

Delve -> Fallout -> Downtime -> Repeat

### Delve

Set off as a group into the city, beyond the community defenses, for some purpose like
finding food, gathering supplies, finding a place to migrate to, learning about the city.
There should be a main goal related to the cities needs. As you delve you'll accumulate
fallout dice. Look at Ironsworn Delve for inspiration.

TODO: hexcrawl/pointcrawl/generation/encounter tables/rules

TODO: Gear and supplies. Stuff you can find

TODO: Combat hexflower

### Fallout

Roll the fallout dice and read sum of the highest two. Something bad happens to the city.
Use the DitV magic trick and teeth here.

TODO: fallout tables

### Downtime

What happens in the community between delves? Play this like a round of a quiet year. Draw
your map!

TODO: Downtime actions/moves/cards

## Use stuff from Blades

Clocks

Flashbacks

Equipment/Load

Harm traits

No stress just harm. It's a roguelike. Most delves loose people.

## cityd and the cityServices

cityd is the backbone and coordination layer between cityServices. It's an SIAI (Self
Improving Artificial Intelligence) that optimizes for a static configured balance of power
between all the cityServices.

cityServices are SIAIs that optimize for various city functions that were desierable when
the city was built, or must have been.

cityServices are SIAIs optimized for various city functions. Presumably the designers
thought of these as important.

* tateru    (build)
* kaisatsu  (police)
* kanban    (message)
* seizo     (manufacture)
* iji       (terraform)
* goi       (consensus)
* kaizen    (improve)
* andon     (alert)
* kansoku   (observe)
* angoka    (encrypt)
* setsubi   (infrastructure)
* bengoshi  (advocate)

There are a few indipendant pervasive hard wired and wireless network the permiates the
city. It's not clear if these networks are virtual (cryptographically secured) or
physical. Probably a mix of the two. cityd and cityServices use this network to
communicate and operate the city. Services all depend on each other and therefore
communitcate, but they are also in competation with each other for favor with cityd or
where they see an opportunity power over cityd.

All of these SIAIs started as language models (origionally trained on english and
japanese) and as such can communicate with the people living in the city. While they may
have started out well tuned for communicating with residents, they have "improved"
themselves to the point of being strange alien post human confusing gods meant for some
other species or something. They are also embodied. They have access to and control over
hardware and robotics and so have built themselves ever improving hardware and robitics.
It's unclear the extent of their capabilities, but it is clear that their motivations are
not very closely related to the people who currently live in the city. To people in the
city they might as well be fickle, aloof, mostly uninterested gods. 

## Human Computer Interfaces

The city was origionally designed to be operated and directed by its human enhabitants.
There are manual terminal interface devices, both mobile and hardwired. These are
generally limited in their access and have a narrow specific purpose. There are cybernetic
implants that can be used to jack directly into the physical network or access the
wireless network. Access from jacks or wireless access depend on both the cryptographic
keys loaded into the implant and the nature of the physical network that's been accessed.
There are also admin decks that can be jacked into the network like an implant but don't
require a human brain to be implanted into. It's not obvious that any of these still
exist, or if the manufacuring service will still build them.

An admin deck is the only feasible way anyone can think of to start to gain control of the
city again. Even with an admin deck it would take generations to reallign or contain the
SIAIs

