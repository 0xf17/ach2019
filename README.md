# Algorithms, Computation and HCI - Studio at Srishti (2019)
The theory formalizes the intuition that any design requires significant resources, by introducing mathematical models of computation to study its problems and quantifying the number of resources needed to solve them, such as time, storage and other relevant contextual parameters. Studying how efficiently problems can be solved on a model of computation, using an algorithm. What are the fundamental capabilities and limitations of computers?

## Assignment

### A1 (Individual exercise) (30% weightage for your final grade)
- **A1.1** Group exercise: Build a collective definition of what is a good algorithm. While this was a group exercise, submit the collective definition (in the form of visual map as discussed in the class) but also include individual arguments if you have.
    - Submission format. PDF file containing the picture and/or text. 
    - Name your file as `A1.1-<YourFirstName>.PDF`.

- **A1.2** Exercise 1: Runtime analysis of Binary Search, Merge Sort and/ Quick Sort
    - Deliverables of each algorithm. (a) Pseudocode, (b) Your experiment protocol, (c) Experiment observations, (d) Analysis and results, (e) GitHub repo link containing algorithm implementation + test cases. 
    - The analysis and results must be able to find the following.
        - Find the relationship between size of the input array 'n' and total runtime for 't' iterations.
        - Find the relationship between maximum allowed value of any element 'm' and total runtime for 't' iteration.
        - Find the relationship between size of the input array 'n' and unit runtime (to execute one iteration of your algorithm).
        - Find all the dependencies between 'n', 'm' and 't'.
        - Find following runtimes for n=10^4 and m=10^5.
            - Best runtime
            - Avg. runtime
            - Worst runtime (each by sampling atleast 10^3 observations)
    - Submission format. PDF file containing all the above list of deliverables.
    - Name your file as `A1.2-<BinarySearch|MergeSort|QuickSort>-<YourFirstName>.PDF`.
    - Note that A1.2 has two PDF file submissions.
        
- **A1.3** Exercise 2: Calculating the number of arithmetic steps required by algorithm
    - Deliverables of each algorithm. (a) Your code + arithmetic cost of each step, (b) Calculation of expression indicating total arithmetic cost of your algorithm in terms of 'n'. (Eg. `3n+1`), (c) Calculation of unit run time (from previous exercise), (d) Recalculating runtimes by the expression. Eg. Your runtime would `f(n)*(ut)`, where f(n) is your previous expression and `ut` being algorithm's unit runtime, (e) Plot the runtimes for various 'n' for both previous exercise and this exercise, (f) GitHub repo link containing algorithm implementation
    - Submission format. PDF file containing all the above list of deliverables.
    - Name your file as `A1.3-<BinarySearch|MergeSort|QuickSort>-<YourFirstName>.PDF`.
    - Note that A1.2 has two PDF file submissions.
   
**Date of Submission for A1: ~~12th October 2019 11:59PM~~ 13th October 2019 11:59PM**

### A2 (Individual Exercise) (30% weightage for your final grade)
- Final proposal to conduct a analysis study on a context of your choice.
- Your proposal to ideally include (in any order) - 
    - (a) Problem/Vision statement - One/two line summary of your inquiry.
    - (b) Objectives of the study - What are the different things you want to study in the context?
    - (c) Design intent - Why do you want to study the chosen context?
    - (c) Background/Overview of the context - Synopsis highlighting important facts explaining the context  
    - (d) Study Plan - How you plan to conduct the study? Design test cases similar to Exercise 1 and 2 but for your chosen context.
- For rolling feedback, share your Google Doc with me and send me an email seeking feedback/review.
- Submission format. PDF file containing all the above list of deliverables.
- Name your file as `A2-<TitleOfYourStudy>-<YourFirstName>.PDF`.

**Date of Submission for A2: 19th October 2019 11:59PM**

## Assessment
Following are assessment criteria for this studio.

Each of your assignment will be assessed on following capabilities and dimensions of practice.

### Capabilities
1. **Investigate / Research and analyze / HCD Capability (See and Connect):** The student recognizes and builds the relevance of specialized research methods to unearth insights of underlying algorithms that are not accessible up front. And is able to assess algorithms through amortized and/or asymptotic complexity. (Capability level - Intermediate)
2. **Synthesize and Envision / Patterns and Systems / HCD Capability (Discern and Align):** The student is able to understand the computational complexity and then derive actionable insights to identify areas where algorithms could be improved. (Capability level - Intermediate)
3. **Construct / Thinking and Construct meaning / HCD Capability (Make):** The student is able to build the description of the enhanced algorithm through both high level and implementation. (Capability level - Intermediate)

### Dimensions of Practice
1. **Informed Practice: Focus Area Knowledge:** The student has an understanding of the relevance of studying algorithms in designing systems, services, and products specifically that interface human and computers; methods of analyzing algorithmic/computational complexity through amortized and asymptotic approaches; Big O notation; models of computations; ways to express algorithms; computing impact factor of algorithms. (Capability level - Intermediate)
2. **Creative Practice: Navigating Complexity:** The student understands the behavior of algorithms, its inputs, outputs, and complex logic; and adopt different methodologies to analyze the algorithm to make sense of how it works and then brainstorm and design how an algorithm might be improved. (Capability level - Intermediate)
3. **Expansive Practice: Communication and Dissemination:** The student is able to extract, understand and express the algorithms and related context through different ways in which an algorithm can be communicated (ie. High-level description, Pseudocode and Flowcharts). Also, the student is able to clearly use mathematical notations to describe aspects of an algorithm wherever needed. (Capability level - Intermediate)

### Studio Habits (will be based on your conduct, participation in the studio and reflection submission at the end of the studio)
1. Stretch and Explore
2. Reflect
3. Engage and Persist

### Checklist for Day 1
1. The Secret Rules of Modern Living Algorithms (About 1 hr) https://www.youtube.com/watch?v=kiFfp-HAu64
2. Small read from a popular text on Algorithms, "Introduction to Algorithms" (Sent on email).

### Week 1
1. What is a (good) algorithm?
2. What is the relevance of studying algorithm for a designer?
3. Introduction to basic algorithms - Searching and Sorting
4. Implementing those algorithms
5. Designing an analysis experiment and preparing observation protocol
6. Recording and plotting observations
7. ~~Assignment announcement and Grouping~~

### Week 1 Exercises
1. See What is GitHub? https://www.youtube.com/watch?v=w3jLJU7DT5E
2. Sign up on GitHub and perform https://guides.github.com/activities/hello-world/
3. Group exercise: Build a collective definition of what is a good algorithm (This is also part of A1)
4. Research about Computer architecture
5. Complete runtime analysis of Linear Search algorithm
6. Exercise 1: Runtime analysis of Binary Search, Merge Sort and Quick Sort (This is also part of A1)

### Week 2
1. Counting Arithmetic instructions
2. Making sense from Arithmetic instructions and manual time recording
3. Predicting runtime based on arithmetic functions.

### Week 2 Exercises
1. Exercise 2: Calculating the number of arithmetic steps required by algorithm (Details are sent over email) (This is also part of A1) 
1. Runtime analysis based on the given objectives for Binary Search, Merge Sort and/or Quick Sort. (Submission: Week 2 Thursday) (This is also part of A1)

### Week 3
1. Discussion of Study proposals (A2).
2. Reworking on Day 1 exercise.
3. ~~Discussing parameters and hyperparameters for an algorithm.~~
4. ~~Early conclusions for analysis (from Exercise 2).~~
5. ~~Identifying deficiencies in current analysis.~~
6. ~~Remedial measures to refine analysis.~~
   - ~~Designing micro test cases.~~
   - ~~Redesign rules to calculate costs.~~
7. ~~Final conclusions from analysis.~~
8. ~~Brief Introduction to order of growth (Theta notation)~~

### Week 3 Exercises
1. ~~Identifying algorithms around us and what determines how good they are.~~

### Week 4
1. Discussing parameters and hyperparameters for an algorithm.
2. Early conclusions for analysis (from Exercise 2).
3. Identifying deficiencies in current analysis.
4. Remedial measures to refine analysis.
   - Designing micro test cases.
   - Redesign rules to calculate costs.
5. Final conclusions from analysis.
6. Brief Introduction to order of growth (Theta notation)
