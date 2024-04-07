# QOSF Mentorship Cohort 9 Submission
## Task 2: Odd to Even

Design a quantum algorithm that when given numbers of range [1,n) and are odd convert them into even numbers, and they must stay in the same range so they cannot be less than 1 nor greater than n. n = 2^k where k is the number of qubits you are going to use.

Example:


B = odd_to_even (n = 31,list= [1,2,2,4,5,6,7,11,17,21,22,23] )
print(B)

One possible output is
 
“[2,2,2,4,4,6,8,10,18,20,22,22]”

Exist multiple solutions

References:

[1] Deutsch, David, and Richard Jozsa. "Rapid solution of problems by quantum computation." Proceedings of the Royal Society of London. Series A: Mathematical and Physical Sciences 439.1907 (1992): 553-558.
[2] Bernstein, Ethan, and Umesh Vazirani. "Quantum complexity theory." SIAM Journal on computing 26.5 (1997): 1411-1473.
[3] Grover, Lov K. , "A fast quantum mechanical algorithm for database search", Proceedings of the 28th Annual ACM Symposium on the Theory of Computing (1996), arXiv:quant-ph/9605043
