# Software Patents: Structure, Claims, and Judicial Outcomes

This repository provides a structured, research-oriented examination of software patents, with emphasis on claim language, patent eligibility, and judicial treatment in U.S. patent law.

This repository focuses on software patents as evaluated under **modern U.S. patent law**, reflecting the legal framework that developed following the America Invents Act (AIA), which took effect primarily on **March 16, 2013**, and during the period in which courts began substantively evaluating software patent eligibility.

Unless otherwise noted, discussions and analyses in this repository reflect **post-AIA statutes, rules, and judicial decisions**.

This repository treats software patents as an evolving body of practice rather than a fixed doctrine, and focuses on understanding patterns in claim structure, technological framing, and judicial outcomes. It also acknowledges the growing role of AI and machine learning in patent prosecution and analysis—including AI-assisted drafting, claim review, and historical pattern analysis—as an emerging factor shaping modern software patent practice.

## Table of Contents

- [Disclaimer](#disclaimer)
- [Types of Patents](#types-of-patents)
- [Overview: Software Patents](#overview-software-patents-high-level)
- [Common Categories of Software Patents](#common-categories-of-software-patents)
- [Common Claim Types in Software Patents](#common-claim-types-in-software-patents)
  - [Method Claims](#1-method-claims)
  - [System Claims](#2-system-claims)
  - [Computer-Readable Medium Claims](#3-computer-readable-medium-claims)

---

## Disclaimer

This repository is for **educational and research purposes only**.
It does **not** constitute legal advice, does **not** create an attorney–client relationship, and should not be relied upon for any legal decision-making.

All analyses are retrospective, based on public materials, and focused on understanding patterns in software patent claims and judicial outcomes.

Nothing in this repository is intended to substitute for governing statutes, regulations, or judicial decisions.

## Introduction: Patents (High-Level)

A patent is a government-granted right that allows an inventor to exclude others from making, using, selling, or importing a claimed invention for a limited time, in exchange for public disclosure of how the invention works.

U.S. patents are defined by their **claims**, which set the legal boundaries of the invention. While patents may include detailed descriptions, figures, and examples, it is the **claims—especially Claim 1—that ultimately define what is protected**.

Patent applications in the United States are administered by the United States Patent and Trademark Office (USPTO).

### Who can file

Applicants whose residence or principal place of business is outside the United States are generally required to be represented by a **U.S.-licensed patent attorney or patent agent** before the USPTO. Patent attorneys and patent agents are registered to practice before the USPTO and have passed the **USPTO registration examination** (commonly referred to as the “patent bar”).

Patent attorneys are licensed attorneys, while patent agents are non-attorney practitioners; both are authorized to represent applicants before the USPTO in patent prosecution matters, including drafting and prosecuting patent applications.

Only patent attorneys may represent clients in patent litigation or provide legal services outside USPTO proceedings.

### Governing rules and guidance

The primary source of procedural guidance for U.S. patent examination and prosecution is the **Manual of Patent Examining Procedure (MPEP)**. The MPEP consolidates statutes, regulations, and USPTO practice guidance and is widely used by examiners and practitioners as a reference, though it does not itself carry the force of law.

Official USPTO patent resources:  
- https://www.uspto.gov/patents  

MPEP (current edition):  
- https://mpep.uspto.gov/RDMS/MPEP/current

---
## Types of Patents
*This section summarizes the primary statutory categories of U.S. patents and situates software patents within that framework.*

Under U.S. patent law, patents generally fall into three broad categories:

### 1. Utility Patents
Utility patents protect **functional inventions**, including:
- Machines
- Processes (methods)
- Manufactured articles
- Compositions of matter
- Improvements to any of the above

In the United States, utility patents generally have a **term of 20 years from the earliest effective non-provisional filing date**, subject to statutory adjustments.

**Software patents are a subset of utility patents**, typically claimed as methods, systems, or computer-readable media.

### 2. Design Patents
Design patents protect the **ornamental appearance** of an article of manufacture, rather than its functional aspects.

Design patents generally have a term of **15 years from issuance** for applications filed on or after **May 13, 2015** (and **14 years from issuance** for earlier-filed design applications).

While design patents may involve software-related products, they generally protect visual design elements (e.g., icons or screen layouts), not software functionality.

### 3. Plant Patents
Plant patents protect new and distinct varieties of plants reproduced asexually.

In the United States, plant patents generally have a **term of 20 years from the filing date**, subject to statutory adjustments.

These are not relevant to software inventions.

This repository focuses on **utility patents involving software-related inventions**, with particular emphasis on how such inventions are evaluated under patent eligibility doctrine.

---

## Overview: Software Patents (High-Level)
*This section explains how courts and examiners approach software patents from a doctrinal perspective.*

Software patents generally protect **specific technological implementations** rather than abstract ideas, mathematical relationships, or business practices performed on a computer.

In practice, courts and examiners tend to evaluate software patents based on **how closely the claimed invention is tied to a concrete technical solution**, as reflected in the claim language—particularly **Claim 1**.

This repository explores software patents at a **high level**, focusing on how different categories of software-related inventions have been treated in U.S. patent law, especially following *Alice Corp. v. CLS Bank* (573 U.S. 208 (2014)).

Alice Ref: https://supreme.justia.com/cases/federal/us/573/208/

## Common Categories of Software Patents

While software patents do not fall into formal legal “types,” they are often discussed in practice according to the **nature of the claimed technological contribution**. Common categories include:

### 1. Technical infrastructure and system-level software

These patents typically focus on:
- Operating systems and kernels
- Memory management
- Network protocols
- Distributed systems and synchronization
- Hardware–software interaction

Claims in this category often emphasize **how** a system operates at a technical level, rather than **what result** is achieved.

### 2. Data processing and transformation software

These patents involve:
- Data encoding or compression
- Signal processing
- Image or audio processing
- Data normalization or transformation pipelines

Outcomes in this category often depend on whether the claims describe a **specific technical mechanism** or merely the processing of information in the abstract.

### 3. Machine learning and AI-related software

These patents may claim:
- Model architectures
- Training or inference workflows
- Feature extraction pipelines
- Model deployment or updating mechanisms

Courts and examiners often scrutinize whether claims describe a **technical improvement to computing** versus the application of known mathematical techniques to generic data.

### 4. User interface and human–computer interaction

Examples include:
- Graphical user interfaces
- Gesture or touch-based interactions
- Presentation and navigation mechanisms

These patents frequently turn on whether the claimed interface provides a **technical solution to a technical problem**, rather than an abstract presentation of information.

### 5. Business process and workflow software

These patents typically address:
- Financial transactions
- Scheduling or resource allocation
- Commercial workflows
- Decision-making systems

This category has historically faced the **most scrutiny** under §101, particularly where claims describe organizing human activity using generic computing components.

### 6. Hybrid hardware–software inventions

These patents involve software claims closely tied to:
- Specialized hardware
- Sensors or physical devices
- Embedded systems

Claims in this category often emphasize **physical components or constraints**, which may influence eligibility analysis depending on how the invention is described.

Regardless of the type of software invention, the same underlying innovation may be claimed in multiple legal forms.

---

## Common Claim Types in Software Patents
*This section explains the principal statutory claim formats used to protect software inventions.*

Once a software invention is identified, it is typically claimed using multiple **claim formats**, each protecting a different aspect of potential infringement. These claim types are largely independent of the underlying software category (e.g., infrastructure software, AI systems, business workflows).

A single software patent family commonly includes **method, system, and computer-readable medium claims** covering the same underlying invention.

**Rule of thumb**:
- **Method** = doing it  
- **System** = having it  
- **Medium** = coding it  

In many software patents, method, system, and computer-readable medium claims appear as **independent claims**, each directed to the same underlying invention but framed in a different statutory category. This structure reflects common practice in software patent drafting and allows the invention to be evaluated across multiple claim formats.

### 1. Method Claims

A **method (or process) claim** protects a sequence of steps performed to achieve the claimed invention.

Typical method claim language may include steps such as:
- receiving a request,
- initializing or opening an execution environment,
- loading configuration data,
- executing one or more software processes.

**General characteristics**:
- Focuses on **actions or operations** performed by a system.
- Often associated with software services or platforms that actively execute the claimed steps.

**Practical considerations**:
- Method claims are typically asserted against parties that **perform all claimed steps**, such as service providers operating a software platform.
- Enforcement may be more complex where different steps are performed by different actors.

**Illustrative example**

A method claim may be implicated when a cloud-based service performs a defined sequence of operations, such as:
- receiving a user request via an API,
- initializing a sandboxed execution environment,
- loading a configuration or policy file,
- executing an AI model or software routine in response.

In this context, the “thing” covered by the claim is the **performance of the steps themselves**, rather than any particular physical object.

**Example (method claim form)**

> A method comprising:  
> receiving, by a computing system, a request to execute a software process;  
> initializing a contained execution environment based on configuration data; and  
> executing the software process within the contained execution environment.

### 2. System Claims

A **system claim** protects the **arrangement of components** configured to perform the claimed functionality.

Typical system claim elements may include:
- software modules,
- configuration files or data structures,
- execution environments,
- processors and memory configured to interact in a defined way.

**General characteristics**:
- Emphasizes **structure and relationships** between components, even when implemented in software.
- Often maps naturally to deployed platforms, products, or architectures.

**Practical considerations**:
- System claims are commonly evaluated based on whether an accused system includes the claimed components or their equivalents.
- Variations in architecture or implementation details may affect how such claims are analyzed.

**Illustrative example**

A system claim may correspond to a deployed software platform or computing system that includes:
- one or more processors,
- memory storing configuration data,
- software modules configured to launch and manage execution environments,
- interfaces that coordinate interactions between components.

In practice, this may map to a **server, virtual machine, or cloud-hosted service instance** configured with specific software components arranged to perform the claimed functionality.

**Example (system claim form)**

> A system comprising:  
> one or more processors;  
> memory storing configuration data; and  
> a launcher module configured to initialize a contained execution environment and cause execution of a software process based on the configuration data.

### 3. Computer-Readable Medium Claims

A **computer-readable medium (CRM) claim**—sometimes referred to as a *Beauregard claim*—protects **software instructions stored on a non-transitory medium**.

Typical CRM claim language includes:
- “A non-transitory computer-readable medium storing instructions that, when executed by one or more processors, cause the processors to perform [method steps].”

**General characteristics**:
- Ties the claimed invention to **stored software instructions**, rather than to execution alone.
- Often mirrors the corresponding method claim in functional content.

**Practical considerations**:
- CRM claims are commonly used to address distribution or deployment of software.
- Like method and system claims, they must be grounded in concrete, non-abstract subject matter.

**Illustrative example**

A computer-readable medium claim may correspond to:
- a software package stored on a server,
- an application distributed via a download,
- a container image or virtual machine image,
- a storage device or non-transitory memory containing executable instructions.

The claim is directed to the **stored instructions themselves**, independent of whether or when they are executed.

**Example (computer-readable medium claim form)**

> A non-transitory computer-readable medium storing instructions that, when executed by one or more processors, cause the processors to:  
> receive a request to execute a software process;  
> initialize a contained execution environment based on configuration data; and  
> execute the software process within the contained execution environment.

Although the method, system, and computer-readable medium claims may recite similar functional language, each claim type is directed to a **different category of subject matter**.

### Why Multiple Claim Types Are Used

Software patent drafters frequently include method, system, and computer-readable medium claims within the same patent family to address **different aspects of potential use or deployment** of the same invention:

1. **Method claims** focus on performing the invention.
2. **System claims** focus on possessing or deploying the invention.
3. **Medium claims** focus on storing or distributing the software that implements the invention.

This multi-claim approach reflects the reality that software inventions may be practiced, deployed, or distributed in different ways.

---

## Contributing

This repository is open for educational and research contributions.  
Please use issues or pull requests for corrections, clarifications, or additions.  
All contributions should adhere to the repository’s educational, non-advisory scope.

## Author and Feedback

This repository was prepared by M. Joseph Tomlinson IV, registered U.S. Patent Agent (USPTO Registration No. 83,522), based on professional experience and independent research.

Portions were drafted with the assistance of AI-based tools and reviewed by the author. The content is intended for educational and research use and reflects retrospective analysis of public materials.

If you identify errors or areas that could benefit from clarification, feedback is welcome. Please open an issue or contact the author.

Contact:
    Email: mjtiv@udel.edu


