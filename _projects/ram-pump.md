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

<div class="ram-pump-lab-row">
  <figure class="ram-pump-lab-figure ram-pump-lab-schematic">
    <img
      src="{{ '/assets/images/ram-pump/lab-schematic.png' | relative_url }}"
      alt="Lab schematic of the AguaClara Vertical Ram Pump test setup"
    />
    <figcaption>Lab schematic of the ACVRP experimental setup at Cornell.</figcaption>
  </figure>

  <figure class="ram-pump-lab-figure ram-pump-lab-video">
    <video controls playsinline preload="metadata">
      <source src="{{ '/assets/images/ram-pump/lab-scale-operation.mp4' | relative_url }}" type="video/mp4" />
    </video>
    <figcaption>Lab-scale operation of the ACVRP prototype.</figcaption>
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

  .ram-pump-lab-row {
    display: flex;
    align-items: flex-start;
    justify-content: center;
    gap: 1.5rem;
    margin: 1.75rem auto 0;
    max-width: 980px;
  }

  .ram-pump-lab-figure {
    flex: 1 1 0;
    max-width: 440px;
    margin: 0;
    text-align: center;
  }

  .ram-pump-lab-schematic img,
  .ram-pump-lab-video video {
    display: block;
    width: 100%;
    height: auto;
    margin: 0 auto;
    border-radius: 10px;
  }

  .ram-pump-lab-video video {
    background: #000;
    height: 100%;
    min-height: 220px;
    max-height: 300px;
    object-fit: contain;
  }

  .ram-pump-lab-figure figcaption {
    margin-top: 0.6rem;
    text-align: center;
    color: #555;
    font-size: 0.9rem;
    line-height: 1.4;
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
    --snifter-image-width: 400px;
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

  .snifter-figure a {
    display: block;
    transition: transform 0.2s ease, box-shadow 0.2s ease, filter 0.2s ease;
  }

  .snifter-figure a:hover {
    transform: translateY(-2px) scale(1.02);
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.18);
    filter: brightness(1.02);
  }

  .snifter-figure img {
    display: block;
    width: 100%;
    height: auto;
    border-radius: 8px;
  }

  .nonlinear-layout {
    --nonlinear-poster-width: 400px;
    display: flex;
    align-items: flex-start;
    gap: 1.5rem;
    margin: 2rem 0;
  }

  .nonlinear-copy-column {
    flex: 1 1 0;
    min-width: 0;
  }

  .nonlinear-copy-column p {
    margin-top: 0;
    margin-bottom: 0.9rem;
  }

  .nonlinear-button-row {
    margin-top: 1.5rem;
    text-align: center;
    width: 100%;
  }

  .nonlinear-poster {
    display: block;
    width: var(--nonlinear-poster-width);
    max-width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
    transition: transform 0.2s ease, box-shadow 0.2s ease, filter 0.2s ease;
    margin-top: 0.75rem;
  }

  .nonlinear-poster:hover {
    transform: translateY(-2px) scale(1.02);
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.18);
    filter: brightness(1.02);
  }

  .nonlinear-poster img {
    display: block;
    width: 100%;
    height: auto;
    border-radius: 10px;
  }

  .nonlinear-poster-caption {
    margin-top: 0.5rem;
    text-align: center;
    color: #555;
    font-size: 0.9rem;
    line-height: 1.4;
  }

  .nonlinear-marquee {
    position: relative;
    margin: 1.5rem 0 0;
    overflow: hidden;
    border-radius: 12px;
    background: rgba(58, 87, 120, 0.04);
    padding: 0.75rem 0;
    border: 1px solid rgba(58, 87, 120, 0.08);
  }

  .nonlinear-marquee-track {
    display: flex;
    width: max-content;
    animation: nonlinear-marquee 28s linear infinite;
    will-change: transform;
  }

  .nonlinear-marquee:hover .nonlinear-marquee-track {
    animation-play-state: paused;
  }

  .nonlinear-marquee-item {
    flex: 0 0 auto;
    margin-right: 1rem;
    text-align: center;
  }

  .nonlinear-marquee-item img {
    display: block;
    width: auto;
    height: 200px;
    object-fit: contain;
    border: none;
    background: transparent;
    box-shadow: none;
    border-radius: 0;
  }

  .nonlinear-marquee-item figcaption {
    margin-top: 0.4rem;
    font-size: 0.8rem;
    color: #555;
  }

  .deployment-carousel {
    --deployment-media-height: clamp(260px, 60vh, 620px);
    --deployment-media-width: min(100%, 540px);
    --deployment-frame-padding: 0;
    position: relative;
    max-width: 920px;
    margin: 2rem auto 0;
  }

  .deployment-carousel-frame {
    position: relative;
    overflow: hidden;
    border-radius: 12px;
    background: transparent;
    border: none;
    padding: var(--deployment-frame-padding);
  }

  .deployment-carousel-track {
    display: flex;
    transition: transform 0.5s ease;
    width: 100%;
  }

  .deployment-slide {
    flex: 0 0 100%;
    width: 100%;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .deployment-slide img,
  .deployment-slide video {
    display: block;
    width: auto;
    max-width: var(--deployment-media-width);
    height: var(--deployment-media-height);
    object-fit: contain;
    margin: 0 auto;
    border-radius: 0;
    background: transparent;
  }

  .deployment-slide figcaption {
    margin-top: 0.8rem;
    text-align: center;
    font-size: 0.9rem;
    color: #4a4a4a;
    line-height: 1.5;
  }

  .deployment-carousel-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    z-index: 2;
    width: 42px;
    height: 42px;
    border: none;
    border-radius: 50%;
    background: rgba(58, 63, 88, 0.9);
    color: white;
    font-size: 1.4rem;
    cursor: pointer;
  }

  .deployment-carousel-btn.prev {
    left: 0.75rem;
  }

  .deployment-carousel-btn.next {
    right: 0.75rem;
  }

  .deployment-carousel-btn:hover {
    background: rgba(58, 63, 88, 1);
  }

  @keyframes nonlinear-marquee {
    from {
      transform: translateX(0);
    }
    to {
      transform: translateX(-50%);
    }
  }

  @media (max-width: 900px) {
    .nonlinear-layout {
      flex-direction: column;
      align-items: stretch;
    }

    .nonlinear-poster {
      width: min(100%, 220px);
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
### Sub-Project: Snifter Valve

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

### Sub-Project: Nonlinear Spring

<div class="nonlinear-layout">
  <div class="nonlinear-copy-column">
    <p><strong>Objective:</strong> Resolve valve actuation failures observed in field caused by hydrostatic overloading.</p>

    <p><strong>Approach:</strong> Designed the Dual Support System using MASTAN and Autodesk Fusion to generate a nonlinear stiffness response matching the pressure profile. Validated design experimentally in the lab across three spring widths.</p>

    <p><strong>Results:</strong> Lab and field testing confirmed closure success under high hydrostatic loading, resolving the targetted failure, but revealed a new failure mode, shaping future investigations and driving further system improvements.</p>

  </div>

  <figure style="margin: 0;">
    <a
      class="nonlinear-poster"
      href="{{ 'assets/images/ram-pump/nonlinear-spring/Ram Pump Final Poster SP25.pptx.png' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Open the nonlinear spring poster in a new tab"
    >
      <img
        src="{{ 'assets/images/ram-pump/nonlinear-spring/Ram Pump Final Poster SP25.pptx.png' | relative_url }}"
        alt="Nonlinear spring poster"
      />
    </a>
    <figcaption class="nonlinear-poster-caption">Nonlinear spring support system poster. (click to view)</figcaption>
  </figure>
</div>

<div class="nonlinear-button-row" style="text-align: center; margin: 2rem 0 0;">
  <a
    class="ram-pump-report-button"
    href="https://docs.google.com/document/d/1zlH7xsi56FLAr1i4EO32GFQONhIG7R9UNZeWnij9IRI/edit?usp=sharing"
    target="_blank"
    rel="noopener noreferrer"
  >
    Click here to view the full report
  </a>
</div>

<div class="nonlinear-marquee" aria-label="Continuous photo strip">
  <div class="nonlinear-marquee-track">
    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/cad-dual-sup.png' | relative_url }}" alt="CAD model of dual support system" />
      <figcaption>Dual support system CAD Model</figcaption>
    </figure>
    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/lab-dual-sup.jpg' | relative_url }}" alt="Lab setup for dual support system" />
      <figcaption>Experimental setup</figcaption>
    </figure>
    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/mastan.png' | relative_url }}" alt="MASTAN analysis plot" />
      <figcaption>MASTAN analysis</figcaption>
    </figure>
    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/osu-dual-sup.png' | relative_url }}" alt="OSU dual support design" />
      <figcaption>Field experimentation design</figcaption>
    </figure>

    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/cad-dual-sup.png' | relative_url }}" alt="CAD model of dual support system" />
      <figcaption>CAD model</figcaption>
    </figure>
    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/lab-dual-sup.jpg' | relative_url }}" alt="Lab setup for dual support system" />
      <figcaption>Lab setup</figcaption>
    </figure>
    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/mastan.png' | relative_url }}" alt="MASTAN analysis plot" />
      <figcaption>MASTAN</figcaption>
    </figure>
    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/osu-dual-sup.png' | relative_url }}" alt="OSU dual support design" />
      <figcaption>Design</figcaption>
    </figure>
    <figure class="nonlinear-marquee-item">
      <img src="{{ '/assets/images/ram-pump/nonlinear-spring/Ram Pump Final Poster SP25.pptx.png' | relative_url }}" alt="Poster summary" />
      <figcaption>Poster</figcaption>
    </figure>
  </div>
</div>

---




### Field Deployment

**Objective:** Bring the finalized ACVRP design to real AguaClara plants in Honduras to internally deliver a reliable clean water supply within the facilities, eliminating manual labor.

**Process:** In January 2026, I led a team of AguaClara students, plant operators, and local technicians through on-site installation at two plants. This meant preparing a user's manual complete with a Bill of Materials, assembling the system on-site, and calibrating the flat spring until the pump ran reliably under real (not simulated) driving head.

**Outcome:** First successful permanent ACVRP installations in the project's 20 years of development. The San Juan Planes system pumps water 5 meters vertically at 3.33 L/min; the Moroceli system pumps 2 meters at 2.50 L/min. Both pumps are now operating without electricity or daily operator intervention, and the San Juan Planes pump's recycled water even supplies a small nearby community of 300, while the Moroceli plant diverts the recycled water into clean water storage tanks.

<div style="text-align: center; margin: 1.5rem 0 0.5rem;">
  <a
    class="ram-pump-report-button"
    href="{{ '/assets/files/AguaClara Ram Pump Manual.pdf' | relative_url }}"
    target="_blank"
    rel="noopener noreferrer"
  >
    Click here to access the official installation manual
  </a>
</div>

<div class="deployment-carousel" aria-label="Field deployment media gallery">
  <div class="deployment-carousel-frame">
    <button class="deployment-carousel-btn prev" type="button" aria-label="Previous deployment media">&#10094;</button>

    <div class="deployment-carousel-track">
      <figure class="deployment-slide">
        <img src="{{ '/assets/images/ram-pump/deployment/sjp-installment.JPG' | relative_url }}" alt="Installation at the San Juan Planes plant" />
        <figcaption>Installation at the San Juan Planes site.</figcaption>
      </figure>

      <figure class="deployment-slide">
        <video controls playsinline preload="metadata">
          <source src="{{ '/assets/images/ram-pump/deployment/operation.mp4' | relative_url }}" type="video/mp4" />
        </video>
        <figcaption>Successful field operation of the ACVRP under real flow conditions.</figcaption>
      </figure>

      <figure class="deployment-slide">
        <img src="{{ '/assets/images/ram-pump/deployment/construct.png' | relative_url }}" alt="Construction and assembly of the ram pump system" />
        <figcaption>Assembly of the ACVRP at the project site.</figcaption>
      </figure>

      <figure class="deployment-slide">
        <img src="{{ '/assets/images/ram-pump/deployment/civil.jpg' | relative_url }}" alt="Site preparation" />
        <figcaption>Site preparation discussion with facility civil engineer.</figcaption>
      </figure>

      <figure class="deployment-slide">
        <img src="{{ '/assets/images/ram-pump/deployment/training.png' | relative_url }}" alt="Training the plant operators" />
        <figcaption>Training local operators and technicians on system operation and maintenance.</figcaption>
      </figure>

      <figure class="deployment-slide">
        <video controls playsinline preload="metadata">
          <source src="{{ '/assets/images/ram-pump/deployment/spring.mp4' | relative_url }}" type="video/mp4" />
        </video>
        <figcaption>Spring behavior with easy operating procedure.</figcaption>
      </figure>

      <figure class="deployment-slide">
        <video controls playsinline preload="metadata">
          <source src="{{ '/assets/images/ram-pump/deployment/fill-bucket.mp4' | relative_url }}" type="video/mp4" />
        </video>
        <figcaption>Plant operators using the ACVRP to fill chemical stock tanks.</figcaption>
      </figure>

      <figure class="deployment-slide">
        <img src="{{ '/assets/images/ram-pump/deployment/moro-installment.png' | relative_url }}" alt="Installation at the Moroceli plant" />
        <figcaption>Field installation at the Moroceli site.</figcaption>
      </figure>
    </div>

    <button class="deployment-carousel-btn next" type="button" aria-label="Next deployment media">&#10095;</button>
  </div>
</div>

<script>
  const deploymentSlides = Array.from(document.querySelectorAll('.deployment-slide'));
  const deploymentTrack = document.querySelector('.deployment-carousel-track');
  const deploymentPrev = document.querySelector('.deployment-carousel-btn.prev');
  const deploymentNext = document.querySelector('.deployment-carousel-btn.next');
  const deploymentFrame = document.querySelector('.deployment-carousel-frame');
  const deploymentHasVideo = deploymentSlides.some((slide) => slide.querySelector('video'));
  let deploymentCurrent = 0;
  let deploymentTimer = null;

  function pauseAllDeploymentVideos() {
    deploymentSlides.forEach((slide) => {
      const video = slide.querySelector('video');
      if (video && !video.paused) {
        video.pause();
      }
    });
  }

  function showDeploymentSlide(index) {
    deploymentCurrent = (index + deploymentSlides.length) % deploymentSlides.length;
    deploymentTrack.style.transform = `translateX(-${deploymentCurrent * 100}%)`;
  }

  function pauseDeploymentTimer() {
    if (deploymentTimer) {
      clearInterval(deploymentTimer);
      deploymentTimer = null;
    }
  }

  function startDeploymentTimer() {
    if (deploymentHasVideo) {
      pauseDeploymentTimer();
      return;
    }

    pauseDeploymentTimer();
    deploymentTimer = setInterval(() => {
      showDeploymentSlide(deploymentCurrent + 1);
    }, 5000);
  }

  function deploymentGoNext() {
    pauseAllDeploymentVideos();
    showDeploymentSlide(deploymentCurrent + 1);
    startDeploymentTimer();
  }

  function deploymentGoPrev() {
    pauseAllDeploymentVideos();
    showDeploymentSlide(deploymentCurrent - 1);
    startDeploymentTimer();
  }

  if (deploymentSlides.length > 0) {
    showDeploymentSlide(0);

    deploymentSlides.forEach((slide) => {
      const video = slide.querySelector('video');
      if (!video) return;

      video.addEventListener('play', () => {
        pauseDeploymentTimer();
      });

      video.addEventListener('pause', () => {
        if (!deploymentHasVideo) {
          startDeploymentTimer();
        }
      });

      video.addEventListener('ended', () => {
        if (!deploymentHasVideo) {
          startDeploymentTimer();
        }
      });
    });

    deploymentPrev.addEventListener('click', deploymentGoPrev);
    deploymentNext.addEventListener('click', deploymentGoNext);
    deploymentFrame.addEventListener('mouseenter', pauseDeploymentTimer);
    deploymentFrame.addEventListener('mouseleave', startDeploymentTimer);

    startDeploymentTimer();
  }
</script>

---