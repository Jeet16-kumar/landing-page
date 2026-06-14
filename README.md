Module 02: Avant-Garde Commerce Landing Engine - Technical Registry

An immersive digital art-piece market interface designed explicitly around the avant-garde editorial aesthetics of high-fashion print campaigns. Engineered for a curated handmade artifacts market, it trades traditional, blocky templates for an expansive cinematic split-pane, full-bleed imagery, and single-page page-routing simulation paths.

---

Technical Specifications & Architecture

1. Dual-Split Horizontal Screen Grid
* Asymmetric Desktop Split: Divides viewports down the center using CSS Grid layout configurations (grid-template-columns: 1.1fr 1fr;). 
* Sticky Display Mural: The left panel locks visual campaign murals directly into a sticky display port (position: sticky; top: 65px; h: calc(100vh - 65px);), serving as an atmospheric visual baseline anchor while the user scrolls down through content on the right side.
* Safe Absolute Background Layering: Background graphics operate strictly on independent Z-index values (z-index: 1) behind content text structures (z-index: 5) to completely eliminate overflow crowding and text clipping hazards on narrow breakpoints.

2. Single-Page Multi-Route Simulation Engine
 Lag-Free Page Switching: Built using a client-side layout token routing script that smoothly maps navigation tabs to dedicated view sections (Home Campaign, Ceramics Page, Textiles Collection, Apothecary Manifest*).
* Fluid Transitions: Swapping sections replaces the active container panel instantly, applying opacity transformations (transition: opacity 0.5s ease) and slight vertical translations without triggering browser page-reloads.

3. High-Contrast Interactive Visuals
* Cinematic Lightbox Overlays: Card nodes trigger a full-screen image lightbox portal mapping target attributes dynamically via native JavaScript strings.
* Luminosity Hover Shifts: Product preview windows apply custom filter transitions (filter: grayscale(100%) contrast(115%); transition: transform 0.6s cubic-bezier(0.25, 1, 0.5, 1);), shifting elements cleanly to full color and scale on mouse hovers.

---

File Registry & Implementation Blueprint

To review or compile this design asset locally, ensure your index.html file matches this structural outline:

``html
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>STUDIO KRAFT / SPOTLIGHT &mdash; Independent Artifacts Market</title>
 <!-- Embedding: Core CSS Spotlight Palette, Inverted Layout Splits, Image Zoom Mechanics -->
</head>
<body>
 <!-- Campaign Top Sticky Navigation & Channel View Switches -->
 <!-- Page View Container 01: Core Brand Manifesto & Asymmetric Splits -->
 <!-- Page View Container 02: Ceramics Collection Product Catalog Grid -->
 <!-- Page View Container 03: Textile Collection High-Contrast Product Grid -->
 <!-- Page View Container 04: Apothecary Extract Product Lab Grid -->
 <!-- Cinematic Lightbox Modal Portal Overlay Layer -->
 <!-- Extra-Long Editorial Dispatch Newsletter Input Footer -->
 <!-- JavaScript Navigation Router & Lightbox Injection Engine Script -->
</body>
</html>
``

youtube link:- https://youtu.be/GKUh-4oXG84
