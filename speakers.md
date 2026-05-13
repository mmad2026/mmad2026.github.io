---
layout: post
title: Speakers
---

More to be announced.


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
            margin: 0;
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
    <img src="assets/img/photos/lars.png" alt="Lars" class="profile-image" />
    <div class="profile-info">
        <h2 class="profile-name">Lars Kai Hansen <a href="http://eivind.imm.dtu.dk/staff/lkhansen/lkhansen.html"><img src="assets/img/globe.png" class="link" /></a></h2>
        <p class="profile-affiliation">Professor, Technical University of Denmark (Denmark)</p>
        <p class="talk-title">Missing-Data-Induced Phase Transition in Spectral PLS for Multimodal Learning</p>
        <p class="talk-summary">
        Partial Least Squares (PLS) learns shared structure from paired data via the top singular vectors of the empirical cross-covariance (PLS-SVD), but multimodal datasets often have missing entries in both views. We study PLS-SVD under independent entry-wise missing-completely-at-random masking in a simple high-dimensional model. We find theoretically and empirically that PLS-SVD exhibits a sharp BBP-type phase transition: below a critical signal-to-noise threshold the leading singular vectors are asymptotically uninformative, while above it they achieve nontrivial alignment with the "planted" shared directions. The theoretical analysis provides closed-form asymptotic overlap formulas.
        </p>
    </div>
</div>
