# Cognition-to-JSON Mapping System

## Purpose

This document defines how cognition reasoning is translated into executable rendering JSON inside the AI-native presentation cognition system.

The objective is NOT:
content serialization.

The objective IS:
communication cognition encoding.

Traditional systems convert:

```text
content
↓
layout json
```

This system converts:

```text
communication cognition
↓
hierarchy reasoning
↓
semantic behavior
↓
audience adaptation
↓
mechanism structure
↓
adaptive rendering json
```

The cognition-to-JSON mapping exists to ensure:

rendering JSON remains:

communication-aware,
NOT coordinate-driven.

---

# Core Mapping Philosophy

JSON should NOT represent:

visual objects only.

JSON SHOULD represent:

communication cognition structures.

The system should ask:

```text
What cognition behavior must survive rendering?
```

NOT:

```text
Where should boxes be placed?
```

Rendering JSON should encode:

- hierarchy
- meaning
- reading flow
- mechanism visibility
- density behavior
- audience cognition
- refinement continuity

---

# Global Cognition-to-JSON Flow

The runtime executes:

```text
Cognition Plan
↓
Slide Blueprint
↓
Workflow Coordination
↓
Hierarchy Encoding
↓
Mechanism Encoding
↓
Semantic Encoding
↓
Adaptive Layout Encoding
↓
Rendering JSON Construction
↓
Renderer Execution
```

JSON becomes:

the executable cognition layer.

---

# Core Mapping Schema

Every cognition-to-JSON mapping should regulate:

```yaml
communication_goal_mapping:
workflow_mapping:
audience_mapping:
hierarchy_mapping:
reading_flow_mapping:
mechanism_mapping:
semantic_mapping:
density_mapping:
layout_mapping:
renderer_mapping:
evaluation_mapping:
```

The mapping system should encode:

communication cognition behavior.

---

# Stage 1 — Communication Goal Mapping

## communication_goal_mapping

### Objective

Translate communication objectives into rendering intent.

Example cognition:

```yaml
communication_goal:
  explain_how_salt_stress_reduces_root_water_uptake
```

Mapped JSON:

```json
{
  "communication_goal":
    "Explain how salt stress reduces root water uptake",

  "rendering_priority":
    "mechanism_readability"
}
```

Communication goals regulate:

all downstream rendering behavior.

---

# Stage 2 — Workflow Mapping

## workflow_mapping

### Objective

Translate workflows into rendering coordination behavior.

Example cognition:

```yaml
primary_workflow:
  teaching_workflow
```

Mapped JSON:

```json
{
  "workflow_behavior": {
    "mode": "teaching_guided",
    "visual_guidance": "strong",
    "density": "low"
  }
}
```

Workflows regulate:

rendering personality.

---

# Stage 3 — Audience Mapping

## audience_mapping

### Objective

Translate audience cognition into accessibility behavior.

Example cognition:

```yaml
audience:
  undergraduate_students
```

Mapped JSON:

```json
{
  "audience": {
    "type": "undergraduate_students",
    "diagram_priority": "high",
    "terminology_complexity": "low"
  }
}
```

Audience mapping regulates:

interpretation accessibility.

---

# Stage 4 — Hierarchy Mapping

## hierarchy_mapping

### Objective

Translate hierarchy reasoning into attention structures.

Example cognition:

```yaml
dominant_focus:
  mechanism_chain
```

Mapped JSON:

```json
{
  "hierarchy": {
    "dominant_focus": "mechanism_chain",
    "secondary_focus": "supporting_annotations",
    "focus_separation": "strong"
  }
}
```

Hierarchy mapping regulates:

attention orchestration.

---

# Stage 5 — Reading Flow Mapping

## reading_flow_mapping

### Objective

Translate cognition progression into navigation structures.

Example cognition:

```yaml
reading_flow:
  progressive_top_to_bottom
```

Mapped JSON:

```json
{
  "reading_flow": {
    "direction": "top_to_bottom",
    "progression": "guided",
    "navigation_strength": "high"
  }
}
```

Reading flow mapping regulates:

interpretation sequencing.

---

# Stage 6 — Mechanism Mapping

## mechanism_mapping

### Objective

Translate causal reasoning into mechanism structures.

Example cognition:

```yaml
mechanism_structure:

  trigger:
    salt_stress

  response:
    osmotic_pressure_increase

  outcome:
    reduced_water_uptake
```

Mapped JSON:

```json
{
  "mechanism_structure": {
    "trigger": "salt_stress",
    "response": "osmotic_pressure_increase",
    "outcome": "reduced_water_uptake",

    "directional_visibility": "strong"
  }
}
```

Mechanism mapping regulates:

scientific interpretability.

---

# Stage 7 — Semantic Mapping

## semantic_mapping

### Objective

Translate semantic meaning into rendering systems.

Example cognition:

```yaml
semantic_behavior:

  green:
    agriculture

  orange:
    stress
```

Mapped JSON:

```json
{
  "semantic_system": {
    "green": ["agriculture"],
    "orange": ["stress"]
  }
}
```

Semantic mapping regulates:

meaning-oriented rendering.

---

# Stage 8 — Density Mapping

## density_mapping

### Objective

Translate cognition load reasoning into layout density behavior.

Example cognition:

```yaml
density_behavior:
  restrained_annotations
```

Mapped JSON:

```json
{
  "density_control": {
    "annotation_density": "low",
    "whitespace_priority": "high"
  }
}
```

Density mapping regulates:

cognitive comfort.

---

# Stage 9 — Layout Mapping

## layout_mapping

### Objective

Translate cognition hierarchy into spatial orchestration.

Example cognition:

```yaml
layout_mode:
  mechanism_centered
```

Mapped JSON:

```json
{
  "adaptive_layout": {
    "layout_mode": "mechanism_centered",
    "spacing_behavior": "editorial_relaxed",
    "focus_behavior": "centralized"
  }
}
```

Layout mapping regulates:

spatial cognition behavior.

---

# Stage 10 — Renderer Mapping

## renderer_mapping

### Objective

Translate cognition requirements into renderer coordination.

Example cognition:

```yaml
activate:
  - hierarchy_renderer
  - mechanism_renderer
```

Mapped JSON:

```json
{
  "renderer_coordination": {
    "activate": [
      "hierarchy_renderer",
      "mechanism_renderer"
    ],

    "rendering_style":
      "editorial_scientific"
  }
}
```

Renderer mapping regulates:

runtime execution behavior.

---

# Stage 11 — Evaluation Mapping

## evaluation_mapping

### Objective

Translate cognition goals into validation targets.

Example cognition:

```yaml
evaluation_targets:
  - hierarchy_clarity
  - mechanism_readability
```

Mapped JSON:

```json
{
  "evaluation_rules": [
    "hierarchy_clarity",
    "mechanism_readability"
  ]
}
```

Evaluation mapping regulates:

communication quality validation.

---

# Full Cognition-to-JSON Example

```yaml
cognition:

  communication_goal:
    explain_how_salt_stress_reduces_root_water_uptake

  audience:
    undergraduate_students

  dominant_focus:
    mechanism_chain

  density_behavior:
    restrained_annotations
```

↓

```json
{
  "communication_goal":
    "Explain how salt stress reduces root water uptake",

  "workflow_behavior": {
    "mode": "teaching_guided"
  },

  "audience": {
    "type": "undergraduate_students",
    "diagram_priority": "high"
  },

  "hierarchy": {
    "dominant_focus": "mechanism_chain"
  },

  "mechanism_structure": {
    "trigger": "salt_stress",
    "outcome": "reduced_water_uptake"
  },

  "density_control": {
    "annotation_density": "low"
  },

  "renderer_coordination": {
    "activate": [
      "hierarchy_renderer",
      "mechanism_renderer"
    ]
  },

  "evaluation_rules": [
    "hierarchy_clarity",
    "mechanism_readability"
  ]
}
```

---

# Cognition-to-JSON Rules

The mapping system must:

- preserve communication goals
- stabilize hierarchy reasoning
- encode semantic meaning
- preserve audience cognition
- regulate density behavior
- support adaptive layouts
- coordinate renderer execution

JSON should prioritize:

communication cognition.

---

# Anti-AI-Slop Mapping Rules

The system must actively prevent:

- coordinate-first serialization
- template-based encoding
- decorative rendering escalation
- infographic-style structures
- stateless rendering logic
- workflow fragmentation
- presentation identity collapse

The JSON should feel:

editorial,
adaptive,
and cognition-aware.

---

# Final Validation

Before JSON execution:

Check:

- Is communication intent preserved?
- Is hierarchy reasoning encoded?
- Is audience accessibility maintained?
- Is semantic meaning stable?
- Is density behavior controlled?
- Is rendering subordinate to cognition?
- Does the JSON feel cognition-oriented rather than coordinate-oriented?

If NO:

refine cognition encoding.

---

# System Identity

This cognition-to-JSON mapping is NOT:

content serialization.

It IS:

communication cognition execution encoding.

---

# Final Philosophy

Cognition-to-JSON mapping is NOT:
layout generation.

It IS:

communication cognition translation
for AI-native presentation systems.
