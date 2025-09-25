---
title: "Blog #8 | Simulator Update - Scheduling and Concurrency"
date: 2024-11-18T09:21:16-05:00
draft: false
tags: ["blogs"]
---

Happy Monday!

Another two week break! Sorry about that. A lot has happened since my [last post](../blog7). As I mentioned previously, I have been working on building a [scheduler simulator](https://en.wikipedia.org/wiki/Scheduling_(computing)). The program expects a list of processes to run with their trace information as input, does stuff, and then gives us two output files. One shows at what time each process undergoes a state transition, with its old and new state, and the other output file shows at what time a process was allocated/deallocated a memory partition, along with how much total and usable memory space remained in the system. 

The difference between the two memory spaces was that the former counted the internal fragmentation within each memory partition. Although that sounds complicated, the solution was much easier than expected. Again, I would love to explain further, but others are working on this assignment, which means I might risk plagiarism accusations if I post my solution on the internet. 

Of course, I will do that eventually, with a complete explanation of how the program works, once my course finishes, but until then you all will have to wait patiently! As of last Friday-ish, you could say I have finished that project, with a decent implementation of various scheduling algorithms such as "first come first serve", "shortest job first", and "round robin". I am now only waiting for example outputs from our course professor, after which I can fine-tune my program to behave as expected. However, until then, I can not "fix" my program, if I do not know what is wrong it.

There is a second part to this assignment. We are asked to extend our program to simulate concepts such as concurrency, shared memory and semaphores, which means the final implementation of this program will include two simulators. I recently reviewed the textbook to learn these concepts and have a rough idea of what I am supposed to do. This is what I will be working on over the next week.

This operating systems course is probably the highlight of this semester. I am really enjoying this course and hope all of my readers feel the same by reading my blogs on it. I will hopefully return next Sunday or Monday and continue to give more updates on my progress. Thanks for reading!

---