# Dynamic Flux Slider
Dynamic Flux Slider is a fork of [Flux slider](https://github.com/joelambert/Flux-Slider).

## So what are the differences?

- Dynamic load from array
- Responsive width
- Resize images to Fill the all the apace
- Focus point for filled images

# How to use?
If not for the new stuff, all remain the same.

	window.f = new flux.slider('#slider', {
		imgList: [
			"img/avatar.jpg", //If width and height isn't defined, the script use the width of the selector and the relative height of the first image.
			"img/the-martian.jpg",
			"img/captain-america.jpg",
			"img/voldemort.jpg"
		],
		focus:[ //The image is fill the container, you can choose the focus point.
			[0,0], //Percentages - left to right, top to bottom
			[0,50],
			[46,0],
			[0,22]
		]
	});

# Planed futures features
- Lazy load (only load the next image in the slider)
- Add new images after the slider start dynamically
- New Transitions (Low priority)
	
# License

Flux is Copyright &copy; 2011 [Joe Lambert](http://www.joelambert.co.uk) and is licensed under the terms of the [MIT License](http://www.opensource.org/licenses/mit-license.php).
