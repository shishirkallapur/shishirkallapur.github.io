---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👤 About Me

I am a graduate student at Northeastern University and have finished my Master's in Artificial Intelligence with a specialization in Machine Learning. I am fascinated by the software and technology currently being developed to produce extraordinary results. I completed my Bachelor of Engineering in CS from NIE,Mysuru.

I'm passionate about innovation and love learning new things quickly. I believe in the power of technology to make a positive impact. I bring strong technical skills, adaptability, and a determined attitude to everything I do.

I believe that my technical skills, passion for innovation, and never willing to give up makes me a valuable asset to the team and I'm driven to use my skills to create meaningful change .I'm eager to explore opportunities where I can contribute and grow while making a difference.

Click here to view my [CV](https://shishirkallapur.github.io/files/Shishir_Kallapur_Resume.pdf).

# 💼 Experience

**Amplifier Security** — *AI Product Intern*  
May 2024 - Aug 2024 (Summer)  
- Spearheaded a comprehensive benchmarking initiative for GPT models, significantly enhancing Ampy’s response accuracy, speed and overall performance.
- Implemented guardrails and prompts that boosted topical relevance by 35%, reducing hallucinations.
- Automated response evaluation with custom Python scripts, improving testing speed by 3x.
- Implemented a Retrieval-Augmented Generation (RAG) prototype with LangChain using Pinecone as Vector DB, enabling contextual replies from proprietary unstructured data.

**JPMorgan Chase & Co.** — *Software Engineer*  
Sept 2021 – Aug 2023  
- Overhauled ServiceNow Knowledge module, enhancing request resolution speed by 20%.
- Integrated JIRA with ServiceNow to automate SDLC tracking and reporting, incorporating CI/CD automation best practices and reducing manual effort by 40%.
- Delivered 5 reusable UI macros to streamline HR documentation workflows; improved HR team’s document update efficiency by 45%.
- Introduced and deployed catalog automation features, reducing request handling time by 30%.

**MiQ Digital** — *Software Developer Intern*  
Jan 2021 - Jul 2021
- Implemented full-stack features using Spring Boot and AngularJS, enhancing platform performance and UX.
- Integrated DSPs (Xandr, DV360) into internal tools, streamlining campaign activation and data processing.
- Enabled DV360 as a viable DSP option, accelerating project timelines and increasing platform utility.  

# 🚀 Projects

## ⚕️ Movie Recommendation System
[GitHub Repo](https://github.com/shishirkallapur/recommendation-system-local)  
This project is an end-to-end, production-style movie recommendation system built for learning MLOps practices. Runs fully on a local machine using open-source tools.

## ⚕️ Local Document-Powered RAG Chatbot
[GitHub Repo](https://github.com/shishirkallapur/Local-Document-Powered-RAG-Chatbot)  
This project is a Streamlit application that enables users to upload PDF documents, process them for information retrieval, and interact with the content through a conversational interface powered by Large Language Models (LLMs) and RAG.

## ⚕️ CS6140: Relating Physical Activity to Problematic Internet Use in Youths  
[GitHub Repo](https://github.com/shishirkallapur/CS6140-Relating-Physical-Activity-to-Problematic-Internet-Use-in-Youths)  
The project is based on a [Kaggle Competition](https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use) where the goal of this project is to develop a model capable of identifying the potential risk of problematic internet use among youths by utilizing relevant physical activity data and internet usage data.

## ⚕️ CS5180: Enhancing Bipedal Robot Locomotion Using Reinforcement Learning with Reference Signal Integration
[GitHub Repo](https://github.com/shishirkallapur/CS5180-RLBipedRobotLocomotion)  
This is our final project for CS5180 Spring 2024 under Professor Lawson L.S Wong. The goal of this project is to enable the successful navigation of a bipedal robot in a custom environment by seamlessly integrating control systems architecture and reinforcement learning (RL) techniques.

## ⚕️ CS5010: Image Processor  
[GitHub Repo](https://github.com/shishirkallapur/CS5010-Image_Processor)  
This is our final project for CS5010 Fall 2023 under Professor Amit Shesh. The project is based on building an image processing application designed with MVC architecture.The application takes in an image and performs an operation on the input image to produce a desired outcome.

## ⚕️ CS5100: Adaptive Difficulty in Games: Leveraging Reinforcement Learning for Player-Driven Immersion 
[GitHub Repo](https://github.com/shishirkallapur/CS5100-Adaptive-Difficulty-in-Games)  
This is our final project for CS5100 Fall 2023 under Professor Rajagopal Venkatesaramani. The project utlizes Reinforcement Learning (RL) to create game levels that adapt to each player’s unique strengths, weaknesses, and preferences.The project also involved creating an Adversarial RL system to test both "Player" and "Environment" working together, where the player is trying to clear levels with ease whereas the "Environment" is continuously learning the "Player"s skills to make levels more difficult.

## ⚕️ CS6120: Comparative Analysis of nGPT, PEGASUS, and BART in Abstractive Text Summarization 
[GitHub Repo](https://github.com/shishirkallapur/CS6120-nGPT-BART-PEGASUS-efficiency-study)  
This is our final project for CS6120 Fall 2024 under Professor Silvio Amir. This project aims to evaluate and compare the performance of nGPT (Nvidia's model) against two state-of-the-art abstractive text summarization models: PEGASUS (Google) and BART (Facebook). The focus is on assessing nGPT's claims of achieving 4-20x faster training times and improved stability for Large Language Models (LLMs) in the context of abstractive text summarization.

## ⚕️ CS5170: Emotion-Driven Audio-Visual Experience: Enhancing Human-Computer Interaction through Real-Time Multimodal Feedback
[GitHub Repo](https://github.com/shishirkallapur/CS5170-Emotion-Driven-Multi-Modal-AI)  
This is our final project for CS5170 Spring 2025 under Professor Stacey Marsella. This project explores an AI-driven system for generating immersive and personalized audio-visual experiences by detecting user emotions and intent in real time.


<!-- # 🔥 News

<font color='red'>2025 Fall PhD/Postdoc positions available here! If you are interested, please feel free to reach out to me or Professor Mallesham Dasari! </font>

- *2025.04*: &nbsp;🙌 Our paper: [TVMC: Time-Varying Mesh Compression Using Volume-Tracked Reference Meshes](https://dl.acm.org/doi/abs/10.1145/3712676.3714440) has been honored with the **Best Reproducible Paper Award** at [2025 MMsys](https://2025.acmmmsys.org/)! South Africa is amazing!
- *2025.02*: &nbsp;🤞 Our demo: [Remote Human-Robot Collaboration in XR](https://sinrg.org/papers/RoboTwin_Demo_HotMobile_24.pdf) has been honored with the **Best Demo Award** at [2025 HotMobile](https://2025.acmmmsys.org/)!
- *2025.01*: &nbsp;🎉 My submission to [2025 ACM MMSys](https://2025.acmmmsys.org/) has been accepted! I'll be heading to Stellenbosch, South Africa, in March 2025!
- *2024.12*: &nbsp;🎉 My submission to [2025 HotMobile](http://www.hotmobile.org/2025/) has been accepted. I'll be heading to Palm Springs, California, in February 2025!
- *2024.09*: &nbsp;😎 I submitted my first conference paper to [2025 ACM MMSys](https://2025.acmmmsys.org/)!
- *2024.08*: &nbsp;🎉 I began my exciting PhD journey at Northeastern University under the guidance of the wonderful Assistant Professor Mallesham Dasari! -->

<!-- # 💡 Research

I am going to explore the future of immersive media and do something cool to shape the future of communication! Currently, I mainly focus on AR/VR, 3D Mesh/Point Cloud compression, and spatial/volumetric video streaming. I am also interested in AI-based 3D content compression and streaming technologies. -->
<!--
# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MMSys 2025</div><img src='images/TVMC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size: 16px; font-weight: bold;">
            TVMC: Time-Varying Mesh Compression Using Volume-Tracked Reference Meshes
    </span>


**Guodong Chen**, Filip Hácha, Libor Váša, Mallesham Dasari.

The 16th ACM Multimedia Systems Conference (MMSys)

[![Code Stars](https://img.shields.io/github/stars/SINRG-Lab/TVMC?style=social&label=Code Stars)](https://github.com/SINRG-Lab/TVMC) <span class='show_paper_citations' data=''></span>![Static Badge](https://img.shields.io/badge/Best%20Reproducible%20Paper%20Award-blue) ![Presenter](https://img.shields.io/badge/Presenter-✅-while  )

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">HotMobile 2025</div><img src='images/HotMobile2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="font-size: 16px; font-weight: bold;">
            Spatial Video Streaming on XR Headsets
    </span>



**Guodong Chen\***, Sizhe Wang\*, Jacob Chakareski, Dimitrios Koutsonikolas, Mallesham Dasari.

The 26th International Workshop on Mobile Computing Systems and Applications (HotMobile)

![Presenter](https://img.shields.io/badge/Presenter-✅-while)

</div>
</div> -->

<!-- ## 🎠Demo

- ![HotMobile 2025](https://img.shields.io/badge/HotMobile-2025-blue) [Remote Human-Robot Collaboration in XR](https://sinrg.org/papers/RoboTwin_Demo_HotMobile_24.pdf), Yang Zhewen\*, **Guodong Chen\***, Mayank Chadha, Barath Balamurugan, and Mallesham Dasari. In *Proceedings of the 26th International Workshop on Mobile Computing Systems and Applications*, pp. 131-131. 2025. ![Static Badge](https://img.shields.io/badge/Best%20Demo%20Award-blue)&nbsp;[![Static Badge](https://img.shields.io/badge/Demo%20Video%20Link-8A2BE2)](https://youtu.be/7PKZyjSJMXk)&nbsp;![Presenter](https://img.shields.io/badge/Presenter-✅-while  ) -->

# 📖 Education

- _2023.09 - 2025.05_, Graduate, Northeastern University, US
- _2017.09 - 2021.05_, Undergraduate, The National Institute of Engineering, India

<!-- # 🎮 Miscellaneous

I did Mathematical Olympiad in high school.

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=n&d=97bHT3iHb1RyhPmFRzsHz-UbADoRGZFiIviWP0M94Fw'></script> -->

<p style="text-align:right;font-size:small;" >Last updated: Jul. 29, 2025</p>
