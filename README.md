<div align="center">

<img src="assets/hero.svg" width="100%" alt="Charles Wang: hardware for plant sensing and imaging"/>

**Hardware engineer building handheld imaging instruments, from the CAD and electronics down to the software that runs them.**

Four leaf-imaging devices built so far. Looking for a role in hardware engineering or R&D.

[![Portfolio](https://img.shields.io/badge/Portfolio-charleswang435.github.io-2E7D32?logo=githubpages&logoColor=white)](https://charleswang435.github.io)
[![Résumé](https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-555?logo=adobeacrobatreader&logoColor=white)](https://charleswang435.github.io/CharlesWangResume2026.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-wangcharles362-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wangcharles362)
[![Email](https://img.shields.io/badge/Email-wangcharles362%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:wangcharles362@gmail.com)

</div>

---

## Projects

<table>
  <tr>
    <td width="38%" valign="top">
      <a href="https://github.com/CharlesWang435/LeafSpec-Cross-Sectional-Imager"><img src="assets/microscope-device.webp" width="100%" alt="Leaf cross-section microscope imager, prototype 1, with the 3D-printed clamp on a motorized linear rail"/></a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/CharlesWang435/LeafSpec-Cross-Sectional-Imager">Leaf Cross-Section Microscope Imager</a> <sub>(M.S. project, in progress)</sub></h3>
      A modular attachment for the LeafSpec confocal microscope that images a full corn-leaf cross section at 100×. A 3D-printed clamp on a motorized rail steps the cut leaf under the objective; a Raspberry Pi 5 web console gives live preview, motor control and autofocus. Prototype 2 swaps the mechanical focus for an <b>electrically tunable liquid lens</b> and a weight-balanced rack-and-pinion stage.
      <br/><br/>
      <b>Stack:</b> optics, liquid lens, motor control, Raspberry Pi, Flask, SolidWorks
      <br/>
      <b>Repo:</b> <a href="https://github.com/CharlesWang435/LeafSpec-Cross-Sectional-Imager">CharlesWang435/LeafSpec-Cross-Sectional-Imager</a> (build log and photos) · <a href="https://charleswang435.github.io/#microscope">portfolio</a>
    </td>
  </tr>
  <tr>
    <td width="38%" valign="top">
      <a href="https://github.com/CharlesWang435/LeafDoc"><img src="assets/leafdoc-device.webp" width="100%" alt="LeafDoc handheld light box with a phone mounted, showing a gallery of corn leaf captures"/></a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/CharlesWang435/LeafDoc">LeafDoc</a></h3>
      A $50 smartphone lightbox, through seven printed enclosure revisions, that blocks ambient light and holds the leaf flat for repeatable backlit images. Used in a Purdue–DARPA study (<b>6,500+ captures</b>). The companion Android app (Kotlin, CameraX + Camera2) gives manual camera control, GPS and trial metadata, frame stitching, and LLM-based plant-health scoring.
      <br/><br/>
      <img src="assets/leafdoc-stitched.webp" width="100%" alt="Stitched backlit corn leaf panorama"/>
      <br/>
      <b>Stack:</b> SolidWorks, 3D printing, Kotlin, CameraX, image stitching
      <br/>
      <b>Repo:</b> <a href="https://github.com/CharlesWang435/LeafDoc">CharlesWang435/LeafDoc</a>
    </td>
  </tr>
  <tr>
    <td width="38%" valign="top">
      <a href="https://github.com/CharlesWang435/LeafDoc#next-the-leafstudio-lightbox"><img src="assets/leafstudio-cad.webp" width="100%" alt="CAD view of the LeafStudio lightbox, closed, with a phone clamped on the lid"/></a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/CharlesWang435/LeafDoc#next-the-leafstudio-lightbox">LeafStudio lightbox</a> <sub>(Proto 1, in build)</sub></h3>
      The next-generation LeafDoc enclosure (formerly LeafSpec RGB): a light-tight box with a diffused 15 × 15 cm LED window, a spring-loaded clamp handle and a push-push latch, so any phone gets identical distance, angle and lighting on every shot. Designed in Fusion and 3D-printed.
      <br/><br/>
      <b>Repo:</b> <a href="https://github.com/CharlesWang435/LeafDoc#next-the-leafstudio-lightbox">CharlesWang435/LeafDoc</a>
    </td>
  </tr>
  <tr>
    <td width="38%" valign="top">
      <a href="https://charleswang435.github.io/#fluoroscan"><img src="assets/fluoroscan-device.webp" width="100%" alt="FluoroScan assembled enclosure with camera mounted on top"/></a>
    </td>
    <td valign="top">
      <h3><a href="https://charleswang435.github.io/#fluoroscan">FluoroScan</a></h3>
      A chlorophyll-fluorescence (Fv/Fm) imager for under $2,000 in parts, against $20,000+ commercial units. Twelve 450 nm LEDs on hand-soldered star boards, a 680/720 nm emission bandpass, and one timed sequence that fires the saturating pulse and trips the shutter together. Prototype, not yet validated against a commercial fluorometer.
      <br/><br/>
      <b>Stack:</b> Raspberry Pi, LED arrays, optics, SolidWorks
      <br/>
      <b>Write-up:</b> <a href="https://charleswang435.github.io/#fluoroscan">portfolio</a>
    </td>
  </tr>
  <tr>
    <td width="38%" valign="top">
      <a href="https://charleswang435.github.io/#multispectral"><img src="assets/multispectral-device.webp" width="100%" alt="Redesigned LeafSpec-Multi multispectral handheld imager"/></a>
    </td>
    <td valign="top">
      <h3><a href="https://charleswang435.github.io/#multispectral">LeafSpec-Multi multispectral imager</a></h3>
      Rebuilt an undocumented handheld multispectral imager from its SolidWorks assembly alone: reverse-engineered every subsystem, hand-soldered <b>120+ LEDs</b> across 6 bands with per-band MOSFET drivers, and moved the Pi and 12 V→5 V power into the body (~30% smaller). Images at 0.04 mm/pixel; its data supported a <a href="https://doi.org/10.1016/j.compag.2025.111018">peer-reviewed study</a> I co-authored (90% classification accuracy).
      <br/><br/>
      <b>Stack:</b> Raspberry Pi, MOSFET switching, 3D printing, reverse engineering
      <br/>
      <b>Write-up:</b> <a href="https://charleswang435.github.io/#multispectral">portfolio</a>
    </td>
  </tr>
</table>

## Experience
- **Hardware Engineer**, LeafSpec LLC · Purdue ABE Plant Sensor Lab (May 2024 – present). Handheld crop-imaging instruments from concept to field deployment; lab imagers in use by partners including Corteva.
- **Summer Research Fellow**, Institute for Digital Forestry, Purdue (May – Jul 2024). LeafSpec-Multi rebuild.
- **Education:** M.S. Agricultural & Biological Engineering, Purdue (expected May 2027) · B.S. Biological Engineering, Purdue (Dec 2025)

## Skills
- **Design & fabrication:** SolidWorks, Fusion, 3D printing (Bambu Lab), enclosure design, optical path layout
- **Electronics:** hand soldering, MOSFET switching, Raspberry Pi, microcontrollers, motor control, LED arrays
- **Software:** Python, C, MATLAB, Kotlin + Android + CameraX, image stitching, web control interfaces
- **Imaging:** multispectral and hyperspectral imaging, chlorophyll fluorescence, microscopy, liquid-lens focusing
