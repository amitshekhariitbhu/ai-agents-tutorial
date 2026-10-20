<p align="center">
    <img alt="AI Agents Tutorial" src="https://github.com/amitshekhariitbhu/ai-agents-tutorial/blob/main/assets/banner.png">
</p>

# AI Agents Tutorial

**Learn AI Agents step by step, from scratch - from function calling to agent loops to multi-agent systems, orchestration, and evaluation.**

---

Prepared and maintained by the **Founder** of Outcome School: [Amit Shekhar](https://x.com/amitiitbhu)

---

**Note: This series will continue to grow as I write more blogs and create more videos on new topics. Keep learning.**

---

## AI Engineering (LLM, RAG, MCP, Agent)

Before diving into AI Agents, it's a good idea to first understand the foundations that agents are built on.

In this video, we will cover the following:

* LLM
* RAG
* MCP
* Agent
* Fine-tuning
* Quantization

Let's get started: [AI Engineering Explained: LLM, RAG, MCP, Agent, Fine-Tuning, Quantization](https://www.youtube.com/watch?v=lnfWvX66FUk)

---

## AI Agent Explained

In this blog, we will learn about the AI Agent - what it is, how it is different from a plain LLM, its five core parts, how it works end to end, the main types, and when to use one.

We will cover the following:

- The Big Picture
- What is an AI Agent
- AI Agent vs Plain LLM vs Chatbot
- The Five Core Parts
- How an AI Agent Works End to End
- A Concrete Example: Research Agent
- Types of AI Agents
- What AI Agents Can Do Today
- When to Use an AI Agent
- Common Failure Modes
- Quick Summary

Let's get started: [AI Agent Explained](https://outcomeschool.com/blog/ai-agent)

---

## How does Function Calling work in LLMs?

In this blog, we will learn about how Function Calling works in LLMs. We will see what it is, why we need it, the key insight behind it, and how it powers AI agents and assistants step by step.

We will cover the following:

- What is Function Calling
- Why We Need Function Calling
- The Key Insight: The Model Does Not Run the Function
- How Function Calling Works Step by Step
- A Concrete Example: get_weather(city)
- The Conversation Loop
- Multi-Step and Parallel Function Calling
- Relation to Structured Outputs and JSON Mode
- Real-World Use: The Backbone of AI Agents
- Quick Summary

Let's get started: [How does Function Calling work in LLMs?](https://outcomeschool.com/blog/how-does-function-calling-work-in-llms)

---

## AI Agent Loop

In this blog, we will learn about the AI Agent Loop - what it is, why an AI Agent needs it, the think-act-observe cycle that powers it, how the loop knows when to stop, and the common ways the loop fails.

We will cover the following:

- The Big Picture
- What is the AI Agent Loop
- Why an AI Agent Needs a Loop
- The Think-Act-Observe Cycle
- The Loop Step by Step
- The Loop in Real Code
- Parallel Tool Calls in One Turn
- How the Loop Knows When to Stop
- Common Loop Failures
- Quick Summary

Let's get started: [AI Agent Loop](https://outcomeschool.com/blog/ai-agent-loop)

---

## ReAct Agent

In this blog, we will learn about the ReAct Agent - what it is, how it is built, its anatomy, how it thinks and acts, and how to handle its common failure modes.

When we hear **ReAct Agent**, it sounds complex. But do not worry. If we break it down into its individual parts, every single piece is simple.

We will cover the following:

- What is a ReAct Agent
- ReAct Agent vs AI Agent
- Anatomy of a ReAct Agent
- The ReAct Prompt Template
- How a ReAct Agent Thinks and Acts
- A Full Trace Example
- Implementing a ReAct Agent
- Common Failure Modes and How to Fix Them
- Quick Summary

Let's get started: [ReAct Agent](https://outcomeschool.com/blog/react-agent)

---

## Reflection Agent

In this blog, we will learn about the Reflection Agent - what it is, how it is built, its anatomy, how it generates, critiques, and revises its own work, and how to handle its common failure modes.

We will cover the following:

- What is a Reflection Agent
- Reflection Agent vs AI Agent
- Anatomy of a Reflection Agent
- How a Reflection Agent Works
- A Full Trace Example
- Reflection Agent vs ReAct Agent
- Common Failure Modes and How to Fix Them
- Quick Summary

Let's get started: [Reflection Agent](https://outcomeschool.com/blog/reflection-agent)

---

## Plan-and-Execute Agent

In this blog, we will learn about the Plan-and-Execute Agent - what it is, its anatomy, how it plans and runs the steps, how it differs from a ReAct Agent, and how to handle its common failure modes.

We will cover the following:

- What is a Plan-and-Execute Agent
- Plan-and-Execute Agent vs AI Agent
- Anatomy of a Plan-and-Execute Agent
- How a Plan-and-Execute Agent Works
- A Full Trace Example
- Plan-and-Execute Agent vs ReAct Agent
- Common Failure Modes and How to Fix Them
- Quick Summary

Let's get started: [Plan-and-Execute Agent](https://outcomeschool.com/blog/plan-and-execute-agent)

---

## AI Agent Memory

In this blog, we will learn about AI Agent Memory - why agents need it, the memory stack, the four core operations (write, read, update, forget), how memory flows at runtime, and the common mistakes.

We will cover the following:

- The Big Picture
- Why AI Agents Need Memory
- The Memory Stack
- The Four Core Operations
- How Memory Flows at Runtime
- What to Store and What Not to Store
- Common Mistakes and How to Fix Them
- Quick Summary

Let's get started: [AI Agent Memory](https://outcomeschool.com/blog/ai-agent-memory)

---

## How does ChatGPT remember you?

In this blog, we will learn how ChatGPT remembers us across chats even though the model itself remembers nothing. We will see why LLMs forget by default, how saved memories, chat history, and Custom Instructions work, and how these memories are added to the prompt before every reply.

We will cover the following:

- Why LLMs forget by default
- The context window
- Memory within one chat
- What ChatGPT Memory is
- Saved memories
- Reference chat history
- Custom Instructions
- How memories enter the prompt
- An end-to-end example
- Viewing and deleting memories
- Temporary Chat
- Where memory helps and where it fails

Let's get started: [How does ChatGPT remember you?](https://outcomeschool.com/blog/how-does-chatgpt-remember-you)

---

## Context Engineering

In this blog, we will learn about Context Engineering - what it is, why it has become the most important skill for building reliable AI applications, how it differs from Prompt Engineering, the components that make up the context, common patterns like RAG, few-shot examples, tools, and memory, and the best practices and common mistakes to keep in mind.

We will cover the following:

- What is Context Engineering?
- The Big Picture
- Why Context Engineering matters
- Prompt Engineering vs Context Engineering
- The components of the context
- Common patterns in Context Engineering
- Common mistakes to avoid
- Best practices
- Quick Summary

Let's get started: [Context Engineering](https://outcomeschool.com/blog/context-engineering)

---

## Agentic RAG

In this blog, we will learn about Agentic RAG - what it is, why standard RAG falls short, the agentic RAG loop, the three building blocks, the common patterns, when to use it, and the limitations to keep in mind.

A hard question often needs more than one search. Some of those searches need different sources. Some depend on what the previous search found. Standard RAG cannot do any of this. Agentic RAG can.

**Agentic RAG = Agentic + RAG**

We will cover the following in this blog:

- The Big Picture
- A Quick Recap of RAG
- A Quick Recap of AI Agent
- Why Standard RAG Falls Short
- What is Agentic RAG
- The Agentic RAG Loop
- The Three Building Blocks
- A Walkthrough with a Real Example
- Common Patterns of Agentic RAG
- Standard RAG vs Agentic RAG
- When to Use Agentic RAG
- Limitations of Agentic RAG
- Quick Summary

Let's get started: [Agentic RAG](https://outcomeschool.com/blog/agentic-rag)

---

## GraphRAG

In this blog, we will learn about GraphRAG and how it improves retrieval by using a knowledge graph along with [vector search](https://outcomeschool.com/blog/how-does-a-vector-database-work).

We will cover the following:

- What is GraphRAG?
- Why normal RAG is not enough
- The big picture of GraphRAG
- How GraphRAG builds the knowledge graph
- How GraphRAG answers a question
- Local search vs Global search
- When to use GraphRAG
- Trade-offs of GraphRAG
- Quick Summary

Let's get started: [GraphRAG](https://outcomeschool.com/blog/graphrag)

---

## Multi-Agent Systems

In this blog, we will learn about Multi-Agent Systems - what they are, the three pillars that hold them together, the common agent roles, how agents communicate and coordinate, the trade-offs, and when to use them.

We will cover the following:

- The Big Picture
- What is a Multi-Agent System
- The Three Pillars
- Common Agent Roles
- How Agents Communicate
- How Agents Coordinate
- Multi-Agent vs Single Agent - The Trade-offs
- Common Mistakes
- When to Use a Multi-Agent System
- Quick Summary

Let's get started: [Multi-Agent Systems](https://outcomeschool.com/blog/multi-agent-systems)

---

## AI SubAgents

In this blog, we will learn about AI SubAgents. We will understand what they are, why we need them, how they work, and how to use them to build AI systems that can handle big and complex tasks.

We will cover the following:

- What is an AI Agent?
- What are AI SubAgents?
- Why do we need SubAgents?
- How do SubAgents work?
- Example use case
- Benefits of using SubAgents
- Challenges with SubAgents
- Best practices

Let's get started: [AI SubAgents](https://outcomeschool.com/blog/ai-subagents)

---

## What is MCP (Model Context Protocol)?

In this blog, we will learn about MCP (Model Context Protocol). We will also see the problem it solves, the pieces it is made of, how a request travels from the AI model all the way to a tool and back, and what we must be careful about while using it.

We will cover the following:

- The problem before MCP
- What is MCP?
- MCP = Model + Context + Protocol
- The USB-C analogy
- How it is different from a normal API
- The three parts of MCP
- How it all works step by step
- How the connection happens
- A real example
- Importance of MCP
- Things we must be careful about
- Summary

Let's get started: [What is MCP (Model Context Protocol)?](https://outcomeschool.com/blog/what-is-mcp-model-context-protocol)

---

## AI Orchestration

In this blog, we will learn about AI Orchestration. We will understand what it is, why we need it, how it is different from AI Agents, and the common patterns we use to coordinate multiple LLMs, tools, and steps together to build real AI products.

We will cover the following:

- What is AI Orchestration?
- Why do we need AI Orchestration?
- AI Orchestration vs AI Agents
- Components of AI Orchestration
- How AI Orchestration works
- Patterns of AI Orchestration
- Sequential Pattern
- Parallel Pattern
- Conditional Pattern
- Loop Pattern
- Orchestrator-Worker Pattern
- Tools for AI Orchestration
- Challenges in AI Orchestration
- Best Practices

Let's get started: [AI Orchestration](https://outcomeschool.com/blog/ai-orchestration)

---

## How AI Agents Communicate

In this blog, we will learn about how AI agents communicate. We will understand why agents need to communicate, the main ways they talk to each other, the message format, and the protocols that make agents work together to finish complex tasks.

We will cover the following:

- What is agent communication?
- Why do agents need to communicate?
- What agents need in order to communicate
- How a message flows between agents
- The ways AI agents communicate
- Direct Communication
- Centralized Communication
- Broadcast Communication
- Shared Memory Communication
- What a message looks like
- The rules agents follow to talk
- Challenges when agents communicate
- Best Practices

Let's get started: [How AI Agents Communicate](https://outcomeschool.com/blog/how-ai-agents-communicate)

---

## How do Computer-Use Agents work?

In this blog, we will learn about how computer-use agents work.

We will cover the following:

- What is a computer-use agent?
- Why do we need a computer-use agent?
- The perceive, think, act loop
- How does the agent see the screen?
- How does the agent decide what to do?
- How does the agent take actions?
- A step-by-step walkthrough with an example
- The system prompt and tools
- Safety and guardrails
- Limitations of computer-use agents
- Conclusion

Let's get started: [How do Computer-Use Agents work?](https://outcomeschool.com/blog/how-do-computer-use-agents-work)

---

## How do Browser Agents work?

In this blog, we will learn about how browser agents work. We will also see how a browser agent sees a web page, how it takes actions, and how the observe-think-act loop completes a task from start to finish.

We will cover the following:

- What is an AI agent?
- Why do we need Browser Agents?
- What is a Browser Agent?
- The parts of a Browser Agent
- How does a Browser Agent see a web page?
- How does a Browser Agent take actions?
- The observe-think-act loop
- A complete example: ordering a book
- A simple code example
- Screenshots vs page structure
- Problems and how they are handled
- Where it works well and where it fails

Let's get started: [How do Browser Agents work?](https://outcomeschool.com/blog/how-do-browser-agents-work)

---

## How does LangChain work?

In this blog, we will learn about how LangChain works. We will also see why we need it, what chains, prompts, memory, and output parsers are, how retrieval and agents fit in, and how the full flow works together in the real world.

We will cover the following:

- What is LangChain?
- Why do we need LangChain?
- The core idea behind LangChain
- LLM and Prompt Template
- What is a Chain?
- Output Parser
- Memory
- Retrieval and RAG
- Tools and Agents
- A complete flow of how LangChain works

Let's get started: [How does LangChain work?](https://outcomeschool.com/blog/how-does-langchain-work)

---

## How does LangGraph work?

In this blog, we will learn about how LangGraph works. We will also see why we need it, what graphs, state, nodes, and edges are, how tools work and who actually calls them, how memory and human-in-the-loop fit in through a complete example, and when to use it in the real world.

We will cover the following:

- What is LangGraph?
- Why do we need LangGraph?
- What is a Graph in LangGraph?
- What is State in LangGraph?
- Nodes and Edges
- Conditional Edges
- A complete example
- Tools and who calls them
- Memory and persistence
- Human-in-the-loop
- When to use LangGraph

Let's get started: [How does LangGraph work?](https://outcomeschool.com/blog/how-does-langgraph-work)

---

## Harness Engineering in AI

In this blog, we will learn about Harness Engineering in AI. We will understand what a harness is, why we need it, and how it is used in AI Agents and evaluation systems.

We will cover the following:

- What is a Harness in AI?
- Why do we need Harness Engineering?
- Components of an AI Harness
- Harness Engineering for AI Agents
- Harness Engineering for Evaluation
- Best Practices in Harness Engineering
- Putting It All Together

Let's get started: [Harness Engineering in AI](https://outcomeschool.com/blog/harness-engineering-in-ai)

---

## AI Agent Observability

In this blog, we will learn about AI Agent Observability. We will also see why we need it, how it is different from normal software monitoring, what we must observe inside an agent, the key concepts like traces and spans, the metrics we must track, the tools we can use, and the best practices to follow.

We will cover the following:

- What is an AI Agent?
- What is Observability?
- What is AI Agent Observability?
- Why do we need AI Agent Observability?
- How is AI Agent Observability different from traditional Observability?
- The Three Pillars of Observability
- Traces and Spans
- What should we observe inside an AI Agent?
- Key Metrics for AI Agent Observability
- How AI Agent Observability works
- Tools and Frameworks for AI Agent Observability
- Observability vs Evaluation
- Challenges in AI Agent Observability
- Best Practices

Let's get started: [AI Agent Observability](https://outcomeschool.com/blog/ai-agent-observability)

---

## AI Agent Evaluation

In this blog, we will learn about AI Agent Evaluation. We will also see why it is different from LLM Evaluation, the types of evaluation we can do, the key metrics we must track, the methods we can use, and the best practices to follow.

We will cover the following:

- What is an AI Agent?
- What is AI Agent Evaluation?
- Why do we need AI Agent Evaluation?
- How is AI Agent Evaluation different from LLM Evaluation?
- Types of AI Agent Evaluation
- Outcome Evaluation
- Trajectory Evaluation
- Tool Use Evaluation
- Planning Evaluation
- Key Metrics for AI Agents
- Agent Benchmarks
- Methods to Evaluate AI Agents
- Frameworks and Tools for AI Agent Evaluation
- Challenges in AI Agent Evaluation
- Best Practices

Let's get started: [AI Agent Evaluation](https://outcomeschool.com/blog/ai-agent-evaluation)

---

## Decoding Sakana Fugu Technical Report

In this blog, we are going to learn about Sakana Fugu, a family of AI models that work like a conductor for a team of other AI models.

We will cover the following:

- What is Sakana Fugu?
- Why Fugu was needed
- The big picture: what Fugu does
- Collective Intelligence
- The two Fugus - Fugu and Fugu-Ultra
- How Fugu picks the right model - the lightweight selection head
- Teaching Fugu who is best - supervised fine-tuning
- Polishing Fugu on real tasks - evolutionary strategies
- How Fugu-Ultra conducts an orchestra - the Conductor
- Teaching Fugu-Ultra to conduct - GRPO
- Stopping the agents from copying each other
- How well does Fugu perform?
- The clever strategies Fugu discovered on its own
- Quick Summary

Let's get started: [Decoding Sakana Fugu Technical Report](https://outcomeschool.com/blog/decoding-sakana-fugu)

---

## What are Agent Skills?

In this blog, we will learn about Agent Skills. We will also see why we need them, what is inside a Skill, how the description makes an agent pick up the right Skill by itself, how progressive disclosure keeps the context window free, how Agent Skills differ from MCP, and how we can create our own Skill.

We will cover the following:

- The problem before Agent Skills
- What are Agent Skills?
- What is inside a Skill?
- The description is the trigger
- Progressive disclosure, the main idea
- A Skill can carry real code
- Where Skills live
- How do we create our own Skill?
- Agent Skills vs MCP
- A real example
- Importance of Agent Skills
- Things we must be careful about
- Summary

Let's get started: [What are Agent Skills?](https://outcomeschool.com/blog/what-are-agent-skills)

---

## Design a Real-Time Voice AI Agent

In this blog, we will learn about how to design a Real-Time Voice AI Agent, a system that listens to a person speaking, understands what they said, thinks about it, takes actions if needed, and talks back in a natural human-like voice, all within a fraction of a second. We will also see why voice is much harder than a text chatbot, the two big ways to build it (the cascaded pipeline of Speech-to-Text, LLM, and Text-to-Speech versus the end-to-end Speech-to-Speech model), how the agent knows when the user has stopped talking, how we handle interruptions, how tools and memory fit in, how we scale it to thousands of calls, the edge cases that break a voice agent in production, the pros and cons of every approach, and when to use which one.

We will cover the following:

- What is a Voice AI Agent?
- Why is Real-Time Voice hard?
- Requirements
- Back-of-the-envelope estimation
- High-Level Architecture
- Component 1: Audio Transport
- Component 2: Voice Activity Detection and Turn Detection
- Component 3: Speech-to-Text (STT)
- Component 4: The Brain - LLM with Tools
- Component 5: Text-to-Speech (TTS)
- Approach 1: Cascaded Pipeline (STT -> LLM -> TTS)
- Approach 2: Speech-to-Speech Model
- Approach 3: Hybrid Approach
- Cascaded vs Speech-to-Speech: Comparison
- Latency Budget: Where every millisecond goes
- Handling Interruptions (Barge-in)
- Tool Calling in a Voice Agent
- Memory and Context
- Telephony: Connecting to real phone calls
- Scaling the system
- Edge Cases and how to handle them
- Observability and Evaluation
- Safety, Security, and Privacy
- Cost
- How to present this design in an interview

Let's get started: [Design a Real-Time Voice AI Agent](https://outcomeschool.com/blog/design-a-real-time-voice-ai-agent)

---

## What is turn-taking in a voice AI agent?

In this blog, we will learn about turn-taking in a voice AI agent, how the agent decides when the user has finished speaking, when it is its turn to talk, and what to do when the user starts speaking again while the agent is talking. We will also see why silence alone is not enough, how semantic turn detection reads the meaning of the words, how barge-in and backchannels are handled, and how half-duplex agents differ from full-duplex agents.

We will cover the following:

- What is turn-taking?
- How humans take turns
- How a voice AI agent works
- Why turn-taking is hard for a machine
- The two jobs of turn-taking
- Approach 1: Wait for silence
- Approach 2: Understand the meaning
- Handling interruptions
- Not every sound is a new turn
- Half-duplex vs full-duplex agents
- A complete walkthrough

Let's get started: [What is turn-taking in a voice AI agent?](https://outcomeschool.com/blog/what-is-turn-taking-in-a-voice-ai-agent)

---

## What is barge-in in a voice AI agent?

In this blog, we will learn about barge-in in a voice AI agent, what happens when the user starts speaking while the agent is still talking, and how the agent stops so it can listen. We will also see why the agent can hear its own voice and how echo cancellation fixes it, how the agent tells a real interruption apart from "uh-huh", a cough, or background noise, what it does after a barge-in, and why it must remember only the part of the reply the user actually heard.

We will cover the following:

- What is barge-in?
- Where the word barge-in comes from
- How a voice AI agent speaks and listens
- Problem 1: The agent hears itself
- Problem 2: Not every sound is an interruption
- How the agent detects barge-in
- What the agent does after barge-in
- Remembering what the user actually heard
- Why barge-in must be fast
- A complete walkthrough

Let's get started: [What is barge-in in a voice AI agent?](https://outcomeschool.com/blog/what-is-barge-in-in-a-voice-ai-agent)

---

## Cascaded vs Speech-to-Speech: How to choose the right voice agent architecture?

In this blog, we will learn about Cascaded vs Speech-to-Speech and how to choose the right voice agent architecture. We will also see how a cascaded voice agent works, how a speech-to-speech voice agent works, how the two differ in delay, tone, control, and cost, what a half-cascade in the middle looks like, and when to use which one.

We will cover the following:

- What is a voice agent architecture?
- What is a cascaded voice agent?
- Strengths and weaknesses of a cascaded voice agent
- What is a speech-to-speech voice agent?
- Strengths and weaknesses of a speech-to-speech voice agent
- The middle path: Half-Cascade
- Differences between Cascaded, Half-Cascade, and Speech-to-Speech
- How to choose the right voice agent architecture

Let's get started: [Cascaded vs Speech-to-Speech: How to choose the right voice agent architecture?](https://outcomeschool.com/blog/cascaded-vs-speech-to-speech)

---

## How do you build a latency budget for a voice AI agent?

In this blog, we will learn about how to build a latency budget for a voice AI agent, a plan that splits the total waiting time for a reply into smaller pieces, one for each step of the agent. We will also see why a voice AI agent needs one, how to pick the total target and split it across every stage, how to measure the real numbers and cut the biggest delays first, how streaming and tool calls change the budget, and what trade-off we must accept.

We will cover the following:

- What is a latency budget?
- Why does a voice AI agent need a latency budget?
- Step 1: Pick the total target
- Step 2: List every stage of the pipeline
- Step 3: Give each stage its share of the time
- Step 4: Measure the real numbers
- Step 5: Cut the biggest delay first
- How streaming changes the budget
- How tool calls fit into the budget
- The trade-off we must accept

Let's get started: [How do you build a latency budget for a voice AI agent?](https://outcomeschool.com/blog/voice-agent-latency-budget)

---

## How does the voice-to-voice latency of a voice agent get measured?

In this blog, we will learn about how the voice-to-voice latency of a voice agent gets measured. We will also see where the time goes inside a voice agent, why the server logs give the wrong answer, how a two-channel recording gives the right answer, how we automate it over many calls, why we look at percentiles instead of the average, and where it works well and where it fails.

We will cover the following:

- What is voice-to-voice latency?
- Why is this latency important?
- Where does the time go?
- Approach 1: Using the logs on the server
- Approach 2: Adding timestamps at every step
- Approach 3: Recording the call on one timeline
- Automating the measurement over many calls
- Why do we look at percentiles and not the average?
- Where it works well and where it fails

Let's get started: [How does the voice-to-voice latency of a voice agent get measured?](https://outcomeschool.com/blog/voice-to-voice-latency)

---

## Why does the time-to-first-audio matter more than total response time?

In this blog, we will learn about why the time-to-first-audio matters more than total response time. We will also see what each of these two times measures, how people experience silence in a conversation, how streaming lets an agent start speaking before the full reply is ready, which steps decide the time-to-first-audio, and when the total response time still matters.

We will cover the following:

- What is time-to-first-audio?
- What is total response time?
- How do people experience waiting on a voice call?
- Why does the time-to-first-audio matter more?
- An example with two voice agents
- How does streaming bring the first audio early?
- What decides the time-to-first-audio?
- The rest of the reply must keep up
- When does the total response time still matter?

Let's get started: [Why does the time-to-first-audio matter more than total response time?](https://outcomeschool.com/blog/time-to-first-audio)

---

## More blogs and videos coming soon!

### License
```
   Copyright (C) 2026 Outcome School

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
