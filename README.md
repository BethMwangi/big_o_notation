# big_o_notation
This repo explains the Big O Notation and its complexities. 



Big O references how **complex** an algorithm is.
It assumes the worst case (algorithm that will run the slowest).
We want to know whether the runtime is constant, linear,exponential, logarithmic and quadratic.
Big O is the way of measuring the efficiency of an algorithm and how well it scales based on the size of the dataset.
let's say you have 20 items and you want to sort them out. One can use alot of algorithms to sort them out, however not all algorithms are built equally. 
Some algorithms are more complex than others.
This is where the big O comes in.Since it measures the worst case senarios and can be used to describe the execution time required or the space used (e.g. in memory or on disk) by an algorithm.
Efficiency covers the following;
 *CPU (time) usage
 *Disk usage
 *Memory usage
 *Network usage
## Algorithmic complexities 
**Why is it important?**
* Allows us to measure an Algorithms efficiency to determine scalability.
* Most problems can be easily solve 

### Types of Algorithic Complexities(running time)


##### Constant Complexity O(1)
 This means that the size of the data is irrelevant, the algorithm will always take a constant time. 1 item takes 1 second, 10 items takes 1 second, 100 items takes 1 second. It always takes the same amount of time.In short it takes the same amount of time regardless of the amount or size of the data.running time is denoted by O(1).

##### Constant Complexity Order of One
This means that the size of the data is irrelevant, the algorithm will always take a constant time. 1 item takes 1 second, 10 items takes 1 second, 100 items takes 1 second. It always takes the same amount of time.In short it takes the same amount of time regardless of the amount or size of the data.running time is denoted by O(1).
##### Logarithmic Complexity
##### Linear Complexity
##### Qadratic Complexity
##### Cubic Complexity
##### Exponential Complexity


##### Logarithmic Complexity O(log n)
In this complexity, the time increases with the size of the data set, but not in a proportional manner. e.g one item takes 1 sec, 10 items take 2 seconds,e.t.c meaning the time increases as the data set is added. e.g the binary search.

##### Linear Complexity O(n)
Unlike logarithmic complexity, the time increases proportionally as the data set enlarges, e.g 1 item takes 1 second, 2 items take 2 seconds, 10 items take 10 seconds..e.t.c.

##### Qadratic Complexity O(n*n)
An algorithm is said to run in logarithmic time if its time execution is proportional to the square of the input size.E This gets slower 1 item takes 1 second, 10 items takes 100 seconds.Example is the bubble sort, insertion sort and the selection sort 

##### Exponential Complexity 
O(2N) denotes an algorithm whose growth doubles with each additon to the input data set. The growth curve of an O(2N) function is exponential - starting off very shallow, then rising meteorically. An example of an O(2N) function is the recursive calculation of Fibonacci numbers:

int Fibonacci(int number)
{
    if (number <= 1) return number;

    return Fibonacci(number - 2) + Fibonacci(number - 1);
}



