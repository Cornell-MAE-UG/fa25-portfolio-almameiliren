---
layout: project
title: CAD Creative
description: A parametric can opener modeled from scratch in Autodesk Fusion.
technologies: [CAD, Fusion 360, Mechanical Design]
image: assets/images/cad-creative/render-1.jpg
order: 2
---

In my sophomore year mechanical design class, we were tasked with studying an object and creating it in Autodesk Fusion from scratch. My chosen object was a can opener.

#### Final Rendering

<div class="cad-gallery cad-render-gallery">
  <figure class="cad-figure cad-render-figure">
    <img src="{{ '/assets/images/cad-creative/render-1.jpg' | relative_url }}" alt="CAD render of the can opener front view" />
  </figure>
  <figure class="cad-figure cad-render-figure">
    <img src="{{ '/assets/images/cad-creative/render-2.png' | relative_url }}" alt="CAD render of the can opener angled view" />
  </figure>
</div>

---

<div class="cad-side-by-side">
  <div class="cad-side-block">
    <h4>Object</h4>
    <div class="cad-gallery cad-detail-gallery">
      <figure class="cad-figure cad-detail-figure">
        <img src="{{ '/assets/images/cad-creative/real-1.jpg' | relative_url }}" alt="Real can opener photographed from the front" />
      </figure>
      <figure class="cad-figure cad-detail-figure">
        <img src="{{ '/assets/images/cad-creative/real-2.jpg' | relative_url }}" alt="Real can opener photographed from the side" />
      </figure>
    </div>
  </div>

  <div class="cad-side-block">
    <h4>Sketches</h4>
    <div class="cad-gallery cad-detail-gallery">
      <figure class="cad-figure cad-detail-figure">
        <img src="{{ '/assets/images/cad-creative/sketch-1.jpg' | relative_url }}" alt="CAD sketch of the can opener" />
      </figure>
      <figure class="cad-figure cad-detail-figure">
        <img src="{{ '/assets/images/cad-creative/sketch-2.jpg' | relative_url }}" alt="Second CAD sketch of the can opener" />
      </figure>
    </div>
  </div>
</div>

<style>
  .cad-side-by-side {
    display: flex;
    gap: 2rem;
    align-items: stretch;
    margin: 2rem 0;
  }

  .cad-side-block {
    flex: 1 1 0;
    min-width: 0;
    padding: 0 1rem;
    position: relative;
  }

  .cad-side-block:first-child {
    border-right: 1px solid #d9d9d9;
    padding-right: 1.5rem;
  }

  .cad-side-block h4 {
    margin-bottom: 1rem;
  }

  .cad-gallery {
    display: flex;
    gap: 0.25rem;
    flex-wrap: wrap;
  }

  .cad-figure {
    flex: 1 1 0;
    min-width: 150px;
    margin: 0;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
  }

  .cad-figure img {
    display: block;
    width: auto;
    max-width: 100%;
    height: 100%;
    max-height: 100%;
    object-fit: contain;
    border-radius: 8px;
    margin: 0 auto;
    background: #f7f7f7;
  }

  .cad-render-gallery .cad-render-figure {
    height: 380px;
  }

  .cad-detail-gallery .cad-detail-figure {
    height: 300px;
  }

  @media (max-width: 768px) {
    .cad-side-by-side {
      flex-direction: column;
    }
  }
</style>

