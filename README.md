# ADAPT-T_Results
Results of experiments conducted for ADAPT-T: An Adaptive Algorithm for Auto-Tuning Worker Thread Pool Size in Application Servers

The complete set of results can be found in this repository as .ods files

The documents have separate sheets for each scenario and follows the following naming convention

1. For results of latency measurements, \<TestName\>\<Optimization\>\<NumberOfConcurrentUsers\> 

2. For results of the thread pool size of the corresponding experiments, \<TestName\>\<Optimization\>Threads\<NumberOfConcurrentUsers\> 

Where,

\<TestName\> : DbRead | DbWrite | Prime1m | Prime10m

\<Optimization\> : Mean | 99P

Mean = Mean latency optimization

99P = 99% latency optimization

In all these documents, the elapsed time is of the hh:mm:ss format and the latency values are expressed in milliseconds 
