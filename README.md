# RMS-Sched

Data should be read as follows :

First line describes the number of jobs, number of machines, and number of configurations:
#nbjobs #nbmacs #nbconfigs

Next lines correspond to jobs' descriptions, one line per job,. Each line consists in a set of X tuples structured as follows:
{#MachineNumber #DurationInConfig-1 #DurationInConfig-2 ... #DurationInConfig-nbconfigs}

Final lines correspond to the Reconfiguration Matrix 
