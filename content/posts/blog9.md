---
title: "Blog #9 | Serving the Dining Philosophers"
date: 2024-11-25T09:04:34-05:00
draft: false
tags: ["blogs"]
---

Happy Monday!

Over the last week, my partner and I have made significant progress on our OS assignment. He is mainly responsible for the written part of the assignment. He has a better conceptual understanding of the course, so although I was primarily responsible for the coding part of the assignment, he has helped me debug my code for the scheduler simulator so that it behaves in a conceptually accurate manner.

The second part of the assignment was a little bit of a headache and required us to go to the prof's/head TA's office every day to understand if we were on the right track. This part required us to implement a system where 5 processes would be able to run concurrently in an efficient manner. 

To solve the [critical section problem](https://en.wikipedia.org/wiki/Critical_section) and the [race conditions](https://stackoverflow.com/questions/34510/what-is-a-race-condition/34550#34550) caused by it, we implemented a basic semaphore acquisition system that resembled the [“dining philosophers” problem](https://en.wikipedia.org/wiki/Dining_philosophers_problem#Problem_statement). We then implemented a protocol that behaved similarly to a bounded waiting system where we made sure that if a process was denied a semaphore the first time, the next time it must be able to acquire that semaphore without fail, further solving issues of livelock and deadlock. 

It is a little different approach from most people, as they might usually try to implement [Dijkstra's solution](https://en.wikipedia.org/wiki/Dining_philosophers_problem#Dijkstra's_solution), but math and programming are about problem solving, and each problem can have multiple solutions, so as long as we come up with a solution we are good!

Except for the part 1 report which discusses and compares the scheduling algorithms with each other, I was able to finish off all the coding parts pretty quickly, giving me lots of time to prepare for finals week.

---

This brings us to our plans for this week:

1. Finish off the Part 1 report from my OS assignment
2. Start revising some material from my OS and RTOS course for the finals week

As you can see, my plans for this week are pretty chill since there's no high stress work remaining anymore. Hopefully, this will help me fix my sleep schedule again (which I accidentally messed up because of the OS assignment ¯\\(ツ)/¯ ).

---