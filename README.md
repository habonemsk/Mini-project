
# AI Multitasking Mini-Project

## Overview
This project is designed to assess the AI's capability to multitask, particularly in retrieving and processing a sequence of problems while adhering to specific output guidelines.

## Unique Features and Observations

1. **AI Multitasking:** The AI consistently tracks each problem's number and ensures solutions align with predefined output guidelines. Subsequent to processing, results are written and updated to a dedicated file every 10 problems.
2. **Memory Management Patterns:** 
   - For the initial set of 10 problems, the AI retains memory of the first 9 but disregards the 10th.
   - Between problems 11 to 20, deviation begins from the 17th problem, where the AI introduces a unique problem.
   - This deviation pattern continues in subsequent sets, notably from the 21st to the 30th problem and so forth.
3. **Recommendations:** It's pivotal to investigate the underlying reasons for these systematic deviations. Understanding the source could offer insights into potential areas of improvement in the AI's training and execution stages.

## Project Instructions

1. **Initialization:** Start by uploading the project file to delineate specific requirements.
2. **Problem Set Preparation:** Curate an input file comprising 100 problems. The file should be housed within the 'combined_problems' directory.
3. **Execution:** Guided by the requirements, the AI will address the first 10 problems from the file.
4. **Problem Display:** ChatGPT will sequentially display the initial 10 problems for user reference.
5. **Output Expectations:** The AI's output will encompass:
    - Python Solution Code
    - Test cases, inclusive of the `benchmark_solution(solution, test_cases)` function and relevant benchmark execution commands.
    - Benchmarking Results
    - All outputs will be consolidated and saved in a new file.

Thank you for your engagement with our project. Your contributions and feedback are highly valued.
