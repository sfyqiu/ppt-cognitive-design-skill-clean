# JSON to HTML Rendering Engine

This document defines the automatic rendering engine
that converts structured JSON slide schemas into executable HTML presentation pages.

The rendering engine transforms:

- cognitive presentation reasoning
- narrative structures
- semantic layout definitions

into:

- visually rendered HTML slides.

---

# Core Rendering Principle

The rendering engine should NOT generate:

decorative visual chaos.

The rendering engine should generate:

- cognitively optimized layouts
- stable visual hierarchy
- semantic visual communication
- audience-centered slide rendering

---

# Rendering Pipeline

```text
User Requirement
    ↓
Presentation Reasoning
    ↓
Slide JSON Schema
    ↓
Layout Engine
    ↓
Component Renderer
    ↓
Semantic Styling Engine
    ↓
HTML Slide Output
```

---

# Rendering Engine Objectives

The engine must:

- parse slide schemas
- identify layout types
- render semantic components
- apply cognitive spacing
- apply visual hierarchy
- generate readable HTML slides

---

# Input Schema Example

```json
{
  "slide_type": "mechanism_flow",

  "title": "How Water Affects Crop Growth",

  "layout": "horizontal_flow",

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
    }

  ]
}
```

---

# Rendering Process

## Step 1 — Parse JSON

The engine reads:

- slide type
- layout type
- semantic theme
- components
- hierarchy rules

---

## Step 2 — Select Layout Engine

Examples:

| Layout Type | Rendering Strategy |
|---|---|
| horizontal_flow | flex horizontal layout |
| center_focus | centered diagram |
| comparison | two-column layout |
| GIS_layer | stacked layer layout |

---

## Step 3 — Render Components

The renderer converts components into HTML elements.

Example:

```json
{
  "type":"mechanism_box",
  "label":"Soil Water",
  "semantic_role":"water"
}
```

↓

```html
<div class=\"box water\">
    Soil Water
</div>
```

---

# Semantic Rendering System

## Semantic Role Mapping

| Semantic Role | CSS Class |
|---|---|
| water | blue |
| growth | green |
| stress | orange |
| neutral | gray |

---

# Layout Rendering Rules

## Horizontal Flow Layout

Rules:

- left-to-right reading path
- stable spacing
- centered alignment
- responsive arrows

---

## Side Panel Rendering

Rules:

- maximum 20% width
- reduced hierarchy
- peripheral placement
- non-blocking layout

---

# Component Rendering Rules

## Title Rendering

```html
<div class=\"title\">
    Slide Title
</div>
```

---

## Mechanism Box Rendering

```html
<div class=\"box growth\">
    Biomass
</div>
```

---

## Arrow Rendering

```html
<div class=\"arrow\">
    →
</div>
```

---

## GIS Panel Rendering

```html
<div class=\"gis-panel\">
    ...
</div>
```

---

# Rendering Hierarchy System

Priority levels:

| Level | Meaning |
|---|---|
| P1 | Primary focus |
| P2 | Secondary support |
| P3 | Peripheral information |

---

# Rendering Constraints

The engine must avoid:

- overlap
- edge overflow
- excessive density
- hierarchy collapse
- competing focal points

---

# Adaptive Rendering Logic

If layout overflow occurs:

```text
1. reduce spacing
2. resize low-priority elements
3. reposition side panels
4. compress secondary regions
```

---

# Cognitive Rendering Rules

The renderer should optimize:

- readability
- audience attention
- explanation pacing
- cognitive simplicity
- semantic grouping

---

# HTML Output Goal

The engine should automatically generate:

```text
- complete HTML slides
- semantic CSS structure
- SVG-compatible layouts
- responsive visual hierarchy
```

---

# Future Output Targets

Future rendering targets:

```text
HTML
SVG
PPTX
Canvas
Figma
Interactive Presentation Systems
```

---

# Future Automation Goal

Future AI rendering workflow:

```text
User:
\"Generate a teaching slide about crop water stress.\"

AI:
- builds JSON schema
- selects layout
- maps semantic colors
- renders HTML
- exports presentation page
```

---

# Long-term Vision

The rendering engine evolves toward:

an autonomous AI presentation generation system.

---

# Final Principle

The rendering engine succeeds when:

complex information becomes visually understandable
with minimal cognitive burden.
