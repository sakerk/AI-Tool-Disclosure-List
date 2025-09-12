# Purpose
### Introduction to AI/ML Tools  

This document provides an overview of **AI-enabled features**, **AI-assisted tools**, **generative AI systems**, and **cloud-based AI platforms** commonly encountered in visual effects (VFX) and animation (ANM) production workflows.  

The purpose of this disclosure is to maintain transparency with contractual and [security compliance requirements](#compliance-with-mpa-and-tpn-security-frameworks) that may restrict or require prior approval for the use of AI/ML technologies in workflows or pipelines delivering client content.  

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

# THE LIST

Disclaimer:
This list is not exhaustive and is subject to periodic updates as new tools emerge and existing technologies evolve. We recommend reviewing the latest version prior to each production cycle to ensure continued compliance and transparency.

If you have any concerns, corrections, or additions, please submit them for review so we can maintain the accuracy and relevance of this resource.

[TOOL DISCLOSURE LIST](https://sakerk.github.io/Tool-Disclosure-List/)
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



##  Compliance with MPA and TPN+ Security Frameworks

The **Tool Disclosure List** is a core mechanism for demonstrating compliance with **MPA Content Security Best Practices v5.3.1 OR-5.0 (AI/ML Security Management)**. 

### Specifically, it:

1. **Supports Client Approval Requirements**

   * Provides a formal inventory of AI/ML tools for **client review and approval** before use in production.

   * Directly addresses the MPA requirement to **obtain client approval for AI/ML application use**.

2. **Manages Risk Transparently**

   * Categorizes tools by **risk level** (Low/Medium/High) and **AI Output Handling Category**, enabling structured risk management.

   * Satisfies the MPA requirement to **identify and manage risks** associated with datasets, applications, and infrastructure changes.

3. **Enforces Acceptable Use**

   * Ensures only tools listed and approved are permitted, integrating AI/ML oversight into the **Acceptable Use Policy (OR-1.1)**.

   * Meets the MPA requirement to **outline appropriate usage for AI/ML datasets and applications**.

4. **Provides an Audit Trail**

   * Serves as a **living document** — reviewed quarterly and updated upon introduction of new tools — ensuring **ongoing compliance and accountability**.

   * Demonstrates to auditors and clients that the studio has an **active, documented process** for managing AI/ML security.
<br>





