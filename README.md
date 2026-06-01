# Pocket Touch

![License](https://img.shields.io/badge/license-MIT-black)
![Status](https://img.shields.io/badge/status-active-white)
![Version](https://img.shields.io/badge/version-0.1.1-black)
![Built With](https://img.shields.io/badge/built%20with-Vite-646CFF)

A lightweight physics-based interaction framework for building bottom sheets, swipe cards, gesture-driven interfaces, and motion-rich app-like web experiences across phones, tablets, and desktops.

Built for modern interaction design.

Built for modern interaction design.

---

# Why Pocket Touch

Most web UI frameworks are still designed around desktop interaction patterns.

Pocket Touch is built differently.

Pocket Touch focuses on:
- touch-first interaction
- gesture-driven interfaces
- physics-based motion systems
- app-like navigation patterns
- spring-based animations
- momentum-driven movement
- elastic natural interactions
- mobile-native UX patterns
- lightweight interaction primitives
- modern fluid web experiences

The goal is simple:

Build interfaces that feel physically real, responsive, and alive.

---

# Current Features (Interaction System)

- Bottom sheets
- Swipe cards
- Modals
- Toasts
- Pull to refresh
- Tabs
- Tab bar
- Action sheet
- Motion UI demos
- Animated interactions
- Pointer-event interactions
- Gesture recognition system
- Velocity tracking engine
- Spring physics system
- Momentum movement
- Rubber banding
- Overscroll resistance
- Drag physics engine
- Persistent transform state system
- Mobile-first primitives
- Lightweight architecture
- CDN support
- Framework agnostic
- ESM/CommonJS builds
- TypeScript definitions

---

# Motion Engine

Pocket Touch includes a lightweight physics-based motion engine for creating native-feeling interactions.

Core APIs:

```js
Pocket.animate()
Pocket.spring()
Pocket.motion()
Pocket.drag()
```

Motion system supports:

- velocity tracking
- spring animations
- drag gestures
- momentum movement
- rubber banding
- overscroll resistance
- persistent transform state
- elastic boundaries

Example:

```js
Pocket.drag(card, {
  axis: 'x',
  momentum: true,
  snapBack: true,
  min: -160,
  max: 160,
  resistance: 0.28,
  friction: 0.92,
  damping: 18,
  stiffness: 180
})
```

Core interaction chain:

```text
drag → velocity → momentum → spring → settle
```

---

# Runnable Examples

Pocket Touch includes runnable examples for:

```text
examples/
  motion-ui/
  bottom-sheet/
  swipe-cards/
  gesture-lab/
  music-player/
```

These examples demonstrate:

- motion systems
- gesture handling
- drag physics
- spring interactions
- touch-first UI patterns
- physics-based motion systems
- gesture handling patterns
- drag and swipe interactions
- spring-based animations
- touch-first UI design patterns

---

# Installation

## NPM

```bash
npm install pocket-touch
```

## CDN

```html
<script src="https://cdn.jsdelivr.net/npm/pocket-touch/dist/pocket.iife.js"></script>
```

---

# Quick Example

```html
<div id="swipeDemo"></div>

<script src="https://cdn.jsdelivr.net/npm/pocket-touch/dist/pocket.iife.js"></script>

<script>
  Pocket.createSwipeCards({
    container: '#swipeDemo',
    cards: [
      {
        content: '<h2>Sheets</h2><p>Panels with depth and movement.</p>'
      },
      {
        content: '<h2>Cards</h2><p>Swipe interactions for modern interfaces.</p>'
      }
    ]
  });
</script>
```

---

# Motion Example

```js
Pocket.drag(card, {
  axis: 'x',
  momentum: true,
  snapBack: true,
  min: -160,
  max: 160,
  resistance: 0.28
})
```

---

# Roadmap

Completed:

- Core interaction primitives
- RAF motion engine
- Spring physics
- Velocity tracking
- Momentum decay
- Drag gestures
- Rubber banding
- Overscroll resistance
- Motion UI examples

Next:

- Snap points
- Gesture thresholds
- Shared motion primitives
- Sheet physics
- Timeline API
- Cinematic interaction choreography

---

# Philosophy

Pocket Touch is built around one principle:

The future of the web is touch-first and physics-driven.

Interfaces should not feel static or digital.

They should feel like real objects with:
- weight
- resistance
- momentum
- natural motion
- 
Pocket Touch provides the primitives to build these experiences without heavy frameworks.

---

# Links

- GitHub: https://github.com/bimalprataps-ctrl/pocket-touch
- npm: https://www.npmjs.com/package/pocket-touch

---

# License

MIT
