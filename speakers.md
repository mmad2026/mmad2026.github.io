---
layout: post
title: Speakers
---

<style>
        .profile-container {
            display: flex;
            align-items: flex-start;
            gap: 30px;
            margin: 20px auto;
            padding: 20px;
            font-family: Arial, sans-serif;
        }

        .profile-image {
            width: 300px;
            height: 300px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .profile-info {
            flex: 1;
        }

        .profile-name {
            font-weight: bold;
            font-size: 1.5em;
            margin: 0 0 8px 0;
            color: #333;
        }

        .profile-links {
            font-style: italic;
            font-size: 1.1em;
            margin: 0 0 15px 0;
        }

        img.link {
            width:20px;
        }

        .profile-affiliation {
            font-style: italic;
            color: #666;
            margin: 0;
            font-size: 1.1em;
        }

        .profile-bio {
            line-height: 1.6;
            color: #444;
            margin: 0;
        }
        .talk-summary {
            color: #555;
            line-height: 1.5;
            text-align: justify;
        }
        .talk-title {
            font-weight: bold;
            margin-bottom: 8px;
            font-size: 18px;
            margin: 10px 0;
        }

        /* Responsive design for mobile */
        @media (max-width: 600px) {
            .profile-container {
                flex-direction: column;
                text-align: center;
            }

            .profile-image {
                width: 150px;
                height: 150px;
            }
        }
</style>

<h1>Speakers</h1>

<div class="profile-container">
    <img src="assets/img/photos/radu.png" alt="Radu" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Radu Ionescu <a href="https://raduionescu.herokuapp.com"><img src="assets/img/globe.png" class="link"></a></h2>
        <p class="profile-affiliation">Professor, University of Bucharest (Romania)</p>
        <p class="talk-title">Scalable real-time abnormal event detection</p>
        <p class="talk-summary">
State-of-the-art video anomaly detectors typically rely on a costly object detection method to increase precision, limiting the processing bandwidth to one video stream per GPU, at around 20-30 FPS. However, for real-world video surveillance, e.g. monitoring an entire city with hundreds or thousands of cameras, the processing costs of object-centric video anomaly detectors are simply too high, given their power consumption and the cost of GPUs. To this end, we will present two lightweight models, capable of processing over 60 video streams at 25 FPS, significantly reducing the processing costs. Different from competing models performing anomaly detection at the object or spatio-temporal cube levels, we present models that take whole video frames as input, which is significantly more efficient. The presented models employ several techniques to achieve efficiency, e.g. adversarial knowledge distillation, self-distillation and masked auto-encoders. Comprehensive experiments on four benchmarks show that the presented methods are significantly faster than state-of-the-art methods, while achieving comparable accuracy levels.
        </p>
    </div>
</div>

<div class="profile-container">
    <img src="assets/img/photos/wenwu.png" alt="Wenwu" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Wenwu Wang <a href="https://personalpages.surrey.ac.uk/w.wang/"><img src="assets/img/globe.png" class="link"></a></h2>
        <p class="profile-affiliation">Professor, University of Surrey (United Kingdom)</p>
        <p class="talk-title">Anomalous Sound Detection</p>
        <p class="talk-summary">
Anomalous Sound Detection (ASD) is a vital research field aimed at identifying abnormal or unexpected sounds in acoustic environments, often without prior knowledge of the anomalies themselves. It has broad applications in areas such as industrial monitoring, surveillance, healthcare, and environmental sensing, where early detection of unusual sounds can indicate equipment malfunctions, safety risks, or other critical events. ASD systems typically learn the characteristics of normal acoustic patterns and detect deviations from these patterns using signal processing and machine learning methods. In this talk, we will explore recent advances in anomalous sound detection, highlighting key challenges, emerging techniques, and future research opportunities. We will also present our latest work on contrastive, self-supervised, and statistical approaches designed to enhance robustness, domain generalization, and anomaly sensitivity across noisy, domain-shifted, and machine-specific industrial datasets.
        </p>
    </div>
</div>

