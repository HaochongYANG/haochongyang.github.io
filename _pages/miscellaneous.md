---
layout: archive
title: "Miscellaneous"
excerpt: "Awards, skills, and hobbies description for Rogers Yang."
permalink: /miscellaneous/
author_profile: true
redirect_from: /miscellaneous.html
---

## Awards
- **University of Toronto Excellence Award (UTEA, $7500)** — University of Toronto, 2025
- **Louis Savlov Scholarships in Sciences and Humanities ($500)** — University College, 2025
- **Summer Undergraduate Data Science Scholarship (SUDS, $7500)** — Data Science Institute, 2024
- **C.L. Burton Scholarship for Mathematics and Physical Sciences ($500)** — University College, 2023
- **Louis Savlov Scholarships in Sciences and Humanities ($500)** — University College, 2022
- **University of Toronto Scholar Award ($1500)** — University of Toronto, 2022
- **Dean’s List Scholar Awards** — Faculty of Arts & Science,  2022 - 2024

## Technical Skills
- **Coding:** Python, Java, JavaScript, C++, Shell, Assembly
- **Data:** R, SQL, Tableau, PowerBI, Kafka, Docker
- **Frameworks:** TensorFlow, PyTorch, Langchain, Django
- **Packages:** Pandas, NumPy, Matplotlib, Scikit-Learn

## Fun Facts
My name is Rogers, which is the English name given by my parents following the famous humanistic psychologist Carl Rogers. I go by it because it's easier to pronounce than my Chinese name Hàochōng (昊翀). Interesting fact is that the character Hao (昊) means the vast sky, and Chong (翀) means bird soaring upwards.

## Sports
- Ultimate Frisbee
- Competitive Swimming
- Running


<head>
  <meta charset="UTF-8">
  <title>Swiper Example</title>
  <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />
  <style>
    .swiper {
      width: 600px;  /* 设置容器宽度 */
      height: 400px; /* 设置容器高度 */
      margin: 0;
    }
    .swiper-slide img {
      width: 100%;
      height: auto;
    }
  </style>
</head>

<!-- 引入 Swiper 的 CSS -->
<link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />

<!-- Swiper 容器 -->
<div class="swiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide"><img src="../images/sports1.JPG" alt="Photo 1"></div>
    <div class="swiper-slide"><img src="../images/sports3.jpeg" alt="Photo 2"></div>
  </div>
  <!-- 如果需要左右导航按钮 -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
</div>

<!-- 引入 Swiper 的 JS -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
<script>
  const swiper = new Swiper('.swiper', {
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
  });
</script>
