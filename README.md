## Firearm Sales and Mortality Rates
In this study, I address the problems of gun violence and political polarization in the United
States using datasets on firearm background checks, which I use to approximate firearm sales,
and mortality rates. My first goal is to determine
whether there is a relationship between a state's usual political leaning and its firearm sales. In 
order to do this, I reduce the dimensions of the firearm sales dataset by performing principal component
analysis and produce an interactive graph plotting each state according to its first and second principal component. 
A still of this graph is pictured below. 
<p align="center">
  <img src="https://user-images.githubusercontent.com/78238322/123457617-f1003500-d598-11eb-8aac-dbc2f5befddd.png" />
</p>
Based on this graph, I conclude that while states with higher firearmsales tend to be Republican and states with 
lower firearm sales tend to be Democratic, the vast majority of states reside somewhere in the middle with no clear 
trends in political party. 

My second goal is to analyze the relationship between deaths from firearms and firearm sales. To do this I construct a 
simple linear regression model, pictured below. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/78238322/123457632-f6f61600-d598-11eb-81cd-2eaa2fb33737.png" />
</p>
From this regression model I conclude that there is a positive linear relationship between firearm sales and deaths by 
firearms in the United States. 
<p>&nbsp;</p>
For a more in depth analysis of this project, see the firearm analysis PDF. 


