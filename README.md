1. Overview
The AI-Based Grievance Redressal Analyser is a GenAI-driven system built to assist senior police officers in evaluating the quality and completeness of grievance redressal processes. The system improves accuracy, consistency, and efficiency by automating the extraction of claims from complaints, providing tailored evidence checklists, scoring responses, and recommending petition statuses.

2. Goals & Objectives
Identify low-quality grievance closures through automated analysis.

Extract discrete claims from natural language complaints using LLMs.

Provide tailored evidence checklists for each extracted claim.

Enable quality assessment of Investigation Officer (IO) responses.

Assist senior officers in approving or escalating petition closures.

Improve the consistency, transparency, and speed of the redressal process.

Restore public trust by enabling fair and data-driven grievance handling.

3. Scope of the Solution
3.1 Core Modules / AI Agents
Claim Extraction Agent

Extracts discrete, actionable claims from unstructured text complaints.

Maps them to one of five predefined claim categories for the prototype:

Delay in investigation

Improper behavior

Missing evidence

Faulty FIR content

Lack of follow-up

Checklist Generator Agent

Generates evidence checklist for each claim type.

Ensures IOs gather relevant materials and documents during investigation.

Response Quality Scorer Agent

Evaluates IO’s responses against extracted claims and the evidence checklist.

Uses rubric-based scoring: Poor, Inadequate, Adequate, Excellent.

Petition Status Evaluator Agent

Suggests final petition status: Closed, Reinvestigation Required, or Escalate to Senior.

Supports override and manual input by senior officers.

3.2 Interfaces
Investigation Officer (IO) Petition Screen

View extracted claims and checklists.

Upload evidence and input responses.

Track quality score and system suggestions.

Senior Officer Dashboard

View all petitions with summarized statuses.

Drill into claims, evidence, and IO responses.

Accept, edit, or reject system recommendations.


9. Dependencies
GenAI models for NLP (claim extraction, summarization, scoring)

Secure data storage and access control for sensitive complaints

Backend support for task management and audit logging

