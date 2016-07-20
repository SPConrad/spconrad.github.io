## Website Performance Optimization portfolio project

Open Index.html in your web browser of choice.


Optimzations: 
main.js: 
	Initial creation of moving pizza elements takes place in pizza.html, allowing the main.js file to be loaded asynchronously 

	Reduced the number of created moving pizza elements from 200 to 120. Further reducing has a negative visual impact on 1920x1080 views

	Moved a few variables and calculations outside of the updatePositions loop. Rather than declaring and calcuating every variable on every iteration, only necessary calcuations are done within the loop.

	Changed a few querySelectorAlls to getElementByID

	Moved variable declarations outside of changePizzaSizes loop. 

pizza.html:
	inlined all CSS and JS necessary for above-the-fold content, allowing the external CSS and JS files to be loaded after the initial page load

index.html et all
	compressed images
	made js calls async where possible


