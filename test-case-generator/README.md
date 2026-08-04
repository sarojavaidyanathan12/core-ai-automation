# Test Case Generator

## Overview

The Test Case Generator is an AI-powered solution that automates the creation of test cases from requirements.

The solution allows users to provide a Jira Story ID, retrieve the associated acceptance criteria, generate structured test cases using AI through the Test Case Generator Agent, obtain approval from a QA Tester, and create the approved test cases directly in TestRail.

The goal is to improve testing efficiency, consistency, quality, and traceability from requirements through to test execution.

## End-to-End Process

1. User provides a Jira Story ID.
2. Acceptance criteria are retrieved from Jira.
3. The Test Case Generator Agent generates structured test cases using AI.
4. Generated test cases are presented to the QA Tester for review and approval.
5. Approved test cases are passed to the workflow.
6. The workflow creates the approved test cases in TestRail.
7. Test cases are available for execution and maintenance within TestRail.

## Components

### Test Case Generator Agent

The Test Case Generator Agent is responsible for:

- Accepting Jira Story IDs
- Retrieving and processing acceptance criteria
- Generating structured test cases using AI
- Presenting generated test cases for QA review
- Managing the approval process
- Passing approved test cases to the automation workflow

### Flow

The Flow is responsible for:

- Processing approved test cases
- Converting test cases into the required TestRail format
- Creating test cases in TestRail
- Managing workflow integration between systems

## Current Capabilities

- Generate test cases from Jira requirements
- Generate structured test cases using AI
- Support QA review and approval
- Create approved test cases in TestRail
- Support multiple test scenarios from a single requirement

## Status

Proof of Concept (POC) currently under development.
