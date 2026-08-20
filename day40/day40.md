# Day 40: AI Assistant Builder

## Overview

For Day 40 of the challenge, I built an AI Assistant using Claude's AI Assistant Builder workflow.

The goal of this task was to understand how an AI assistant can be designed using a structured prompt, customized through an interview process, generated as a complete HTML application, tested, and documented.

## What I Learned

During this task, I learned how to:

* Design an AI assistant using a structured prompt.
* Use Claude to generate a complete HTML application.
* Configure an AI assistant through an interactive interview.
* Define an assistant's behavior using a system prompt.
* Test an AI assistant before deployment.
* Explore the documentation associated with an AI-generated application.
* Publish Claude artifacts directly inside Claude.
* Understand the difference between running an artifact inside Claude and deploying the HTML independently.
* Organize project files and screenshots in a GitHub repository.

## Workflow

### 1. Read the Resources

I first read the provided resources to understand the requirements and expected workflow for the AI Assistant Builder.

### 2. Watched the Solution Video

I watched the solution video to understand the implementation process and the expected final result.

### 3. Opened Claude

I opened Claude and started the assistant-building process.

### 4. Set Effort Level

I set Claude's effort level to **Low**, as required by the challenge.

### 5. Started a New Conversation

I created a new conversation so that the assistant-building process had a clean context.

### 6. Pasted the AI Assistant Builder Prompt

I pasted the provided AI Assistant Builder prompt into Claude.

The prompt guided Claude through the process of designing the assistant and generating the application.

### 7. Completed the Interview

Claude asked a series of questions to determine how the assistant should be designed.

I answered the questions using the available MCQ/quiz choices rather than providing free-form responses.

### 8. Generated the HTML Application

After completing the interview, Claude generated the complete HTML application for the AI assistant.

The generated application included the interface and functionality required by the builder prompt.

### 9. Published the Claude Artifact

I preferred publishing the generated artifact through Claude's artifact interface.

This allows the assistant to run within Claude's environment without manually adding an Anthropic API key to the application.

### 10. API Key Understanding

I also learned an important deployment difference.

When the artifact runs inside Claude, the Claude environment handles the API interaction.

However, if the generated HTML is downloaded and opened directly in a browser or deployed on an external website, live Claude API requests require a valid Anthropic API key.

A real API key should never be hardcoded into publicly accessible frontend code.

### 11. Tested the Assistant

I tested the generated assistant to verify that:

* The interface works correctly.
* User interactions work.
* The assistant produces responses.
* The assistant follows its intended behavior.
* The generated application works as expected.

### 12. Reviewed the System Prompt

I reviewed the generated system prompt to understand how the assistant's behavior was defined.

The system prompt controls important aspects such as:

* Assistant role
* Instructions
* Response behavior
* User interaction
* Restrictions
* Expected output

### 13. Explored Documentation

I explored the documentation panel to understand the generated application's structure and supporting information.

### 14. Captured Screenshots

I took screenshots of the important parts of the project, including:

* Assistant interface
* Interview process
* Generated application
* System prompt
* Documentation panel

```

## Key Learnings

### 1. Prompt Design Matters

A well-structured prompt can guide an AI model through a complete application-building workflow.

### 2. System Prompts Define Behavior

The system prompt is an important part of an AI assistant because it defines its role, instructions, behavior, and limitations.

### 3. Artifacts Simplify Prototyping

Claude artifacts provide a convenient way to generate and run interactive applications without manually setting up a complete development environment.

### 4. Deployment Changes API Requirements

An application running inside Claude's artifact environment is different from an HTML application deployed independently.

When deploying independently, API authentication and secure backend handling become important.

### 5. Testing Is Essential

Generating an application is only one part of the process. Testing the assistant helps identify UI issues, incorrect behavior, and implementation problems before submission.


## Conclusion

Day 40 helped me understand the complete workflow of creating an AI assistant with Claude—from designing the assistant with a structured prompt and completing an interview to generating, testing, documenting, and publishing the final application.

It also helped me understand the difference between running an AI application inside a hosted AI environment and deploying the application independently with API authentication.
