# Deep_learning_charity

### Analysis:

The goal of this Charity funding predictor is to create an algorithm to predict whether certain applicants for funding would be successful. 

### Preprocessing: 

• We first start by loading in the CSV that contains over 30,000 organizations that have received funding from alphabet soup over the past few years. 

• Now we know that our target is the column Is_Successful and whether this reads a yes or a no. 

• Once we determine our target, we know that we need to drop some columns, this is the EIN and NAME columns. These are unrelated to our algorithm. 

• We then attempt to trim the rare categorical values in our columns that have 10 or more unique values. And add a new name for this called other. 

• Using get _dummies we then encode the categorical variables

### Compiling, Training, and Evaluating the Model:


• For the first model I used 2 hidden layers. This was to get a baseline of what my accuracy would be just given a simple 2 hidden layers. One relu and one sigmoid to see if I could get to an accuracy of 75 percent. I was unable to, only reaching about 72.

• For the second model I used 3 hidden layers. This time only pulling an accuracy of a higher 72.7 

• For the last model I used 4 hidden layers. This time getting a higher 73.13.

![Screenshot 2021-12-15 182742](https://user-images.githubusercontent.com/81705144/146285833-3095a808-0c95-45bf-97e6-3243657b775a.png)

### Summary:

With these results I think going back and doing some more preprocessing would get a score that would be much higher as the layers only seemed to increase by 1%. Possibly dropping more columns that may not be entirely relevant to the model we need, or changing what we considered rare categorical values. 


>- Matthew Villarreal
