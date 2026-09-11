---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  .pub-card {
    display: flex;
    flex-direction: row;
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    padding: 20px;
    margin-bottom: 24px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.04);
    gap: 24px;
    align-items: flex-start;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .pub-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 20px rgba(0,0,0,0.1);
  }
  .pub-left {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 200px;
    flex-shrink: 0;
  }
  .pub-badge {
    background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
    color: #ffffff;
    padding: 4px 16px;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: bold;
    margin-bottom: 12px;
    text-align: center;
    box-shadow: 0 2px 4px rgba(42, 82, 152, 0.3);
  }
  .pub-image {
    max-width: 100%;
    border-radius: 6px;
    border: 1px solid #eaedf0;
    object-fit: cover;
    cursor: pointer;
    transition: opacity 0.2s ease;
  }
  .pub-image:hover {
    opacity: 0.85;
  }
  .pub-right {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    flex-grow: 1;
  }
  .pub-title {
    font-size: 1.05em;
    font-weight: 600;
    line-height: 1.3;
    margin-bottom: 8px;
    color: #24292e;
  }
  .pub-authors {
    font-size: 0.95em;
    margin-bottom: 4px;
    color: #24292e;
  }
  .pub-journal {
    font-size: 0.9em;
    font-style: italic;
    margin-bottom: 16px;
    color: #586069;
  }
  .pub-btn {
    display: inline-block;
    border: 1px solid #d1d5da;
    background: #f6f8fa;
    color: #24292e;
    padding: 6px 18px;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: 600;
    text-decoration: none !important;
    width: max-content;
    transition: background-color 0.2s ease;
  }
  .pub-btn:hover {
    background: #e1e4e8;
  }
  
  /* Lightbox Overlay */
  #img-modal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(20, 25, 35, 0.6);
    backdrop-filter: blur(8px);
    -webkit-backdrop-filter: blur(8px);
    z-index: 9999;
    align-items: center;
    justify-content: center;
  }
  #img-modal img {
    max-width: 85%;
    max-height: 85%;
    border-radius: 8px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);
  }
  .close-btn {
    position: absolute;
    top: 25px;
    right: 35px;
    color: #ffffff;
    font-size: 35px;
    font-weight: bold;
    cursor: pointer;
    opacity: 0.8;
  }
  .close-btn:hover {
    opacity: 1;
  }

  /* Mobile Responsiveness */
  @media (max-width: 768px) {
    .pub-card {
      flex-direction: column;
      align-items: center;
    }
    .pub-left {
      width: 100%;
      max-width: 300px;
      margin-bottom: 16px;
    }
  }
</style>

<!-- Hidden overlay container -->
<div id="img-modal">
  <span class="close-btn">&times;</span>
  <img id="modal-img" src="" alt="Expanded View">
</div>

## 2026

<div class="pub-card">
  <div class="pub-left">
    <div class="pub-badge">NCA</div>
    <img class="pub-image" src="/images/Taxonomy_UNET.jpg" alt="U-Net Review Architecture">
  </div>
  <div class="pub-right">
    <div class="pub-title">A comprehensive review of U-Net architectures for medical image segmentation: emerging trends and federated learning perspectives</div>
    <div class="pub-authors">MF Hossen, A Sarkar, T Majumder, <strong>MF Nabi</strong>, MF Ahamed, FB Shafi, et al.</div>
    <div class="pub-journal">Neural Computing and Applications 38 (12), 493 (2026)</div>
    <a href="#" class="pub-btn">PDF</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-left">
    <div class="pub-badge">Sci Data</div>
    <img class="pub-image" src="/images/roadsens-data.jpg" alt="RoadSens-4M Dataset Diagram">
  </div>
  <div class="pub-right">
    <div class="pub-title">RoadSens-4M: A multimodal smartphone & camera dataset for holistic road-way analysis</div>
    <div class="pub-authors">A Khandakar, DG Michelson, SG Rabbani, FB Shafi, MF Ahamed, <strong>MF Nabi</strong>, et al.</div>
    <div class="pub-journal">Scientific Data (2026)</div>
    <a href="#" class="pub-btn">PDF</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-left">
    <div class="pub-badge">AI in Med</div>
    <img class="pub-image" src="/images/ukan-architecture.jpg" alt="UKAN-CBAM Architecture">
  </div>
  <div class="pub-right">
    <div class="pub-title">Rethinking U-Net architecture in medical imaging: Advancing the efficient and interpretable UKAN-CBAM framework for colorectal polyp segmentation</div>
    <div class="pub-authors">MF Ahamed, FB Shafi, MR Islam, <strong>MF Nabi</strong>, J Haider</div>
    <div class="pub-journal">Artificial Intelligence in Medicine, 103352 (2026)</div>
    <a href="#" class="pub-btn">PDF</a>
  </div>
</div>

## 2025

<div class="pub-card">
  <div class="pub-left">
    <div class="pub-badge">Results Eng</div>
    <img class="pub-image" src="/images/cattle-work.jpg" alt="Sensor Architecture">
  </div>
  <div class="pub-right">
    <div class="pub-title">Review of sensor technologies, DC-DC converters, and power electronics for sustainable monitoring in precision livestock farming</div>
    <div class="pub-authors">FB Shafi, MF Ahamed, <strong>MF Nabi</strong>, A Khandakar, W Rohouma, MA Ayari, et al.</div>
    <div class="pub-journal">Results in Engineering, 107975 (2025)</div>
    <a href="#" class="pub-btn">PDF</a>
  </div>
</div>

<script>
  const modal = document.getElementById("img-modal");
  const modalImg = document.getElementById("modal-img");
  const images = document.querySelectorAll(".pub-image");
  const closeBtn = document.querySelector(".close-btn");

  images.forEach(img => {
    img.addEventListener("click", function() {
      modal.style.display = "flex";
      modalImg.src = this.src;
    });
  });

  closeBtn.addEventListener("click", function() {
    modal.style.display = "none";
  });

  modal.addEventListener("click", function(e) {
    if (e.target === modal) {
      modal.style.display = "none";
    }
  });
</script>
