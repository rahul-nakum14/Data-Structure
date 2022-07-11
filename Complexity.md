TIME COMPLEXITY : -
time complexity refers to an “amount of time taken by an algorithm to run”

SPACE COMPLEXITY : -
    space complexity as “amount of resources, usually space or memory, taken by an algorithm to run”.

    Auxiliary space is the extra space used by an algorithm, which on adding with the space taken by the input values, gives us space complexity.

    Space complexity = Auxiliary Space + Space taken by input values
    
    
Asymptotic Notations are the expressions that are used to represent the complexity of an algorithm.


Types of Algorithm Analysis:

1)  Worst case (Ο) (Big O)
2) Best case (Ω) (Omega)
3) Average case (θ) (Theta)

Worst case:
In the worst-case analysis, we calculate the upper bound on the running time of an algorithm.
the worst-case time complexity of linear search would be Θ(n).

Best Case: 
In the best case analysis, we calculate the lower bound on the running time of an algorithm. 
We must know the case that causes a minimum number of operations to be executed. In the linear search problem, the best case occurs when x is present at the first location. 
The number of operations in the best case is constant (not dependent on n). 
So time complexity in the best case would be Θ(1) 

Average Case:
In average case analysis, we take all possible inputs and calculate computing time for all of the inputs. 
Sum all the calculated values and divide the sum by the total number of inputs.So we sum all the cases and divide the sum by (n+1)

Types of Data Structure Asymptotic Notation
1. Big-O Notation (Ο) – Big O notation specifically describes worst case scenario.
2. Omega Notation (Ω) – Omega(Ω) notation specifically describes best case scenario.
3. Theta Notation (θ) – This notation represents the average complexity of an algorithm.

WHAT IS BIG-O NOTATIONS: 
Big O notation specifically describes worst case scenario. It represents the upper bound running time complexity of an algorithm.

![image](https://user-images.githubusercontent.com/106817606/178297862-c1c4e94f-2f25-415e-97da-eee2ea789f7c.png)

```O(1) < O(log n) < O (n) < O(n log n) < O(n^2) < O (n^3)< O(2^n) < O(n!)```

![image](https://user-images.githubusercontent.com/106817606/178298686-9a8fa3b3-42fc-4ad8-80d8-1226d31cc33a.png)

O(1)
Big O notation O(1) represents the complexity of an algorithm that always execute in same time or space regardless of the input data.

O(1) example
The following step will always execute in same time(or space) regardless of the size of input data.

Accessing array index(int num = arr[5])
O(n)
Big O notation O(N) represents the complexity of an algorithm, whose performance will grow linearly (in direct proportion) to the size of the input data.

O(n) example
The execution time will depend on the size of array. When the size of the array increases, the execution time will also increase in the same proportion (linearly)

Traversing an array
O(n^2)
Big O notation O(n^2) represents the complexity of an algorithm, whose performance is directly proportional to the square of the size of the input data.

O(n^2) example

Traversing a 2D array
Other examples: Bubble sort, insertion sort and selection sort algorithms (we will discuss these algorithms later in separate tutorials)

Similarly there are other Big O notations such as:
logarithmic growth O(log n), log-linear growth O(n log n), exponential growth O(2^n) and factorial growth O(n!).

WHAT IS Omega Notation (Ω) :
The notation Ω(n) is the formal way to express the lower bound of an algorithm's running time.It measures the best case time complexity or the best amount of time an algorithm can possibly take to complete.

![image](https://user-images.githubusercontent.com/106817606/178299402-c18c490b-fec1-465b-b739-83553e8c8a33.png)


WHAT IS Theta Notation (θ) :
The notation θ(n) is the formal way to express both the lower bound and the upper bound of an algorithm's running time. It is represented as follows 

![image](https://user-images.githubusercontent.com/106817606/178299542-af06a920-c67e-42a4-baf3-93cb5d6a2121.png)

