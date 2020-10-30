# EMR-GIT-WORKSHOP-2020
This contains some of the material that I found useful.

## DOCS
1. Documentation : https://git-scm.com/docs


# AGENDA ?
1. The main idea is to get familiar with Git. 
* Q : Is this the best walk-through ever ? 
* A : No, not even close. 

2. What we will be looking at ? </br>
    a.) What is GIT ? </br>
    b.) What is it's USE ?  </br> 
    c.) Some workflows that usually developers usually use. </br>
    d.) To make you familiar with GIT and provide a usual walk-thorough. </br>
    e.) We will not be doing the usual "HELLO WORLD" program, instead we will do some useful thing. </br>


## Some Inportant Git Commands : 
1. Network Commands : Clone, Push, Fetch, Pull 
2. Some more : add, status, commit etc. 
3. How to call for help -- Use Man-Pages(Manual Pages -- use git {command} --help)

### Resources to learn the Internal Working: 
1. You have to know that Git is based on Graph Structure and that each commit is a node in the graph.
2. If you have studied LL(Linked Lists) you know that we must have a HEAD (the git also has a reference named HEAD).
3. Then how to handle merge-conflicts is a must to know, because you will have merge conflicts and then you will be stuck.
4. **https://www.coursera.org/learn/version-control-with-git** 


### What Next ? 
Q. I have learned quite a bit in this lesson, what should I do next ? <br/>
A. Very well then, I have made a homework for you. [Homework-Repository-Link](https://github.com/jalotra/EMR-GIT-HOMEWORK). You have to use all the knowledge that you have learnt to complete the assignment. <br />
These are the steps to take : 
1. Fork the repository.
2. And then clone the repo (Hint : Use git clone {reponame})
3. Create a new branch (namely call it {dev}, HINT : Use git branch {nameofthenewbranch} and git checkout {nameofthenewbranch})
4. Fill the function in the src/matrix_mul.cpp and the compile and test your code.
5. Once you pass all the tests then push the changes to the (same {dev} branch)
6. Then create a pull-request to do the {main} branch and describe what you have changed in the code.
7. And since you are the owner in the first place, merge the code after looking at the code. 


