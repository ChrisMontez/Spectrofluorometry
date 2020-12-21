# Fluorescein Content in a Disodium Phosphate Buffer

##  Objective
The objective of this experiment was to determine the concentration of fluorescein dissolved in a 0.05M Disodium Phosphate Buffer. 
All data-collection efforts were performed in the Instrumentation Lab at the University of the Incarnate Word. The visualizations in this repository were created using Seaborn. Regression analysis  of the calibration curve was performed using scikit-learn.
### Python Libraries Used 
* Numpy
* Matplotlib
* Seaborn
* Scikit Learn



##  Instrumentation 
**Horiba PTI Quantamaster 4**
<p align = "center">

<img src="img/instrument.jpg"  width="600">

</p>





##  Calibration
<p  align = "center" >
<img src="img/table.PNG", width="500">
<img src="img/fluorescein_conc.png" width="500">
</p>

##  Detection Limit
<p  align = "center" >
<img src="img/detection_limit.png" width="500">
</p>


##   Analysis 

<p  align = "center" >
<img src="img/analyte.png" width="500">
</p>

<p  align = "center" >
<img src="img/analyte_cal.png" width="500">
</p>

## Conclusion

Spectrofluorometric analysis was performed on a sample containing an unknown concentration of fluorescein in a 0.05 M disodium phosphate buffer. A linear regression model was created using seven fluorescein/buffer solutions of known concentration, and the Python scikit-learn library.  
* The R-Squared value for the regression analysis is 0.996   
* **The concentraion of fluorescein in the unknown sample is 0.004 μmol.**