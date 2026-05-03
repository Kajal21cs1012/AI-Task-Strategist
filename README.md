# AI-Task-Strategist

## Chosen Vertical
**Personal Productivity & Logical Assistant**

## Approach & Logic
This assistant uses **Google Gemini 1.5 Flash** to perform "Reasoning over Tasks." Instead of just listing to-dos, it evaluates the urgency and complexity of a task to provide a logical execution strategy.

## How it Works
1. User inputs a raw task.
2. The system sends it to Gemini API with a specific system prompt for logical analysis.
3. It returns a **Priority Score** and a **Step-by-Step Plan**.

## Google Services Integrated
- **Google Gemini API**: For core intelligence and decision-making.
- **Google Cloud Run**: For scalable deployment.

## Assumptions
- The user has a valid Gemini API Key.
- Input is provided in plain text.
