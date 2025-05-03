---
title: "Lumos"
permalink: /lumos/
---

<!-- Load elegant font -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@1,600&display=swap" rel="stylesheet">

<style>
/* Fade-in animation */
@keyframes fadeInUp {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

.fade-in {
  animation: fadeInUp 1.2s ease-out both;
}

/* Title section with oversized quotes */
.lumos-wrapper {
  max-width: 800px;
  margin: 60px auto 40px auto;
  font-family: 'Playfair Display', serif;
  color: #e0e0e0;
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
  color: #888;
  font-family: 'Playfair Display', serif;
  position: absolute;
  opacity: 0.4;
}

.lumos-title::before {
  content: "“";
  top: -20px;
  left: -20px;
}

.lumos-title::after {
  content: "”";
  bottom: -20px;
  right: -20px;
}

/* Section layout */
.lumos-section {
  max-width: 800px;
  margin: 0 auto;
  padding-top: 10px;
  font-size: 16px;
  line-height: 1.7;
}

/* Poems */
.poem-block {
  font-family: 'Playfair Display', serif;
  font-style: italic;
  font-size: 18px;
  color: #e0e0e0;
  margin-top: 20px;
  margin-bottom: 30px;
  padding-left: 20px;
  border-left: 3px solid #999;
}

/* Image sections */
.photo-block {
  text-align: center;
  margin-top: 40px;
}

.photo-block img {
  max-width: 80%;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.3);
  transition: transform 0.3s ease;
}

.photo-block img:hover {
  transform: scale(1.02);
}

.photo-block p {
  font-size: 14px;
  color: #aaa;
  margin-top: 10px;
}
</style>

<!-- Header -->
<div class="lumos-wrapper fade-in">
  <div class="lumos-title">
    Lumos — A quiet light where poems, thoughts, and small triumphs thrive.
  </div>
</div>

<!-- Content -->
<div class="lumos-section fade-in">

## ✍️ Selected Poems

<!-- Poetic image above the poems -->
<div class="photo-block">
  <img src="/images/lumos/IMG_6776.jpg" alt="Bengali Poem image">
  <p>A quiet sky. A thought unfolds.</p>
</div>

<div class="poem-block">
  “The atom splits, the sky remembers —<br>
  What we break, we also become.”
</div>

<div class="poem-block">
  “Time folds not like pages,<br>
  But like pressure in the mantle.”
</div>

## 🏃 5K Finish (Spring 2024)

<div class="photo-block">
  <img src="/images/lumos/Lilac_Run_5K.jpg" alt="5K finish line photo">
  <p>I ran my first 5K after a year. More than distance, it measured persistence and growth after recovering from a knee injury.</p>
</div>

</div>
