---
title: UNH Insect Database
lead: Advancing Insect Research through Taxonomic Excellence
project: UNH Insect Database
---

<div class="homepage-container">
  <!-- Top Section: Large Image & Info Box Side-by-Side -->
  <div class="top-section">
    <img src="/src/assets/images/Insects/NCSU_0025626_Head_View_3X.jpg" alt="Pinned Bee Specimen" class="large-image">
    
  <div class="info-box">
      <h2>Welcome to the UNH Insect Database</h2>
      <p>
        Our collection is home to thousands of preserved insect specimens, supporting global taxonomic research. 
        Learn more about the diversity of species housed within the UNH Entomology Lab.
      </p>

  <h3>Explore & Get Involved</h3>
      <p>
        Use our search tool to explore taxonomic records, or follow us on Instagram for updates and discoveries.
      </p>
      <div class="button-container">
        <a href="/about" class="learn-more">Learn More</a>
        <a href="https://www.instagram.com/unhentomologycollection" target="_blank" class="instagram-button">Visit Instagram</a>
      </div>
    </div>
  </div>

  <!-- Middle Section: Search Feature & Important Notice -->
  <div class="middle-section">
    <!-- Explore Our Collection Card -->
    <div class="feature-box">
      <h2>Explore Our Collection</h2>
      <p>Use the search feature below to access detailed taxonomic records from our collection.</p>  
      <autocomplete-otu class="search-bar"/>
    </div>

    <!-- Important Notice Card -->
  <div class="feature-box">
      <h2>Important Notice</h2>
      <p>Our database is continuously updated as new specimens are cataloged. Data accuracy and completeness are ongoing priorities.</p>
    </div>
  </div>

  <!-- Bottom Section: Four Symmetrical Images -->
  <div class="image-grid">
    <img src="/src/assets/images/Insects/Owen1.jpg" alt="Butterfly in grass">
    <img src="/src/assets/images/Insects/Owen2.jpg" alt="Wasp carrying caterpillar">
    <img src="/src/assets/images/Insects/Owen3.jpg" alt="Green beetles on rocks">
    <img src="/src/assets/images/Insects/Owen4.jpg" alt="Ant on branch with larvae">
  </div>

  <!-- Get Involved Section -->
  <div class="get-involved">
    <h2>Get Involved</h2>
    <p>
      Learn how you can contribute to and collaborate with the <em>{{ frontmatter.project }}</em>. 
      For detailed project descriptions, visit our <a href="/about">About</a> page.
    </p>
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

/* Top Section: Large Image & Info Box */
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

/* Info Box */
.info-box {
  width: 50%;
  padding: 2rem;
  background: var(--color-base-muted);
  border-radius: 8px;
  box-shadow: var(--shadow-md);
}

/* Button Styles */
.button-container {
  display: flex;
  gap: 1rem;
  margin-top: 1rem;
}

.learn-more {
  background: transparent;
  color: var(--color-primary);
  text-decoration: none;
  font-weight: bold;
}

.instagram-button {
  background: var(--color-primary);
  color: var(--color-primary-content);
  padding: 0.5rem 1rem;
  border-radius: 4px;
  text-decoration: none;
  font-weight: bold;
}

/* Middle Section */
.middle-section {
  display: flex;
  justify-content: space-between;
  width: 100%;
  margin-top: 3rem;
  gap: 2rem;
}

.feature-box {
  flex: 1;
  padding: 2rem;
  background: var(--color-base-muted);
  border-radius: 8px;
  box-shadow: var(--shadow-md);
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

/* Get Involved Section */
.get-involved {
  margin-top: 3rem;
  padding: 2rem;
  text-align: center;
  background: var(--color-base-muted);
  border-radius: 8px;
  box-shadow: var(--shadow-md);
}
</style>
