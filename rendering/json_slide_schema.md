# JSON Slide Schema Specification

This document defines the structured JSON schema system
for the PPT Cognitive Design Skill rendering engine.

The purpose of the schema system is to transform:

- cognitive reasoning
- narrative structure
- layout intelligence
- semantic visual mapping

into:

- machine-readable slide rendering instructions.

---

# Core Principle

The JSON schema acts as:

an intermediate representation layer

between:

AI reasoning

and

visual rendering.

---

# Rendering Pipeline

```text
User Requirement
    ↓
Presentation Reasoning
    ↓
Narrative Planning
    ↓
Slide JSON Schema
    ↓
Rendering Engine
    ↓
HTML / SVG / PPT Output
```

---

# Schema Objectives

The schema should:

- standardize slide structure
- separate reasoning from rendering
- support adaptive layouts
- support semantic rendering
- support future automation

---

# Core Slide Schema

Example:

```json
{
  "slide_type": "mechanism_flow",

  "title": "How Water Affects Crop Growth",

  "subtitle": "Mechanism-oriented teaching slide",

  "cognitive_objective":
    "Help students understand how water influences biomass and yield.",

  "layout": "horizontal_flow",

  "semantic_theme": {
    "water": "blue",
    "growth": "green",
    "stress": "orange"
  },

  "components": [

    {
      "type": "mechanism_box",
      "label": "Soil Water",
      "semantic_role": "water"
    },

    {
      "type": "arrow",
      "direction": "right"
    },

    {
      "type": "mechanism_box",
      "label": "Root Uptake",
      "semantic_role": "growth"
    },

    {
      "type": "arrow",
      "direction": "right"
    },

    {
      "type": "mechanism_box",
      "label": "Transpiration",
      "semantic_role": "stress"
    }

  ],

  "side_panel": {

    "type": "GIS_note",

    "title": "GIS Connection",

    "content":
      "Water stress varies spatially and can be monitored using GIS and remote sensing."
  },

  "bottom_note":
    "Understanding crop water mechanisms supports precision agriculture."
}
```

---

# Schema Layers

The rendering schema contains:

| Layer | Function |
|---|---|
| Narrative Layer | Meaning and explanation |
| Layout Layer | Positioning and spacing |
| Semantic Layer | Visual meaning |
| Rendering Layer | HTML/SVG generation |

---

# Supported Slide Types

## 1. Mechanism Flow

Used for:

- causal chains
- scientific explanation
- educational mechanism teaching

---

## 2. Workflow Slide

Used for:

- process explanation
- pipelines
- AI architecture

---

## 3. GIS Layer Slide

Used for:

- spatial information systems
- remote sensing workflows
- GIS integration explanation

---

## 4. Comparison Slide

Used for:

- before vs after
- traditional vs intelligent systems
- experimental comparison

---

## 5. Scientific Storytelling Slide

Used for:

- phenomenon explanation
- mechanism interpretation
- evidence progression

---

# Semantic Theme System

The schema should support semantic color mapping.

Example:

```json
{
  "semantic_theme": {
    "water": "#4A90E2",
    "growth": "#43A047",
    "stress": "#FB8C00",
    "neutral": "#90A4AE"
  }
}
```

---

# Layout Schema

The schema should define:

- component priority
- visual hierarchy
- spacing rules
- reading direction
- alignment behavior

Example:

```json
{
  "layout_rules": {
    "reading_path": "left_to_right",
    "primary_focus": "mechanism_flow",
    "side_panel_position": "top_right",
    "collision_strategy": "adaptive_spacing"
  }
}
```

---

# Rendering Component Types

Supported component types:

```text
title
subtitle
mechanism_box
workflow_node
arrow
icon
diagram
GIS_panel
bottom_note
highlight_text
legend
```

---

# Cognitive Rendering Rules

The schema should support:

- low cognitive density
- progressive disclosure
- semantic grouping
- hierarchy clarity
- audience-aware rendering

---

# Adaptive Rendering Goal

Future rendering engine capabilities:

- automatic layout balancing
- responsive rendering
- semantic diagram generation
- audience-adaptive rendering
- AI-controlled whitespace optimization

---

# Future Output Targets

The schema should eventually support rendering into:

```text
HTML
SVG
PPTX
Figma
Canvas
Interactive Slides
```

---

# Long-term Vision

The JSON schema system enables:

AI-native presentation generation.

The AI system should eventually generate:

- complete slide structures
- semantic visual systems
- adaptive layouts
- executable presentation pages

without manual layout construction.

---

# Final Principle

The schema should represent:

communication intelligence

rather than:

visual decoration instructions.
