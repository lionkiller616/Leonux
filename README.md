# 🧠 Design Philosophy – Leonux

## Vision

Craft a **new visual language** that embraces minimalism, abstraction, softness, and comfort in interaction. The goal is to create a visually soothing, emotionally neutral interface with a **2D depth illusion**, **dark mode by default**, and **gentle micro-interactions** — all grounded in principles from **graphic design** and **modern UI/UX**.

---

## ✨ Core Principles

### 1. **Minimal**
- Every pixel has purpose.
- Avoid visual noise or unnecessary decoration.
- Reduce interface friction with focused interactions.

### 2. **Abstract**
- UI elements are symbolic and geometric.
- Avoid skeuomorphism — forms are functional and expressive, not literal.
- Shapes, layouts, and icons lean toward abstraction.

### 3. **Soft**
- Rounded corners on all elements (8–16px radii).
- No hard shadows — use soft, diffused shadows or ambient glow.
- Text and icons maintain optical smoothness and uniformity.

### 4. **2D Depth**
- Flat surfaces with layered illusions using blur, opacity, and color contrast.
- Blur-based separation instead of drop shadows.
- Avoid elevation stacks; prefer z-indexed layers.

### 5. **Dark by Default**
- Dark backgrounds reduce eye strain.
- Soft darks (#121212 to #1E1E1E) as base, no pure black.
- Light text on dark backgrounds using soft white (#EDEDED or lower).

### 6. **Soft Colors**
- Inspired by nature, atmosphere, and pastel palettes.
- Harmonized using contrast rules and accessibility guidelines.
- Primary + accent colors are gentle, not saturated.

### 7. **Typography**
- Font family: **Inter** (or custom minimal geometric sans-serif).
- Clear hierarchy: H1 to Caption, with consistent rhythm.
- Text emphasis through size, weight, and spacing — never boldness alone.

### 8. **Micro Animations**
- Subtle transitions: scale, opacity, shadow blur.
- Motion respects rhythm and user flow.
- Use `cubic-bezier` easing for natural feel:
  ```css
  transition: all 0.25s cubic-bezier(0.25, 0.8, 0.25, 1);
  ```

### 9. **Soft Blur**

* Use background blur (8px–16px) to create separation.
* Combine with transparency for frosted glass effect.
* Blur used for aesthetics *and* UX signaling (e.g., modal backdrops).

---

## 🔧 Implementation Guidelines

| Element        | Style Guide Summary                                               |
| -------------- | ----------------------------------------------------------------- |
| **Cards**      | Soft background, rounded corners, subtle shadow or blur           |
| **Buttons**    | Rounded, low-saturation color, hover glow or subtle shadow scale  |
| **Inputs**     | Flat style, soft border on focus, no hard outlines                |
| **Icons**      | Line-based, consistent weight, rounded caps                       |
| **Containers** | Padding-based structure, 2D layered depth                         |
| **Modals**     | Transparent background, blurred backdrop, soft entrance animation |

---

## 🎯 UX Goals

* Make users feel calm and focused.
* Remove digital harshness.
* Build visual trust through balance and restraint.
* Provide a timeless, modern experience for any application layer (OS, app, web, embedded UI).

---

## 🌌 Inspired By

* Material Design (grid & motion systems)
* macOS aesthetics (smoothness & blur)
* Deepin OS (abstract & soft elements)
* Bauhaus + Swiss design (graphic principles)
* Human-centered minimalism

---

## 🪪 Design Language Identity

**Name:** *Leonux*
**Tagline:** *“The Soft Edge of Simplicity”*
