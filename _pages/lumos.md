---
#title: "Lumos"
permalink: /lumos/
layout: single
author_profile: true
---

<!-- Load elegant font, Bengali font, and lightbox assets -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@1,600&family=Noto+Serif+Bengali&display=swap" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/glightbox/dist/css/glightbox.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/glightbox/dist/js/glightbox.min.js"></script>
<script>
document.addEventListener("DOMContentLoaded", function() {
  GLightbox({ selector: '.glightbox' });
});
</script>

<style>
@keyframes fadeInUp {
  0% { opacity: 0; transform: translateY(20px); }
  100% { opacity: 1; transform: translateY(0); }
}
.fade-in { animation: fadeInUp 1.2s ease-out both; }

.lumos-wrapper {
  max-width: 800px;
  margin: 60px auto 40px auto;
  font-family: 'Playfair Display', serif;
  text-align: center;
  position: relative;
}
.lumos-title {
  font-size: 36px;
  font-style: italic;
  line-height: 1.5;
  padding: 40px 20px;
  position: relative;
}
.lumos-title::before,
.lumos-title::after {
  font-size: 100px;
  font-family: 'Playfair Display', serif;
  position: absolute;
  opacity: 0.4;
}
.lumos-title::before { content: "\201C"; top: -20px; left: -20px; }
.lumos-title::after { content: "\201D"; bottom: -20px; right: -20px; }

.lumos-section {
  max-width: 800px;
  margin: 0 auto;
  padding-top: 10px;
  font-size: 16px;
  line-height: 1.7;
}

.lumos-section h2 {
  font-size: 24px;
  font-family: 'Playfair Display', serif;
  font-weight: bold;
  text-align: left;
  margin-top: 60px;
  margin-bottom: 10px;
  position: relative;
}

.lumos-section h2::before {
  content: "";
  position: absolute;
  bottom: -6px;
  left: 0;
  width: 50px;
  height: 2px;
  background-color: #aaa;
}

.poem-block {
  font-family: 'Playfair Display', serif;
  font-style: italic;
  font-size: 18px;
  margin-top: 20px;
  margin-bottom: 30px;
  padding-left: 20px;
  border-left: 3px solid #999;
}

.poetry-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin-top: 30px;
}

.poem-img-block {
  width: 180px;
  text-align: center;
}
.poem-img-block img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.3);
  transition: transform 0.3s ease;
}
.poem-img-block img:hover {
  transform: scale(1.03);
}
.caption-row {
  margin-top: 8px;
  font-size: 14px;
  font-style: italic;
  line-height: 1.4;
}
.caption-row span:first-child {
  display: block;
  font-family: 'Noto Serif Bengali', serif;
}

.fivek-flex {
  display: grid;
  grid-template-columns: 200px 1fr;
  align-items: center;
  gap: 20px;
  margin-top: 50px;
}
.fivek-img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
}

.art-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
  margin-top: 20px;
}
.art-card {
  text-align: center;
  max-width: 220px;
  position: relative;
}
.art-card img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.3);
  transition: transform 0.3s ease;
}
.art-card img:hover {
  transform: scale(1.05);
}
.art-caption {
  margin-top: 6px;
  font-size: 14px;
  font-style: italic;
  transition: opacity 0.3s ease;
}
.art-caption::after {
  content: attr(data-bn);
  display: block;
  font-family: 'Noto Serif Bengali', serif;
  font-style: normal;
  font-size: 13px;
  margin-top: 4px;
  opacity: 0;
  transition: opacity 0.3s ease;
}
.art-card:hover .art-caption::after {
  opacity: 1;
}
</style>

<div class="lumos-wrapper fade-in">
  <div class="lumos-title">
    Lumos — A quiet light where poems, thoughts, and small triumphs thrive.
  </div>
</div>

<div class="lumos-section fade-in">



## Selected Poems

<div class="poetry-grid">
  <div class="poem-img-block">
    <a href="/images/lumos/poem-1.jpg" class="glightbox" data-title="Poem 1">
      <img src="/images/lumos/poem-1.jpg" alt="Poem 1">
    </a>
    <div class="caption-row">
      <span>অন্ধকারে আলো ফোটে</span>
      <span>— Light blossoms in darkness</span>
    </div>
  </div>

  <div class="poem-img-block">
    <a href="/images/lumos/poem-2.jpg" class="glightbox" data-title="Poem 2">
      <img src="/images/lumos/poem-2.jpg" alt="Poem 2">
    </a>
    <div class="caption-row">
      <span>পৃথিবীর গভীর গভীরে</span>
      <span>— Deep in the heart of the Earth</span>
    </div>
  </div>

  <div class="poem-img-block">
    <a href="/images/lumos/poem-3.jpg" class="glightbox" data-title="Poem 3">
      <img src="/images/lumos/poem-3.jpg" alt="Poem 3">
    </a>
    <div class="caption-row">
      <span>সময়ের নদীতে ভাসি</span>
      <span>— Floating on the river of time</span>
    </div>
  </div>

  <div class="poem-img-block">
    <a href="/images/lumos/IMG_6776.jpeg" class="glightbox" data-title="Poem 4">
      <img src="/images/lumos/IMG_6776.jpeg" alt="Poem 4">
    </a>
    <div class="caption-row">
      <span>শব্দেরা রক্তে মেশে</span>
      <span>— Words dissolve into blood</span>
    </div>
  </div>
</div>

<div class="poem-block">
  “The atom splits, the sky remembers —<br>
  What we break, we also become.”
</div>

<div class="poem-block">
  “Time folds not like pages,<br>
  But like pressure in the mantle.”
</div>



## 5K Finish (Spring 2024)

<div class="fivek-flex">
  <img src="/images/lumos/Lilac_Run_5K.jpg" alt="5K finish" class="fivek-img">
  <div>
    <h3>5K Finish</h3>
    <p>I ran my first 5K after a year. More than distance, it measured persistence and growth after recovering from a knee injury.</p>
  </div>
</div>



##  Digital Art

<div class="art-gallery">
  <div class="art-card">
    <a href="/images/lumos/Warli-art-1.jpg" class="glightbox">
      <img src="/images/lumos/Warli-art-1.jpg" alt="Warli Art 1">
    </a>
    <div class="art-caption" data-bn="ওয়ারলি শিল্পে বৃত্তের গল্প">Warli-inspired scene — a story in circles</div>
  </div>
  <div class="art-card">
    <a href="/images/lumos/Warli-art-2.jpg" class="glightbox">
      <img src="/images/lumos/Warli-art-2.jpg" alt="Warli Art 2">
    </a>
    <div class="art-caption" data-bn="কৃষি ও ঘরের উপজাতি সুর">Harvest and home in tribal rhythm</div>
  </div>
</div>

</div>
