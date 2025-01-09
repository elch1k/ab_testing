Here I dive into ordinary Data Analyst task to make a common AB test. As I mentioned in .ipynb file it's really necessary to properly model the whole experiment: determine hypotesis, choose right metrics and randomization units, calculating sample size with a predetermined power and significance level and etc.. 
This is a truly difficult and expensive process that a company must be confident in choosing. In my way I just grab data from the [kaggle](https://www.kaggle.com/datasets/sergylog/ab-test-data) and then just make some research and AB test analysing. Since I did not have clear conditions for what to research, I simply took into account all possible variants that might be interesting from this AB test data.

Well, the research was conducted around all users and platform users. We can now see their distribution, and as we see, there are many more ordinary users and they distort our data.
![image_01](https://github.com/elch1k/ab_testing/blob/main/images/image_01.png?raw=true)
