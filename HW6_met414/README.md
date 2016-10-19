# Assignment 1
## Energy Consumption by Residential Units

For this assignemnt I worked very closely with my group mates Will Xia, Kelsey Reid, Matt Sloane, Ozgur Akkas.

In earlier Homeworks we had used the "! Curl O-"  method to download the data, however we were instructed to use the 'PUIDATA' environmental variable moving forward. An attempt to follow the skeleton notebook led us to issues with the environmental variable. After conferring with Professor Bianco we realized that PUIDATA existed as a file and not a folder. I deleted the file off Jupyter and created the new folder using the mkdir bash command on the terminal. After this issue was resolved I was able to successfully download the data using the environmental variable. 

The collaboration within the group was critical to our ability to generate the plots and calculate the chi sq values. Closely following the skeleton notebook and consulting with our colleague Yao enabled us to pace through the assignment while communicating via email and meeting together for group work. 

We generated 2 scatter matrices, 2 scatter plot, 1 log plot, 2 additional plots with a fit line and 1 with a 2nd degree polynomial fit line. We calculated the Chi-Sq values for both plots with a fit line. The Total Energy Usage by Residential Units generated a Chi-Sq value of 38.11 (Fig 6) as compared to 420.67 for Res Units by Energy (Fig 7).

The null hypotesis states that the Linear Fit (model 1) is a better fit than the 2nd Dregree Polynomial fit (model 2). Degrees of freedom (dof) is equal to 1 and according to the table provided, the critical value is 3.84. As the Likelihood Ratio (35.8) is much larger than the critical value (3.84) we can reject the null hypothesis.

# Assignment 2

The write up for our Citibike study can be found here:

https://www.authorea.com/users/106219/articles/134338/_show_article?access_token=8Nww4GhkDJi3rmQq1Ec2pw
