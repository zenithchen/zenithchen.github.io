## Projects
---
### Egocentric Cooking Video Analysis

<div class="project-tags">
  <span class="project-tag">VLMs</span>
  <span class="project-tag">Egocentric Video Understanding</span>
  <span class="project-tag">Action Recognition</span>
</div>

This project investigates how vision-language models can transform long, untrimmed egocentric cooking videos into structured representations of cooking processes. I developed a VLM-based evaluation pipeline for fine-grained action recognition, while ongoing research links action sequences with object identity, location, and physical state to study causal provenance and refine uncertain predictions. 

<img
  src="{{ '/images/egocentric_cooking_video.gif' | relative_url }}"
  alt="Egocentric cooking video analysis"
  style="width: 600px; max-width: 100%; height: auto;">

---
### SkinSense: AI-Assisted Skin Lesion Documentation and Tracking

<div class="project-tags">
  <span class="project-tag">Computer Vision</span>
  <span class="project-tag">SAM</span>
  <span class="project-tag">MedGemma</span>
  <span class="project-tag">React + FastAPI</span>
</div>

We developed SkinSense, a non-diagnostic, AI-assisted platform for documenting and tracking skin lesions over time. It organizes images, symptoms, and visible changes into longitudinal records that support communication with healthcare professionals. The system combines computer vision–based lesion segmentation and measurement with multimodal AI to generate consistent, non-diagnostic visual descriptions. 

<img src="images/mode-share-app2.png?raw=true"/>

[View Report](/content/SkinSense_Final_Report.pdf)

---
###  Urban Informal Settlement Detection 

<div class="project-tags">
  <span class="project-tag">Machine Learning</span>
  <span class="project-tag">Remote Sensing</span>
  <span class="project-tag">Sentinel-2 Imagery</span>
  <span class="project-tag">Google Earth Engine</span>
</div>

We developed a machine-learning framework that combines Sentinel-2 imagery with multi-scale spectral, textural, and structural features to map urban informal settlements across Guangzhou. The best-performing model achieved 93% overall accuracy, demonstrating a scalable approach to large-area urban analysis. 

<img src="images/mode-share-app2.png?raw=true"/>

[View Report](/content/Detecting Urban Informal Settlements with Remote Sensing_Final.pdf)

---
### Fire Response Situational Awareness Platform

<div class="project-tags">
  <span class="project-tag">Machine Learning</span>
  <span class="project-tag">REST API</span>
  <span class="project-tag">Geospatial Data</span>
</div>

The project is intended to present the methodology for analyzing property fire risk in Philadelphia and an API tool that aims to improve the fire department’s situational awareness. This new API tool can provide real-time information and assessments for all parcels in the city. We also built a web application using the API. [Click here to check out the app!](/cpln692_final/index.html)

<img src="images/fire_api.png?raw=true"/>

[View Report](/content/Fire_Response_Situational_Awareness_API.html)

---
### Train Occupancy Prediction

<div class="project-tags">
  <span class="project-tag">R</span>
  <span class="project-tag">Multinomial Logistic Regression</span>
  <span class="project-tag">Geospatial Data</span>
</div>

In this project, we built multinomial logit models to spatially predict the occupancy levels of Belgian. Specifically, the spatial network of the trains was analyzed to select the OD pairs and train lines with certain characteristics of occupancy levels to increase accuracy while ensuring generalizability. Cost-benefit analysis was used to adjust the model. 
The final model has a relatively high total accuracy of 0.8 and a satisfying generalizability.

<img src="images/EA-spatial network.png?raw=true"/>

We also designed a website called SmartOccupancy with 3 main functions to help transportation planners rebalance train service provision and maximize profit. <a href="https://www.youtube.com/watch?v=i8b7DR42uhw">Check out the video here</a>

<img src="images/trainoccupancy.png?raw=true"/>

[View Code](/content/occupancy_prediction.html)

<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
