---
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

# Portfolio

This page presents selected projects from my PhD and research work in robotic surgery, medical imaging, and AI-assisted surgical guidance.

---

# Robot-assisted SPECT for intraoperative nuclear imaging

![Robot-assisted SPECT](/images/portfolio/Picture1.jpg)

Urology commonly combines fluorescence imaging and gamma tracing to localize targets during minimally invasive surgery, but fluorescence offers limited depth information and preoperative SPECT/CT often misaligns with the intraoperative anatomy.

I developed a method to generate intraoperative nuclear images using a tracked DROP-IN gamma probe, enabling tomographic reconstruction without a conventional SPECT gantry.

I implemented the full workflow: vision-based probe tracking, count-rate acquisition, a lookup-table detection model derived from Monte Carlo simulations, and tomographic reconstruction of tracer uptake. I integrated these components into a workflow that overlays the 3D signal directly onto the laparoscopic view, providing surgeons with real-time nuclear information in the operative field.

I validated the approach in prostate cancer sentinel-node procedures by comparing robot-assisted SPECT results with fluorescence imaging and preoperative SPECT/CT. The system detected all nodes visualized on SPECT/CT, including nodes missed by fluorescence due to tissue attenuation.

**Publication:**  
European Urology, 2024

---

# Freehand magnetic particle imaging (fhMPI)

![fhMPI](/images/portfolio/Picture2.jpg)

Magnetic tracers are an emerging alternative to radioactive guidance in sentinel lymph node surgery.

I assembled the fhMPI setup by integrating a magnetometer probe with an optical tracking system and surgical navigation platform. This included probe tracking calibration, background correction, and generating the look-up table used for reconstruction.

The modality achieved sensitivity of 2.2 × 10⁻² mg/mL and detected hotspots up to 1.5 cm deep.

**Publication:**  
Journal publication — see Google Scholar

---

# Click-On gamma probe

![Click-On probe](/images/portfolio/Picture3.jpg)

I worked on development and evaluation of the second-generation Click-On gamma probe.

I implemented video tracking and quantified dexterity and workflow performance.

The Click-On probe:

• Reduced movements by 40%  
• Reduced path length by two-thirds  
• Improved surgical decision-making

---

# Optical navigation of DROP-IN gamma probe

![Optical navigation](/images/portfolio/Picture4.jpg)

I developed an optical navigation method allowing the gamma probe to be localized directly in the laparoscopic video stream.

I built a full computer-vision pipeline:

• Probe detection  
• Pose estimation  
• Real-time surgical navigation overlay  

This strengthened the integration between robotic surgery and nuclear imaging.

**Publication:**  
Journal of Nuclear Medicine, 2021
