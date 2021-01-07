# openmp-optional-individual-submission-

# YouTube Link: https://www.youtube.com/watch?v=wemp3Vsdppk

This recorded video is on "OpenMP", how OpenMP uses processors from our computer, and make program execution faster by distributing tasks among them. 


#1:26  Simple "Hello, world" demonstration <\br>
#3:32 Solving an integral(basically "pi" estimation), but the required time is very high. (due to random data sharing  inside the code) \

#7:20 New approach (Solved previous issue), required time drops significantly, but speed does not increase with the increase of the number of threads. (due to shared cache structure) \
#13:09 Another new approach to solve data congestion in the cache using "omp_critical". This time thread's number decreases the required time. 
