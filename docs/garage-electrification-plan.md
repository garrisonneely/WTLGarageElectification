# Garage Electrification Plan (Draft for Subcommittee Review)

Date: 2026-01-24  
Status: Draft v0.1

## Executive summary
Goal: Create a phased plan to support **resident EV charging**, with a long-term target of providing **L2 charging to as many cars as want it**.

Operational note: We have a **property management company** that can likely facilitate much of the research and coordination (especially with Xcel and retrieval of building electrical documentation). This plan assumes we use property management as the **primary point of contact** for utility and building-record requests, with the subcommittee providing questions, reviewing outputs, and making recommendations to the board.

Current impediments:
1. **Electrical capacity constraints:** The garage distribution panel and the upstream utility (Xcel) service appear to have limited headroom for additional L2 charging. There was a major electrical infrastructure improvement nearby that may have changed upstream constraints; we should verify.
2. **Existing capacity already consumed:** One resident has the lone L2 hookup, apparently fully subscribing current garage panel capacity. Two other spots rely on long extension cords, which is not an acceptable long-term solution.

Proposed approach:
- **Phase 0–1:** Gather data and quantify constraints (utility + in-building).
- **Phase 2 (intermediate):** Enable safe, permitted **120V “drip charging” outlets** for any interested resident (wiring and infrastructure paid for by resident), requiring code-compliant conduit and metering/fee structure.
- **Phase 3 (long-term):** Build a scalable L2 program (potentially load-managed) based on verified capacity and cost models.

---

## Guiding principles
- **Safety first:** No extension cords as a policy; permanent, code-compliant installations only.
- **Fairness and transparency:** Clear eligibility, costs, and queueing rules; no “first mover captures all capacity.”
- **Scalability:** Any near-term work should avoid dead-ends and keep an upgrade path to L2.
- **Cost allocation:** Residents who benefit directly should pay for their run/conduit; shared infrastructure upgrades may be split via a program/assessment if approved.
- **Operational simplicity:** A program the board can administer without constant bespoke exceptions.

---

## Scope
In scope:
- Utility capacity inquiry and documentation.
- Electrician/engineer assessment of garage electrical infrastructure.
- Design options for phased EV charging (120V now, L2 later).
- Cost models (per-spot vs shared upgrades) and governance policy proposals.

## Roles and workflow
- **Subcommittee:** Defines questions, maintains this repo, consolidates findings, drafts recommendations.
- **Property management company:** Primary facilitator for (a) Xcel communication and studies, (b) requesting building electrical records/as-builts, and (c) coordinating vendor access to electrical rooms.
- **Electrician / electrical engineer:** Performs load calculations, site assessment, and produces stamped/permit-ready recommendations if we proceed.
- **Board:** Approves spend, policies, resident communications, and any construction direction.

Recommended workflow:
1. Subcommittee drafts a single consolidated question list / request.
2. Property management submits/coordinates with Xcel and vendors.
3. Subcommittee translates responses into board-ready memos and options.

Out of scope (for now):
- Selecting a specific EV charging vendor.
- Committing to a construction project before we have validated constraints.

---

## Phase 0 — Organize and document the current state (1–2 weeks)
### Objectives
- Establish a factual baseline: what exists today, what is allowed, and what is safe.

### Tasks
1. **Inventory current installations and behaviors**
   - Map garage electrical rooms/panels relevant to EV loads.
   - Document the existing L2 hookup (breaker size, circuit path, metering/billing arrangement, permissions).
   - Document where extension cords are being used and the operational/safety issues created.
2. **Collect relevant documents**
   - Building electrical diagram (single-line / distribution): `artifacts/WaterTowerLofts_Electrical.pdf`.
   - Panel schedules, as-builts, and any garage-specific electrical drawings (if available).
   - HOA policies (if any) on electrical modifications.
   - Any past proposals or correspondence with Xcel/electricians.

   Where possible, request these through **property management** (they often have existing vendor/utility contacts and access to archived building records).

### What to extract from the building electrical diagram
Capture these details as a short “facts” list so the electrician and Xcel conversations stay grounded:
- Utility service details (service size/amps, voltage, phase) and where it lands in the building.
- Main switchboard/switchgear identifiers and any notes about spare capacity.
- Garage distribution panel(s): panel names/labels, feeder sizes, and any subpanels.
- Where EV loads are currently tied in (identify the existing L2 circuit path if possible).
- Physical constraints hinted by the drawings (routing, risers, electrical rooms).

### Deliverables
- A “Current State” memo with photos and a simple map.
- A list of unknowns that must be resolved in Phase 1.

---

## Phase 1 — Validate upstream utility capacity (Xcel) (2–6 weeks)
### Objective
Determine whether the building’s upstream electrical service can support incremental EV load now, and what upgrades would be required to increase capacity.

### Tasks
1. **Open a formal inquiry with Xcel (via property management)**
   - Ask for current service capacity details and any constraints.
   - Ask whether the recent nearby infrastructure improvement changes available capacity for our service.
   - Ask what the process is for a service upgrade study and typical timeline.
2. **Request/confirm technical artifacts**
   - Service size and configuration.
   - Any transformer capacity limits.
   - Requirements for increased load (engineering study, transformer upgrade, lead times).

### Notes for property management
- Ask Xcel to respond **in writing** (email/letter) and include any reference numbers for the inquiry.
- If Xcel requires an “authorized account holder” or signed authorization, property management can typically handle this faster than individual residents.

### Key questions for Xcel (send as a single list)
1. What is our current service size and what is typical remaining headroom?
2. Are there known constraints on our transformer or feeder that limit adding EV load?
3. Did the recent nearby infrastructure work change available capacity for our building or block?
4. What is the process and cost range for initiating a load study / service upgrade?
5. What are typical lead times for transformer or service upgrades in this area?

### Deliverables
- Written response from Xcel (email/letter) plus any supporting docs.
- A simple summary: “How much additional continuous load could we add without a service upgrade?”

---

## Phase 1B — Validate in-building electrical constraints (2–6 weeks, in parallel)
### Objective
Understand what changes inside the garage/building are required for:
- Safe 120V outlets at scale (intermediate)
- Future L2 charging at scale (long-term)

### Tasks
1. **Hire an electrician (or electrical engineer if needed)**
   - Request an assessment specifically focused on EV charging readiness.
2. **Assess garage distribution and pathways**
   - Panel capacity and whether a subpanel upgrade/new subpanel is needed.
   - Available conduit pathways and feasibility of running new conduit to spots.
   - Feasible number of circuits based on panel space and load calculations.
3. **Options and costs**
   - Rough-order-of-magnitude (ROM) costs for:
     - Additional 120V circuits
     - Subpanel upgrades / new feeders
     - Load management approaches (if used)

### Key questions for the electrician
1. What is the maximum additional continuous load the garage panel(s) can safely support today?
2. What is the safest, code-compliant approach to get 120V outlets to multiple parking spots?
3. What physical constraints exist (pathways, drilling, firestopping, conduit routing)?
4. What upgrades would be required to support N L2 chargers (e.g., 10, 20, 40) assuming load management vs no load management?
5. What are the permitting requirements and inspection steps?

### Deliverables
- A short assessment letter/memo.
- A ROM cost table with 2–3 options (e.g., “120V expansion,” “L2-ready conduit,” “L2 + load management”).

---

## Phase 2 — Intermediate program: 120V outlets (drip charging) with L2-ready infrastructure
### Objective
Enable any resident who wants a standard AC plug to charge safely, without extension cords, while ensuring the installed infrastructure is **L2-capable later**.

### Policy concept
- Residents may request a dedicated outlet near their parking spot.
- Residents pay for:
  - Conduit run to their spot
  - Outlet installation
  - Any required portion of shared upgrades (if applicable)
- Installations must be:
  - Permitted and inspected
  - In conduit (no cord runs)
   - Using materials and routing that will support future L2 wiring (where practical). Ask an electrician to price the incremental cost difference between “120V-only” versus “L2-ready” conduit/wiring so we understand the tradeoff.

### Design considerations
- **Conduit sizing**: choose conduit that can accommodate later L2 conductors where feasible.
- **Circuit strategy**: dedicated circuits vs shared circuits; avoid nuisance trips.
- **Billing**: decide approach (flat monthly fee vs submetering vs owner reimbursement).
- **Queueing**: if capacity is limited, define first-wave rules and expansion triggers.

### Deliverables
- A written “120V outlet program” policy for board review.
- A standard resident request form + installation agreement.
- A standard electrical spec (so every install is consistent).

---

## Phase 3 — Long-term program: scalable L2 charging
### Objective
Provide L2 charging broadly through one of these approaches:

### Option A: Spot-based L2 (resident-owned EVSE)
- Residents install their own EVSE at their spot.
- Requires robust panel/service upgrades and/or load management.

### Option B: Managed networked charging (shared infrastructure)
- Building installs a managed EV charging system with load management.
- Can allow many “assigned” chargers while staying within service limits.

Potential add-on: **Public/paid charging (revenue)**
- Investigate whether one or more chargers could be made available to non-residents (paid access) to offset costs.
- Consider constraints up front: access control, parking enforcement/towing rules, resident priority, liability/insurance, hours of availability, and whether public use creates security/traffic issues.
- If pursued, require a clear policy (who can use it, when, pricing, and how to handle disputes) and confirm any board/HOA legal requirements.

### Option C: Mixed model
- Some assigned L2 spots plus a set of shared “temporary charging” spaces.

### “Temporary parking + charging” concept (investigate)
- Create a small number of shared charging locations in-garage or near the building.
- Intended for short-term charging sessions and visitors.
- Requires rules (time limits, enforcement, access control).

### Deliverables
- A board-ready decision memo comparing options A/B/C:
  - Cost
  - Scalability
  - Fairness
  - Maintenance burden
  - Vendor lock-in risk

---

## Risks and mitigations
- **Upstream utility constraints unchanged** → Mitigate with phased approach + load management exploration.
- **Fairness concerns (existing L2 owner)** → Mitigate with transparent policy; potentially renegotiate if needed.
- **Safety / compliance** → Mitigate with permitting, inspection, and clear rules.
- **Cost shock** → Mitigate with ROM estimates early and multiple options.

---

## Next steps (recommended)
1. Draft subcommittee charter and invite members.
2. Document current state (photos, panel labels, current L2 circuit details).
3. Send property management the Xcel question list and ask them to open the inquiry on behalf of the HOA.
4. Ask property management to help schedule at least one electrician site visit (including access to electrical rooms).
5. Draft a “no extension cords” policy proposal with a transition plan.

