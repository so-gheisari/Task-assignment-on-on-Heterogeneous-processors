# Task-assignment-on-on-Heterogeneous-processors
This is a simple sample code for scheduling tasks in form of DAGs on Heterogeneous Cloud Computing platforms using Learning Automata

A cloud computing environment is a distributed system in which idle resources are available in a wide area network like the Internet. Since these resources have diverse specifications, computational clouds are highly heterogeneous systems. Dispatching cloud applications onto processing nodes is known as task scheduling. Finding proper machines or even virtual machines (VMs) that can execute jobs in order to gain high utilization in such a heterogeneous environment is perceived as a multi-objective optimization problem. In this paper, a dynamic learning automata-based task scheduling algorithm is proposed. In the algorithm, which is named LADA, each application is modeled as a Directed Acyclic Graph (DAG) that contains tasks as nodes and data dependencies between them as edges. At first, tasks are grouped based on their data dependencies in order to collect independent tasks to one group. Then, a variable- structure learning automaton is associated with each task in the groups to discover an appropriate pair task-machine combination. Main goals of LADA are minimizing makespan and energy consumption through efficient task placement that leads to load balance and maximizes resource utilization. In addition, an improvement is added, which upgrades the results by using a different grouping policy before task assignment. Eventually, computer simulation outcomes reveal the superior performance of the proposed algorithms on high heterogeneous environment compared with the state-of-the-art algorithms. Total execution time and energy consumption decrease up to 50% and 37%, respectively.

The paper status is under-review and here, just a simple task assignment develpoment by Python has been added. The main simulation have been don on CloudSim simulator. 
