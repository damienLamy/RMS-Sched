# RMS-Sched

Data should be read as follows :

First line describes the number of jobs, number of machines, and number of configurations:
#nbjobs #nbmacs #nbconfigs

Next lines correspond to jobs' descriptions, one line per job,. Each line consists in a set of X tuples structured as follows:
{#MachineNumber #DurationInConfig-1 #DurationInConfig-2 ... #DurationInConfig-nbconfigs}

Final lines correspond to the Reconfiguration Matrix 

Note that files _1 to _5 are designed as Russian dolls (RJSSP_S_1_1 can be recovered from RJSSP_S_1_5 by considering only 1 configuration)
