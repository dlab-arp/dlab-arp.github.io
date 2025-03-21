---
layout: single_projects
permalink: /projects/
---
<!-- title: "Projects" -->
<div class="projects-page">
<div class="project-title-wrapper" style="text-align: center;">
<h2 class="project-title"> Reimagining Interpretability in Segmentation: A Multi-Scale Coherence Framework </h2>
</div>
<figure style="text-align: center; margin-bottom: 0em;">
  <a href="/assets/images/xds_heatmap.PNG" target="_blank" class="no-hover-effect" style="display: block; width: 100%; margin: 0 auto; margin-bottom: 0em">
    <img src="/assets/images/xds_heatmap.PNG" alt="The Consistency Heatmaps from 2 different MRI scans. The resolution of the maps decrease by a factor of 2 from left to right" style="max-height: 256px; object-fit: contain;">
  </a>
  <figcaption style="text-align: center; font-style: italic; font-size: 0.9em; color: rgba(136, 5, 176, 0.99); margin: 0 auto; margin-top: 0em; margin-bottom: 1em">
    The Consistency Heatmaps from 2 different MRI scans. The resolution of the maps decrease by a factor of 2 from left to right
  </figcaption>
</figure>

<p style="margin-bottom: 0;">Ever wonder how your AI model really “sees” an image beneath the final segmentation map? In this project, we introduce a novel multi-scale coherence framework that illuminates the hidden decision-making process inside deep learning models—particularly where they might be uncertain or unreliable.</p>
<p style="margin-bottom: 0; text-indent: 0em;">Using an XOR-based Deep Supervision (XDS) technique, our approach peels back the layers of segmentation from coarse to fine resolution. We then measure cross-scale consistency and visualize exactly where the model’s predictions align or deviate. Think of it as giving your segmentation model an on-the-fly “lie detector,” revealing hotspots of confusion at boundary regions, detecting out-of-distribution inputs, and offering new metrics (like Transition Dice Score and Outlier Consistency Score) for trustworthiness.</p>
<p style="margin-bottom: 0; text-indent: 0em;">Our method is computationally and architecturally lightweight (no major architectural overhauls needed) and domain-agnostic—we’ve demonstrated it on brain MRI and cell microscopy data, but it can be applied to virtually any segmentation task that demands reliability and interpretability.</p>

<h4 style="margin-top: 1em;">Key Highlights </h4>
  <ul>
    <li><strong>XDS Phased Training:</strong>A curriculum-inspired pipeline that refines segmentation from coarse to fine scales.</li>
    <li><strong>Heatmaps of Uncertainty:</strong> Multi-scale coherence maps that show exactly where and why the model struggles (e.g., tricky organ/lesion boundaries in MRI)</li>
    <li><strong>Practical OOD Detection:</strong> Identify out-of-distribution scans by tracking consistency across resolutions—critical for robust clinical or industrial AI deployment.</li>
  </ul>

<table style="width: 100%;  margin-top: 0em; border-collapse: collapse;">
  <tbody>
    <tr>
      <td style="width: auto; padding: 0em; text-align: left; vertical-align: middle; border: none;"><div style="font-size: 1.4em;">Curious to see how it all works? </div></td>
      <td style="padding: 0.5em; border: none; vertical-align: middle;"><a href="#" class="highlight-link" onclick="alert('Coming Soon!'); return false;"  target="_blank" rel="noopener noreferrer"><div style="font-size: 1.4em;">Paper</div></a></td>
      <td style="padding: 0.5em; border: none; vertical-align: middle; "><a href="#" class="highlight-link" onclick="alert('Coming Soon!'); return false;" target="_blank" rel="noopener noreferrer;"><div style="font-size: 1.4em;">Code</div></a></td>
    </tr>
    
  </tbody>
</table>

<div class="projects-page">
<div class="project-title-wrapper" style="text-align: center; margin-top: 1.5em">
<h2 class="project-title"> maxATAC: Genome-Scale transcription factor binding prediction from ATAC-Seq with deep neural networks </h2>
</div>
<figure style="text-align: center; margin-bottom: 0em;">
  <a href="/assets/images/maxatac_arch.PNG" target="_blank" class="no-hover-effect" style="display: block; width: 100%; margin: 0 auto; margin-bottom: 0em">
    <img src="/assets/images/maxatac_arch.PNG" alt="maxATAC: Architecture and Workflow" style="max-height: 256px; object-fit: contain;">
  </a>
  <figcaption style="text-align: center; font-style: italic; font-size: 0.9em; color: rgba(136, 5, 176, 0.99); margin: 0 auto; margin-top: 0em; margin-bottom: 1em">
    maxATAC: Architecture and Workflow
  </figcaption>
</figure>
<p style="margin-bottom: 0;">While genes are often considered the primary drivers of health and disease, many crucial mutations reside in noncoding regions—regulatory DNA sequences that determine when and where genes are activated. These regions are interpreted by transcription factors (TFs), specialized proteins that read DNA sequence to orchestrate gene expression in a highly cell-specific manner. However, systematically mapping TF binding sites across diverse cell types is a daunting challenge. maxATAC is a deep learning framework that harnesses ATAC-seq data to predict TF binding sites with remarkable accuracy. By integrating chromatin accessibility with deep neural networks, maxATAC unveils how genetic variants and cellular contexts influence gene expression and impact disease risk and progression.</p>
<p style="margin-bottom: 0; text-indent: 0em;">We built maxATAC, the most comprehensive suite of deep neural network models for transcription factor (TF) binding prediction—spanning 127 human TFs and counting! Unlike conventional motif scanning, which relies on static sequence patterns, maxATAC leverages real-world ATAC-seq datasets to train models that recognize cell-type-specific chromatin accessibility. Our approach integrates multi-cell-type training, deep convolutional architectures, and advanced data augmentation strategies to generalize TF binding predictions across diverse cellular contexts. Whether applied to bulk or single-cell ATAC-seq, maxATAC infers TF occupancy with unprecedented precision, enabling researchers to explore gene regulatory mechanisms in both health and disease.</p>
<h4 style="margin-top: 1em;">Key Highlights </h4>
  <ul>
    <li><strong>Wide Coverage:</strong>Genome-scale coverage for 127 TFs, each with a specialized deep CNN model.</li>
    <li><strong>Cross-cell-type robustness:</strong> MPredicts TF occupancy even in unseen primary cells or single-cell data.</li>
    <li><strong>Beyond motifs:</strong> Learns context-dependent features missed by basic motif scanning, yielding more accurate and insightful binding maps.</li>
  </ul>
<p style="margin-bottom: 0; text-indent: 0em;">With maxATAC, uncovering where TFs bind in living cells becomes more precise, scalable, and easier than ever. If you’re digging into transcriptional regulation, complex disease genetics, or single-cell studies, consider giving maxATAC a spin!</p>

<table style="width: 100%;  margin-top: 0em; border-collapse: collapse;">
  <tbody>
    <tr>
      <td style="width: auto; padding: 0em; text-align: left; vertical-align: middle; border: none;"><div style="font-size: 1.4em;">Learn More: </div></td>
      <td style="padding: 0.5em; border: none; vertical-align: middle;"><a href=" https://doi.org/10.1371/journal.pcbi.1010863" class="highlight-link" onclick="alert('Coming Soon!'); return false;"  target="_blank" rel="noopener noreferrer"><div style="font-size: 1.4em;">Paper</div></a></td>
      <td style="padding: 0.5em; border: none; vertical-align: middle; "><a href="https://github.com/MiraldiLab/maxATAC" class="highlight-link" onclick="alert('Coming Soon!'); return false;" target="_blank" rel="noopener noreferrer;"><div style="font-size: 1.4em;">Code</div></a></td>
    </tr>
    
  </tbody>
</table>
</div>

<div class="projects-page">
<div class="project-title-wrapper" style="text-align: center; margin-top: 1.5em">
<h2 class="project-title">Benchmarking HEp-2 Cell Segmentation Methods in Indirect Immunofluorescence Images - Standard Models to Deep Learning</h2>
</div>
<figure style="text-align: center; margin-bottom: 0em;">
  <a href="/assets/images/maxatac_arch.PNG" target="_blank" class="no-hover-effect" style="display: block; width: 100%; margin: 0 auto; margin-bottom: 0em">
    <img src="/assets/images/maxatac_arch.PNG" alt="HEp2" style="max-height: 256px; object-fit: contain;">
  </a>
  <figcaption style="text-align: center; font-style: italic; font-size: 0.9em; color: rgba(136, 5, 176, 0.99); margin: 0 auto; margin-top: 0em; margin-bottom: 1em">
    HEp2 Image: Need HEp2 Images...check how well this works
  </figcaption>
</figure>
<p style="margin-bottom: 0;">Indirect Immunofluorescence (IIF) is a gold-standard technique for detecting autoimmune diseases, relying on HEp-2 (Human Epithileal) cell imaging to identify autoantibodies linked to conditions such as lupus, rheumatoid arthritis, and multiple sclerosis. However, manual assessment of these fluorescence patterns is time-consuming and subject to variability, necessitating automated solutions for accurate and reproducible analysis.</p>
<p style="margin-bottom: 0; text-indent: 0em;">In this study, we conducted an extensive benchmarking of deep learning-based segmentation models for HEp-2 cell analysis, comparing 17 CNN-based architectures and 2 transformer-based models under diverse training conditions. Our experiments, leveraging the I3A dataset and rigorous statistical validation, establish baseline performance and highlight key challenges such as class imbalance and annotation quality. To address these issues, we evaluated advanced pretraining strategies, data augmentation techniques, and generative adversarial networks (GANs) for improving segmentation performance, particularly for underrepresented staining patterns.</p>
<p style="margin-bottom: 0; text-indent: 0em;">Our insights not only highlight the current state of HEp-2 cell segmentation but also provide a roadmap for future research, guiding the development of more sophisticated and robust deep learning models capable of overcoming the unique challenges posed by HEp-2 cell analysis.</p>
</div>
<table style="width: 100%;  margin-top: 0em; border-collapse: collapse;">
  <tbody>
    <tr>
      <td style="width: auto; padding: 0em; text-align: left; vertical-align: middle; border: none;"><div style="font-size: 1.4em;">Learn More: </div></td>
      <td style="padding: 0.5em; border: none; vertical-align: middle;"><a href="#" class="highlight-link" onclick="alert('Coming Soon!'); return false;"  target="_blank" rel="noopener noreferrer"><div style="font-size: 1.4em;">Paper</div></a></td>
      <td style="padding: 0.5em; border: none; vertical-align: middle; "><a href="#" class="highlight-link" onclick="alert('Coming Soon!'); return false;" target="_blank" rel="noopener noreferrer;"><div style="font-size: 1.4em;">Code</div></a></td>
    </tr>
    
  </tbody>
</table>



<!--Learn More | <a href="#" class="highlight-link" onclick="alert('Coming Soon!'); return false;">Paper</a> | <a href="#"  class="highlight-link" onclick="alert('Coming Soon!'); return false;">Code</a> font-size: 1.1em; style="font-size: 1.1em;"-->


<!-- This is the last div. -->


