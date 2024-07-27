# Enterprise AIOps

## Overview

Enterprise AIOps transforms traditional cloud operations from rule-driven manual processes to AI-driven automated operations. The goal of Enterprise AIOps is to improve the efficiency, performance, and reliability of cloud systems by automating routine tasks, predicting and preventing potential issues, and providing insights for proactive decision-making.

## Levels of AIOps

AIOps solutions span across multiple levels of cloud operations:
- Level-1 Service Desk
- Level-2 Incident Management
- Level-3 Problem Management
- Level-4 Site Reliability Engineering
- DevOps Engineering
- Foundational Engineering
- FinOps

## Process

1. **Data Collection and Preparation**: AIOps begins with collecting data from cloud workloads and performing Data Ops to prepare and unify the data for AI, storing it in a data lake.
2. **AI and MLOps**: Once the data is prepared, traditional AI models, large language models (LLMs), or agentic flow with retrieval-augmented generation (RAG) and external data sources are used to perform MLOps for prediction, inference, or generation depending on the use case.
3. **Event Creation**: After MLOps performs actions using AI, an event is created using an event engine with a set of rules to correlate the event to the automation.
4. **Automation Orchestration**: Once the event identifies the action, it calls the orchestrator to initiate the automation. Automation is kicked off via the service catalog, which performs the necessary changes or fixes to the workload.
5. **Dashboard and ChatOps Integration**: All AIOps processes are captured on the AIOps dashboard and integrated with ChatOps to include the operations team. The operations team can provide manual input to the AIOps system using ChatOps.


