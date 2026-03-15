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
  /* Page-local gallery override: masonry columns for mixed portrait/landscape images. */
  .page__content figure.clicks-grid,
  .page__content figure.clicks-grid.third,
  .page__content figure.clicks-grid.half {
    display: block;
    margin: 1.25rem 0;
    column-gap: 1rem;
    column-width: 260px;
  }

  .page__content figure.clicks-grid > a,
  .page__content figure.clicks-grid > img {
    display: inline-block;
    width: 100%;
    margin: 0 0 1rem;
    break-inside: avoid;
    page-break-inside: avoid;
  }

  .page__content figure.clicks-grid img {
    display: block;
    width: 100%;
    height: auto;
    margin: 0;
  }

  .page__content figure.clicks-grid figcaption {
    display: block;
    width: 100%;
    break-inside: avoid;
    page-break-inside: avoid;
  }

  @media (max-width: 600px) {
    .page__content figure.clicks-grid,
    .page__content figure.clicks-grid.third,
    .page__content figure.clicks-grid.half {
      column-count: 1;
      column-width: auto;
    }
  }
</style>

{% include gallery class="clicks-grid" %}
