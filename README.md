# Project report

## Title: AI-Powered Automatic Curriculum Generator Using LangGraph

## Overview

This project implements an **LLM-driven curriculum generation** system using **LangGraph**.  
The system takes a learner’s goal—for example, “I want to learn digital design with Verilog to implement simple FPGA projects”—and automatically:  
- **Clarifies and expands** the user’s learning goal  
- **Classifies** it into a subject category (ECE, ML, etc.)  
- **Generates a week-wise curriculum outline**  
- **Gathers learning resources** (text, video, MOOCs) in parallel  
- **Builds a complete, structured curriculum plan**  

The workflow demonstrates concepts of:  
- Graph-based execution  
- Parallel nodes  
- State merging  
- LLM-oriented program design  
- TypedDict state propagation  

The final output is a **clean multi-week curriculum** suitable for students with beginner, intermediate or advanced level courses.  

## Reason for picking up this project

This project aligns strongly with the course’s goals because:  
- It applies **software engineering principles** such as modular design, state handling, and structured workflows.  
- It uses **graph-based reasoning**, which is part of modern AI/LLM engineering.  
- It integrates **multiple programming concepts**: Python functions, prompt engineering, asynchronous flow, and typed states.  
- It demonstrates practical usage of AI frameworks like **LangChain and LangGraph**, which are widely used in industry.  
- It shows how LLMs can automate real educational tasks—an applied example directly connected with digital systems learning and engineering tools covered in the course.

## Plan

I plan to excecute these steps to complete my project.  

[TODO] **Step 1 – Define the CurriculumState schema**  
Create a TypedDict-based representation of all fields needed in the graph (outline, resources, final plan, etc.)  

[TODO] **Step 2 – Implement core graph nodes**  
Write functional nodes that:  
- refine user goal  
- classify subject  
- generate outline  
- collect text/video/course resources  
- build the final curriculum  
[TODO] **Step 3 – Implement graph execution flow**  
Connect nodes using LangGraph (START → expand → classify → outline → resources → final builder)  

[TODO] **Step 4 – Implement parallel resource gathering**  
Add 3 parallel branches (text, video, course), merging into a single final step.  

[TODO] **Step 5 – Integrate LLM calls**  
Define `call_llm()` to handle structured prompting and predictable outputs.  

[TODO] **Step 6 – Build the full workflow**  
Compile the StateGraph and run it end-to-end on an example input.  

[TODO] **Step 7 – Validate final curriculum output**  
Run the pipeline with multiple goals and verify that results are coherent and structured.  

[TODO] **Step 8 – Write documentation and prepare the final report**  
Add README, notebook explanations, and comments.  
