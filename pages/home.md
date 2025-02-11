---
title: UNH Insect Database
lead: Advancing Insect Research through Taxonomic Excellence
project: UNH Insect Database
---

<!-- Header Section -->
<div class="homepage-header">
  <h1 class="title">{{ frontmatter.title }}</h1>
  <p class="subtitle">{{ frontmatter.lead }}</p>
</div>

<div class="homepage-container">
  <!-- Top Section: Large Image & Info Box -->
  <div class="top-section">
    <img src="/src/assets/images/Insects/NCSU_0025626_Head_View_3X.jpg" alt="Pinned Bee Specimen" class="large-image">
    
  <!-- Main Info Box (Now contains Collection + Get Involved) -->
  <div class="info-box">
      <h2>Explore Our Collection</h2>
      <p>Use the search feature below to access detailed taxonomic records from our collection.</p>
      <autocomplete-otu class="search-bar"/>

  <h2>Get Involved</h2>
      <p>Discover ways to contribute and collaborate with the <em>{{ frontmatter.project }}</em>.</p>

  <div class="button-container">
        <div class="button-box">
          <a href="/about" class="learn-more">Learn More</a>
        </div>
        <div class="button-box">
          <a href="https://www.instagram.com/unhentomologycollection" target="_blank" class="instagram-button">Visit Instagram</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Bottom Section: Four Symmetrical Images -->
  <div class="image-grid">
    <img src="/src/assets/images/Insects/Owen1.jpg" alt="Butterfly in grass">
    <img src="/src/assets/images/Insects/Owen2.jpg" alt="Wasp carrying caterpillar">
    <img src="/src/assets/images/Insects/Owen3.jpg" alt="Green beetles on rocks">
    <img src="/src/assets/images/Insects/Owen4.jpg" alt="Ant on branch with larvae">
  </div>
</div>

<style>
/* General Layout */
.homepage-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}

/* Header */
.homepage-header {
  text-align: center;
  padding: 3rem 1rem;
}

.title {
  font-size: 2.5rem;
  font-weight: bold;
}

.subtitle {
  font-size: 1.2rem;
  color: var(--color-secondary);
}

/* Top Section */
.top-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  gap: 2rem;
}

/* Large Image */
.large-image {
  width: 50%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Main Info Box */
.info-box {
  width: 50%;
  padding: 2rem;
  background: var(--color-base-muted);
  border-radius: 8px;
  box-shadow: var(--shadow-md);
}

/* Buttons & Button Container */
.button-container {
  display: flex;
  justify-content: center;
  gap: 1rem;
  margin-top: 1rem;
}

.button-box {
  background: var(--color-base-light);
  padding: 1rem;
  border-radius: 8px;
  box-shadow: var(--shadow-sm);
}

.learn-more, .instagram-button {
  display: block;
  text-align: center;
  text-decoration: none;
  font-weight: bold;
  padding: 0.75rem 1.5rem;
  border-radius: 6px;
}

.learn-more {
  background: transparent;
  color: var(--color-primary);
}

.instagram-button {
  background: var(--color-primary);
  color: var(--color-primary-content);
}

/* Image Grid */
.image-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.5rem;
  margin-top: 3rem;
  width: 100%;
}

.image-grid img {
  width: 100%;
  height: 300px; /* Ensuring uniform size */
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
</style>
