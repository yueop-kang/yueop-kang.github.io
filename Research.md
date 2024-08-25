---
layout: default
title: Research Topic
---


<div style="display: flex; justify-content: space-between; flex-wrap: nowrap; padding: 20px;">
  <a href="/research_topic1">
    <img src="assets/images/test-image.jpg" alt="Figure 1" style="width: 80%; max-width: 400px; height: auto;"/>
  </a>
  <a href="/research_topic2">
    <img src="assets/images/test-image.jpg" alt="Figure 2" style="width: 80%; max-width: 400px; height: auto;"/>
  </a>
  <a href="/research_topic3">
    <img src="assets/images/test-image.jpg" alt="Figure 3" style="width: 80%; max-width: 400px; height: auto;"/>
  </a>
</div>

<style>

  @media (max-width: 800px) {
    div {
      flex-wrap: wrap;
    }
    div img {
      width: 45%;
      margin-bottom: 10px;
    }
  }

  @media (max-width: 500px) {
    div img {
      width: 100%;
      margin-bottom: 10px;
    }
  }
</style>