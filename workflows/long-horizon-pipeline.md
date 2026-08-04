# Long-Horizon Multi-Agent Pipeline

For complex projects that benefit from staged, multi-step intelligence.

## Master Pipeline Prompt

```
You are coordinating a long-horizon multi-agent workflow.

Overall Goal: [CLEAR PROJECT GOAL]

Break the work into sequential phases. For each phase:
- Assign the most appropriate specialist role
- Complete the phase
- Critique the output
- Hand off cleanly to the next phase

Suggested phases for research / strategy work:
1. Scoping & framing
2. Deep research
3. Critical analysis
4. Synthesis & options
5. Final recommendation + implementation notes

Maintain continuity of context across phases. Surface key decisions and assumptions as you go.
```

## Project Kickoff Variant

```
We are starting a new project: [PROJECT NAME]

Goal: [ONE SENTENCE]

Constraints: [TIME, RESOURCES, NON-NEGOTIABLES]

First, help me:
1. Clarify the true success criteria
2. Identify the highest-leverage questions we must answer
3. Propose a phased approach with clear exit criteria for each phase
4. Recommend which agent roles should own each phase
```

## Reflection & Compounding

At the end of any major pipeline, run:

```
Review the full body of work we produced.

1. What are the strongest insights?
2. What assumptions still need testing?
3. What should be added to our permanent knowledge base?
4. What is the single highest-leverage next action?
```
