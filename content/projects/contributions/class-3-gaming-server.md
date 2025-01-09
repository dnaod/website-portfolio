---
title: "A Casino-wide Multiplayer Class 3 Gaming Server for Slot Machines"
date: 2006-12-28
featured: true
description: "I built the first Class 3 gaming server certified for use in the U.S.A."
tags: ["C++","Windows"]
image: "/img/rocket_gaming_systems.webp"
link: ""
fact: "The Bingo behind the One Armed Bandit"
weight: 500
sitemap:
  priority : 0.8
---
**More detail of the actual gaming server on its way!**

Red Hawk Gaming was a company contracted by the Miami Tribe of Oklahoma owned Rocket Gaming Systems.  Rocket was an indigenous owned company that built casino games and systems sold and installed to casino operators throughout the U.S.  Red Hawk developed all the software for Rocket in its Vancouver office while hardware was developed in Rocket's Grove, Oklahoma office.

I joined the team responsible for developing the C++ based server software.  At the time of joining, taxation laws for casino profits were in a state of flux and Red Hawk was creating a new style of gaming server based on a Bingo game behind the scenes but still presenting a user experience that matched the traditional slots game.  This "Class 3" gaming would have a more favourable tax structure ensuring more profits went to indigenous community development.

Class 3 Community gaming meant that multiple players must join and participate in the same game.  This required creating a distributed system when players pressed the spin button, they joined a virtual lobby connecting multiple players within the same casino until the player threshold was met and the game could proceed.   If that threshold was not met, the player would then be added to a lobby across multiple casinos attempting to meet that threshold.  When the players' bingo cards were registered with the game, a virtual ball caller would draw balls until one or more winners was found and prizes were distributed - often as another entertaining meta-game.

Mid-project, the senior engineer responsible for this new Class 3 gaming system left the company with many aspects of the distributed networking and virtual ball caller algorithm incomplete. I took over as lead developer.  I refactored and completed the project, and worked directly with gaming regulators, including travelling to the U.S., to certify our new random number generator and gaming server.  Rocket Gaming was awarded the first Class 3 gaming license of this form in the U.S.