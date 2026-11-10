# Mehedi Hasan

**Graduate Research Assistant · Michigan State University**  
Efficient and trustworthy machine learning · Foundation models · Computer vision · Robotic perception

I am an M.S. student in Biosystems Engineering at Michigan State University, with a B.S. in Computer Science from BRAC University. My research connects efficient learning and reliable evaluation with practical perception and automation systems. I am preparing for **Fall 2027 PhD applications**.

[Website](https://sites.google.com/view/i-am-mehedi) · [Google Scholar](https://scholar.google.com/citations?user=i_9-VFoAAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/mehedihasan96/) · [Email](mailto:hasanme1@msu.edu)

## Research interests

- **Efficient foundation models:** structural and token pruning, parameter-efficient adaptation, knowledge distillation, and vision-language learning.
- **Trustworthy machine learning:** calibration, uncertainty, selective prediction, out-of-distribution evaluation, and external validation.
- **Vision and intelligent systems:** medical imaging, remote sensing, detection and tracking, robotic manipulation, and intelligent sensing.
- **Privacy-preserving learning:** federated learning and resource-aware analytics.

## Selected research

### TAP-Path — Efficient and trustworthy pathology foundation models

Task-adaptive structural and token pruning for Virchow2, combined with reliability evaluation and frozen external validation. The [preprint](https://arxiv.org/abs/2609.04071) reports **24.96% fewer encoder parameters**, **35.20% lower analytical encoder FLOPs**, and **91.22% mean accuracy on 433 external CPTAC samples**.

**Status:** arXiv preprint, 2026.

### CIRR-MoE — Reliability-guided mixture of experts

Cross-inductive routing learned from out-of-fold expert errors, separating expert competence, prediction-failure risk, and unfamiliarity. The project studies conformal coverage, selective prediction, out-of-distribution detection, robustness, and external evaluation for industrial prediction.

**Status:** manuscript under review, 2026.

### ChainDoRA — Parameter-efficient LLM adaptation

Co-developed a Tensor-Train factorized extension of weight-decomposed low-rank adaptation. The [preprint](https://doi.org/10.13140/RG.2.2.25941.18402) reports **72.30% average accuracy across seven commonsense benchmarks** on LLaMA-7B with **5.35M trainable parameters**, compared with 56.98M for DoRA in the study's matched setting.

**Status:** preprint, 2026. · [Project repository](https://github.com/AshfakYeafi/Chain-DoRA)

### LIA-MTR — Memory-efficient vision-language learning

Co-developed a recurrent multi-timescale retention bridge with linear sequence-interaction complexity. The [preprint](https://arxiv.org/abs/2608.01614) reports processing **262,144 visual patches within 11.2 GB VRAM** in its hardware benchmark.

**Status:** arXiv preprint, 2026.

### AquaPick — Vision-guided robotic handling

A perception-to-action pipeline for deformable catfish fillets, integrating detection, Kalman tracking, conveyor-motion prediction, camera-to-robot mapping, and suction handling. My work includes dataset curation, detector evaluation, system integration, and physical validation with Cartesian and delta-arm systems.

**Status:** ongoing research and journal manuscript development. · [Related SPIE work](https://doi.org/10.1117/12.3095045) · [Related ASABE work](https://doi.org/10.13031/aim.202500466)

### LoveDA — Resolution-aware remote-sensing segmentation

Developed a SegFormer-B2 land-cover segmentation pipeline using weighted cross-entropy/Dice training and overlapping tiled inference.

| Validation inference protocol | mIoU |
| --- | ---: |
| Images resized to 512 × 512 | 49.45% |
| Native 1024 × 1024 images evaluated with overlapping 512 × 512 tiles | **53.09%** |

The tiled evaluation covered **1,669 LoveDA validation images** across seven land-cover classes. The **3.64 percentage-point gain** came from changing inference resolution and tiling with the retained checkpoint; additional continuation fine-tuning did not produce the selected improvement. These are project validation results, not a test-server or state-of-the-art claim.

**Status:** ongoing experimental project, 2026.

## Background

- **Michigan State University:** graduate research in machine vision, intelligent sensing, and robotic automation for food processing.
- **BRAC University and research collaborations:** computer vision, medical AI, efficient language models, and privacy-preserving learning.
- **Huawei Technologies Bangladesh:** former Solution Engineer working with service and network analytics.
- **BRACU Mongol Tori:** earlier contributions to rover perception and autonomy.

## Tools and engineering

**Research:** Python, C/C++, SQL, MATLAB, PyTorch, TensorFlow/Keras, Hugging Face Transformers/PEFT, scikit-learn, OpenCV, and YOLO.

**Systems:** Linux, Git, Docker, Jupyter, ROS/ROS2, camera calibration, tracking, and robotic integration.

**Software development:** JavaScript/TypeScript, React, Node.js, MySQL, MongoDB, and Firebase.

## Publications and contact

See my [Google Scholar profile](https://scholar.google.com/citations?user=i_9-VFoAAAAJ&hl=en) for the full publication record and my [website](https://sites.google.com/view/i-am-mehedi) for research updates.

For research opportunities and collaboration: **[hasanme1@msu.edu](mailto:hasanme1@msu.edu)**.

[Personal email](mailto:mehedihasan162120@gmail.com) · [X / Twitter](https://twitter.com/munnass95) · [Instagram](https://instagram.com/mahadi_munna/) · [Earlier résumé](https://drive.google.com/file/d/1ZmzDHSUNatlSz9ol8kFIRHpbdkLZoSoT/view)
