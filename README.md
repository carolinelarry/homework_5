# Matplotlib - The Power of Plots

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens and provide a top-level summary of the study results.

## Process

* Checked the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID.

* Used the cleaned data for the remaining steps:

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

<img width="480" alt="Screen Shot 2021-09-12 at 11 12 15 AM" src="https://user-images.githubusercontent.com/79863465/132994963-d84baf5f-fff3-48e1-9e36-0bc021997248.png">


* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

<img width="449" alt="Screen Shot 2021-09-12 at 11 12 25 AM" src="https://user-images.githubusercontent.com/79863465/132994965-d30ce998-963f-462e-a69e-4e049eaa6c72.png">


* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determined if there were any potential outliers across all four treatment regimens.

* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.

<img width="481" alt="Screen Shot 2021-09-12 at 11 12 40 AM" src="https://user-images.githubusercontent.com/79863465/132994974-13ec2b5c-2632-4039-a0d7-44918bdd3037.png">


* Selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

<img width="486" alt="Screen Shot 2021-09-12 at 11 12 47 AM" src="https://user-images.githubusercontent.com/79863465/132994992-c5843df9-cfce-4c58-9c43-07d887b2ec84.png">


* Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

<img width="494" alt="Screen Shot 2021-09-12 at 11 12 55 AM" src="https://user-images.githubusercontent.com/79863465/132994998-038c3e79-a1a5-489a-b528-62a299bde69d.png">


* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot.

<img width="526" alt="Screen Shot 2021-09-12 at 11 13 02 AM" src="https://user-images.githubusercontent.com/79863465/132995007-d7b1afc5-2244-4ba5-b8b4-21aebb95c131.png">


## Contact
Email: cgrace1011@gmail.com

- - -

## References

Mockaroo, LLC. (2021). Realistic Data Generator. [https://www.mockaroo.com/](https://www.mockaroo.com/)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
