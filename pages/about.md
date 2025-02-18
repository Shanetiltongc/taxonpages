

---
title: About
contact_email: istvan.miko@gmail.com
copyright: All content is CC 0 so that it may be shared throughout the world.
---

<div :key="$route.path">

<!-- About Page Header (Matching Home Page) -->
<div class="homepage-header">
  <div class="header-box">
    <h1 class="title">{{ frontmatter.title }}</h1>
    <p class="subtitle">Student-Run Page for the UNH Entomology Lab</p>
  </div>
</div>

<!-- Content Grid Container -->
<div class="grid">

  <!-- Welcome Section -->
  <div class="info-box">
    <h2 class="text-2xl font-bold mb-2">Welcome</h2>
    <p class="mb-4">
      Welcome to the student-run site of the UNH Entomology Lab. This platform is maintained by students to share insights, news, and community updates about our fascinating insect collections. For official information and more details, please visit the 
      <a href="https://colsa.unh.edu/unh-collections/insects-other-arthropods" class="text-blue-600 hover:underline">official UNH Insect Lab website</a>.
    </p>
  </div>

  <!-- Our Mission & Collection Overview -->
  <div class="info-box">
    <h2 class="text-2xl font-bold mb-2">Our Mission & Collection Overview</h2>
    <p class="mb-4">
      The UNH Collection of Insects and Other Arthropods (UNHC) is dedicated to expanding our knowledge of insects and sharing that knowledge with the University of New Hampshire community and the public. With nearly 700,000 specimens and growing, the UNHC is the largest arthropod depository in northern New England.
    </p>
  </div>

  <!-- History of the Collection -->
  <div class="info-box">
    <h2 class="text-2xl font-bold mb-2">History of the Collection</h2>
    <p class="mb-4">
      Our collection began in the late 1800s through the efforts of pioneering entomologists at the New Hampshire College of Agriculture and Mechanical Arts. It moved to Durham in 1893 and now holds approximately 700,000 specimens—making it the largest insect collection in a New England state university.
    </p>
  </div>

  <!-- Regional & International Holdings -->
  <div class="info-box">
    <h2 class="text-2xl font-bold mb-2">Regional & International Holdings</h2>
    <p class="mb-4">
      Our collection has grown into a nationally and internationally recognized resource. Focused collections from unique natural habitats have provided unparalleled insights into regional biodiversity, making the collection a key faunal resource in the Northeast.
    </p>
  </div>

  <!-- Notable Collections -->
  <div class="info-box">
    <h2 class="text-2xl font-bold mb-2">Notable Collections</h2>
    <ul class="list-disc list-inside mb-4">
      <li><strong>Horseflies (Tabanidae)</strong> – curated by John Burger</li>
      <li><strong>Ant-like & Ant-Loving Beetles (Anthicidae & Pselaphinae)</strong> – Don Chandler</li>
      <li><strong>Leafhoppers</strong> – also by Don Chandler</li>
      <li><strong>Bird Lice</strong> – researched by James Keirans</li>
      <li><strong>Oribatid Mites (Oribatida)</strong> – studied by Marcel Reeves</li>
    </ul>
  </div>

  <!-- Meet the Team -->
  <div class="info-box">
    <h2 class="text-2xl font-bold mb-2">Meet the Team</h2>
    <div class="team-card">
      <strong>Istvan Miko</strong><br>
      <em>Collection Manager</em><br>
      Oversees the curation and management of our entomological collections.
    </div>
    <div class="team-card">
      <strong>Research Associate</strong><br>
      Focuses on biodiversity studies and taxonomic classification. (Name to be updated)
    </div>
  </div>

  <!-- Contact & Data Section -->
  <div class="info-box">
    <h2 class="text-2xl font-bold mb-2">Contact & Data</h2>
    <p class="mb-4">
      Have a question, found new data, or noticed an error? We'd love to hear from you!
    </p>
    <ul class="list-disc list-inside mb-4">
      <li>Email: <a href="mailto:{{ frontmatter.contact_email }}" class="text-blue-600 hover:underline">{{ frontmatter.contact_email }}</a></li>
      <li>Project Tracker: <a href="https://github.com/our/project/tracker" class="text-blue-600 hover:underline">File an Issue</a></li>
    </ul>
    <div class="open-access-box">
      <strong>Open Access:</strong> All content is shared under CC 0, allowing it to be freely used and distributed globally.
    </div>
  </div>

</div> <!-- End Grid Container -->

<!-- Styles for About Page -->
<style>
/* Header Styling */
.homepage-header {
  display: flex;
  justify-content: center;
  padding: 2rem 1rem;
}

.header-box {
  width: 80%;
  padding: 1.5rem;
  background: var(--color-base-muted);
  border: 4px solid var(--color-base-border);
  border-radius: 12px;
  box-shadow: var(--shadow-md);
  text-align: center;
}

.title {
  font-size: 2.5rem;
  font-weight: bold;
}

.subtitle {
  font-size: 1.2rem;
  color: var(--color-secondary);
}

/* Grid Container */
.grid {
  max-width: 1200px;
  margin: 2rem auto;
  display: grid;
  grid-template-columns: repeat(2, minmax(300px, 1fr)); /* Prevents boxes from shrinking */
  gap: 2rem;
  flex-wrap: wrap; /* Ensures responsiveness */
}

/* Info Box Styling */
.info-box {
  background: linear-gradient(135deg, var(--neutral-bg), var(--color-base-muted));
  border: 4px solid var(--color-base-border);
  border-radius: 12px;
  padding: 2rem;
  box-shadow: var(--shadow-md);
  min-width: 320px; /* Prevents squishing */
}

/* Team Member Cards */
.team-card {
  background-color: var(--color-base-background);
  padding: 1rem;
  border-radius: 8px;
  border: 1px solid var(--color-base-border);
  margin: 0.5rem 0;
  min-width: 320px; /* Ensures cards stay readable */
}

/* Open Access Box */
.open-access-box {
  background-color: var(--color-base-muted);
  padding: 1rem;
  border-radius: 8px;
  border: 1px solid var(--color-base-border);
  min-width: 320px; /* Prevents collapse */
}
</style>

</div>
