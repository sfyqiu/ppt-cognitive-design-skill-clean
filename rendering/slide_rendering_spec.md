# Slide Rendering Specification

This document defines how the PPT Cognitive Design Skill framework renders visually structured presentation slides.

The rendering layer converts:

- cognitive reasoning
- narrative planning
- layout strategy
- semantic visual mapping

into:

- executable visual slide layouts.

---

# Core Rendering Philosophy

Rendering is NOT decoration.

Rendering is:

- cognitive communication
- visual hierarchy construction
- semantic information organization
- audience attention guidance

The renderer should prioritize:

audience understanding efficiency.

---

# Rendering Pipeline

```text
User Requirement
    ↓
Presentation Reasoning
    ↓
Slide Structure Planning
    ↓
Layout Selection
    ↓
Visual Semantic Mapping
    ↓
Rendering Specification
    ↓
HTML/SVG Slide Output
```

---

# Slide Rendering Objective

Each rendered slide should contain:

- one primary cognitive objective
- one dominant focal point
- one stable visual hierarchy
- one optimized reading path

---

# Rendering Principles

## 1. Hierarchy First

The renderer must establish:

- primary focus
- secondary information
- supporting details

Avoid:

- equal visual emphasis
- crowded layouts
- competing focal points

---

## 2. Cognitive Simplicity

The renderer should reduce:

- visual overload
- excessive text
- diagram complexity
- unnecessary decoration

The renderer should increase:

- whitespace
- visual grouping
- directional guidance
- progressive explanation

---

## 3. Semantic Visual Mapping

Visual style must communicate meaning.

Examples:

| Meaning | Color |
|---|---|
| Water | Blue |
| Crop Growth | Green |
| Stress | Orange |
| Neutral Systems | Gray |
| Scientific Emphasis | Dark Blue |

---

# Slide Canvas Specification

## Default Slide Ratio

```text
16:9
```

---

## Recommended Canvas Size

```text
1600 × 900 px
```

---

# Layout System

## Supported Layout Types

### 1. Center-focus Layout

Used for:

- key concepts
- important diagrams
- teaching explanations

---

### 2. Horizontal Mechanism Flow

Used for:

- causal chains
- workflows
- process explanations

Example:

```text
Soil Water
    →
Root Uptake
    →
Transpiration
    →
Biomass
    →
Yield
```

---

### 3. Comparison Layout

Used for:

- before vs after
- traditional vs intelligent systems
- problem vs solution

---

### 4. Layered GIS Layout

Used for:

- GIS reasoning
- multi-layer data integration
- spatial information explanation

---

### 5. Modular Layout

Used for:

- multiple independent concepts
- agent systems
- framework architecture

---

# Typography System

## Title

Recommended:

```text
40–52 px
```

Characteristics:

- bold
- high contrast
- concise

---

## Subtitle

Recommended:

```text
24–30 px
```

---

## Body Text

Recommended:

```text
18–24 px
```

Rules:

- short sentences
- maximum readability
- avoid dense paragraphs

---

# Spacing System

## Principle

Whitespace is part of cognition.

The renderer should maintain:

- stable margins
- consistent spacing
- visual breathing room

---

## Recommended Margins

```text
80–120 px
```

---

## Recommended Component Spacing

```text
24–48 px
```

---

# Diagram Rendering Rules

## Mechanism Diagrams

Should include:

- directional arrows
- semantic color mapping
- progressive flow
- minimal text

Avoid:

- scientific clutter
- equation-heavy visuals
- excessive annotations

---

## Arrow Rules

- blue arrows → water movement
- green arrows → growth progression
- orange arrows → stress interruption

---

# GIS Rendering Rules

GIS-related slides should include:

- layer structure
- spatial hierarchy
- clean legends
- readable overlays

Avoid:

- overloaded maps
- tiny labels
- excessive raster detail

---

# Cognitive Load Control

Each slide should explain:

ONE:

- mechanism
- concept
- relationship
- workflow
- comparison

Avoid:

- multi-topic slides
- simultaneous narratives
- visual competition

---

# Rendering Output Structure

The rendering engine should eventually generate:

```json
{
  "slide_type": "mechanism_flow",
  "title": "How Water Becomes Yield",
  "layout": "horizontal_flow",
  "components": [
    "title",
    "flow_diagram",
    "supporting_labels",
    "GIS_note"
  ],
  "semantic_colors": {
    "water": "blue",
    "growth": "green",
    "stress": "orange"
  }
}
```

---

# Rendering Technologies

## Initial Rendering Stack

```text
HTML
CSS
SVG
```

---

## Future Rendering Stack

```text
React
Tailwind
SVG Engine
PptxGenJS
Figma API
Canvas Rendering
```

---

# Interactive Rendering Goal

Future rendering interaction:

```text
User:
\"Reduce complexity.\"

AI:
- simplify layout
- reduce labels
- enlarge diagram
- increase whitespace
```

The renderer becomes:

an interactive presentation rendering agent.

---

# Rendering Quality Evaluation

Rendered slides should be evaluated by:

- cognitive clarity
- visual hierarchy
- audience readability
- semantic consistency
- presentation rhythm

NOT:

visual decoration quantity.

---

# Final Principle

Rendering succeeds when:

the audience understands complex ideas effortlessly.

Rendering fails when:

the audience becomes visually or cognitively overloaded.
