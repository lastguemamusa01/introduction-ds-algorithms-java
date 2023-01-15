# introduction-ds-algorithms-java

al algorithm is a way of solving well-specified computational problems

algorithm - a finite set of rules that give a sequence of operations for solving a specific type of problem - knuth

algorithm like recipe of tea

euclid's algorithm - find the GCD of 2 positive integers - recursive algorithm

sorting data 


Bubble sort - each pass the high number is in the right side

running time - estimate time -> to estimate hardware requirements

knowing algorithms - could now if it is feasible or impossible

for improvement existing algorithms

ds - data structure 

ds - ways in which we store data. help in faster access or faster saving of the data

like library - in the racks in order by a-z

choose ds depending which operation used frequently or want to be faster

## Correctness of an algorithm

step 1 - statment to be proven
step 2 - list all assumptions
step 3 - chain of reasoning from assumptions to the statement

for check the algorithm is correct - we need to prove that incorrectness of an algorithm

step 1- give a set of data for which the algorithm does not work.

step 2 - usually consider small data sets 

step 3 - especially consider borderlines cases

## Analysis of algorithms

Big O notation

when algorithms implemented - consider 2 things

1 - how much space does it take to store data in memory to execute algorithm ? - space complexity
2 - how much time does it take for an algorithm to run ? - time complexity

time complexity > space complexity( ram is cheaper)

measure time an algorithm - same input, different kind of machine(computer or phone), also enviroment affect

like shortest path from a to b - it varying by person like adult or child, type of transportation like car or walk
even is the same distance. also could be vary depending the days and the enviroment like traffic, rain or sunny days.
etc

time will be different

shortes path could be shortest step from a to b


1 ms to sort 5 lements

2 to 4 ms to sort 11 lements

even runing in same machine, every time could throw little variation of time.

even same input data size


order of the growth - run the algorithm with huge data

linear growth - 20 - 100 - 1000
quadratic growth - 40 - 1000 - 100000

asymtotic analisys -  run the algorithm with huge data

## type of time complexity

3 type of analysis

worst, average and best case 

best case - not important

average case - complex with statical analysis

deal with worst case - > the important one

Ram model of computation

assume - we have infinite memory, each operation(+,-) takes unit time, for each memory access, unit time is consumed

data may be accessed from ram or disk, it is assumed that the data is in the ram

## Bubble sort complexity


array of 5 numbers

worst case - descending order

12 - 8 -7 - 5 - 2

need to sort to ascending order

1 comparison and 3 swap for each comparion - > 4 comparison

4 x 4 = 16 

16 steps - first pass

second pass - >  4 x 3 = 12

so for every passes

16 + 12 + 8 + 4 = total of 40 steps

40 steps for 5 elements

16 + 12 + 8 + 4 = 40 
= 4(4+3+2+1)
= 4(n-1+n-2+...+3+2+1)
= 2 x n x (n-1)
= quadric equations 
= pn^2+qn+r
= 5^2 = 25 



## pseudo code in bubble sort

for i = 0 to A.length-2
    for j = 0 to A.length-2-i









