The dataset used is the Wisconsin breast cancer data set from the scikit-learn sample data collection :

		Classes- 2
		Samples per class- 212(M),357(B)
		Samples total- 569
		Dimensionality- 30
		Features- real, positive

Description of each of the 10 parameters of the cell nuclei :

		#radius           : radius of an individual nucleus. It is measured by averaging length of the radial line segments
		#texture          : measured by finding the variance of grey scale intensities in the component pixels
		#perimeter        : total distance between the snake points 
		#area             : measured by counting the number of pixels on the interior of the snake and adding one half of pixels in the perimeter
		#smoothness       : calculated by measuring the difference between length of a radial line and mean length of lines surrounding it
		#compactness      : given by combining perimeter and area of cell nuclei by using formula (perimeter)^2/area
		#concavity        : measure of number and severity of concavities or indentations in a cell nucleus.      
		#concave points   : measures the number rather than magnitude of contour concavities 
		#symmetry         : measured by calculating length differences between lines perpendicular to major axis or longest hord through center to the cell 					boundary in both directions
		#fractal dimension: is calculated using the coastline approximation by calculating “coastline approximation” - 1
		
Below are the list of works that have been as a part fo this project :

		1. Applied two classifier models, Decision Trees and Support Vector Machines to classify breast cancer
		   from a set of characteristics of the cell nuclei in an image of a fine needle aspirate of a breast mass.
		2. Compared the two different classifiers and used hyper parameter optimisation and 
		   scatter plots for observation.
