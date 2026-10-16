# Glossary

## Index

- [Programs](#programs)
  - [Agent Ready award](#agent-ready-award)
  - [Agent Solutions Hub](#agent-solutions-hub)
  - [MACH certification](#mach-certification)
- [Organizations and solutions](#organizations-and-solutions)
  - [agentic capability claim](#agentic-capability-claim)
  - [agentic solution](#agentic-solution)
  - [membership category](#membership-category)
  - [shared responsibility model](#shared-responsibility-model)
- [Agent stack](#agent-stack)
  - [agent](#agent)
  - [agent platform](#agent-platform)
  - [agent runtime](#agent-runtime)
  - [model](#model)
- [Capabilities and controls](#capabilities-and-controls)
  - [agent identity](#agent-identity)
  - [approval threshold](#approval-threshold)
  - [audit trail](#audit-trail)
  - [authority boundary](#authority-boundary)
  - [autonomy](#autonomy)
  - [deterministic guardrail](#deterministic-guardrail)
  - [human in the loop](#human-in-the-loop)
  - [human on the loop](#human-on-the-loop)
  - [kill switch](#kill-switch)
- [Evidence and assessment](#evidence-and-assessment)
  - [assessment instrument](#assessment-instrument)
  - [claim](#claim)
  - [evidence](#evidence)
  - [self-declared](#self-declared)
  - [verified](#verified)
- [Standards and frameworks](#standards-and-frameworks)
  - [Agent Governance and Assurance Framework (AGAF)](#agent-governance-and-assurance-framework-agaf)
  - [AIUC-1](#aiuc-1)
  - [CSA Agentic Profile](#csa-agentic-profile)
  - [ISO/IEC 42001](#isoiec-42001)
  - [NIST AI RMF](#nist-ai-rmf)

## Programs

### Agent Ready award

An annual MACH Alliance award for members that do more than certification requires to help end users deploy agentic solutions.

### Agent Solutions Hub

The MACH Alliance directory where end users find and compare agentic solutions from member organizations.

### MACH certification

The MACH Alliance's assessment that a member organization and the claims it makes can be relied on.

## Organizations and solutions

### agentic capability claim

A member's statement that it offers an agentic solution.

### agentic solution

The product, product capability, composed system or delivered implementation that an end user adopts.

### membership category

The type of membership a member organization holds. The categories are independent software vendor, system integrator, and enabler and infrastructure provider.

### shared responsibility model

How responsibility for an agentic solution is split among the parties that supply its parts, such as the platform, the product, the model, the implementation and the customer's configuration.

## Agent stack

### agent

A system where an AI model evaluates context and makes decisions that shape what the system does. A model generating or transforming content inside a flow somebody else authored sits below that line and is not an agent.

### agent platform

An agent runtime plus the services that control what an agent can do, including its identity, its permissions, its audit trail and the means to limit or stop it while it runs.

### agent runtime

The service that runs an agent in production. It hosts the agent, keeps each session separate and scales with demand.

### model

The AI model an agent uses to interpret context and make decisions.

## Capabilities and controls

### agent identity

A credential that identifies one agent, separate from any person or other system, so its actions can be attributed to it and its access revoked.

### approval threshold

The point at which an action needs a [human in the loop](#human-in-the-loop), set by action type, value or level of risk.

### audit trail

The record of what an agent did and why, detailed enough for a customer to reconstruct its actions.

### authority boundary

The limit on which tools an agent can call, what data it can reach and how much value it can move.

### autonomy

The range of actions an agent can take without a person approving them first.

### deterministic guardrail

A rule enforced by the platform or runtime, outside the model, that the agent cannot override. An instruction in the agent's prompt is not a deterministic guardrail.

### human in the loop

Oversight in which a person must approve each action before it takes effect.

### human on the loop

Oversight in which the agent acts without prior approval and a person monitors it, with the ability to intervene, override or stop it.

### kill switch

A control that stops an agent immediately and revokes its access.

## Evidence and assessment

### assessment instrument

The set of criteria, and the evidence each one requires, used to assess an agentic solution.

### claim

Something a member asserts about its organization or a solution.

### evidence

What a reviewer examines to decide whether a claim holds.

### self-declared

Stated by the member without independent checking.

### verified

Confirmed by an independent reviewer, using objective evidence.

## Standards and frameworks

### Agent Governance and Assurance Framework (AGAF)

The Framework published by the MACH Alliance Agent Adoption & Operations Working Group for governing the agents an organization runs.

### AIUC-1

A certification standard for the security, safety and reliability of individual AI agents, maintained by the Artificial Intelligence Underwriting Company. Certification requires third-party testing and an audit by an accredited auditor.

### CSA Agentic Profile

The Cloud Security Alliance's agentic profile of the [NIST AI RMF](#nist-ai-rmf), which defines four autonomy tiers.

### ISO/IEC 42001

The international standard for AI management systems. Certification applies to an organization's governance of AI.

### NIST AI RMF

A voluntary framework for managing AI risk, published by the US National Institute of Standards and Technology.

---

The definition of *agent* is quoted from the [Agent Governance and Assurance Framework](https://github.com/machalliance/wg-agent-adoption-operations), September 2026 Draft, MACH Alliance Agent Adoption & Operations Working Group, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
