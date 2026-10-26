# AI Voice Calling Workflow

An AI-powered voice workflow designed to prepare customer context, conduct personalized conversations, evaluate call outcomes, and support relevant follow-up actions.

## Overview

This project documents a multi-stage voice automation workflow that combines workflow orchestration, Large Language Models (LLMs), external service integrations, and post-call evaluation logic.

The workflow processes available customer information, prepares relevant context for an AI voice agent, evaluates the conversation outcome, and supports follow-up activities based on the results.
<img width="4000" height="2050" alt="spinny convoflow_agent_workflow_updated" src="https://github.com/user-attachments/assets/862c1755-21e6-4bbf-96f4-e246dc3e6c5c" />




The workflow is organized into three main stages.

### 1. Pre-Call Preparation

- Retrieve relevant customer information and interaction history.
- Normalize customer names and prepare contextual information.
- Process customer preferences and previously discussed vehicle options.
- Apply conditional logic to determine the appropriate calling context.
- Retrieve relevant location information and prepare inputs for the voice agent.

### 2. Live Customer Conversation

- Trigger an outbound voice interaction.
- Provide the AI agent with relevant customer and conversation context.
- Support natural conversations, customer queries, and vehicle discussions.
- Assist with test-drive scheduling and other relevant actions.
- Capture conversation transcripts and call execution information.

### 3. Post-Call Processing

- Determine whether the call was connected successfully.
- Evaluate the transcript using an LLM-based evaluation step.
- Extract relevant conversation outcomes and customer intent.
- Process booking information and other tool-generated results.
- Update workflow variables and prepare appropriate follow-up actions.
- Support customer follow-ups, messaging actions, and failure handling.

## Key Components

| Component | Purpose |
|---|---|
| Workflow orchestration | Coordinates the sequence of processing steps and conditional branches. |
| Large Language Models (LLMs) | Support name normalization, conversation evaluation, and structured information extraction. |
| External service integrations | Retrieve customer context and support connected actions. |
| AI voice agent | Conducts customer conversations and supports relevant actions. |
| Evaluation logic | Interprets call outcomes, customer intent, and conversation results. |
| Data transformation | Prepares structured information for subsequent workflow steps. |
| Error handling | Supports retries and defined failure paths for selected operations. |

## Technology Stack

- **AI/LLMs:** OpenAI models
- **Workflow Automation:** Node-based workflow orchestration
- **Programming Concepts:** Conditional logic, variable transformations, and data processing
- **Integrations:** HTTP-based service integrations
- **Data Formats:** JSON and structured outputs
- **Conversational AI:** AI voice agents and transcript processing
- **Evaluation:** Prompt-based evaluation and outcome classification

## My Contributions — AI Intern

- Worked on workflow nodes and the overall execution flow.
- Developed and refined prompts for AI-based processing and evaluation.
- Contributed to agent prompts and conversation design.
- Worked on external service integrations and data flow between workflow components.
- Contributed to evaluation logic for interpreting call transcripts and outcomes.
- Supported call auditing, conversation quality analysis, and testing.
- Worked on identifying workflow issues and improving processing reliability.

## Key Learnings

- Designing multi-stage AI workflows.
- Integrating LLMs into practical automation use cases.
- Structuring prompts for consistent model outputs.
- Working with conditional branches and structured data.
- Understanding voice-agent orchestration and conversation evaluation.
- Handling integration failures and validating workflow outcomes.

## Project Scope

This repository provides a high-level technical overview and visual documentation of the workflow. It is intended to demonstrate workflow design, AI integration concepts, and hands-on learning.

Internal credentials, private customer information, proprietary prompts, and confidential configuration details are intentionally excluded.

---

**Focus Areas:** AI Workflows · Generative AI · LLM Evaluation · Conversational AI · Workflow Automation · API Integrations
