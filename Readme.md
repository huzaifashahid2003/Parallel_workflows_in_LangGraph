# CSS Essay Evaluator

An AI-powered essay evaluation system built with **LangGraph** and **LLMs**.

### Features

* Evaluates **Language, Analysis, and Clarity of Thought**
* Runs evaluations in parallel using LangGraph
* Generates individual scores and feedback
* Calculates an overall average score

### Tech Stack

**Python · LangGraph · LangChain · LLMs**

### How It Works

The essay is passed into the LangGraph workflow, where multiple evaluator nodes independently assess different aspects of the essay. Their feedback and scores are then combined to generate the final evaluation.
