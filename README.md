# Stock-Analysis

## Overview of Project

The purpose of this analysis is to be able to quickly analyze large data sets, in this case, the performance of several stocks over a number of years. This can be an invaluable tool to help someone save time when working with large datasets. Initially we only analyzed twelve stocks, but we wanted to refactor the code in order to include even more data and still yield results in a timely manner. 

## Results

After refactoring the script it did run much faster in comparison to the original analysis. The runtime for the initial script  for 2017 and 2018 were around 0.60 seconds while the refactored code for 2017 and 2018 was approximately 0.11 seconds. Both years with the original script and refactored script were approximately the same, this may not be the case if data was expanded for one year vs. the other. 

## Summary

### Advantages

Code refactoring can make the code more flexible overall. It appears to be cleaner and easier to read after refactoring, which can make it is easier to maintain. Also, with that added flexibility we can add more functionality to the code if deemed necessary. 

### Disadvantages

Refactoring code may be very time consuming and we may not know where to go or where to start when refactoring code. There are also chances for mistakes when refactoring original code, especially if one is not sure where to begin when trying to remove “code smell,” or duplicity. 

### Application of Pros and Cons

The original VBA script was duplicating a lot of code and I do believe once it was refactored it was much cleaner and easier to read. It also improved upon the runtimes which goes to speak to being more flexible when analyzing data and the ability to add functionality. 
While refactoring the script I did run in to several more errors than I did with the original script, which took some additional time and research. 
