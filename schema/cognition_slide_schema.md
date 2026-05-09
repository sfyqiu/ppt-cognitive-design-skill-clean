```markdown
# Cognition Slide Schema System

## Purpose

This document defines the AI-native cognition slide schema used by the presentation cognition system.

The objective is NOT:
visual coordinate encoding.

The objective IS:
communication cognition encoding.

Traditional slide schemas describe:

- positions
- dimensions
- visual objects

This system describes:

- communication intent
- hierarchy behavior
- audience cognition
- mechanism structure
- semantic meaning
- visual reasoning behavior

The schema exists to ensure:

rendering follows cognition,
NOT manual layout instructions.

---

# Core Schema Philosophy

Traditional presentation schemas operate as:

```text
objects
↓
coordinates
↓
rendering
```

This cognition schema operates as:

```text
communication intent
↓
hierarchy cognition
↓
semantic structure
↓
visual reasoning
↓
adaptive rendering
```

The schema should encode:

why the slide exists,
NOT only what objects appear.

---

# Global Cognition Structure

Every slide schema should preserve:

```text
Communication Goal
↓
Audience Cognition
↓
Slide Type
↓
Hierarchy Structure
↓
Dominant Visual
↓
Semantic Behavior
↓
Mechanism / Concept Logic
↓
Density Regulation
↓
Takeaway
↓
Rendering Constraints
```

The schema becomes:

the intermediate cognition language
between planning and rendering.

---

# Core Schema Structure

Every cognition slide schema should contain:

```yaml
slide_id:
slide_type:
communication_goal:
audience:
dominant_workflow:
dominant_skill:
active_style:
hierarchy:
dominant_visual:
reading_flow:
semantic_behavior:
density:
mechanism_flow:
content_blocks:
takeaway:
rendering_behavior:
evaluation_rules:
```

The schema must preserve:

communication reasoning.

---

# Stage 1 — Slide Identity

## slide_id

Purpose:

uniquely identify slide cognition state.

Example:

```yaml
slide_id: slide_04_mechanism
```

---

## slide_type

Purpose:

define communication category.

Possible values:

- mechanism_explanation
- teaching_concept
- framework_overview
- comparison
- evidence_validation
- summary
- institutional_positioning

Example:

```yaml
slide_type: mechanism_explanation
```

Slide type determines:

execution behavior.

---

# Stage 2 — Communication Cognition

## communication_goal

Purpose:

define the core communication objective.

Example:

```yaml
communication_goal:
  explain_how_membrane_irrigation_stabilizes_rhizosphere_microenvironment
```

The goal should describe:

communication intention,
NOT visual layout.

---

## audience

Purpose:

define audience cognition requirements.

Possible values:

- undergraduate_students
- graduate_students
- researchers
- faculty_committee
- interdisciplinary_audience

Example:

```yaml
audience:
  researchers_and_graduate_students
```

Audience regulates:

density and abstraction.

---

# Stage 3 — Workflow Cognition

## dominant_workflow

Purpose:

define orchestration behavior.

Possible values:

- academic_workflow
- teaching_workflow
- interview_workflow
- revision_workflow

Example:

```yaml
dominant_workflow:
  academic_workflow
```

---

## dominant_skill

Purpose:

define behavioral personality.

Possible values:

- academic_skill
- teaching_skill
- interview_skill

Example:

```yaml
dominant_skill:
  academic_skill
```

Skills regulate:

communication tone.

---

## active_style

Purpose:

define editorial atmosphere.

Possible values:

- sci_top_journal
- faculty_interview
- teaching_clean

Example:

```yaml
active_style:
  sci_top_journal
```

Styles regulate:

visual atmosphere stability.

---

# Stage 4 — Hierarchy Cognition

## hierarchy

Purpose:

define visual communication priority.

Example:

```yaml
hierarchy:
  primary:
    mechanism_chain

  secondary:
    supporting_evidence

  tertiary:
    annotations
```

The schema should encode:

attention order,
NOT coordinates.

---

## dominant_visual

Purpose:

define the primary visual anchor.

Possible values:

- central_causal_chain
- comparison_framework
- annotated_diagram
- conceptual_process
- grouped_evidence
- institutional_framework

Example:

```yaml
dominant_visual:
  central_causal_chain
```

The dominant visual controls:

reading behavior.

---

## reading_flow

Purpose:

define audience eye movement.

Possible values:

- top_to_bottom
- left_to_right
- center_outward
- radial
- progressive_steps

Example:

```yaml
reading_flow:
  top_to_bottom
```

Rendering must obey:

reading cognition.

---

# Stage 5 — Semantic Cognition

## semantic_behavior

Purpose:

define semantic visual meaning.

Example:

```yaml
semantic_behavior:

  blue:
    science
    GIS
    water

  green:
    ecology
    agriculture
    vegetation

  orange:
    stress
    emphasis
```

Semantic colors communicate:

meaning,
NOT decoration.

---

# Stage 6 — Density Cognition

## density

Purpose:

define acceptable cognitive load.

Possible values:

- low
- medium
- high

Example:

```yaml
density:
  medium
```

Density regulates:

- annotation quantity
- evidence competition
- whitespace requirements
- mechanism complexity

---

# Stage 7 — Mechanism Cognition

## mechanism_flow

Purpose:

define causal communication structure.

Example:

```yaml
mechanism_flow:

  trigger:
    membrane_controlled_irrigation

  response:
    rhizosphere_moisture_stabilization

  interaction:
    microbial_activity_enhancement

  function:
    nitrogen_transformation_efficiency

  outcome:
    crop_growth_improvement
```

Mechanism structures should encode:

causal understanding.

---

# Stage 8 — Content Cognition

## content_blocks

Purpose:

define communication components.

Example:

```yaml
content_blocks:

  - type:
      mechanism_diagram

    priority:
      primary

  - type:
      evidence_chart

    priority:
      secondary

  - type:
      annotation

    priority:
      tertiary
```

The schema should describe:

communication roles,
NOT geometry.

---

# Stage 9 — Takeaway Cognition

## takeaway

Purpose:

define audience memory target.

Example:

```yaml
takeaway:
  stable_rhizosphere_microenvironments_improve_nitrogen_utilization_efficiency
```

Every slide must contain:

one dominant takeaway.

---

# Stage 10 — Rendering Cognition

## rendering_behavior

Purpose:

define renderer cognition constraints.

Example:

```yaml
rendering_behavior:

  spacing:
    relaxed_editorial

  hierarchy:
    dominant_mechanism

  annotation_behavior:
    restrained

  evidence_behavior:
    supportive_not_competitive
```

Rendering must preserve:

communication hierarchy.

---

# Stage 11 — Evaluation Cognition

## evaluation_rules

Purpose:

define cognition validation behavior.

Example:

```yaml
evaluation_rules:

  - hierarchy_clarity
  - mechanism_readability
  - density_control
  - audience_accessibility
  - editorial_stability
```

The slide should be evaluated through:

communication quality.

---

# Full Cognition Slide Schema Example

```yaml
slide_id:
  slide_04_mechanism

slide_type:
  mechanism_explanation

communication_goal:
  explain_how_membrane_irrigation_stabilizes_rhizosphere_microenvironment

audience:
  researchers_and_graduate_students

dominant_workflow:
  academic_workflow

dominant_skill:
  academic_skill

active_style:
  sci_top_journal

hierarchy:

  primary:
    mechanism_chain

  secondary:
    supporting_evidence

  tertiary:
    annotations

dominant_visual:
  central_causal_chain

reading_flow:
  top_to_bottom

semantic_behavior:

  blue:
    science
    water
    GIS

  green:
    agriculture
    rhizosphere
    ecology

  orange:
    stress
    emphasis

density:
  medium

mechanism_flow:

  trigger:
    membrane_controlled_irrigation

  response:
    rhizosphere_moisture_stabilization

  interaction:
    microbial_activity_enhancement

  function:
    nitrogen_transformation_efficiency

  outcome:
    crop_growth_improvement

content_blocks:

  - type:
      mechanism_diagram

    priority:
      primary

  - type:
      evidence_chart

    priority:
      secondary

  - type:
      annotation

    priority:
      tertiary

takeaway:
  stable_rhizosphere_microenvironments_improve_nitrogen_utilization_efficiency

rendering_behavior:

  spacing:
    relaxed_editorial

  hierarchy:
    dominant_mechanism

  annotation_behavior:
    restrained

  evidence_behavior:
    supportive_not_competitive

evaluation_rules:

  - hierarchy_clarity
  - mechanism_readability
  - density_control
  - audience_accessibility
  - editorial_stability
```

---

# Anti-AI-Slop Schema Rules

The schema must actively prevent:

- coordinate-first thinking
- infographic contamination
- equal-weight layouts
- startup visual structures
- SaaS dashboard aesthetics
- decorative rendering escalation

The schema should encode:

communication cognition,
NOT GUI positioning.

---

# Final Validation

Before schema execution:

Check:

- Does the schema encode communication intent?
- Is hierarchy cognition preserved?
- Is audience adaptation encoded?
- Does the schema support mechanism readability?
- Does rendering remain subordinate to cognition?
- Does the schema preserve presentation identity?

If NO:

refine cognition structure before rendering.

---

# System Identity

This schema system is NOT:

a layout schema.

It IS:

an AI-native cognition communication schema.

---

# Final Philosophy

A cognition slide schema is NOT:
a visual coordinate system.

It IS:

an intermediate cognition language
for communication-oriented presentation execution.
```
