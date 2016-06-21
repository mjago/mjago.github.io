---
layout:            post
title:             "Pub real-ale selection menu"
menutitle:         "Pub beer guide"
category:          Projects
author:            mjago
tags:              Sinatra, javascript
---

<div class="bg-scroll" style="background-image: url('{{ site.github.url }}/assets/hop_screen_shot.png')"></div>

This is an automated pub beer guide I created with the Sinatra framework and javascript. As beers are put onto the bar they appear on the "blackboard" as shown, complete with type, ABV, and price. Beers may be entered into the system as they are _tapped_. This can trigger an update of a website containing a page showing the _blackboard_, or club members may be sent an email of the latest beers _coming next_.

## BatmanJS

The batman javascript library was used to create the _blackboard_ update mechanism. The _blackboard_ itself is designed to be displayed on a suitable large flat-screen TV, and could clearly be used for other marketing and sport display too.

