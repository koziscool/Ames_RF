
### <span style="color:crimson">Ames Housing</span>

There are many many parties who are greatly interested in accurate understanding of house prices for reasons both personal and financial.  Therefore it is a subject of immense value to create good (or in some cases better) models for house prices, as well as deeping our conceptual understanding of the housing market in general.

We use various ML techniques to model the Ames, IA, housing price data, thereby considering different issues and tackling different problems associated with the same data set.  

#### <span style="color:crimson">Neigborhood-based Demographic Visualization</span>

We do the usual data cleaning and imputation that you would typically do for any data anaylsis project.

But in addition, we also do an exploratory analysis of Ames housing development.  Specifically, we do a neighborhood and distance-based analysis to aggregate Ames houses and create a visualization of construction trends across over time and how they overlay neighborhoods and price.

#### <span style="color:crimson">Linear Models</span>

We use a generic multi-linear correlation model (implicitly without regularization) and compare that to a LASSO model with L1 penalties.  Specifically, we compare the performance of each model on train/test sets to evaluate the possibility of overfitting.

#### <span style="color:crimson">Tree Models</span>
 
We also consider a generic Random Forest model and Gradient Boosting model along with a modified Random Forest model with a Term Structure adjustment.  We evaluate the Random Forest vs. the Gradient Boosting model in terms of accuracy and feature importance, and we evaluate the Term Structure adjustment in terms of ensemble improvement to the Random Forest.
