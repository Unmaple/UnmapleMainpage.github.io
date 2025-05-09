---
permalink: /
title: "Mingjie Zeng"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<div class="grid__wrapper">
  <div class="grid__item">
    <h2 class="archive__item-title">Education</h2>
    <ul class="taxonomy__index">
      <li>
        <strong>Huazhong University of Science & Technology</strong><br>
        B.Eng in Automation (AI & Automation School)<br>
        GPA: 4.71/5.0 | National Scholarship (2023-2024)
      </li>
      <li>
        <strong>University of Cambridge</strong><br>
        Summer Research Student (Lucy Cavendish College)<br>
        Top 25% Outstanding Participant
      </li>
    </ul>

    <h2 class="archive__item-title">Research Focus</h2>
    <ul class="taxonomy__index">
      <li>Medical AI: TrustedMed diagnostic system development</li>
      <li>Edge Computing: Embedded deployment of CV algorithms</li>
      <li>Computational Biology: Molecular property prediction</li>
    </ul>

    <h2 class="archive__item-title">Selected Projects</h2>
    <ul class="taxonomy__index">
      <li>
        <a href="/portfolio/lightning-identification/">
          Lightning Waveform Identification System<br>
          <small>Accuracy improved from 65% to 97% with InceptionTime model</small>
        </a>
      </li>
      <li>
        <a href="/portfolio/compound-toxicity/">
          Molecular Toxicity Prediction<br>
          <small>Developed WeightedKNN model with mol2vec embeddings</small>
        </a>
      </li>
      <li>
        <a href="/portfolio/crowd-analysis/">
          Embedded Crowd Analysis System<br>
          <small>Deployed YOLOX+ByteTrack on RK3588 platform</small>
        </a>
      </li>
    </ul>
  </div>

  <div class="grid__item">
    <h2 class="archive__item-title">Latest Updates</h2>
    <ul class="taxonomy__index">
      <li>2024.08 - Paper accepted by IEEE TIM (1st author)</li>
      <li>2024.07 - Joined LairLab for medical AI research</li>
      <li>2024.06 - Won National Mathematical Modeling 1st Prize</li>
    </ul>

    <div class="notice--info">
      <strong>Connect with me:</strong><br>
      <a href="/cv/" class="btn btn--inverse">Full CV</a>
      <a href="/publications/" class="btn btn--inverse">Publications</a>
      <a href="/contact/" class="btn btn--inverse">Contact</a>
    </div>
  </div>
</div>

<style>
.grid__wrapper {
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 2rem;
}

@media screen and (max-width: 768px) {
  .grid__wrapper {
    grid-template-columns: 1fr;
  }
}
</style>
