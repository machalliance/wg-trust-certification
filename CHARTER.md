# Trust & Certification Working Group Charter

## Purpose

Certification exists to give end users a trustworthy signal. It answers a question buyers cannot easily answer for themselves: can this technology, and the organization behind it, be relied upon to deliver on the architectural and operational promises being made?

Agentic capabilities change what that question means. When a solution acts on a user's behalf, reasons probabilistically, invokes tools, and takes actions with real consequences, the properties that make it trustworthy are not fully captured by criteria written for deterministic systems. A product can be well-architected by every existing measure and still leave an end user unable to answer basic questions: what is this agent permitted to do, what did it actually do, who is accountable when it is wrong, and how do I control it.

This working group examines how agentic capabilities affect certification criteria and trust. It has two jobs. The first is to determine which certification criteria must change or be added so that certification continues to mean something as solutions become agentic. The second is to determine what end users need in order to discover and compare agentic solutions, which is a need that certification alone does not meet.

Three signals result, and they are meant to work together. Certification establishes that an organization and its claims can be trusted. The Agent Ready award recognizes those doing materially more to help end users succeed. The Agent Solutions Hub is where an end user finds and compares specific solutions. This group defines the criteria behind all three.

The unit of concern is the agentic solution, not only the company that sells it. Certification attaches to organizations, but what an end user actually adopts and must trust is a specific solution: a product, a capability within a product, a composed system, or a delivered implementation. Criteria that assess only the organization will not tell an end user whether the thing in front of them is trustworthy.

The population remains MACH Alliance membership. This group is not defining criteria for the whole market, but changing how member organizations and their solutions are assessed and represented.

The mission is end-user trust. That framing sets the bar: a criterion earns its place only if it distinguishes a trustworthy agentic solution from an untrustworthy one in a way an end user would care about.

Other working groups in the [Agent Ecosystem](https://github.com/machalliance/agent-ecosystem) initiative address [enterprise agentic architecture](https://github.com/machalliance/wg-enterprise-agent-architecture) and [agent adoption and operations](https://github.com/machalliance/wg-agent-adoption-operations). This group is focused on assessment and signal: what must be true of an agentic solution, and how that is evidenced, certified, and communicated to the market.

### 1. Certification Criteria

- Assess where current certification criteria fall short when applied to agentic capabilities
- Define what distinguishes a trustworthy agentic solution, and the vendor or service provider behind it, from a non-agentic one
- Revise and extend criteria so agentic capabilities are assessed on evidence rather than claims
- Keep criteria assessable: each must be verifiable by a certification reviewer within a realistic review process

### 2. Discovery and Comparison

A forthcoming Agent Solutions Hub will give end users a place to find and compare agentic solutions from member organizations. The Hub is a separate initiative and is not this group's responsibility to build or operate. What the group owns is the trust question underneath it: a listing is only useful if an end user can rely on what it claims.

- Define what must be validated or verified before a solution is listed, so the Hub is a trust signal rather than a self-reported catalogue
- Define a shared vocabulary for describing agentic solutions so that comparison across listings is meaningful
- Keep Hub validation consistent with certification and the Agent Ready award, so the three signals reinforce rather than contradict each other
- Recognize those who go beyond baseline certification in supporting end users deploying agentic solutions

### 3. Annual Cycle

- Assess and revise the Agent Ready award criteria annually, so recognition tracks a capability landscape that moves faster than certification programs typically revise
- Feed each cycle's findings back into the certification criteria, so what starts as a differentiator can become a baseline expectation

## Example Questions

Examples below illustrate the types of challenges this working group seeks to examine and address.

- Which existing certification criteria still hold for agentic capabilities, which need reinterpretation, and which are silent on risks that matter?
- What evidence should be required to demonstrate an agentic capability, given that behavior is probabilistic and cannot be verified by inspection alone?
- How should a solution disclose what its agents are permitted to do, what data they access, and what actions they can take without human approval?
- What should be exposed so a customer can reconstruct what an agent did and why?
- Where does accountability sit when an agentic solution is composed from a vendor's product, a third-party model, an integrator's implementation, and a customer's own configuration?
- What must a solution provide so that a customer retains meaningful control: authority boundaries, approval thresholds, kill switches, and the ability to constrain autonomy?
- How should service providers, as distinct from technology vendors, be assessed on their ability to deliver agentic solutions responsibly?
- Where an agentic solution spans several organizations, what is certified, and how far does that signal extend?
- What distinguishes a product that happens to include agentic features from one that genuinely enables customers to deploy agentic solutions?

## Initial Deliverables

The following is the initial set of artifacts the working group will develop. The group recommends criteria; the MACH Alliance Executive Board ratifies them. Deliverables are therefore written as recommendations with the reasoning behind each change made explicit, so the board is deciding on evidence rather than on assertion.

### 1. Agentic Capability Gap Analysis

An analysis of current certification criteria assessed against agentic capabilities. It identifies which criteria remain sufficient, which require reinterpretation when applied to agents, where existing criteria fall short, and where entirely new criteria are needed. This establishes the evidence base for the revised criteria and makes the reasoning behind each change traceable.

*Example:* An existing criterion on API access is evaluated against an agentic use case, and the analysis identifies that it addresses programmatic access but is silent on scoped, revocable, and auditable authorization for an autonomous caller.

### 2. Revised Certification Criteria for Agentic Capabilities

A drafted set of certification criteria covering agentic capabilities, ready for pilot review with a small set of vendors. Each criterion specifies what is being assessed, why it matters to end-user trust, and what evidence must be supplied to satisfy it. The draft covers both technology vendors and service providers, and distinguishes criteria that assess the organization from those that assess a specific solution. Agentic criteria are conditional on claims: they apply to members claiming an agentic capability, and a member making no such claim remains certified without meeting them. Agentic capability is not becoming a condition of membership.

*Example:* Any agentic capability claim must be accompanied by documentation of the actions the agent can take without human approval, and a demonstration of how a customer restricts that set.

### 3. 2027 Agent Ready Award Criteria

Criteria for the 2027 Agent Ready award, recognizing those that support end users in deploying agentic solutions. This is a revision of an existing program rather than a new one: the [inaugural 2026 cohort](https://machalliance.org/insights-hub/mach-alliance-recognizes-first-cohort-of-agent-ready-award-recipients) recognized over thirty members with agentic technology running in production, assessed against distinct criteria per membership category, with the award sitting atop MACH Certification and current certification required for eligibility. Annual renewal is mandatory as criteria evolve.

The working group's task is therefore to determine what the 2027 criteria should require that the 2026 criteria did not. The 2026 bar was, in essence, evidence of production agentic capability. As that becomes common, the bar has to move toward what distinguishes solutions that end users can actually trust and adopt, which is the same question the certification criteria are being revised to answer. The criteria are revised annually, so each cycle should raise the bar deliberately, and a capability that distinguishes a recipient one year is a candidate to become a baseline certification expectation in a later one.

The revision covers all membership categories the award spans, currently independent software vendors, system integrators, and enablers and infrastructure providers, and should state how a category's criteria differ and why. The 2027 criteria must be final in time to evaluate candidates and make awards in early 2027, which sets the working backward date for the first cycle.

### 4. Agent Solutions Hub Validation Criteria

Criteria for validating and verifying solutions listed in the Agent Solutions Hub. The Hub is built and operated as a separate initiative; this group supplies the basis on which a listing is trusted. The criteria define what a listing must assert, what evidence supports each assertion, what is verified before publication versus attested by the member, and how a listing is kept current or withdrawn when it goes stale.

*Example:* A listing claiming an agent integrates via an open standard names the standard and points to something a prospective end user can independently exercise, rather than asserting interoperability in prose.

## Who This Working Group Serves

**End Users and Enterprise Buyers**
Organizations selecting agentic technology and services, who need a reliable basis for comparing solutions and understanding what they are committing to.

**Technology Vendors**
Vendors building agentic capabilities into their products, who need to know what will be assessed and what evidence they will be expected to produce.

**Service Providers and System Integrators**
Partners delivering agentic solutions for clients, who are assessed on delivery capability rather than product architecture.

**Certification Reviewers and Program Operators**
Those who administer certification, who need criteria that are unambiguous, evidence-based, and practical to assess consistently.
