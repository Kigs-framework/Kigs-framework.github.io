---
layout: post
title:  "Upgrador mechanism added"
---

### Upgrador mechanism

The `Upgrador` class purpose is to be able to add a specific behaviour to several classes (`CoreModifiable`) without implementing it in the base class.
An example of `Upgrador` is done in `UIPopUp` ([UIPopUp.h](https://github.com/assoria/kigs/blob/master/framework/2DLayers/Headers/UI/UIPopUp.h) ,  [UIPopUp.cpp](https://github.com/assoria/kigs/blob/master/framework/2DLayers/Sources/UI/UIPopUp.cpp) ) so you can add a "PopUp" behaviour to all type of object inheriting `UIItem`. 

Upgrador mechanism is detailed in this Wiki page : [Upgrador](https://github.com/assoria/kigs/wiki/Upgrador) 

