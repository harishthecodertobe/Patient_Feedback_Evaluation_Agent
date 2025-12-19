# Patient_Feedback_Evaluation_Agent
Context-grounded Agentic AI system for evaluating patient feedback by analyzing sentiment, healthcare context, and user intent beyond basic NLP classification.
## Problem Statement
Design an AI agent that evaluates brief patient feedback after clinic visits.
The agent must go beyond simple sentiment analysis and identify healthcare
context and patient intent.

## Approach
A context-grounded agent was designed using:
- Healthcare domain knowledge
- Rule-based interpretation
- Explainable classification logic

The agent retrieves domain context from an indexed knowledge base before
performing sentiment and intent analysis.

## Context Grounding
Healthcare context and interpretation rules are stored in structured documents
and used during analysis to avoid sentiment-only misclassification.

Context includes:
- Clinical care quality
- Appointment and waiting time management
- Administrative staff behavior
- Communication-related concerns

## Agentic AI Components
- **System Prompt**: Defines agent role and reasoning constraints
- **User Prompt**: Patient feedback input
- **Context**: Healthcare domain knowledge
- **Tools**: Not required (analysis-focused task)

## Example
**Input:**
"The doctor was good, but the waiting time was too long."

**Output:**
- Sentiment: Mixed
- Context: Clinical Care Quality, Appointment Management
- Classification: Service-related concern with positive clinical experience
  ## Agent Configuration (.uis file)

The `.uis` file represents the visual configuration of the agent created using
a platform-specific Agentic AI interface.

It includes:
- Context attachment (Feedback_Index)
- Classification prompt logic
- Execution flow

This file is included for reference; the agent’s reasoning and context grounding
are documented separately.


## Notes
- This project focuses on analysis and reasoning.
- RPA is intentionally not used, as automation is outside the scope of Q2.
