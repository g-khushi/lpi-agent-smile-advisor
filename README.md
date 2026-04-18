# LPI Agent — SMILE Advisor

## Overview
This agent connects to the LPI sandbox and uses multiple tools along with a local LLM (Ollama) to generate explainable answers.

## Tools Used

1. smile_overview  
Returns SMILE methodology overview.

2. query_knowledge  
Returns domain-specific knowledge.

3. get_case_studies  
Returns real-world case studies.

## Example

Input:
"What are digital twins in healthcare?"

Output:
- SMILE overview
- Knowledge results
- Case studies
- Final LLM-generated answer

## How to Run

npm run build  
python agent.py "your query"
