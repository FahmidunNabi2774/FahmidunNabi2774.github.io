---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>

/* =========================================================
   PUBLICATION CARDS
   ========================================================= */

.pub-card {
  display: flex;
  flex-direction: row;
  background: #ffffff;
  border: 1px solid #e1e4e8;
  border-radius: 12px;
  padding: 20px;
  margin-bottom: 24px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.04);
  gap: 24px;
  align-items: flex-start;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.pub-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 20px rgba(0, 0, 0, 0.10);
}


/* LEFT SIDE */

.pub-left {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 200px;
  flex-shrink: 0;
}


/* BADGE */

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


/* PUBLICATION IMAGE */

.pub-image {
  display: block !important;
  width: 100% !important;
  max-width: 200px !important;
  height: auto !important;

  border-radius: 6px !important;
  border: 1px solid #eaedf0 !important;

  object-fit: cover;

  cursor: zoom-in !important;

  transition:
    opacity 0.2s ease,
    transform 0.2s ease;
}

.pub-image:hover {
  opacity: 0.85;
  transform: scale(1.02);
}


/* RIGHT SIDE */

.pub-right {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  flex-grow: 1;
}


/* TITLE */

.pub-title {
  font-size: 1.05em;
  font-weight: 600;
  line-height: 1.3;
  margin-bottom: 8px;
  color: #24292e;
}


/* AUTHORS */

.pub-authors {
  font-size: 0.95em;
  margin-bottom: 4px;
  color: #24292e;
}


/* JOURNAL */

.pub-journal {
  font-size: 0.9em;
  font-style: italic;
  margin-bottom: 16px;
  color: #586069;
}


/* PDF BUTTON */

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


/* =========================================================
   IMAGE MODAL
   ========================================================= */

.pub-modal {

  position: fixed !important;

  top: 0 !important;
  left: 0 !important;

  width: 100vw !important;
  height: 100vh !important;

  /* Extremely high so Minimal Mistakes/theme CSS
     cannot place it behind the page */

  z-index: 2147483647 !important;

  display: flex !important;

  align-items: center !important;
  justify-content: center !important;

  box-sizing: border-box;

  padding: 30px;

  /* Dark background */

  background: rgba(8, 12, 20, 0.78) !important;

  /* Blur whatever is behind the modal */

  backdrop-filter: blur(15px) !important;
  -webkit-backdrop-filter: blur(15px) !important;

  /* Hidden initially */

  opacity: 0;
  visibility: hidden;
  pointer-events: none;

  transition:
    opacity 0.25s ease,
    visibility 0.25s ease;
}


/* =========================================================
   ACTIVE MODAL
   ========================================================= */

.pub-modal.active {

  opacity: 1 !important;

  visibility: visible !important;

  pointer-events: auto !important;
}


/* =========================================================
   LARGE IMAGE INSIDE MODAL
   ========================================================= */

.pub-modal-image {

  display: block !important;

  width: auto !important;
  height: auto !important;

  max-width: 90vw !important;
  max-height: 85vh !important;

  object-fit: contain !important;

  margin: 0 !important;
  padding: 0 !important;

  border-radius: 10px !important;

  background: #ffffff;

  box-shadow:
    0 20px 60px rgba(0, 0, 0, 0.55),
    0 0 0 1px rgba(255, 255, 255, 0.15);

  cursor: default !important;

  transform: scale(0.92);

  transition: transform 0.25s ease;
}


/* Image zoom-in animation */

.pub-modal.active .pub-modal-image {
  transform: scale(1);
}


/* =========================================================
   CLOSE BUTTON
   ========================================================= */

.pub-modal-close {

  position: absolute !important;

  top: 20px !important;
  right: 30px !important;

  width: 46px;
  height: 46px;

  display: flex !important;

  align-items: center;
  justify-content: center;

  color: #ffffff !important;

  font-family: Arial, Helvetica, sans-serif;

  font-size: 38px;
  font-weight: 300;

  line-height: 1;

  cursor: pointer !important;

  background: rgba(0, 0, 0, 0.35);

  border-radius: 50%;

  user-select: none;

  transition:
    background 0.2s ease,
    transform 0.2s ease;
}

.pub-modal-close:hover {

  background: rgba(255, 255, 255, 0.20);

  transform: scale(1.10);
}


/* =========================================================
   MOBILE RESPONSIVE
   ========================================================= */

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


  .pub-image {

    max-width: 300px !important;
  }


  .pub-modal {

    padding: 15px;
  }


  .pub-modal-image {

    max-width: 95vw !important;

    max-height: 80vh !important;
  }


  .pub-modal-close {

    top: 15px !important;

    right: 15px !important;
  }

}

</style>


<!-- =========================================================
     2026
     ========================================================= -->

## 2026


<!-- PUBLICATION 1 -->

<div class="pub-card">

  <div class="pub-left">

    <div class="pub-badge">
      NCA
    </div>

    <img
      class="pub-image"
      src="/images/Taxonomy_UNET.jpg"
      alt="U-Net Review Architecture"
    >

  </div>


  <div class="pub-right">

    <div class="pub-title">
      A comprehensive review of U-Net architectures for medical image segmentation: emerging trends and federated learning perspectives
    </div>

    <div class="pub-authors">
      MF Hossen, A Sarkar, T Majumder,
      <strong>MF Nabi</strong>,
      MF Ahamed, FB Shafi, et al.
    </div>

    <div class="pub-journal">
      Neural Computing and Applications 38 (12), 493 (2026)
    </div>

    <a href="#" class="pub-btn">
      PDF
    </a>

  </div>

</div>


<!-- PUBLICATION 2 -->

<div class="pub-card">

  <div class="pub-left">

    <div class="pub-badge">
      Sci Data
    </div>

    <img
      class="pub-image"
      src="/images/roadsens-data.jpg"
      alt="RoadSens-4M Dataset Diagram"
    >

  </div>


  <div class="pub-right">

    <div class="pub-title">
      RoadSens-4M: A multimodal smartphone &amp; camera dataset for holistic road-way analysis
    </div>

    <div class="pub-authors">
      A Khandakar, DG Michelson, SG Rabbani, FB Shafi,
      MF Ahamed, <strong>MF Nabi</strong>, et al.
    </div>

    <div class="pub-journal">
      Scientific Data (2026)
    </div>

    <a href="#" class="pub-btn">
      PDF
    </a>

  </div>

</div>


<!-- PUBLICATION 3 -->

<div class="pub-card">

  <div class="pub-left">

    <div class="pub-badge">
      AI in Med
    </div>

    <img
      class="pub-image"
      src="/images/ukan-architecture.jpg"
      alt="UKAN-CBAM Architecture"
    >

  </div>


  <div class="pub-right">

    <div class="pub-title">
      Rethinking U-Net architecture in medical imaging: Advancing the efficient and interpretable UKAN-CBAM framework for colorectal polyp segmentation
    </div>

    <div class="pub-authors">
      MF Ahamed, FB Shafi, MR Islam,
      <strong>MF Nabi</strong>,
      J Haider
    </div>

    <div class="pub-journal">
      Artificial Intelligence in Medicine, 103352 (2026)
    </div>

    <a href="#" class="pub-btn">
      PDF
    </a>

  </div>

</div>


<!-- =========================================================
     2025
     ========================================================= -->

## 2025


<!-- PUBLICATION 4 -->

<div class="pub-card">

  <div class="pub-left">

    <div class="pub-badge">
      Results Eng
    </div>

    <img
      class="pub-image"
      src="/images/cattle-work.jpg"
      alt="Sensor Architecture"
    >

  </div>


  <div class="pub-right">

    <div class="pub-title">
      Review of sensor technologies, DC-DC converters, and power electronics for sustainable monitoring in precision livestock farming
    </div>

    <div class="pub-authors">
      FB Shafi, MF Ahamed,
      <strong>MF Nabi</strong>,
      A Khandakar, W Rohouma, MA Ayari, et al.
    </div>

    <div class="pub-journal">
      Results in Engineering, 107975 (2025)
    </div>

    <a href="#" class="pub-btn">
      PDF
    </a>

  </div>

</div>


<br>

<p>
  <em>
    All published work conducted in collaboration with Qatar University under Prof. Dr. Amith Khandakar.
  </em>
</p>


<!-- =========================================================
     IMAGE MODAL JAVASCRIPT
     ========================================================= -->

<script>

document.addEventListener("DOMContentLoaded", function () {


  /* ---------------------------------------------------------
     CREATE MODAL ELEMENT
     --------------------------------------------------------- */

  var modal = document.createElement("div");

  modal.className = "pub-modal";


  /* ---------------------------------------------------------
     CREATE CLOSE BUTTON
     --------------------------------------------------------- */

  var closeButton = document.createElement("div");

  closeButton.className = "pub-modal-close";

  closeButton.innerHTML = "&times;";

  closeButton.setAttribute(
    "aria-label",
    "Close image"
  );

  closeButton.setAttribute(
    "role",
    "button"
  );


  /* ---------------------------------------------------------
     CREATE MODAL IMAGE
     --------------------------------------------------------- */

  var modalImage = document.createElement("img");

  modalImage.className = "pub-modal-image";

  modalImage.alt = "Publication preview";


  /* ---------------------------------------------------------
     ADD ELEMENTS TO MODAL
     --------------------------------------------------------- */

  modal.appendChild(closeButton);

  modal.appendChild(modalImage);

  document.body.appendChild(modal);


  /* ---------------------------------------------------------
     OPEN MODAL
     --------------------------------------------------------- */

  function openModal(image) {

    modalImage.src = image.src;

    modalImage.alt =
      image.alt || "Publication preview";


    /* Make modal visible */

    modal.classList.add("active");


    /* Prevent page scrolling */

    document.body.style.overflow = "hidden";

  }


  /* ---------------------------------------------------------
     CLOSE MODAL
     --------------------------------------------------------- */

  function closeModal() {

    modal.classList.remove("active");


    /* Restore page scrolling */

    document.body.style.overflow = "";


    /* Remove image after animation */

    setTimeout(function () {

      if (!modal.classList.contains("active")) {

        modalImage.src = "";

      }

    }, 250);

  }


  /* ---------------------------------------------------------
     FIND ALL PUBLICATION IMAGES
     --------------------------------------------------------- */

  var publicationImages =
    document.querySelectorAll(".pub-image");


  /* ---------------------------------------------------------
     ADD CLICK EVENT TO EACH IMAGE
     --------------------------------------------------------- */

  publicationImages.forEach(function (image) {

    image.addEventListener(
      "click",
      function (event) {

        event.preventDefault();

        event.stopPropagation();

        openModal(this);

      }
    );

  });


  /* ---------------------------------------------------------
     CLOSE USING X BUTTON
     --------------------------------------------------------- */

  closeButton.addEventListener(
    "click",
    function (event) {

      event.preventDefault();

      event.stopPropagation();

      closeModal();

    }
  );


  /* ---------------------------------------------------------
     CLOSE WHEN CLICKING BACKGROUND
     --------------------------------------------------------- */

  modal.addEventListener(
    "click",
    function (event) {

      if (event.target === modal) {

        closeModal();

      }

    }
  );


  /* ---------------------------------------------------------
     CLOSE WITH ESCAPE KEY
     --------------------------------------------------------- */

  document.addEventListener(
    "keydown",
    function (event) {

      if (
        event.key === "Escape" &&
        modal.classList.contains("active")
      ) {

        closeModal();

      }

    }
  );


});

</script>
