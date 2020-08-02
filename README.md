# virtual-paint
This is a opencv based virtual paint, you'll need a working webcam for this
I have only added two colors, green and blue as it takes a lot of trial and error to get the perfect masked image :P
It mainly works on 3 functions, it captures the image, finds the color from a range i have specified and creates a contour boundary around the color. 
Then it appends a list with the points that the tip of the colored object is travelling through and continously plots them through the drawOnCanvas function.
you can press 'q' to quit anytime
