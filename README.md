# Swash

Skies of Arcadia and Zelda games are great: both have straightforward
adventure, simple but deep combat systems (based on tactical CHOICES more than
rote execution; that use good music programmatically; and that resolve before
they wear out their welcome), and plots excavated through world exploration.
More of that! The Zelda game of reference here is Wind Waker: there will be
ships and ports. First draft is going to look a lot like a 'Skies of Arcadia'
ripoff, because it will be.

## World

The surface of the planet is water. The known world is one small continent on
the only plateau to reach above the water, dominated by a single central
mountain with the Imperial Castle on top, surrounded by islands. Each island is
unique and most are sovereign, though some belong to the continental empire.
Those that do are not universally happy about it, although the whole continent
and its inner ring of islands are. Discontents help you evade the empire, so you
can learn to sneak gradually.

The empire is modeled after the British empire at their naval peak. Ships have
to sail with the wind. The Imperial Navy will be the primary enemy (it may, I
dunno, level up to space baddies eventually). They'll sail a variety of ships,
tending toward big, strapped up, not necessarily fast ships of the line. The
naval big bads will be big triple-decker gunboats; the hero will have to
outsail them, because you never get one. Instead, you level up from a small
sailboat with no guns to a small 20-gun ship to the equivalent of a French 74:
big enough guns (in poundage) to hang (the final ship will also have extremely
good range/accuracy), but small enough to be fast and quite shipshape. You'll
have to build up your crew to get cannons running as fast as a ship is capable.

The game starts in a village, far out from center. The village, which has, like,
5 houses, is in a tiny, homey rural archipelago. The village has shipping
concerns outside Imperial purview, between independent parties: these are
considered by the Imperial government to be piracy. Bureaucratic overreach and,
quite frankly, rude.

## Scene Opens
Zooms in to birds-eye view of the village. Scene begins outside A House, where

## Our Hero

, who is cut from the same cloth as Moomintroll, more or less, is being told by
A Friend to go to the sailboat to meet parent. You begin

## Walking around

Sailing is the main part of the game, but there are ports and villages and such.
Walking Around happens all the time you're not in a boat/ship. You never fight
while Walking Around; Our Hero is cagey and innocent. Baddies are a distinct
minority in this game, outside of their ships. When they are around, Our Hero
avoids the sightlines (displayed in arcs around them) of baddies. You snoop
invisibly, and if you get caught, you lose. You walk around with `hjkl` or arrow
keys, `space` to talk to people.

## So You Meet Parent

Hello, says parent. Turns out you have to {{do something}} which requires taking
a boat to two other islands. But today is special. Today you're old enough to go
out and about, so by god, you're learning to sail. Your parent gives you the
rudder. Cue instructions! First you open a map and set a marker; then you sail.

## Sailing

You have a birds-eye view of the ship and the wind is pictured as a
bunch of arrows. You start medium speed pointed toward your marker. You can
pick a speed (slow, medium, fast) and steer left and right.

`H |= left   J |= down  K |= up   L |= right`

`A: open map S:         D:        F: fire guns`

Your angle to the wind determines your speed; the sails are automatically set
to an ideal angle to the wind and jib algorithmically. Totally hands off: you
have the wheel and a shipshape crew (first one of parent/friend; then your crew
once you level up) has the sails. This trip is short, and downwind. There's a
HUD with compass, and you see your marker, first at the edge of the canvas and
then on the place to dock or the arbitrary spot of water you picked. Docking or
running into it, respectively, stop your ship and erase the marker. You arrive
at {{island B}}. You get {{thing A}} and turn your sights to {{Island C}}. It is
upwind, so you are taught to tack. The ideal line against the wind might be
displayed when your angle is close to it.

### Naval combat

It's a thing. It's gonna be a bit sanitized, because that stuff in real life was
horrific. In this game, everyone has lifeboats and in battles, both sides always
hit the hull. The arcs of all ship's guns' range is displayed radiating from the
sides of the ships. When they're in range, you just hold f and your crew will
fire your cannons as fast as they can. Slower sailing means more accurate guns.
Eventually, someone's hull breaks. If it's the baddie, you win! The other crew
is stuck on their slow little lifeboats and you are free to sail away, your hull
regenerating as your crew's carpenter works. If it's you that gets sunk, you
probably have to restart right outside the other ship's range.

One exception: maybe 3/4 of the way through, you have to go to a certain port
with your 20-gun ship. While you're off your boat doing a Plot Thing, the port
is closed off by an overwhelming force of Imperial gunboats. You make a plucky
stand, but your ship is sunk and you and your crew are taken prisoner. You have
to escape from prison (someone you helped earlier in the game busts you out,
then you have to not get caught), and on your way out, you pass a beautiful
74-gun ship with a shallow draught and fast lines made by the Friggin'
Stradivarius of Independent Island Shipbuilders. The Empire has just confiscated
it. You steal it, make your getaway, and that is how you get your Boss Ship.

#### Encounters
Not sure about the proper frequency, degree of scripting vs algorithms, etc
The fundamental act should be exploration, not combat
>>>>>>> Stashed changes

## Music
120 bpm is standard; maybe things can speed up during a boss fight or such?

Anyway, the standard exists to make layering easy. Layering, along with a new
technology called "melodies", enables a very simple theme for a region to be
programmatically varied as players explore different areas within it. Each area
has a unique, distinctive set of clips it loops.

Layering different tempi at the same rhythm enables shifting polyrhythms and
chords, which is just basically the shit, and enables really cool, distinctive
feels for different areas.

## Geo(graph|metr)y
At all times, the player is in an area; and every area is within a region. Every
region has a musical theme; every area has a unique variation on that theme. The
only exception is maybe if location is trumped by a surprise boss fight; but
encounters should be geographically determined.
### Regions
1. have one or two areas that are significant to the plot or that are subplots:
  * unlock an ability
  * treasure
  * a monster terrorizing an island
  * find a ship
  * enemy camp
  * etc etc

2. have habited places (all cities and towns are safe)
