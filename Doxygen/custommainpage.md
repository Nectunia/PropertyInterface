Welcome to the PropertyInterface!  
  
You'll see here how to use or to extand this powerfull asset. But first lets see what this asset can do for you.  
  
## Why use this Asset ?
![WhyUseThisAsset](https://github.com/Nectunia/PropertyInterface/blob/gh-pages/Diagrams/WhyUseThisAsset.png) 
  
## What does this Asset do ?
This asset allow you to easily add Property to GameObject.  
* Each Property is a component so it can be linked to your other Components.  
* Each Property can be found by script via a powerfull and easy to use custom Tag system.  
* Each Property values can be filled with raw values or sourced from other Component.  
  
A complete and easy to use library allow you to handle Property by script as well.  
  
## How does it work ?
  
![HowDoesItWorks](https://github.com/Nectunia/PropertyInterface/blob/gh-pages/Diagrams/HowItWorks.png)  
  
1.  Add Property to GameObject.  
2. Select a Tag for the Property.  
3. Select a Tag in your custom component _(the only thing you have to script)_.  
4. Your custom component will now be able to interact with all Properties in all GameObjects wich have the same Tag.
  
_Each Property is a component so it can be specificaly refered to your custom component instead of using Tag sytem_
  
## What about performance ?
As you can see below, a Property is not the lightest component there is. However it will take a significant amount of Property before it really affects the performance of your game.  
![BenchMark](https://github.com/Nectunia/PropertyInterface/blob/gh-pages/Diagrams/BenchMark.png)
  
_All tests have been done with the following configuration :_
* _OS : Windows 10 Familly 64Bits_  
* _UNITY : 2019.3.0f6_  
* _CPU : Intel Core I7-4800MQ (4 x 2.7GHz)_  
* _GPU : Nvidia GeForce GTX870m 3GB GDDR5_
* _RAM : 8GB DDR3 800Mhz_  
* _HD : Sata 7200rpm_  
