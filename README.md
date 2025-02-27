Download link :https://programming.engineering/product/practice-2-program-that-can-be-used-to-gather-data/

# Practice-2-Program-That-Can-Be-Used-To-Gather-Data
Practice 2 Program That Can Be Used To Gather Data
SPECIFICATIONS:

Write a program that can be used to gather data about the number of hours college students spend on Facebook and Twitter (combined) in one month.

Main Function

In Main, ask the user how many students were surveyed.

Main should make a vector to define an vector of floats with the number of elements equal to the number of students surveyed.

Main should then call a function called getFBTData to allow the user to enter the number of hours each student spent on Facebook and/or Twitter (combined) this month into the vector.

Main should then call a function called printVector to print out the values in the vector.

Main should then call a function called getMIn to get the minimum hours spent in a month.

Main should then call a function called getMax to calculate and display the maximum of the values entered.

Main should then call a function called getAverage to calculate and display the average of the values entered.

Main should then call printAboveAvg. This function will print out all the times that are greater than the average.

Main should then call printBelowAvg. This function will print out all the times that are equal to or below the average.

Main should then print out a tab and then the header “STATISTICS FOR TIME SPENT ON FACEBOOK & TWITTER” in all capital letters, then skip down to the next line and then print out the average, max & minimum.

The labels “Average:”, “Minimum:”, and “Maximum:” should all have a colon “:” after the word.



getFBTData Function

Allow the user to enter the number of hours each student spent on Facebook and/or Twitter into the vector. The function will accept as arguments the following:

An vector of floats

An integer that indicates the number of elements in the vector.

Input Validation: Do not accept negative numbers for input.



printVector Function

This function should print out the text “Number of hours each student spent on Facebook/Twitter: “. Then, the function should print out each element in the vector with a space between each element.

The function will accept as arguments the following:

An vector of floats
An integer that indicates the number of elements in the vector.

getMin Function

The function should iterate through the vector and find the minimum value which should be returned.

Write a function that accepts as arguments the following:

An vector of floats

An integer that indicates the number of elements in the vector.

getMax Function

The function should iterate through the vector and find the maximum value which should be returned.

Write a function that accepts as arguments the following:

An vector of floats

An integer that indicates the number of elements in the vector.


getAverage Function

The average of a set of values is calculated by adding all the values and then dividing the sum by the number of values in the set.

Write a function that accepts as arguments the following:

An vector of floats

An integer that indicates the number of elements in the vector.

The function should determine the average of the vector. The average is the value the function should return.

printAboveAvg Function

This function should print out the text “Number of hours each student spent on Facebook/Twitter that is above the average is: “. Then, the function should print out each element in the vector that is greater than the average with a space between each element.

The function will accept as arguments the following:

An vector of floats
An integer that indicates the number of elements in the vector.
The average time
printBelowAvg Function

This function should print out the text “Number of hours each student spent on Facebook/Twitter that are equal to or below the average is: “. Then, the function should print out each element in the vector that is equal to or less than the average with a space between each element.

The function will accept as arguments the following:

An vector of floats
An integer that indicates the number of elements in the vector.
The average time
