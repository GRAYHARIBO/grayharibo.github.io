---
layout: default
title: Development of Soft Actuators to Prevent Heart Failure
---

# {{ page.title }}

<div class="message">
Undergraduate Research Intern, Sep. 2023 – Jun. 2024  
The <a href="https://hero.snu.ac.kr/">Healthcare Robotics Lab (HeRo Lab)</a> at Seoul National University specializes in implantable medical devices and soft actuators. Under the supervision of Prof. Amy Kyungwon Han, I worked alongside Yongjin Kim and Jeong Hyeon Lee on developing soft actuators designed to prevent heart failure, as well as pneumatic soft actuators without drivelines.
</div>

<img src="/images/svc.jpg" alt="SVC Occlusion Mechanism" style="width: 50%; float: right; margin: 0.5rem; border-radius: 5px;">

<small style="display: block; text-align: right; font-size: 0.8rem; margin-top: -0.5rem;">
Image Source: <a href="https://my.clevelandclinic.org" target="_blank" style="color: #555;">Cleveland Clinic</a>
</small>


Heart failure can be caused by various factors, including coronary artery diseases like angina or myocardial infarction, which are often linked to aging. Other causes include primary myocardial diseases and hypertension. To address heart failure, mechanical circulatory support devices like Left or Right Ventricular Assist Devices (LVADs or RVADs) and intra-aortic balloon pumps are sometimes used. For our project, we investigated a technique based on findings that show occluding and releasing the superior vena cava (SVC) in patients with high pulmonary arterial pressure could reduce the pressure exerted on the pulmonary artery. This concept, outlined in [this study](https://link.springer.com/article/10.1007/s12265-019-09916-y), formed the foundation for developing our SVC occlusion mechanism.

### Conceptual Design and Mechanism Development

To create an effective occlusion and release mechanism for the SVC, I developed two primary approaches:

1. **Internal Occlusion Mechanism**:
   - For this approach, I explored methods to reduce the vessel’s effective cross-sectional area from within. Specifically, I investigated using a **low-melting point alloy (LMPA)** and origami structures to occlude the SVC, inspired by techniques used in [this research](https://www.science.org/doi/10.1126/scirobotics.abg2171). I also experimented with **shape memory alloys (SMA)**, which exhibit contraction when heated.
   - While these methods showed potential for effectively reducing blood flow, they posed challenges. Direct contact with blood increased the risk of **hemolysis** and other secondary damage. Additionally, prolonged contact with the inner vessel walls could lead to tissue damage, which would be particularly concerning for long-term applications.

2. **External Occlusion Mechanism**:
   - To avoid the risks associated with internal occlusion, we shifted focus to an external occlusion mechanism, aiming for a device that would wrap around the vessel and apply pressure from outside. This approach would be simpler mechanically and reduce the likelihood of direct contact with blood or vessel tissue.
   - I designed and tested two types of actuators for this purpose:
     - **Peano-HASEL Actuators**: Using electrostatic and hydraulic principles, this actuator shortens in length upon voltage application. I fabricated this actuator and tested its feasibility for controlled SVC occlusion, confirming its potential (see image below).
     
       <img src="/images/peano_hasel.png" alt="Peano-HASEL Actuator Prototype" style="width: 100%; margin: 0.5rem; border-radius: 5px;">

     - **Liquid-Gas Phase Change Actuator**: This actuator, which I developed in more depth, leverages the phase transition of a low-boiling point material to achieve effective occlusion without a driveline.

### Detailed Study on Liquid-Gas Phase Change Actuator

In this approach, I focused on using **3M Novec 7000**, a phase-change material with a boiling point of 34°C, which transitions from liquid to gas through **Joule heating**. The concept was to design a pneumatic actuator that could function effectively in vivo without relying on external pumps or drivelines. This design required a silicone-based structure and a heating circuit that would heat the Novec 7000, causing it to vaporize and create pneumatic pressure.

<img src="/images/joule_heating.png" alt="Joule Heating Pressure Test" style="width: 50%; float: right; margin: 0.5rem; border-radius: 5px;">

#### Design and Fabrication Process
- **Silicone-Based Structure**: The actuator structure was made from silicone for its high elasticity and thermal endurance, inspired by work from Martinez, Ramses V., et al. Silicone provided the necessary flexibility to withstand the volume changes induced by the phase transition.
- **Heating Circuit**: I designed a heating system using **NiCr wires** embedded within the actuator, which could be controlled via an Arduino-based circuit and power supply. The heating circuit allows precise control over the phase transition process by regulating temperature.

#### Experimental Results and Challenges
- **Pressure Variability**: I conducted a series of experiments to measure pressure changes in response to Joule heating, allowing us to validate the actuator’s potential for effective SVC occlusion.
- **Leakage and Consistency**: Although the actuator demonstrated promising pressure capabilities, some challenges remained. Inconsistent wall thickness due to fabrication limitations led to uneven operation, and minor leakage concerns arose, which would require further design improvements for safe in vivo application.

### Academic and Extracurricular Involvement
During my time in this lab, I also had the opportunity to attend the **2024 Korea Robotics Society Conference**. This experience allowed me to explore a wide range of ongoing research in robotics, providing valuable insights and inspiration for my own work. Additionally, it was a chance to bond with lab colleagues through team activities like snowboarding, fostering a collaborative and supportive environment within the lab.

<img src="/images/robotics_conference.jpg" alt="Korea Robotics Society Conference 2024" style="width: 100%; margin: 0.5rem; border-radius: 5px;">

### Reflections and Insights
This project was instrumental in deepening my understanding of cardiovascular diseases and medical treatment methods. Through iterative discussions and collaboration with professors and team members, I explored innovative engineering solutions for medical device development, validated proof-of-concept mechanisms, and gained practical experience in designing and testing actuator systems.

### Equipment Frequently Used
- **SLA Printer**: Used for fabricating precise silicone molds required for actuator construction.
- **Silicone Curing Oven**: Essential for curing silicone components used in actuator designs.
- **Vacuum Chamber**: Used for degassing and curing silicone, ensuring uniformity in the actuator structure.
- **Arduino**: Utilized for controlling analog circuits within the actuator setups.
- **Mark-10 Force Gauge**: For measuring the force output of the soft actuators.
