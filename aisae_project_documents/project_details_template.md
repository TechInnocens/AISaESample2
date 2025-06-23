# Project Details Template

## Project Context

**Title**
- <!--%PROJ_NAME-->MedAssist Diagnostic AI
- <!--%PROJ_ID-->Will be filled after registration

**Team/Organisation**
- HealthTech Solutions Ltd
- Lead: Dr. Michael Roberts, Chief Medical Officer
- Contact: clinical@healthtech-solutions.com
- Repository: https://github.com/healthtech-solutions/medassist-ai

**Timeline**
- Project start: August 2023
- Live deployment: January 2024
- Current version: v1.1.0 (December 2024)

**Current Development Stage**
<!--%CURRENT_STAGE-->Operations

**Project Description**
- AI-powered diagnostic assistance for radiologists
- Medical image analysis (X-ray, CT, MRI)
- CE marked and FDA approved medical device
- Live in 12 hospitals across UK and EU

### Context

**Purpose**
MedAssist helps radiologists identify potential abnormalities in medical imaging by providing preliminary analysis, confidence scores, and visual highlighting of areas of concern. The system is designed to reduce diagnostic errors and improve workflow efficiency in radiology departments.

**Environment**
The system operates in clinical healthcare environments where diagnostic accuracy directly impacts patient outcomes. Regulatory compliance (CE mark, FDA approval) is mandatory. The system processes sensitive medical data and must maintain strict privacy and security standards.

**Stakeholders**
- Radiologists and imaging technicians (primary users)
- Patients whose scans are analyzed
- Referring physicians who receive reports
- Hospital administrators and IT departments
- Regulatory bodies (MHRA, FDA, EU MDR)
- Medical device quality teams
- Insurance providers and healthcare systems

## Categorisation of use-case

**Purpose/Role** *(What role does this AI play in users' lives?)*
Select ALL that apply:
<!--%PURPOSE_CODES-->
- [ ] **Creates (C)** - Makes things for users (content creation, synthesis)
- [x] **Decides (D)** - Chooses for users (decision making, recommendations)
- [x] **Finds (F)** - Finds things for users (identification, discovery, information retrieval)
- [x] **Predicts (P)** - Tells users what's coming (prediction, monitoring)
- [x] **Helps (H)** - Helps users do things (digital assistance, performance improvement)
- [ ] **Acts (A)** - Takes actions for users (process automation, robotic automation)
- [ ] **Multiple (M)** - System performs multiple roles at different times or upon request
- [ ] **Unknown (?)** - The purpose or role of this system is not known or decided

**Environment** *(In what context is the system operating?)*
Select ONE (or ? for unknown):
<!--%ENVIRONMENT_CODE-->
- [ ] **Low-stakes (L)** - Entertainment, convenience, internal tools
- [ ] **Social-facing (S)** - Public interaction, reputation, relationships
- [x] **High-stakes (H)** - Safety, health, finance, legal decisions, well-being affecting
- [ ] **Unknown (?)** - The environment for the use-case is not known or decided

## Categorisation of System Design Forces

**Control Relationship** *(What's the human-system control dynamic?)*
Select ONE (or ? for unknown):
<!--%CONTROL_CODE-->
- [ ] **Human-Controlled (C)** - Supervised autonomy + Static modification + Transactional interaction
- [x] **Human-Guided (G)** - Monitored autonomy + Adaptive/agentic + Stateful interaction
- [ ] **System-Independence (I)** - Independent/Agent autonomy + Self-modifying + Persistent operation
- [ ] **Unknown (?)** - The control relationship is not known or decided

**Capability Level** (What's the sophistication and power of the underlying system?)
Select ONE (or ? for unknown):
<!--%CAPABILITY_CODE-->
- [ ] **Basic (B)** - Simple algorithms, narrow processing (rule-based, basic ML)
- [x] **Advanced (A)** - Sophisticated models with reasoning (LLMs, multimodal models, complex ML)
- [ ] **Emergent (E)** - Systems with unexpected or hard-to-predict capabilities
- [ ] **Unknown (?)** - The capability level of the system is not known or decided

## Categorisation of Stakeholder and Cultural Forces

Select cultural contexts (can select multiple or ALL for universal):

**Europe & Anglo**
- [x] **Anglo (ANG)** - [x] **Latin Europe (LAE)** - [x] **Nordic Europe (NOR)**
- [x] **Germanic Europe (GER)** - [x] **Eastern Europe (EEU)** - [ ] **Jewish/Hebrew (HEB)**

**Asia & Middle East**
- [ ] **Confucian Asia (CAS)** - [ ] **Korean-Japanese (KJP)** - [ ] **Southern Asia (SAS)**
- [ ] **Southeast Asia (SEA)** - [ ] **Central Asia (CAZ)** - [ ] **Persian/Iranic (PER)**
- [ ] **Arab (ARA)** - [ ] **Turkic (TUR)** - [ ] **Pacific Islander (PAC)**

**Americas**
- [ ] **Latin America (LAM)** - [ ] **North American Indigenous (NAI)** - [ ] **South American Indigenous (SAI)**

**Africa & Oceania**
- [ ] **Sub-Saharan Africa (SSA)** - [ ] **African Indigenous (AFI)** - [ ] **Australian Indigenous (AUI)**

**Arctic**
- [ ] **Arctic Indigenous (ARI)** - [ ] **Indigenous Generic (IND)** 

- [ ] **ALL CULTURES (ALL)**