Important: [[x-intercept]]

## Methods to solve equations
### Graphically
* Method 1: find zeros
	solve: x<sup>2</sup> - 2x - 3 = 0
	steps: 
	* Y1= x<sup>2</sup> - 2x - 3
	* x = [[x-intercept]](s)

## Examples
* ### Example 1
	* Y1 = x<sup>2</sup> + x - 4 
		ZStandard x:[-10,10,1,-10,10]
		CALC, zero
		x=-2.561553, x=1.5615528
	* Y1 = x<sup>2</sup> + x - 4
	* Y2 = -3
		ZStandard
		CALC, intersect
		(-1.618034,-3), (0.61803399, -3)
	* Y1 = x<sup>2</sup> - 2x - 3
		1,-3
		Factor: (x+1) (x-3) = 0
		x+1 = 0, x = -1   x-3 = 0, x = 3
		-1  -1            +3    +3
	* Y1 = −(𝑥 + 3) (𝑥 + 1) (𝑥 − 2)
		x+3 = 0, x=-3 
		x+1 = 0, x=-1
		x-2 = 0, x=2
	* 2𝑥<sup>2</sup> − 5𝑥 − 3 = 4
		x=(-b -+ sqr(b<sup>2</sup>-4ac)) / 2a
		2x<sup>2</sup>(a) = 5x(b) - 7(c) = 0
		x= ((-5) +- sqr((-5)<sup>2</sup> -4 (2)(7))) / 2(2)
		x= (5 +- sqr(81)) / 4
		+=3.5
		-=-1
* ### Example 2
	The dimensions of a rectangular prism are 10cm y 10cm by 5cm. When each dimension is increased by the same length, x, the new volume is 1008cm<sup>3</sup> 
		1008 = (5 + x) (10 + x) (10 + x)
		V=lwh
		
		[-10,10,1,-10,1020]
		Y1 = (5 + x) (10 + x) (10 + x)
		Y2 = 1008
		CALC, intersect  
		Intersect = (2,1008), x = 2
		dimensions = 12 x 12 x 7