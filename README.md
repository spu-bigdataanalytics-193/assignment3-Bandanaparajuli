# assignment3-Bandanaparajuli
assignment3-Bandanaparajuli created by GitHub Classroom

The data consists of flight arrival and departure details for all commercial flights within the USA, from October 1987 to April 2008.All 
data are downloaded and stored as bz2 format because of its huge size.The goal of this project is to compare two ways of counting the total filghts of each carrier. First,I used Looping through each record and counting each airline's flight and after I have used map shuffle reduce model to get the
counts of flights from each carrier.
Map Shuffle and Reduce step go one after another.Map reduce requires you to divide the task into 3 different pieces. We cant miss any of the step. Shuffle is the important step which actually transfers the
output from map step to reduce phase.

1.Map- This step takes the dataset and changes into another set of data.It creates several chunks of data.

2.Shuffle- This is the second step where all data are rearranged for next step to run in parallel.It groups the results from mapping step which has the same key.

3.Reduce-It reduces the data that come from mapping and shuffling step.For example in my project case getting the counts.

Map Shuffle Reduce is very efficient way which save times and divides the task.

