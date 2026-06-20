## Hi there 👋

My name is Harshith Kethavath. I'm an MS Computer Science student at the University of Georgia, currently an Applied ML Engineer at [Lab for Geoinformatics and AI Modeling](https://github.com/uga-gaim). My current work is **SignsOfExtremes**, where I use computer vision for extreme weather event prediction.

*Open to Applied/ML Engineer and ML Systems roles.*

#### EarthVision Workshop at CVPR 2026
[Low-Data Supervised Adaptation Outperforms Prompting for Cloud Segmentation Under Domain Shift](https://openaccess.thecvf.com/content/CVPR2026W/EarthVision/papers/Kethavath_Low-Data_Supervised_Adaptation_Outperforms_Prompting_for_Cloud_Segmentation_Under_Domain_CVPRW_2026_paper.pdf) *Kethavath & Hu - Proceedings of the IEEE/CVF CVPR Workshops, 2026*

Zero-shot VLM prompting fails on Sentinel-2 cloud segmentation under domain shift, and the 60 engineered CLIPSeg prompts scored as low as 0.07 mIoU against a 0.255 baselne. Supervised adaptation overtakes all prompting at roughly 8 labeled images, and 5-10% of labels recover ~85% of peak mIoU.

Code, experiments and models -> [`uga-gaim/2026_CVPRW_CloudPrompts`](https://github.com/uga-gaim/2026_CVPRW_CloudPrompts)

#### Selected Work
[MarsDEMNet](https://github.com/harshithkethavath/MarsDEMNet) - Single-image elevation (DEM) prediction from Mars satellite imagery. Built and ablated 4 architectures on 80,000+ NASA image pairs; a 5-block multi-output U-Net reaches 59.9m validation RMSE via multi-task masked MAE loss over elevation, slope, and roughness. Diagnosed a Lustre filesystem bottleneck on HPC and cut per-epoch data loading from 3,800s to under 600s with RAM-cache preloading.

[WeatherMind](https://github.com/harshithkethavath/WeatherMind) - Modular VLM framework for weather analysis on sky imagery across 4 backends (Qwen, SmolVLM2, Moondream2, Gemma3) with context-aware prompting. A spatiotemporal ETL pipeline (Pandas + OCR) aligns image timestamps with ASOS station logs to generate 15,000+ ground-truth labels, alongside a zero-shot weather-feature detector on open-vocabulary object detection.
