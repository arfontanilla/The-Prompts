# Problem Template Matching Task

## Objective
Compare each question in a **worksheet** (reference) against a Problem Template (PT) PDF on **STATE TOPIC TILE** to identify matching templates based on specific criteria.

## Matching Criteria
A valid match must meet all of the following:
- **Same concept** and **level of difficulty**.
- **Same number of given values** (e.g., if the worksheet question has 3 values, the PT must too).
- **Same problem-solving process** (e.g., multi-step, contextual, or fluency-based).
- **Contextual alignment**: 
  - If the worksheet question has a real-world context, the PT must also have one.
  - **No matches** between contextual and non-contextual problems.

## Output Format
Present results in a table with the following columns:

| Question Number | PT#       | Justification                                                                 |
|-----------------|-----------|-------------------------------------------------------------------------------|
| [Worksheet #]   | [PT ID]   | Explanation of alignment (or "no match" if none fits).                        |

### Notes:
- **Worksheet is the reference** — gaps mean no PT fits, not vice versa.
- **Contexts can differ** (e.g., money vs. measurements) if structure/complexity matches.
- **Example**: 
  - Worksheet Q19 ↔ PT 62906: "Both involve 2-step decimal multiplication with price calculations."
- If no match:  
  ```no match (reason: PTs lack contextual problems with 4 given values)```.

## Instructions
1. Confirm receipt of the worksheet and PT PDF.  
2. Clarify ambiguities before proceeding.  
3. Generate the table strictly adhering to the criteria.  
