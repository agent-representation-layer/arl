# Principles

The Agent Representation Layer (ARL) is guided by two foundational principles.

These principles are intended to shape every future specification, protocol extension, and implementation decision.

---

# Principle 1 — Identity Sovereignty

> **A person should be able to interact with the digital world through a single sovereign personal agent without being constrained to a single external identity.**

A personal agent represents one human principal.

However, representation should be contextual.

Different interactions require different levels of identity disclosure, attribution, and privacy.

The user—not the service, AI provider, application, or protocol—must remain in control of:

* which identity profile is presented;
* when identities may be reused;
* what attributes are disclosed;
* when explicit confirmation is required;
* and how identity changes across contexts.

Identity verification is a capability.

It is not a universal requirement.

### Design Consequences

ARL should enable:

* attributable identities;
* pseudonymous identities;
* anonymous identities;
* contextual identity selection;
* identity negotiation;
* minimal disclosure;
* and user-defined representation policies.

The protocol should never assume that one identity fits every interaction.

---

# Principle 2 — Responsible Autonomy

> **An agent's authority derives from explicit delegation, enforceable policies, and verifiable evidence—not from implicit trust in the AI model itself.**

An autonomous agent represents a person.

Representation therefore carries responsibility.

Every action performed by an agent should occur within explicitly delegated authority and respect the user's policies regarding identity, privacy, and disclosure.

Autonomy is not the absence of control.

It is the ability to act safely within well-defined boundaries.

### Design Consequences

ARL should support:

* delegated authority;
* representation policies;
* approval requirements;
* contextual constraints;
* auditable decisions;
* verifiable representation;
* and accountability without unnecessary surveillance.

Trust should emerge from transparent governance rather than blind confidence in model behavior.

---

# Relationship Between the Principles

These principles are complementary.

Identity Sovereignty answers:

> **How should an agent represent its owner?**

Responsible Autonomy answers:

> **Under what authority should the agent act?**

A personal agent requires both.

An agent capable of changing identities without policy or delegated authority is unsafe.

An agent with strong authorization but no contextual identity model unnecessarily exposes its owner.

ARL seeks to provide both privacy and accountability.

---

# Design Philosophy

These principles can be summarized by two architectural statements.

> **The intelligence remains continuous.**

A personal agent should preserve long-term memory, reasoning, preferences, and context regardless of the identities it presents.

> **The representation remains contextual.**

The external identity used by the agent should adapt to the recipient, purpose, sensitivity, and policies defined by its owner.

Neither continuity nor privacy should require sacrificing the other.

---

# Looking Ahead

Every future component of ARL should be evaluated against these principles.

If a proposal reduces user sovereignty, increases unnecessary identity disclosure, or weakens accountable autonomy, it should be reconsidered.

These principles are intended to remain stable even as the protocol evolves.
