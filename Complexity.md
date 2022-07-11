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

WHAT IS Omega Notation (Ω) :
The notation Ω(n) is the formal way to express the lower bound of an algorithm's running time.It measures the best case time complexity or the best amount of time an algorithm can possibly take to complete.

