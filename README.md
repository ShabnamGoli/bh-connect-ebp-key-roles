# BH-CONNECT & BHSA: Key Roles in Evidence-Based Practice (EBP) Implementation

**EPI-CAL Work Sample | Design & Development Overview**

[View the Live Microlearning](https://golishabnam-lab.github.io/bh-connect-ebp-key-roles-guided/)

---

## Project Overview, Audience, Learning Strategy

### Project Overview

This work sample was developed in response to a request for a 5 minute accessible microlearning based on the California Department of Health Care Services (DHCS) resource, *BH-CONNECT and BHSA EBP Requirements: Key Roles*.
The source material describes how four stakeholder groups—behavioral health practitioners, counties, Centers of Excellence (COEs), and DHCS—share responsibility for implementing evidence-based practices.
The primary design challenge was to transform dense, policy-oriented content into a short learning experience that helps learners quickly understand who does what, how responsibilities differ, and whom to involve when an implementation need arises.
The final solution is a browser-based microlearning combining video, visual comparison, expandable role-based content, a glossary, and an application-based knowledge check.

### Audience

The intended audience includes:

- Behavioral health practitioners
- County behavioral health staff
- Center of Excellence personnel
- DHCS staff
- Program and implementation staff supporting EBP delivery
- Other stakeholders who need a high-level understanding of EBP implementation roles

Because learners may have varying familiarity with behavioral-health terminology, the course includes an on-demand glossary for acronyms and EBP names.

### Learning Need

The DHCS source contains detailed information across multiple EBPs, stakeholder groups, implementation processes, reporting responsibilities, and quality requirements.
The key performance need was identified as:

> Learners need to quickly distinguish stakeholder responsibilities and determine which implementation partner is appropriate for a given need.

The design therefore prioritizes role differentiation and application, rather than memorization of policy details.

### Learning Goal

Learners will understand the four key stakeholder roles and how their responsibilities contribute to EBP implementation.

### Learning Objectives

By the end of the microlearning, learners will be able to:

1. Identify the applicable quality-review process for each EBP.
2. Differentiate stakeholder responsibilities across key implementation processes.
3. Select the appropriate implementation partner for a common implementation need.

The objectives intentionally progress from identification → differentiation → application.

### Scope Analysis

The complete DHCS framework includes responsibilities related to:

- Implementation planning
- Training
- Technical assistance
- Fidelity monitoring / accreditation / certification
- Data collection
- Service delivery
- Payment

Because the requested learning experience was limited to approximately five minutes, the course focuses on the content most important for building a usable mental model:

- Four stakeholder groups
- EBP-specific quality-review requirements
- Training
- Quality oversight
- Service delivery
- One applied implementation scenario

The broader areas of implementation planning, technical assistance, data collection, and payment are acknowledged and linked to the complete DHCS resource rather than fully taught.
Detailed timelines, claims procedures, reporting schedules, exemptions, and administrative requirements were intentionally excluded because they would shift the product from microlearning into comprehensive policy training.

# Learning Experience, Activities, Assessment & ADDIE

### Learning Experience and Activity Design

The course follows a simple learning progression:
Overview → Quality Requirements → Roles in Action → Application → Completion

#### Introductory Video

A short video introduces the four stakeholder groups and establishes how they work together.
The video includes:

- synchronized captions
- a complete transcript
- learner-controlled playback

Its purpose is orientation rather than detailed instruction.

The visual sequence was designed in **Canva** and assembled/refined in **Clipchamp**, where narration timing and the sequential introduction of the four stakeholder groups were synchronized for the final web-delivery version.

#### Quality Requirements Comparison

A matched two-card layout helps learners distinguish between:

- Fidelity monitoring: ACT, FACT, CSC, IPS, HFW
- Accreditation: Clubhouse Services
- Certification: MST, FFT, PCIT

This visual comparison reduces the cognitive effort required to interpret the source material.

#### Roles in Action

Expandable sections allow learners to compare stakeholder responsibilities across:

- Training
- Quality Oversight
- Service Delivery

Progressive disclosure keeps the interface concise while still allowing learners to examine responsibility differences.

#### Glossary

A course-level glossary provides definitions for terms such as EBP, BHSA, DHCS, COE, ACT, FACT, CSC, IPS, HFW, MST, FFT, and PCIT.
This functions as embedded performance support rather than requiring learners to memorize terminology.

### Assessment Design

The knowledge check measures application, not recall.
Learners are presented with an ACT team whose fidelity report identifies areas for improvement. The team needs individualized guidance and additional training and must identify the appropriate implementation partner.
The correct response is the Center of Excellence (COE).
Immediate explanatory feedback reinforces why COEs are responsible for technical assistance and improvement support.
The assessment therefore tests whether learners can answer:

> “Who should I go to for this implementation need?” rather than simply recalling information from the preceding screen.

### ADDIE Approach

#### Analysis

I analyzed:

- the stakeholder request
- learner audience
- DHCS source complexity
- required 3–5 minute duration
- differences among EBP requirements
- accessibility needs
- likely learner familiarity with terminology

The central instructional need identified was role differentiation.

#### Design

The course was structured around three progressively more complex objectives:
Identify → Differentiate → Select
I used progressive disclosure, repeated stakeholder categories, and visual consistency to minimize cognitive load.

#### Development

The microlearning was built as a custom browser-based experience using HTML, CSS, and JavaScript.
Development included:

- player-style navigation
- interactive accordions
- glossary functionality
- video integration
- captions and transcript
- knowledge-check logic
- responsive layout
- accessibility features

#### Implementation

The course was deployed through GitHub Pages, allowing reviewers and learners to access it directly through a browser without an LMS or specialized software.

#### Evaluation

Iterative QA focused on:

- content accuracy
- objective alignment
- scope
- terminology
- interaction functionality
- keyboard navigation
- focus visibility
- reduced-motion support
- responsive behavior
- source attribution
- assessment alignment

# Accessibility, Tools, Constraints, Complexity & Future Support

### Accessibility Approach

Accessibility was incorporated during design and development rather than added at the end.
Implemented features include:

- semantic HTML
- keyboard navigation
- visible focus states
- synchronized captions
- full video transcript
- accessible form controls
- screen-reader-accessible feedback messages
- accessible glossary dialog
- responsive layout that adapts to screen size and zoom
- reduced-motion support
- text alternatives to audiovisual content

The project documents the accessibility features implemented rather than making a blanket compliance claim.

### Tools Used

**HTML, CSS, and JavaScript**
 Used to build the custom course interface, navigation, interactions, glossary, knowledge check, responsive behavior, and accessibility features.
**GitHub / GitHub Pages**
 Used for version control, deployment, and browser-based delivery.
**Canva**
 Used to design the visual assets and build the animated introductory video, including the sequence in which the four stakeholder groups are introduced.
**Clipchamp**
 Used to assemble and refine the video, synchronize narration with the visual sequence, adjust timing, and prepare the final video file for web delivery.

### Constraints

The project required balancing several constraints:
**Time:** The complete experience needed to remain approximately 3–5 minutes.
**Content density:** The source contained considerably more information than could be responsibly taught within that duration.
**Accuracy:** Simplification could not alter or generalize stakeholder responsibilities incorrectly.
**Terminology:** Learners encounter numerous specialized acronyms and EBP names.
**Authoring environment:** The course was developed without access to Storyline or Rise, requiring a custom web-based solution.

#### Development Note

This work sample was built as a custom web-based microlearning because I did not have access to **Articulate Storyline** during development. With Storyline and a fuller production environment, I could recreate the same instructional architecture with richer interactions and animation options, LMS tracking, and SCORM/xAPI publishing. The custom web approach demonstrates the ability to design and develop the experience independently of a specific authoring platform.

### Complexity

The greatest complexity was not technical interaction—it was content architecture.
The source contains:

- four stakeholder perspectives
- multiple EBPs
- different quality-review pathways
- multiple implementation processes
- responsibilities that sometimes vary by EBP group

The primary design challenges were:

1. Simplifying without distorting the source
2. Prioritizing content within a five-minute constraint
3. Making a high-acronym environment understandable
4. Creating an experience that remained accessible and usable

### Recommended Job Aid

A logical companion resource would be a one-page EBP Implementation Roles Quick Reference.
The microlearning answers:

> How do the roles work together?

The job aid would answer:

> Who do I contact for this specific implementation need?

The job aid could organize the four stakeholder groups across the full implementation lifecycle:

- Implementation planning
- Training
- Technical assistance
- Quality / fidelity
- Data collection
- Service delivery
- Payment and policy

Each cell would contain a concise responsibility statement and link back to the official DHCS resource.
This would provide performance support after training without increasing the duration or cognitive load of the microlearning.

### Potential Future Enhancements

For a production implementation, next steps could include:

- downloadable job aid
- additional role-based scenarios
- LMS / SCORM or xAPI integration
- completion tracking and analytics
- learner usability testing
- formal screen-reader testing
- periodic review as DHCS guidance changes

### Design Rationale

The core design principle was clarity over comprehensiveness.
The microlearning does not attempt to replace the DHCS resource. Instead, it gives learners a concise framework for understanding the stakeholder system, recognizing key differences, and knowing where to look or whom to involve next.
## Source

California Department of Health Care Services  
**BH-CONNECT and BHSA EBP Requirements & Key Roles**

https://bhcoe.dhcs.ca.gov/resources/bh-connect-bhsa-ebp-requirements-key-roles/

---

**Designed and developed by Shabnam Goli, PhD** | [Portfolio](https://www.shabnamgoli.com/)
