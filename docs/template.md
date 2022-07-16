---
template: overrides/main.html
---

# Table
<figure markdown>

| Browser                              | Version | Release date |         |        |      Usage |
| ------------------------------------ | ------: | -----------: | ------: | -----: | ---------: |
|                                      |         |              | desktop | mobile |    overall |
| :fontawesome-brands-chrome: Chrome   |     49+ |      03/2016 | 25.65%  | 38.33% |     63.98% |
| :fontawesome-brands-safari: Safari   |     10+ |      09/2016 |  4.63%  | 14.96% |     19.59% |
| :fontawesome-brands-edge: Edge       |     79+ |      01/2020 |  3.95%  |    n/a |      3.95% |
| :fontawesome-brands-firefox: Firefox |     53+ |      04/2017 |  3.40%  |   .30% |      3.70% |
| :fontawesome-brands-opera: Opera     |     36+ |      03/2016 |  1.44%  |   .01% |      1.45% |
|                                      |         |              |         |        | __92.67%__ |

  <figcaption markdown>

Browser support matrix sourced from [caniuse.com].[^1]

  </figcaption>
</figure>

  [^1]:
    The data was collected from [caniuse.com] in January 2022, and is primarily
    based on browser support for [custom properties], [mask images] and the
    [:is pseudo selector] which are not entirely polyfillable. Browsers with a
    cumulated market share of less than 1% were not considered, but might still
    be fully or partially supported.

# Codes
=== "8.x"

    ``` yaml
    extra:
      analytics:
        provider: google
        property: UA-XXXXXXXX-X
    ```

=== "7.x"

    ``` yaml
    google_analytics:
      - UA-XXXXXXXX-X
      - auto
    ```