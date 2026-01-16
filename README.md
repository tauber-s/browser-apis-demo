# Browser APIs – Demo Examples

This repository contains **minimal and focused demo examples** of major **Browser API groups**, created to support a short technical presentation about how JavaScript interacts with the browser runtime.

The goal is **conceptual clarity**, not production-ready code.

---

## Purpose

- Demonstrate how different **browser subsystems** are exposed through APIs
- Highlight the distinction between **JavaScript (language)** and **Browser APIs (environment)**
- Provide runnable, easy-to-understand examples
- Support a **5-minute technical presentation**

---

## What Are Browser APIs?

Browser APIs are **interfaces exposed by the browser runtime**, not part of the JavaScript language itself.

They allow JavaScript to:
- Manipulate the rendered document
- Perform network requests
- Persist data locally
- Access device capabilities
- Render graphics

Each API represents a boundary between JavaScript and native browser functionality.

---

## Demo Overview

### DOM API – UI & Rendering

- Demonstrates direct manipulation of the document
- Shows how JavaScript interacts with the rendering engine

**Key concepts:**
- Event listeners
- DOM tree updates
- UI re-rendering

---

### Networking API – Fetch

- Performs an HTTP request using the Fetch API
- Illustrates asynchronous browser-managed networking

**Key concepts:**
- Promises
- Browser networking stack
- CORS and async execution

---

### Storage API – Web Storage

- Uses `localStorage` for key-value persistence
- Demonstrates synchronous client-side storage

**Key concepts:**
- Persistence across page reloads
- Storage limits and constraints
- Sync API trade-offs

---

### Device & Hardware API – Geolocation

- Requests the user’s geographic position
- Shows permission-based access

**Key concepts:**
- Security sandbox
- User consent
- Error handling for denied permissions

---

### Graphics API – Canvas

- Uses the Canvas API for low-level drawing
- Demonstrates immediate-mode rendering

**Key concepts:**
- 2D rendering context
- Manual drawing lifecycle
- Performance vs control trade-off

---

## Important Notes

- Some demos require **HTTPS** or **user permission** (e.g., Geolocation)
- Browser support may vary slightly across engines
- These examples are intentionally minimal

---