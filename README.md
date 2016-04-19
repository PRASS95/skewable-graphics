## Skewable Graphics for PIXI 

The *SkewGraphics* class provides support for **skew** transformations in **PIXI**.


### How to:


 ``` 
	let shape = new SkewGraphics();
	shape.skew.x = -15;
	shape.skew.y = 15;

	// or

	shape.skew = new PIXI.Point(-15,15);


 ```


### About

- The *SkewGraphics* class is based on *Graphics* class in PIXI v3.0.10
