# OctoAcme Team Composition Guide

## Purpose
Provide guidance on how to compose effective teams using OctoAcme personas for different project types, sizes, and complexity levels.

## Core Principles
- **Right-sizing:** Match team composition to project scope, not budget
- **Clarity:** Every critical function has a defined owner
- **Flexibility:** Roles can be shared or combined in small teams; add specialists as complexity grows
- **Accountability:** Clear ownership reduces gaps and improves decision-making

---

## Team Composition by Project Type

### Small Features or Iterations (1-2 sprints)

**Minimum Team:**
- Product Manager (1)
- Project Manager (1, can overlap with Product Manager role)
- Developers (2-3)
- QA/Testing (1, can be developer-led)

**When to add specialists:**
- Add DevOps if infrastructure changes are needed
- Add Security if data handling or compliance is involved

**Key Characteristic:** Lean, co-located, minimal dependencies

---

### Medium Projects (3-6 sprints)

**Core Team:**
- Product Manager (1)
- Project Manager (1)
- Developers (3-5)
- QA/Testing Lead (1)
- Scrum Master/Agile Coach (0.5-1)

**Add when:**
- Security requirements are significant → Security/Compliance Officer (0.5-1)
- Infrastructure changes or deployment complexity → DevOps Engineer (0.5-1)
- Multiple teams or dependencies → Scrum Master (1 dedicated)

**Key Characteristic:** Defined roles, regular ceremonies, clear communication cadence

---

### Large Projects or Programs (6+ sprints, multiple teams)

**Core Team Per Sub-Team:**
- Product Manager (1 per team)
- Project Manager (1 per team)
- Developers (4-8)
- QA/Testing Lead (1-2)
- Scrum Master/Agile Coach (1 dedicated)

**Program-Level Roles:**
- Executive Sponsor (1)
- Security/Compliance Officer (1, shared across teams)
- DevOps/Infrastructure Engineer (1-2, shared across teams)
- Program Manager (1, coordinating sub-project managers)

**Key Characteristic:** Multiple teams, formal governance, executive oversight, specialized roles

---

## Role-Sharing Guidelines

### When Roles Can Be Combined

| Combined Roles | Recommended For | Notes |
|---|---|---|
| PM + Project Manager | Small features | Requires strong both business and delivery skills |
| Developer + QA | Tiny teams (<3 devs) | Works if test-driven development is practiced |
| Project Manager + Scrum Master | Teams <5 | Scrum Master duties are lightweight; escalations are clear |
| Security + Compliance | Small organizations | Often the same function; benefits from single owner |

### When Roles Must Be Separate

- **Developer + QA Lead:** Conflicts of interest; need independent validation
- **Product Manager + Developers:** Creates misaligned incentives (features vs. quality)
- **Project Manager + Executive Sponsor:** Too much power concentration; need oversight
- **Security + Product Manager:** Security decisions should not be compromised by feature speed

---

## Assembling Your Team: Decision Tree
