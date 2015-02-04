---
layout: page
permalink: /research/
title: Research projects
tagline: Flight, muscle, and computational approaches 
tags: [research, muscle, flight]
modified: 5-30-2014
comments: false
---


My work splits between how muscles generate force in order to move us around and how that movement works in the real world. Some specific projects are described below. 

## Squeezing through: how birds fit in tight spaces

![Pigeon in flight]({{ site.url }}/images/pigeon_in_flight.jpg "A most majestic pigeon")

We are used to thinking of bird flight as something that occurs in the clear blue sky, but birds spend a substantial portion of their time navigating complex environments. Hunting, congregation, and nesting behavior are all essential to an individual's success and all take place in cluttered arboreal or urban settings. A charismatic example of this is the [Northern Goshawk](https://www.youtube.com/watch?feature=player_detailpage&v=p-_RHRAzUHM#t=104), which flies through forests at up to 55 mph, but even the humble pigeon routinely weaves its way through skeins of branches. To tease apart the strategies employed in this type of flight we present trained pigeons with increasingly challenging regular arrays of obstacles, initially providing them gaps greater than their wingspan and eventually narrowing their passage down to less than a quarter of their full wingspan. 

What we found was that the pigeons adopted one of two distinct strategies while gliding through tight spaces, either holding their wings paused at the top of their upstroke or folding their into a perched posture. The folded posture was adopted more in more challenging situations when more collisions with obstacle occurred, and was found to be about 30% more stable than the paused posture. So why not use the more stable position in all cases? The folded posture takes longer to execute than the paused posture, forcing the bird to travel in a ballistic trajectory for longer. In the real world, navigation entails trade offs between control and stability.

## Muscle's force/length curve depends on lattice spacing

![Length-tension curve]({{ site.url }}/images/length_tension_curve.png "Force generation changes with overlap and lattice spacing")

Muscle's contractile apparatus is composed of two types of rope-like filaments that tug on each other to produce shortening. As the muscle shortens, these filaments slide past each other and are able to generate carrying amounts of force. The relationship between the maximum force a muscle can generate and its length is one of the basic physiological properties of muscle and is known, logically enough, as the length-tension curve. 

For the last 60 years, we've attributed the change in force seen across the length-tension curve as a result in the changes in filament overlap, however there is another dimension that is changing at the same time, the spacing between the thick and thin filaments. This thick-thin filament spacing, or lattice spacing, grows as the muscle shortens, to maintain a constant volume within the muscle cell. Through simulations and experiments, we've shown that changes in lattice spacing are a big part of what determines the shape of muscle's length-tension curve. 

## Energy distributions within muscle

![Muscle's lattice]({{ site.url }}/images/lattice_fade.jpg "Myosin (red) surrounds and binds to actin (blue)")

Locomotion requires energy. Very fast locomotion requires a larger amount of energy than muscle can produce in such a short time period, thus muscle must use energy that it previously produced and stored as elastic deformation. Cyclical or repeated movements can be directly powered by muscle, but energy may be conserved in such cases through elastic energy storage. Traditionally we've looked primarily at tendons, insect exoskeletons, and bones as locations where this energy is stored. However, a small but growing body of literature has recently suggested the thick and thin filaments in muscle act as elastic storage locations. Our simulations suggest that the myosin motors themselves are capable of storing more energy than the filaments, energy that may be released to power very fast movements or reduce the cost of cyclical movements. Additionally, our simulations show that this energy is stored in the radial deformations of myosin motors, in a direction that is perpendicular to the axis of muscle shortening.

## Simple motor molecules

![Spring models of molecules]({{ site.url }}/images/2sXBand1QVI.png "Cartoon and theory, protein structure drives molecular simulations")

The molecular motor myosin drives the contraction of muscle, but doesn't just produce force in the axis of shortening. Models of muscle contraction have primarily treated myosin as a simple spring oriented parallel to its direction of movement. This assumption does not allow prediction of the relationship between the forces produced and the spacing between contractile filaments or of radial forces, perpendicular to the axis of shortening, all of which are observed during muscle contraction. We develop an alternative model, still computationally efficient enough to be used in simulations of the sarcomere, that incorporates both extensional and torsional (angle dependent, like those found in a watch) springs. Our model captures much of the spacing dependent kinetics and forces that are missing from single-spring models of the cross-bridge.

