# Mini Component Library (Pure CSS)

This project is a simple UI component library built with pure HTML and CSS.
It was created using an AI-assisted workflow, with a focus on clarity,
simplicity, and documenting decision-making.

Components are demonstrated in a single HTML page and styled using
reusable CSS classes.

## Components

Buttons:

```html
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-disabled" disabled>Disabled</button>

INPUTS (HTML):
<input class="input" placeholder="Normal input" />
<input class="input input-error" placeholder="Input with error" />

CARD (HTML):
<div class="card">
  <div class="card-title">Card Title</div>
  <div class="card-body">Card content</div>
</div>

BADGES (HTML):
<span class="badge">New</span>

ALERT(HTML):
<div class="alert">This is an alert message</div>

NAVBAR (HTML):
<div class="navbar">
  <div>My Library</div>
  <div>
    <a href="#">Home</a>
    <a href="#">About</a>
  </div>
</div>

MODAL (HTML):
<div class="modal-overlay">
  <div class="modal">Modal content</div>
</div>

NOTES: - All components are styled using pure CSS - No JavaScript is used in
this project - The modal is static and demonstrates styling only - AI usage and
decisions are documented in PROMPTLOG.md
```

- Modal uses a softened overlay to maintain background clarity and reduce visual fatigue.
