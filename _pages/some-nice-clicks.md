---
title: "Some Nice Clicks"
permalink: /some-nice-clicks/
author_profile: true
gallery:
  - image_path: clicks/camping_1.jpeg
    alt: "Photo 1"
  - image_path: clicks/forest_park_run_1.jpeg
    alt: "Photo 2"
  - image_path: clicks/sf_trip_1.jpeg
    alt: "Photo 3"
  - image_path: clicks/ski_trip_1.jpeg
    alt: "Photo 3"
  - image_path: clicks/ski_trip_2.jpeg
    alt: "Photo 3"
---

<style>
  /* Page-local gallery override: responsive grid with fixed 0.5in spacing. */
  .page__content figure.clicks-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 0.5in;
    margin: 1.25rem 0;
  }

  .page__content figure.clicks-grid > a {
    display: block;
  }

  .page__content figure.clicks-grid img {
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    margin: 0;
    display: block;
  }
  
  .page__content figure.clicks-grid figcaption {
    grid-column: 1 / -1;
  }

  @media (max-width: 600px) {
    .page__content figure.clicks-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

{% include gallery class="clicks-grid" %}
