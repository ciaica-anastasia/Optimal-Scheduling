# Optimal-Scheduling

Found an optimal solution for the nurse scheduling problem (NP-hard) - the operations research problem of finding an optimal way to assign employees to shifts, using simulated annealing algorithm. Took into account hard (employee coverage, prohibited working patterns) and soft (individual work preferences) constraints.
Justified the choice of this algorithm over the genetic algorithm. Conducted an analysis of the results.

###### Final_SA_Random(1HC,1SC) 
- 1 hard constraint, 1 soft constraint
- generates a random solution (some kind of work schedule) and then applies the optimization algorithm that will filter out inappropriate solutions 

###### SA_random
- older version of random solution

###### SA_linear
- a linear algorithm is applied first, which builds a certain valid solution, which is then fed to the input to the Simulated Annealing algorithm

#### See [proposal](https://github.com/ciaica-anastasia/Optimal-Scheduling/blob/main/proposal.pdf) and [poster](https://github.com/ciaica-anastasia/Optimal-Scheduling/blob/main/poster.pdf) for more details.
