# Project Details
*(Note: The AISaE by Design Framework does not provide legal or regulatory advice. Developers should ensure they adhere to all legal and regulatory requirements for their development work)*


## Project Context
*(These details are project-specific and will not be included in any reusable patterns)*

**Project Name** (full title of your project)
<!--%PROJ_NAME-->SmartCity Traffic AI: Adaptive Traffic Management System

**Current Development Stage** (choose from Concept, Prototype, Release Development, or Operations)
<!--%CURRENT_STAGE-->Prototype

**Team/Organisation**
- Lead organisation or team: Transport for London Digital Innovation Team
- Project website or repository: https://github.com/TfL-Digital/smartcity-traffic-ai

### Context

**Purpose**
Describe the purpose of this system from the perspective of its users. What need or goal does this AI system address?
To optimise traffic flow in central London by dynamically adjusting traffic light timings, coordinating signal phases across intersections, and providing real-time routing recommendations to reduce congestion, emissions, and journey times for all road users including pedestrians, cyclists, and vehicles.

**Environment**
Describe the context in which this system will operate (e.g. industry, work area, geographies, etc)
Urban transport infrastructure across Central London, initially covering Zone 1 with 200+ controlled intersections. The system operates 24/7 in a complex multi-modal transport environment including buses, emergency vehicles, cyclists, and pedestrians.

**Stakeholders**
List all groups who will be impacted by this system (direct users, affected parties, decision makers)
Primary users: TfL traffic controllers, emergency services dispatchers, public transport operators
Secondary stakeholders: London commuters, residents, business owners, delivery companies, cyclists, pedestrians
Decision makers: TfL board, Mayor of London, borough councils, emergency services

Identify any vulnerable or high-risk groups
Elderly pedestrians requiring longer crossing times, disabled individuals with mobility aids, visually impaired pedestrians, emergency services requiring priority access, school children during peak times, cyclists in mixed traffic

Note any specific cultural or demographic groups who are intended users or be affected
Diverse London population including tourists unfamiliar with local traffic patterns, shift workers with non-standard commute times, delivery drivers from various cultural backgrounds, international students and workers new to UK traffic systems.

## Categorisation of use-case

*(Combination of Purpose + Environment)*

**Purpose/Role** (What role does this AI play in users' lives?. Select ALL that apply:)
<!--%PURPOSE_CODE-->
- [ ] **Creates (C)** - Makes new things for users (new content creation)
- [x] **Decides (D)** - Chooses for users (decision making, recommendations)
- [ ] **Finds (F)** - Finds things for users (identification, discovery, information retrieval)
- [x] **Predicts (P)** - Tells users what's coming (prediction, monitoring)
- [ ] **Helps (H)** - Provides guidance to users (digital assistance, performance improvement)
- [x] **Acts (A)** - Takes actions for users (process automation, robotic automation)
- [ ] **Explains (E)** - Makes things clearer for users (summarising, interpretation, synthesising)
- [ ] **Translates (T)** - Converts input from one form to another (language translation, modality conversion, input recognition)
- [ ] **Unknown (?)** - The purpose or role of this system is not known or decided

**Environment** (In what context is the system operating? Select ONE or ? for unknown)
<!--%ENVIRONMENT_CODE-->
- [ ] **Low-stakes (L)** - Entertainment, convenience, internal tools
- [ ] **Social-facing (S)** - Public interaction, reputation, relationships
- [x] **High-stakes (H)** - Safety, health, finance, legal decisions, well-being affecting
- [ ] **Unknown (?)** - The environment for the use-case is not known or decided

## Categorisation of System Design Forces

**Autonomy level** (What level of autonomy does the system have in performing actions? Select ONE or ? for unknown)
<!--%AUTONOMY_CODE-->
- [ ] **Supervised(S)** - Human approves each action
- [x] **Monitored (M)** - Human has oversight and can intervene, but system operates independently
- [ ] **Independent (I)** - Performs actions without specific human input or oversight
- [ ] **Unknown (?)** - The autonomy level of the system is not known or decided

**Self-learning level** (What ability does the system have to change its own execution to reflect updated understanding or experiences? Select ONE or ? for unknown)
<!--%SELF_LEARNING_CODE-->
- [ ] **Static(S)** - Fixed capabilities, doesn't learn or change during normal operations.
- [x] **Adaptive/Agentic (M)** - Uses memory type structures or similar to improve responses and approaches.
- [ ] **Self-modifying (I)** - Can modify its own capabilities, processes or objectives.
- [ ] **Unknown (?)** - The self-learning level of the system is not known or decided.

**Persistence level** (What level of persistence does the system have in for users or context? Select ONE or ? for unknown)
<!--%PERSISTENCE_CODE-->
- [ ] **Transactional (T)** - Stateless, each interaction or session is independent.
- [ ] **Stateful (S)** - Remembers context/history, builds continuity
- [x] **Persistent (P)** - Ongoing pursuit of goals and task execution without requiring prompting
- [ ] **Unknown (?)** - The persistence level of the system is not known or decided.

**Capability Level** (What's the sophistication and power of the underlying system? Select ONE or ? for unknown)
<!--%CAPABILITY_CODE-->
- [ ] **Basic (B)** - Simple algorithms, narrow processing (rule-based, basic ML). Does what you expect, clear decisions, predictable failures
- [x] **Advanced (A)** - Sophisticated models with a degree of simulated reasoning (LLMs, multimodal models, complex ML), some surprises, novel failure modes. 
- [ ] **Emergent (E)** - Systems with unexpected or hard-to-predict capabilities. May produce new capabilities, unclear boundaries 
- [ ] **Unknown (?)** - The capability level of the system is not known or decided

**Data Sources** (select all that apply)
<!--%DATA_CODE-->
- [x] **Controlled Internal(I)** - Operating organisation's own data
- [ ] **User-Provided(U)** - End users input
- [x] **Verified Public(V)** - Vetted datasets, government, academic sources
- [ ] **Unverified Public(W)** - Scraped web content, social media
- [x] **Third-Party Licensed(T)**

**Other Behaviours** (What other system behaviours are relevant? Select any/all applicable, leave blank if none apply)
<!--%OTHER_SYS_CODE-->
- [ ] **Agentic Interaction (A)** - System will operate in an agentic colony structure (i.e. communicating with and sharing work with other cognitive agents)
- [x] **Upstream (U)** - System operates upstream of other cognitive agents (i.e. the system will call other AI to execute tasks).
- [ ] **Downstream (D)** - System is downstream of other cognitive agents (i.e. the system is called by other AI to execute tasks).

## Categorisation of Stakeholder and Cultural Forces

At this moment Stakeholder and Cultural forces are not in scope for the framework and default to "All":

<!--%CAPABILITY_CODE-->
- [X] **ALL STAKEHOLDERS GROUPS (ALL)**

<!--%CULTURES_CODE-->
- [X] **ALL CULTURES (ALL)**