# Website - Removed Sections (can restore later)

## Problem Section (removed 2026-02-08)
Was between the hero and "What We Do" services section. White background, two-column layout with typer animation and product image.

```html
<!-- Problem Section -->
<section class="problem">
  <div class="container">
    <div class="problem__content">
      <div class="problem__text">
        <h2>It starts with the part. It ends with <span id="typer-text"></span><span class="typer-cursor">|</span></h2>
        <p>The core of how we think is quickly.</p>
        <p>The core of what we offer is trust.</p>
      </div>
      <div class="problem__visual">
        <img src="assets/images/AdobeStock_501601066.jpeg" alt="Toroidal inductor on circuit board">
      </div>
    </div>
  </div>
</section>
```

CSS styles for `.problem`, `.problem__content`, `.problem__text`, `.problem__visual`, `.problem__typer` are still in styles.css.
JS typer animation is still in main.js (targets `#typer-text`, cycles through: 'partnership.', 'new ideas.', 'repeat orders.', 'a higher bar.').

## Industries We Serve Section (removed 2026-02-08)
Dark background, 3x2 grid. Heading: "Wherever the part matters, we belong."

```html
<section class="industries industries--dark">
  <div class="container">
    <div class="section-header section-header--center">
      <p class="section-label animate-on-scroll">Industries We Serve</p>
      <h2 class="section-title" style="color: #fff;">Wherever the part matters, we belong.</h2>
    </div>
    <div class="industries__grid">
      <div class="industries__item animate-on-scroll">
        <h3>Power & Energy</h3>
        <p>Power supplies, inverters, renewable energy systems. The backbone of the grid.</p>
      </div>
      <div class="industries__item animate-on-scroll">
        <h3>Medical Devices</h3>
        <p>Imaging equipment, patient monitors, surgical tools. Zero margin for error.</p>
      </div>
      <div class="industries__item animate-on-scroll">
        <h3>Aerospace & Defense</h3>
        <p>Avionics, guidance systems, satellite communications. Specs that don't bend.</p>
      </div>
      <div class="industries__item animate-on-scroll">
        <h3>Telecommunications</h3>
        <p>Signal filtering, base stations, networking hardware. Always on, always clean.</p>
      </div>
      <div class="industries__item animate-on-scroll">
        <h3>EV & Automotive</h3>
        <p>Charging infrastructure, onboard power, motor drives. The future runs on copper.</p>
      </div>
      <div class="industries__item animate-on-scroll">
        <h3>Industrial Automation</h3>
        <p>Robotics, PLCs, motion control. Machines that can't afford downtime.</p>
      </div>
    </div>
  </div>
</section>
```

CSS styles for `.industries--dark`, `.industries__grid`, `.industries__item` are still in styles.css.

## Process Section 4-item grid (removed 2026-02-08)
Was the 4-item grid (Clear Communication, Global Reach, Predictable Quality, Ownership Mentality) under "Partnership, not transactions." on homepage. Content moved to `learn-more.html` as expanded full page. The homepage now just shows the heading + "Learn More →" link.
