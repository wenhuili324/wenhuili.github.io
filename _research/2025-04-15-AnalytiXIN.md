---
title: "AI-Driven Energy Analytics for Manufacturing (AnalytiXIN)"
layout: post
mathjax: true
categories: media
---
I participated two sub-projects under the `AnalytiXIN` initiative.

The first sub-project was conducted in collaboration with Toyota. Their paint defect inspection process relies on the Surface Verification System (SVS), which uses multiple cameras to capture images of every angle and inch of a car’s surface. These images are then analyzed to highlight potential defect areas. However, the system generates a high number of false positives—regions flagged as defects that are not actual flaws—leading to a time-consuming manual review process.

To address this, we developed a deep neural network that correlates environmental conditions in the painting booth—such as temperature, humidity, and airborne particle concentration—with the occurrence and location of defects. Our model achieved over 80% accuracy in distinguishing true defects from false positives. This allows engineers to prioritize inspections for vehicles more likely to have real defects and also provides insights for optimizing painting booth conditions to reduce the likelihood of future defects.

The second sub-project focused on predicting the energy usage of manufacturing facilities, including systems such as HVAC and lighting. Accurate forecasting of temporal energy consumption can significantly enhance power supply management and reduce energy waste. In this work, we explored various deep learning models, including a novel dynamic attention-based recurrent neural network (A-RNN) for industrial energy forecasting. Our proposed model, A-RNN, demonstrated superior performance, reducing prediction errors by up to 50% compared to standard RNN models.

We further developed an end-to-end solution by integrating A-RNN with two databases and a visualization pipeline, enabling comprehensive energy data management and analysis. This system empowers small and mid-sized manufacturers to better understand their energy consumption patterns, correlate them with machinery and operational processes, and ultimately improve energy efficiency while reducing their carbon footprint.

See our publications:
[Industrial Energy Forecasting Using Dynamic Attention Neural Networks](https://doi.org/10.1016/j.egyai.2025.100504)

