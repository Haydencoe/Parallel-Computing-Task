# Parallel-Computing-Task

The task is a simple statistical tool for analysing historical weather records from Lincolnshire. 
The provided data files include records of air temperature collected over a period of more than 80 years from five weather stations in Lincolnshire:
Barkston Heath, Scampton, Waddington, Cranwell and Coningsby. The tool loads the provided dataset and performs statistical summaries of temperature
including the min, max and average values, and standard deviation. 

Due to the large amount of data (i.e. 1.8 million records), all statistical calculations are performed on parallel hardware and implemented by software written in OpenCL. The tool also reports memory transfer, kernel execution and total program execution times for performance assessment.

The main files of the program are: Tutorial 3.cpp &

