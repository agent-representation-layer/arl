# Vision

## The Missing Layer in Agent Interoperability

Artificial Intelligence is rapidly moving toward an ecosystem of autonomous agents.

Open standards such as the **Model Context Protocol (MCP)** and the **Agent-to-Agent Protocol (A2A)** are enabling agents to interact with tools, services, and one another across organizational and technological boundaries.

These standards represent an important step toward an open, interoperable agent ecosystem.

However, they also expose a new architectural question:

> **How should a single personal agent represent the person behind it across different contexts?**

Today, this question has no common answer.

## The Problem

A truly personal AI agent should become a long-lived digital companion.

Over time it learns:

* preferences;
* goals;
* relationships;
* habits;
* knowledge;
* memories;
* and the user's evolving context.

Its greatest value comes from this continuity.

Yet continuity introduces a new challenge.

The same agent may interact with:

* employers;
* banks;
* healthcare providers;
* government services;
* online communities;
* marketplaces;
* personal contacts;
* and countless autonomous agents.

Each interaction may require a different level of identity disclosure.

Some require full attribution.

Others require only proof of authority.

Some benefit from pseudonymity.

Others should remain anonymous.

Current interoperability efforts successfully define how agents communicate.

They do not define how a single agent should represent the same human differently across these contexts while preserving continuity, privacy, and user control.

## Why Existing Approaches Fall Short

Two common approaches exist today.

The first is to use a single identity everywhere.

While this preserves continuity, it unnecessarily correlates unrelated aspects of a person's digital life.

The second is to create multiple specialized agents.

While this separates identities, it fragments memory, reasoning, preferences, and long-term context.

Neither approach fully reflects how people naturally operate.

Humans do not become different individuals when interacting with a bank, an employer, or an online community.

They present different facets of the same identity depending on context.

Personal AI agents should be capable of doing the same.

## Our Vision

We envision a future where every person is represented by **one sovereign personal agent**.

That agent maintains:

* one continuous memory;
* one evolving understanding of its owner;
* one long-term relationship;
* and one reasoning process.

At the same time, it can present different identity profiles depending on context.

The same agent may represent its owner as:

* a verified identity;
* a professional identity;
* a persistent pseudonym;
* a service-specific pseudonym;
* or an anonymous session.

The choice belongs to the user.

Not the application.

Not the service.

Not the model provider.

## Agent Representation Layer

The **Agent Representation Layer (ARL)** is proposed as an architectural layer that complements existing interoperability standards.

Its purpose is not to replace protocols such as MCP or A2A.

Instead, ARL explores how autonomous agents should represent the people behind them.

ARL seeks to standardize concepts such as:

* contextual identity;
* identity selection;
* representation policies;
* delegated authority;
* disclosure rules;
* identity negotiation;
* and contextual privacy.

In this architecture:

* **MCP** enables Agent ↔ Tool interoperability.
* **A2A** enables Agent ↔ Agent interoperability.
* **ARL** enables Agent ↔ Human Representation.

## Guiding Philosophy

ARL is built upon a simple architectural principle:

> **A person's intelligence should remain continuous. Their representation should remain contextual.**

A user should never need multiple personal agents simply to preserve privacy.

Likewise, a user should never be forced to expose the same identity across every interaction simply to preserve continuity.

The future should provide both.

## An Open Proposal

ARL is intentionally presented as an open architectural proposal rather than a finished specification.

The objective of this project is to validate whether this architectural layer is needed, define its boundaries, and collaborate with the broader community before any protocol specification is developed.

We welcome discussion, criticism, prior art, alternative approaches, and new use cases.

The goal is not to create another protocol.

The goal is to explore whether the emerging ecosystem of autonomous agents is missing a standard way for agents to represent the people they serve.
