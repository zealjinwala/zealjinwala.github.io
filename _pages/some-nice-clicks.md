---
title: "Some Nice Clicks"
permalink: /some-nice-clicks/
author_profile: true
gallery:
  - image_path: clicks/2CA23EB7-9031-4B1C-9DB5-E15231724674_1_105_c.jpeg
    alt: "Photo 1"
  - image_path: clicks/photo2.jpg
    alt: "Photo 2"
  - image_path: clicks/photo3.jpg
    alt: "Photo 3"
---

<style>
  /* Page-local gallery override: spacing and wrapping adapt to each image's natural size. */
  .page__content figure.clicks-fluid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
    gap: 0.85rem;
    margin: 1.25rem 0;
  }

  .page__content figure.clicks-fluid > a,
  .page__content figure.clicks-fluid > img {
    width: auto;
  }

  .page__content figure.clicks-fluid img {
    width: auto;
    max-width: min(100%, 420px);
    height: auto;
    margin: 0;
    display: block;
  }
  
  .page__content figure.clicks-fluid figcaption {
    width: 100%;
  }

  @media (max-width: 600px) {
    .page__content figure.clicks-fluid img {
      max-width: 100%;
    }
  }
</style>

{% include gallery class="clicks-fluid" %}
