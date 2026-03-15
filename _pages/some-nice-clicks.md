---
# title:
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
  - image_path: clicks/balloon_fest.jpeg
    alt: "Photo 3"
  - image_path: clicks/philly_sky.jpeg
    alt: "Photo 3"
  - image_path: clicks/some_hike.jpeg
    alt: "Photo 3"
  - image_path: clicks/sunset_df.jpeg
    alt: "Photo 3"
  - image_path: clicks/sf_coastline.jpeg
    alt: "Photo 3"
  - image_path: clicks/pikes_peak_1.jpeg
    alt: "Photo 3"
  - image_path: clicks/pikes_peak_2.jpeg
    alt: "Photo 3"
  - image_path: clicks/philly_sunset.jpeg
    alt: "Photo 3"
  - image_path: clicks/philly_sunset_2.jpeg
    alt: "Photo 3"
---

<style>
  /* Page-local gallery override: non-uniform wrapped layout with fixed 0.5in spacing. */
  .page__content figure.clicks-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
    gap: 0.5in;
    margin: 1.25rem 0;
  }

  .page__content figure.clicks-grid > a {
    display: block;
    width: auto;
  }

  .page__content figure.clicks-grid img {
    width: auto;
    height: auto;
    margin: 0;
    display: block;
  }
  
  .page__content figure.clicks-grid figcaption {
    width: 100%;
  }

  @media (max-width: 600px) {
    .page__content figure.clicks-grid img {
      width: 100%;
      height: auto;
    }
  }
</style>

{% include gallery class="clicks-grid" %}
