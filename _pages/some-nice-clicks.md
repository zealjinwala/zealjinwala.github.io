---
# title:
permalink: /some-nice-clicks/
author_profile: true
gallery:
  - image_path: clicks/camping_1.jpeg
    alt: "camping_1"
  - image_path: clicks/forest_park_run_1.jpeg
    alt: "forest_park_run_1"
  - image_path: clicks/sf_trip_1.jpeg
    alt: "sf_trip_1"
  - image_path: clicks/ski_trip_1.jpeg
    alt: "ski_trip_1"
  - image_path: clicks/ski_trip_2.jpeg
    alt: "ski_trip_2"
  - image_path: clicks/balloon_fest.jpeg
    alt: "balloon_fest"
  - image_path: clicks/philly_sky.jpeg
    alt: "philly_sky"
  - image_path: clicks/some_hike.jpeg
    alt: "some_hike"
  - image_path: clicks/sunset_sf.jpeg
    alt: "sunset_sf"
  - image_path: clicks/sf_coastline.jpeg
    alt: "sf_coastline"
  - image_path: clicks/pikes_peak_1.jpeg
    alt: "pikes_peak_1"
  - image_path: clicks/pikes_peak_2.jpeg
    alt: "pikes_peak_2"
  - image_path: clicks/philly_sunset.jpeg
    alt: "philly_sunset"
  - image_path: clicks/philly_sunset_2.jpeg
    alt: "philly_sunset_2"
---

<style>
  /* Page-local gallery override: enforce clear row/column gaps in wrapped layout. */
  .page__content figure.clicks-grid,
  .page__content figure.clicks-grid.third,
  .page__content figure.clicks-grid.half {
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    gap: 1rem;
    margin: 1.25rem 0;
  }

  .page__content figure.clicks-grid > a,
  .page__content figure.clicks-grid > img {
    display: block;
    width: calc(33.3333% - 0.6667rem);
    margin: 0;
  }

  .page__content figure.clicks-grid img {
    display: block;
    width: auto;
    height: auto;
    max-width: 100%;
    margin: 0;
  }

  .page__content figure.clicks-grid figcaption {
    display: block;
    width: 100%;
  }

  @media (max-width: 900px) {
    .page__content figure.clicks-grid > a,
    .page__content figure.clicks-grid > img {
      width: calc(50% - 0.5rem);
    }
  }

  @media (max-width: 600px) {
    .page__content figure.clicks-grid > a,
    .page__content figure.clicks-grid > img {
      width: 100%;
    }

    .page__content figure.clicks-grid img {
      max-width: 100%;
    }
  }
</style>

{% include gallery class="clicks-grid" %}
