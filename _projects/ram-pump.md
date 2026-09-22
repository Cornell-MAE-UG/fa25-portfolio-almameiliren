---
layout: project
title: Hydraulic Ram Pump
description: 
technologies: []
image: assets/images/ram-pump/ram-pump.png
order: 1
---

<div class="ram-pump-intro">
  <div class="ram-pump-copy">
    <h3>AguaClara Vertical Ram Pump (ACVRP)</h3>
    <p>AguaClara Cornell develops gravity-powered water treatment technologies, delivering clean water to communities without reliable power. There are currently 26+ AguaClara plants serving 105,000+ people across 4 countries.</p>
    <p>Within these plants, one challenge had remained unsolved for 20 years: delivering treated water back up to the top of the facility for chemical dosing and plumbing support, without electricity.</p>
    <p>I led the design, testing, and field deployment of the AguaClara Vertical Ram Pump (ACVRP), a fluid-mechnical system that uses the water hammer effect and a spring-actuated dual check valve system to automatically pump water up in elevation without any electrcity.</p>
    <p>After two decades of development, my team achieved the first successful permanent field installations in January 2026, deploying pumps that lift water 5 meters at 3.33 L/min and 2 meters at 2.50 L/min at not one but two AguaClara plants in Honduras.</p>
  </div>

  <figure class="ram-pump-figure">
    <img
      class="ram-pump-hero"
      src="{{ '/assets/images/ram-pump/ram-pump.png' | relative_url }}"
      alt="AguaClara Vertical Ram Pump schematic"
    />
    <figcaption>Labeled CAD model of the field-scale ACVRP.</figcaption>
  </figure>
</div>

<style>
  .ram-pump-intro {
    display: flex;
    align-items: flex-start;
    gap: 1.5rem;
    margin: 1.5rem 0;
  }

  .ram-pump-copy {
    flex: 1 1 auto;
    min-width: 0;
  }

  .ram-pump-hero {
    display: block;
    width: auto;
    max-width: 320px;
    height: 475px; /* adjust this to change the image height */
    object-fit: cover;
    border-radius: 8px;
    flex-shrink: 0;
    margin: 0;
  }

  .ram-pump-report-button {
    display: inline-block;
    padding: 0.9rem 1.5rem;
    background-color: #3a5778;
    color: #ffffff;
    border-radius: 10px;
    text-decoration: none;
    font-weight: 600;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
    transition: background-color 0.3s ease, transform 0.3s ease, box-shadow 0.3s ease;
  }

  .ram-pump-report-button:hover {
    background-color: #2d425d;
    transform: translateY(-2px);
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.18);
  }

  .snifter-layout {
    --snifter-image-width: 360px;
    display: flex;
    align-items: center;
    gap: 1.5rem;
    margin: 1.5rem 0;
  }

  .snifter-copy {
    flex: 1 1 0;
    min-width: 0;
  }

  .snifter-figure {
    flex: 0 0 auto;
    width: var(--snifter-image-width);
    max-width: 100%;
    margin: 0;
  }

  .snifter-figure img {
    display: block;
    width: 100%;
    height: auto;
    border-radius: 8px;
  }

  .photo-marquee {
    position: relative;
    margin: 2rem 0 1rem;
    overflow: hidden;
    border-radius: 12px;
    background: rgba(58, 87, 120, 0.04);
    padding: 0.75rem 0;
  }

  .photo-marquee-track {
    display: flex;
    width: max-content;
    animation: photo-marquee 32s linear infinite;
    will-change: transform;
  }

  .photo-marquee:hover .photo-marquee-track {
    animation-play-state: paused;
  }

  .photo-marquee-item {
    flex: 0 0 auto;
    width: 220px;
    margin-right: 1rem;
    text-align: center;
  }

  .photo-marquee-item img {
    display: block;
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
  }

  .photo-marquee-item figcaption {
    margin-top: 0.4rem;
    font-size: 0.8rem;
    color: #555;
  }

  @keyframes photo-marquee {
    from {
      transform: translateX(0);
    }
    to {
      transform: translateX(-50%);
    }
  }

  @media (max-width: 768px) {
    .snifter-layout {
      flex-direction: column;
    }

    .snifter-figure {
      width: min(100%, 320px);
    }
  }
</style>


---
## Sub-Project: Snifter Valve

<div class="snifter-layout">
  <div class="snifter-copy">
    <p><strong>Objective:</strong> Automate air replenishment in the air chamber, which loses air over time to "waterlogging," degrading system efficiency and increasing structural stress.</p>
    
    <p><strong>Approach:</strong> Designed and tested two snifter valve configurations (weak-spring, no-spring), generating pump performance curves across a range of flow rates to quantify the efficiency tradeoff.</p>

    <p><strong>Results:</strong> Incorporation of a snifter valve with no internal spring resolves waterlogging without compromising system efficiency for typical operating head values (5-7 m).</p>
  </div>

  <figure class="snifter-figure">
    <a
      href="{{ 'assets/images/ram-pump/Ram Pump Final Poster Fall 2025.pptx.png' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Open snifter valve image in a new tab"
    >
      <img
        src="{{ 'assets/images/ram-pump/Ram Pump Final Poster Fall 2025.pptx.png' | relative_url }}"
        alt="Snifter valve schematic or pump illustration"
      />
    </a>
    <figcaption style="margin-top: 0.5rem; text-align: center; color: #555; font-size: 0.9rem;">
      Snifter valve performance comparison and design summary. (click to view)
    </figcaption>
  </figure>
</div>

<div style="text-align: center; margin: 2rem 0;">
  <a
    class="ram-pump-report-button"
    href="https://docs.google.com/document/d/1h0MfTRBt6UYLZksfVFfP3qivh-L5cSewN1GLPfwBg44/edit?usp=sharing"
    target="_blank"
    rel="noopener noreferrer"
  >
    Click here to view the full report
  </a>
</div>

---

## Sub-Project: Nonlinear Spring

<div class="snifter-layout">
  <div class="snifter-copy">
    <p><strong>Objective:</strong> lkhkjh</p>
    
    <p><strong>Approach:</strong> Designed and tested two snifter valve configurations (weak-spring, no-spring), generating pump performance curves across a range of flow rates to quantify the efficiency tradeoff.</p>

    <p><strong>Results:</strong> Incorporation of a snifter valve with no internal spring resolves waterlogging without compromising system efficiency for typical operating head values (5-7 m).</p>
  </div>

  <figure class="snifter-figure">
    <a
      href="{{ 'assets\images\ram-pump\Ram Pump Final Poster SP25.pptx.png' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Open snifter valve image in a new tab"
    >
      <img
        src="{{ 'assets\images\ram-pump\Ram Pump Final Poster SP25.pptx.png' | relative_url }}"
        alt="Snifter valve schematic or pump illustration"
      />
    </a>
    <figcaption style="margin-top: 0.5rem; text-align: center; color: #555; font-size: 0.9rem;">
      Nonlinear spring performance and design summary. (click to view)
    </figcaption>
  </figure>
</div>

<div style="text-align: center; margin: 2rem 0;">
  <a
    class="ram-pump-report-button"
    href="https://docs.google.com/document/d/1zlH7xsi56FLAr1i4EO32GFQONhIG7R9UNZeWnij9IRI/edit?usp=sharing"
    target="_blank"
    rel="noopener noreferrer"
  >
    Click here to view the full report
  </a>
</div>

<div class="photo-marquee" aria-label="Project photo strip">
  <div class="photo-marquee-track">
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/field-cad.png' | relative_url }}" alt="Field-scale ram pump CAD model" />
      <figcaption>Field CAD</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/field-cad-2.png' | relative_url }}" alt="Labeled field-scale ram pump CAD model" />
      <figcaption>Labeled CAD</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/mount.png' | relative_url }}" alt="Flat spring mount design" />
      <figcaption>Spring mount</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/waste-valve.png' | relative_url }}" alt="Modified waste valve design" />
      <figcaption>Waste valve</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/deployment/construct.png' | relative_url }}" alt="Assembling the ram pump for deployment" />
      <figcaption>Deployment</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/deployment/teach.png' | relative_url }}" alt="Teaching plant operators" />
      <figcaption>Training</figcaption>
    </figure>

    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/field-cad.png' | relative_url }}" alt="Field-scale ram pump CAD model" />
      <figcaption>Field CAD</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/field-cad-2.png' | relative_url }}" alt="Labeled field-scale ram pump CAD model" />
      <figcaption>Labeled CAD</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/mount.png' | relative_url }}" alt="Flat spring mount design" />
      <figcaption>Spring mount</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/waste-valve.png' | relative_url }}" alt="Modified waste valve design" />
      <figcaption>Waste valve</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/deployment/construct.png' | relative_url }}" alt="Assembling the ram pump for deployment" />
      <figcaption>Deployment</figcaption>
    </figure>
    <figure class="photo-marquee-item">
      <img src="{{ '/assets/images/ram-pump/deployment/teach.png' | relative_url }}" alt="Teaching plant operators" />
      <figcaption>Training</figcaption>
    </figure>
  </div>
</div>

---


---