# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.
From this lab we learned how find a naive equation, the min term, and the max term
equations. Finally we implemented the verilog code onto vivado using the equations we solved for. Finally, we
implmented it onto the board to show how it works corresponding to the truth table.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
The edges are connected because they are adjacent to each other.

### Why are the names Sum of Products and Products of Sums?
Sum of products menas you are anding terms together to create a group than oring thoose groups together.
The prodocut of sums is the inverese of that, oring terms together to create a group and anding the groups together.

### Open the test.v file – how are we able to check that the signals match using XOR?

We did this by xoring the naive led with the min and max terms. If it did not equal 0 then it would fail the test case. 
