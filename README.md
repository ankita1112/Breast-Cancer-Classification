## Breast-Cancer-Classification

### Dataset
The dataset used is the Wisconsin breast cancer data set from the scikit-learn sample data collection :

- Classes: 2
- Samples per class- 212(M),357(B)
- Samples total- 569
- Dimensionality- 30
- Features- real, positive

Description of each of the 10 parameters of the cell nuclei :
1. radius           : radius of an individual nucleus. It is measured by averaging length of the radial line segments
2. texture          : measured by finding the variance of grey scale intensities in the component pixels
3. perimeter        : total distance between the snake points 
4. area             : measured by counting the number of pixels on the interior of the snake and adding one half of pixels in the perimeter
5. smoothness       : calculated by measuring the difference between length of a radial line and mean length of lines surrounding it
6. compactness      : given by combining perimeter and area of cell nuclei by using formula (perimeter)^2/area
7. concavity        : measure of number and severity of concavities or indentations in a cell nucleus.      
8. concave points   : measures the number rather than magnitude of contour concavities 
9. symmetry         : measured by calculating length differences between lines perpendicular to major axis or longest hord through center to the cell 					boundary in both directions
10. fractal dimension: is calculated using the coastline approximation by calculating “coastline approximation” - 1
		
## Implementation		
Below are the list of works that have been as a part fo this project :

1. Applied two classifier models, Decision Trees and Support Vector Machines to classify breast cancer
		   from a set of characteristics of the cell nuclei in an image of a fine needle aspirate of a breast mass.
2. Compared the two different classifiers and used hyper parameter optimisation and 
		   scatter plots for observation.
