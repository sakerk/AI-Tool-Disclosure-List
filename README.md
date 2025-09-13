# Background
The Tool Disclosure List (TDL) is part of maintaining transparency with contractual and [security compliance requirements](#compliance-with-mpa-and-tpn-security-frameworks) that may restrict or require prior approval for the use of AI/ML technologies in workflows or pipelines delivering client content. 

Beyond compliance, the TDL also serves as a foundation for an **ethically run AI pipeline**. By formally documenting the tools in use, the studio ensures:  

- Clear alignment with client contracts, MPA Content Security Best Practices, and TPN audit requirements.  
- Proactive disclosure of tools that require client approval before being used in production.  
- Prevention of unauthorized or “shadow AI” use in creative workflows.  
- Assurance that AI/ML use respects intellectual property rights, performer rights, and industry ethical standards.  
- Reinforcement of client trust by ensuring that all outputs are produced under **documented, approved, and transparent conditions**.

### Introduction to AI/ML Tools  

Here we provide an overview of **AI-enabled features**, **AI-assisted tools**, **Generative AI systems**, and **Cloud-based AI platforms** commonly encountered in visual effects (VFX) and animation (ANM) production workflows.  

  

AI/ML tools vary widely in form, function, and integration:  
- Some are **embedded features** within industry-standard commercial software.  
- Others are **standalone desktop applications** or **open-source frameworks**.  
- Increasingly, tools are delivered as **cloud-hosted SaaS platforms** that process or generate content offsite.  

For clarity and consistency, tools are classified into the following categories:  

1. **AI-Enabled Features (Embedded)**  
   - Functions built into licensed software, often using AI/ML under the hood, but considered baseline features of the tool.  
   - *Example: Adobe After Effects motion tracking, Nuke denoising.*  

2. **AI-Assisted Tools (Enhancement/Assistive)**  
   - Utilities that automate or accelerate discrete production tasks while requiring human oversight.  
   - *Example: Topaz AI upscaling, rotoscoping aids.*  

3. **Generative AI Systems**  
   - Applications that create new expressive content (images, video, audio, text) that did not exist before.  
   - Always require **client disclosure and approval** before use in deliverables.  
   - *Example: Stable Diffusion, RunwayML (local mode), Adobe Firefly desktop.*  

4. **Cloud AI Platforms**  
   - SaaS or cloud-hosted services where content/data is uploaded, processed, or generated remotely.  
   - Always require **explicit disclosure and prior client approval** due to data security, IP ownership, and residency concerns.  
   - *Example: Google Veo, RunwayML (cloud), Pika Labs.*  

This classification ensures that AI/ML tool use is **transparent, consistently documented, and aligned with both client agreements and industry compliance obligations**, while also recognizing that not all AI tools carry the same purpose, integration, or risk profile.  


<br>



<br>

# Tool Disclosure List (TDL)

Disclaimer:
This list is not exhaustive and is subject to periodic updates as new tools emerge and existing technologies evolve. We recommend reviewing the latest version prior to each production cycle to ensure continued compliance and transparency.

*If you have any concerns, corrections, or additions, please submit them for review so we can maintain the accuracy and relevance of this resource.*

### [Tool Disclosure List Site](https://sakerk.github.io/Tool-Disclosure-List/)
<br>

This is a searchable, community-driven resource for tracking AI tool disclosures. The data is sourced from a centralized [Google Spreadsheet](https://docs.google.com/spreadsheets/d/17YEFTLMnJ2ddWnQDSxp4-ykfDH0Fy2KR1Cxj4q7rpUU/edit?gid=0#gid=0) 
, which serves as our master document. You can easily search, filter, and export entries to CSV or Markdown (MD) formats for your own use.

If you'd like to contribute to the list, please reach out — we're happy to add collaborators.
<br>

##  How to Read and Use the Tool Disclosure Table

This table helps studios, legal departments, auditors, vendors, and artists maintain transparency around AI-assisted tools in VFX and animation workflows. Each column provides specific information relevant to legal, ethical, and production compliance.

| **Column**                      | **Purpose**                                                     | **Values / Examples**                                                                                                                                                                                                                                                                               |
| ------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Tool Name**                   | Product or platform name.                                       | *Adobe After Effects, SideFX Houdini, RunwayML*                                                                                                                                                                                                                                                     |
| **License Type**                   | Licensing or distribution type.                                 | *Commercial, Open-source, Hybrid*
| **Tool Type**          | Industry category.                                   | *AI-Enabled Features, AI-Assisted Tools, Generative AI Systems, Cloud AI Platforms*                                                                                                                                                                                                                                                                   |
| **Tool Category**          | Ai Functionality.                                   | *AI-Enabled Features, AI-Assisted Tools, Generative AI Systems, Cloud AI Platforms* 
| **Hosting Model**          | Where and how the Tool is run and or installed.                                   | *Local / On-Prem, Hybrid ( Local install with Cloud based processing), Cloud (SaaS / Platform)*                                                                                                                                                                                                  |
| **Risk Level**                  | Quick “traffic light” shorthand showing legal/producer/auditor concern. | *Low, Medium, High* which is tied to the Output Handling category column. ** See Output Handling and Risk Level Categories selections below.                                                                                                                                                                                                                                                                             |
| **Output Handling Category** | Compliance handling bucket.     | *Standard Software Features – No Approval Required (Low)*<br>*Generative Content – Approval Required (High)*<br>*Assisted, Artist-Controlled – No Approval Required (Medium)*<br>*Internal Use / Non-Deliverable – No Approval Required (Low)*<br>*Disclosure Required – Producer Decides (Medium)* |
| **Usage Description**           | Plain-English explanation of how the tool uses AI.              | *“AI assists with denoising and tracking in compositing tasks.”*                                                                                                                                                                                                                                    |
| **Official Website**            | The tool’s official site or reference link.                     | *[https://www.example.com](https://www.example.com)*                                                                                                                                                                                              |

<br>
<br>

## Output Handling and Risk Level Categories

| Category | Approval Status | Risk Level | What it Means | Examples | Why |
|----------|----------------|---------------|---------------|----------|-----|
| **Standard Software Features** | No Approval Required | Low | AI functions embedded in licensed, industry-standard tools. | Adobe After Effects motion tracking, Foundry Nuke denoising, Autodesk Flame cleanup | These are standard features of professional tools, not considered “AI-generated deliverables.” |
| **Generative Content** | Approval Required |  High | AI that generates new expressive content (images, video, text, audio) that could be used in deliverables. | Adobe Firefly, RunwayML, Stable Diffusion (ComfyUI/Automatic1111), Topaz AI upscaling | This is the risk area Studio Execs/Producers want to control. AI-created content in the finished product. |
| **Assisted, Artist-Controlled** | No Approval Required | Low |AI assists, but a human artist directs, reviews, and approves the final result. | Photoshop AI-assisted upscaling, manual Topaz AI review, roto/mask suggestions | Final creative control rests with the artist; output is human-directed. |
| **Internal Use / Non-Deliverable** | No Approval Required | Low |AI used for technical or workflow efficiency, not deliverables. | Metadata tagging, mocap cleanup, 3D model topology extraction, simulation acceleration | These uses don’t generate expressive content, only optimize internal processes. |
| **Disclosure Required** | Producer/Studio Exec to Decide if Approval Needed | Medium | Gray areas where AI use may impact creative results depending on configuration. | SideFX Houdini ML plug-ins, experimental hybrid workflows | Disclosure ensures transparency; Producer/Execs review and decide if approval is required.  

<br>
<br>
<br>



#  Compliance with MPA and TPN+ and other Security Frameworks

The [Tool Disclosure List](https://sakerk.github.io/Tool-Disclosure-List/) is a core mechanism for demonstrating compliance with various security frameworks.
Below is an **AI/ML Security Management Policy** template that you can use to demonstrate compliance. This Policy is part of another project based around building out a Security Governance Framework(SGF)

<br>
<br>
<br>

## OR-05 – AI/ML Security Management Policy 

| Unified Control No.                      | Mapped MPA 5.3.1 Controls (TPN+)                             | Mapped NIST Controls (NIST 800-171A-R3)                                                                                                    |
| -----------------------------------------| ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| OR-05 – AI/ML Security Management Policy | OR-5.0 – Organizational Security – AI/ML Security Management | 3.11.1 (Risk Assessment), 3.11.2 (Vulnerabilities), 3.13.1 (Boundary Protection), 3.14.1 (Flaw Remediation), 3.15.1 (System Security Plan) |


## 2. Scope
This policy applies to all employees, contractors, and third parties using or integrating AI/ML tools, platforms, or services into [ INSERT COMPANY NAME HERE ], workflows, or deliverables.

### Control Objective  


Establish and maintain a formal **AI/ML Security Management Policy** that governs the use of internally developed and third-party licensed AI/ML systems to ensure compliance with client requirements, industry standards, and applicable laws.

---

### Policy Requirements  

| **Policy Requirement** | **Details** |
|-------------------------|-------------|
| Policy Tailoring        | Document and regularly review AI/ML-specific risks and controls. |
| Risk Management         | Assess risks to datasets, models, applications, network, and supporting systems. |
| Client Approval         | Obtain client approval prior to using AI/ML applications in production workflows. |
| Data Integrity          | Verify sources, integrity, and provenance of datasets before use. |
| Compliance              | Align AI/ML usage with local laws, regulations, contracts, and client policies. |
| Acceptable Use          | Define appropriate usage of AI/ML datasets, integrated with Acceptable Use Policy (OR-1.1). |
| Sandboxing              | Restrict generative AI use to internally managed and sandboxed LLMs. |
| Training                | Provide tailored AI/ML security training by job role. |
| Tool Disclosure         | Maintain a Tool Disclosure List of all AI/ML tools in use, categorized by type, risk level, and approval status. |




