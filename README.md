# ACM Research coding challenge (Spring 2023)


## What can I do with this data set?

I was most interested in finding out what variables distinguish each star type. 

1) To do so, I first created a histogram and scatter graph to see how many star there were of each star type.
- I found that there was 40 stars of each star type (6 types) which added up to 240 total stars in the data set.

  ![image](https://user-images.githubusercontent.com/62407356/216208854-2ab50412-5305-4182-9300-99b87575b03c.png) ![image](https://user-images.githubusercontent.com/62407356/216208896-17dd8bb4-64e1-4508-a94d-a0e4c22b2277.png)


2) I then created many scatter graphs comparing 2 variables.
- I found that star of types 0 (Brown Dwarf) and 1 (Red Dwarf) have the smallest ranges for all of the varibles except for magnitude. 
- Stars of type 5 (Hypergiant) have the largest ranges for all the variables, except for magnitude and star color.

3) I also tried to recreate the Hertzsprung-Russell Diagram by creating a scatter graph of star temperature vs absolute magnitude.
![image](https://user-images.githubusercontent.com/62407356/216208819-05decafa-38bc-4817-b44d-c7b89e828f26.png)

4) Lastly, I called the corr() method to look for any strong correlations between the 5 variables with numerical values (Temperature, Luminosity, Radius, Absolute magnitude, Star type).
- I found that absolute magnitude had the strongest correlation to star type, while luminousity and radius also had strong correlations. Temperature had weak correlation with every other variable with a numerical value.
![image](https://user-images.githubusercontent.com/62407356/216208380-f94e31b1-b43d-4f9f-988c-f9f3ec34314a.png)


## Resources I used

I have never used Kaggle before, so it took me some time to find the right tutorials and learn the basics. These are the resourcs I referenced when writing my code:
- https://www.youtube.com/watch?v=fvF2H85ko9c
- https://www.kaggle.com/discussions/getting-started/113026
- https://www.w3schools.com/python/matplotlib_scatter.asp
- https://www.w3schools.com/python/matplotlib_plotting.asp


## Star type key given by the ACM repo

Please note that the star type, denoted as integers, are translated as the following:
- Brown Dwarf -> Star Type = 0
- Red Dwarf -> Star Type = 1
- White Dwarf -> Star Type = 2
- Main Sequence -> Star Type = 3
- Supergiant -> Star Type = 4
- Hypergiant -> Star Type = 5
