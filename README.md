# jupyter-exploration.

This repository holds the projects for my class 6271-ITAI-1378-Comp Vision-Artificial Intel-RT-16348. 

**Contents:**
* My_First_Notebook.ipynb
* L02_Zaldivar_Cesar_ITAI1378.ipynb
* L03_A_ZaldivarCesar_ITAI_1378.ipynb
* L04
* L05
* L06
* Midterm

Easy Pantry
Team Members
Cesar

Project Tier
Tier 1: One model doing one job — object detection with YOLO11

Problem Statement
Households often lose track of pantry inventory, leading to duplicate purchases, forgotten ingredients, and inefficient grocery planning. This matters to families and home cooks who want to save time, reduce waste, and streamline shopping.

Solution Overview
Easy Pantry uses object detection to identify pantry items such as pasta boxes, snack bags, and soda cans from a phone photo. The system counts each item type and generates a simple inventory report. Future versions may suggest recipes based on detected items.

Technical Approach
CV Technique: Object Detection

Model Architecture: CNN (YOLO11)

Model: YOLO11

How we will use it: Pretrained first, optional transfer learning

Framework: PyTorch + Ultralytics
Why this approach: YOLO11 is fast, accurate, and easy to run in Colab, making it ideal for multi-class pantry detection.

Dataset
Source: Personal pantry photos + optional Roboflow datasets

Size: ~100 images

Labels: pasta_box, snack_bag, soda_can

Link: Added later if using Roboflow

Success Metrics
Primary: mAP50 ≥ 0.85

Secondary: < 1 second per image

Milestone Plan
(Insert the 10-week table from Slide 7)

Resources
Compute: Google Colab

Cost: $0

Risks & Mitigation
Risk	Probability	Plan B
Not enough data	Medium	Use Roboflow datasets
Training slow	Medium	Use pretrained YOLO11


Demo Video
(To be added during final)

AI Usage Log
See docs/AI_usage_log.md

Current Status
[x] Repository created

[x] Proposal submitted

[ ] First working demo

[ ] System works on my data

[ ] Metrics measured

[ ] Final submitted 
