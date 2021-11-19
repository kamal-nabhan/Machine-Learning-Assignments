# Machine Learning Assignments

The assignments were given as a part of Task 6 in the IIT Certified Programming Professional &amp; Master Data Science Program. The Repo contains two ipython Notebooks

## 1] Assignment 5: 

### Ground Cricket Chirps

   In _The Song of Insects_ (1948) by George W. Pierce, Pierce mechanically measured the frequency (the number of wing vibrations per second) of chirps (or pulses of sound) made by a striped ground cricket, at various ground temperatures.  Since crickets are ectotherms (cold-blooded), the rate of their physiological processes and their overall metabolism are influenced by temperature.  Consequently, there is reason to believe that temperature would have a profound effect on aspects of their behavior, such as chirp frequency.

   In general, it was found that crickets did not sing at temperatures colder than 60º F. or warmer than 100º F.
  
Tasks

    1. Find the linear regression equation for this data.
    2. Chart the original data and the equation on the chart.
    3. Find the equation's $R^2$ score (use the `.score` method) to determine whether the
    equation is a good fit for this data. (0.8 and greater is considered a strong correlation.)
    4. Extrapolate data:  If the ground temperature reached 95, then at what approximate rate would you expect the crickets to be chirping?
    5. Interpolate data:  With a listening device, you discovered that on a particular morning the crickets were chirping at a rate of 18 chirps per second.  What was the approximate ground temperature that morning? 

## 2] Assignment 6: 

### Brain vs. Body Weight

   In the file `brain_body.txt`, the average brain and body weight for a number of mammal species are recorded. Load this data into a Pandas data frame.

Tasks

    1. Find the linear regression equation for this data for brain weight to body weight.
    2. Chart the original data and the equation on the chart.
    3. Find the equation's $R^2$ score (use the `.score` method) to determine whether the
    equation is a good fit for this data. (0.8 and greater is considered a strong correlation.)


## 3] Assignment 7: 


### Salary Discrimination

The file `salary.txt` contains data for 52 tenure-track professors at a small Midwestern college. This data was used in legal proceedings in the 1980s about discrimination against women in salary.

The data in the file, by column:

      1. Sex. 1 for female, 0 for male.
      2. Rank. 1 for assistant professor, 2 for associate professor, 3 for full professor.
      3. Year. Number of years in current rank.
      4. Degree. Highest degree. 1 for doctorate, 0 for master's.
      5. YSdeg. Years since highest degree was earned.
      6. Salary. Salary/year in dollars.

Tasks

      1. Find the linear regression equation for this data using columns 1-5 to column 6.
      2. Find the selection of columns with the best $R^2$ score.
      3. Report whether sex is a factor in salary.


## 4] Assignment 8: 

### How Much is Your Car Worth?

Data about the retail price of 2005 General Motors cars can be found in `car_data.csv`.

The columns are:

      1. Price: suggested retail price of the used 2005 GM car in excellent condition.
      2. Mileage: number of miles the car has been driven
      3. Make: manufacturer of the car such as Saturn, Pontiac, and Chevrolet
      4. Model: specific models for each car manufacturer such as Ion, Vibe, Cavalier
      5. Trim (of car): specific type of car model such as SE Sedan 4D, Quad Coupe 2D          
      6. Type: body type such as sedan, coupe, etc.      
      7. Cylinder: number of cylinders in the engine        
      8. Liter: a more specific measure of engine size     
      9. Doors: number of doors           
      10. Cruise: indicator variable representing whether the car has cruise control (1 = cruise)
      11. Sound: indicator variable representing whether the car has upgraded speakers (1 = upgraded)
      12. Leather: indicator variable representing whether the car has leather seats (1 = leather)

Tasks, Part 1

      1. Find the linear regression equation for mileage vs price.
      2. Chart the original data and the equation on the chart.
      3. Find the equation's $R^2$ score (use the `.score` method) to determine whether the
      equation is a good fit for this data. (0.8 and greater is considered a strong correlation.)

Tasks, Part 2

      1. Use mileage, cylinders, liters, doors, cruise, sound, and leather to find the linear regression equation.
      2. Find the equation's $R^2$ score (use the `.score` method) to determine whether the
      equation is a good fit for this data. (0.8 and greater is considered a strong correlation.)
      3. Find the combination of the factors that is the best predictor for price.

Tasks, Hard Mode

      1. Research dummy variables in scikit-learn to see how to use the make, model, and body type.
      2. Find the best combination of factors to predict price.
