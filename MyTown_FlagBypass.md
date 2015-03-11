Placing tile entities that MyTown pops off (without allowing outsiders to modify)
===

Mytown will not allow you to place certain tile entities in your town to stop griefing. (e.g. MFR Rancher)
This tutorial will show you how to allow those blocks in your town
![Pops off](http://i.imgur.com/88FYyEs.png)

I) Allow modification of blocks by everyone
---
Type the following command:
####`/town perm town set modifyBlocks true`
*(This will allow outsiders to modify all blocks in your town)*

![modifyBlocks command](http://imgur.com/IaD4005.png)

II) Add to whitelist
---
###1) Place down the block.
###2) Type the following command:
####`/town perm town whitelist add modifyBlocks`

![whitelist command](http://i.imgur.com/g4JJhWO.png)

###3) You will get a wooden hoe named __Selector__

![hoe got](http://i.imgur.com/ZiddZnO.png?1)

###4) __Right-click__ the block you want to whitelist with the hoe

![whitelisted](http://i.imgur.com/KEmBwou.png)

III) Re-disable modification by outsiders
---
Type the following command:
####`/town perm town set modifyBlocks false`


You are now able to place this whitelisted block in your town.


Avoiding the temporary enabling of modifyBlocks:
---
1) Create a plot somewhere in your town where nothing is built and anyone can go.

2) Type: `/town perm plot set modifyBlocks true`

3) Go to the plot each time you want to add a block to your town's whitelist.
