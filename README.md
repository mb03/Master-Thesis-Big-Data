# Big Data Computing
This page is a showcase of my Master Thesis. 
I hope to find whether there is interest in such a project and the effort of publishing this service is worthy.
My project applies batch operation on a large dataset of unstructured data in order to achieve DB-like operation in a concurrent manner on huge amount of data. It is written in C++ and therefore aims to be more powerful than current publicly available option. 
The input format is either json or a python object and the output is in the json format.
The developed API, provides the following functions:
- Map
- Reduce
- FlatMap
- Filter
- Cartesian
- Collect
- Persist

Tests against the fastest market competitor suggests that we achieve around 20 times its speed while using 90% less resources, namely memory and computational power, only focusing on the architecture (not on the language itself). You can see this in the following plot (which is a little biased by the limited supply of machines, but other tests suggest the same). The speedup is structural, since we suppose this factor is almost a constant in the deployment version.
![Running time on same input and execution](https://raw.githubusercontent.com/mb03/Master-Thesis-Big-Data/master/img/comparison.png)

This is only a proof of concept, it is not ready for the market, and may have some bug and some memory leaks, but it is for sure an interesting alternative to actual solutions, especially in terms of performances.
 
In case of further interest, I am willing to expose the service via API and to dive deep in it.

Thank you for your time.
[mb03](https://github.com/mb03)
