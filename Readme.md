#### Question 1

Data  were  collected  on  a  random  sample  of  adults  who  were  undergoing  a  physical examination. The data are stored in BMI.txt.Fit a model of the following form to these data: 
Yi= 0+ 1Xi+ eiei~ NID(0, 2),
where Y= BMI= Body Mass Index (kg/m2), 
X= Waist= waist circumference (cm).

**(a)** Provide an appropriate scatter-plot for these data. Comment on this plot.(15marks)
**(b)** Calculate  a  95%  confidence  interval  for  the  slope.  Interpret  this  confidence  interval. (10marks)
**(c)** Test  the  hypothesis  H0: 1=  0.3against  H1: 10.3.  Quote  the  value  of  the  test statistic and the associated p-value. (15marks)
**(d)** Predict the BMI of an adult with a waist circumference 88cm. Interpret the associated 95% confidence interval.(10 marks)


#### Question 2)
Data  were  collected  on  a  random  sample  of  adults  who  were  undergoing  a  physical examination. The data are stored in BMI.txt(on Canvas & P: drive).Fit a model of the following form to these data: 
Yi= 0+ 1X1i+ 2X2i+ 3X3i+ 4X4i+ 5X5i+ eiei~ NID(0, 2),
where
Y= BMI= Body Mass Index (kg/m2),
X1 = Waist= waist circumference (cm),
X2 = Leg = upper leg length (cm),
X3 = Elbow = elbow breadth (cm),
X4= Wrist= wrist breadth (cm),
X5= Arm= arm circumference (cm).

**(a)** Interpret the estimate of 3.(5 marks)

**(b)** Interpret and comment on the value of R-squared. (7marks)

**(c)** Test the hypothesis H0: 1= 2= 3= 4= 5= 0against H1: 1, 2, 3, 4, 5not all 0.Quote  the  value  of  the  test  statistic  and  the  associated  p-value. Explain  the  practical implications of your conclusion.(7marks)

**(d)** Can Elbow  and  Wrist  be excluded fromthe  current  model?  Specify  an  appropriate hypothesis to test this. Quote the value of the test statistic and the associated p-value. Explain the practicalimplication of your conclusion.(9marks)

**(e)** Is  there  evidence  of  collinearity  in  the  current  model?  What  recommendation(s),  if any, would you make?(10marks)

**(f)** Test the hypothesis H0: 3= 0, assuming all predictor variables in the current model are uncorrelated. (12marks)


#### Question 3
Data were collected on a random sample of adults who were undergoinga physical examination. The data are stored in BMI.txt(on Canvas & P: drive).Fit a model of the following form to these data: 
Yi= 0+ 1X1i+ 2X2i+ 3X3i+ 4X4i+ 5X5i+ eiei~ NID(0, 2),where Y= BMI= Body Mass Index (kg/m2),
X1 = Waist= waist circumference (cm),
X2 = Leg = upper leg length (cm),
X3 = Elbow = elbow breadth (cm),
X4= Wrist= wrist breadth (cm),
X5= Arm= arm circumference (cm).

Calculate the following for each case: the residuals (e), the studentized residuals (r), leverages (h) and Cook’s distances (d). (

**a)** By how much does the model under/over-estimate BMI for case 1?(5 marks)

**(b)** Providing a suitable plot, identify which cases are outliers.Quote the value of the studentized residual for the most extreme case.(10marks)

**(c)** Providing  a  suitable  plot,  identify  which  cases  are  of  high  leverage. Quote  the value of leverage for the most extreme case. Explain precisely why thiscase is of high leverage. (15marks)

**(d)** Provide a suitable plot of Cook’s distances.  Interpret this plotand  explain  any cases  you  identify.Quote  the  Cook’s  distance  for  the  most  extreme  case. (10 marks)

**(e)** Based  on  the  above  analyses,  what  recommendation(s)  would  you  make  for  this model? Explain. (10marks)

#### Question 4
Data  were  collected  on  a  random  sample  of  adults  who  were  undergoing  a  physical examination. The data are stored in BMI.txt(on Canvas & P: drive).For  a  simple  linear  regression  of  variable  Y  =  BMI  on  variable  X  = Elbow,  fit  the following three models to the data :
Q4.1.lm:Yi= 0+ 1Xi+ ei, ei~ NID(0, 2)
Q4.2.lm:log(Yi) = 0+ 1Xi+ ei, ei~ NID(0, 2)
Q4.3.lm:log(Yi) = 0+ 1log(Xi) + ei, ei~ NID(0, 2)

**(a)**Provide appropriate diagnostic plots for each model. Comment on each of the diagnostic plots. (3 x 12 marks)

**(b)**Which of the models would you choose for these data? Explain. (6 marks)

**(c)**Explain why these particular transformations above (logarithmic) would have been considered.(8 marks)
