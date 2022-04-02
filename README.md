# Semantic Web for Hugo

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5771170.svg)](https://doi.org/10.5281/zenodo.5771170)

By using JSON-LD and [Schema.org](https://schema.org) vocabulary, **Semantic Web for Hugo** adds *structured data* and *linked data* into a [Hugo](https://gohugo.io)-powered website. Through it, search engines can easily read the data and establish relationships between objects enabling them to intelligently store information about a website and use it to help display the website in search results.

## Usage

You can download the latest release or add this as a Hugo Module. More information is available in the official [website](https://semweb.youronly.one/).

## Features

These are the supported types:

- Organization ([Schema.org Type](https://schema.org/Organization))
  - Thing > Organization
- Person ([Schema.org Type](https://schema.org/Person))
  - Thing > Person
- WebContent ([Schema.org Type](https://schema.org/WebContent))
  - Thing > CreativeWork > WebContent
- WebSite ([Schema.org Type](https://schema.org/WebSite))
  - Thing > CreativeWork > WebSite
- WebPage ([Schema.org Type](https://schema.org/WebPage))
  - Thing > CreativeWork > WebPage
- Article ([Schema.org Type](https://schema.org/Article))
  - Thing > CreativeWork > Article
- BlogPosting ([Schema.org Type](https://schema.org/BlogPosting))
  - Thing > CreativeWork > Article > SocialMediaPosting > BlogPosting
- ImageObject ([Schema.org Type](https://schema.org/ImageObject))
  - Thing > CreativeWork > MediaObject > ImageObject
- VideoObject ([Schema.org Type](https://schema.org/VideoObject))
  - Thing > CreativeWork > MediaObject > VideoObject

### TODO

The following are on the table:

#### HowTo

- HowTo - [Schema.org Type](https://schema.org/HowTo))
  - Thing > CreativeWork > HowTo
- HowToSection ([Schema.org](https://schema.org/HowToSection))
  - Thing > CreativeWork > HowToSection
  - Thing > Intangible > ItemList > HowToSection
  - Thing > Intangible > ListItem > HowToSection
- HowToTip ([Schema.org](https://schema.org/HowToTip))
  - Thing > CreativeWork > HowToTip
  - Thing > Intangible > ListItem > HowToTip
- HowToStep ([Schema.org](https://schema.org/HowToStep))
  - Thing > CreativeWork > HowToStep
  - Thing > Intangible > ItemList > HowToStep
  - Thing > Intangible > ListItem > HowToStep
- ListItem ([Schema.org](https://schema.org/ListItem))
  - Thing > Intangible > ListItem

#### Reviews

- Review ([Schema.org Type](https://schema.org/Review))
  - Thing > CreativeWork > Review
- CriticReview ([Schema.org Type](https://schema.org/CriticReview))
  - Thing > CreativeWork > Review > CriticReview
- TVSeason ([Schema.org Type](https://schema.org/TVSeason))
  - Thing > CreativeWork > TVSeason
  - Thing > CreativeWork > CreativeWorkSeason > TVSeason
- TVSeries ([Schema.org Type](https://schema.org/TVSeries))
  - Thing > CreativeWork > TVSeries
  - Thing > CreativeWork > CreativeWorkSeries > TVSeries
  - Thing > Intangible > Series > CreativeWorkSeries > TVSeries
- Movie ([Schema.org Type](https://schema.org/Movie))
  - Thing > CreativeWork > Movie
- Book ([Schema.org Type](https://schema.org/Book))
  - Thing > CreativeWork > Book

#### Other types

- ItemList ([Schema.org](https://schema.org/ItemList))
  - Thing > Intangible > ItemList
- BreadcrumbList ([Schema.org Type](https://schema.org/BreadcrumbList))
  - Thing > Intangible > ItemList > BreadcrumbList

### Under consideration

#### Food and drinks

- Menu ([Schema.org Type](https://schema.org/Menu))
  - Thing > CreativeWork > Menu
- MenuItem ([Schema.org Type](https://schema.org/MenuItem))
  - Thing > Intangible > MenuItem
- Recipe ([Schema.org](https://schema.org/Recipe))
  - Thing > CreativeWork > HowTo > Recipe
- NutritionInformation  ([Schema.org](https://schema.org/NutritionInformation))
  - Thing > Intangible > StructuredValue > NutritionInformation

#### FAQ types

- FAQPage ([Schema.org](https://schema.org/FAQPage))
  - Thing > CreativeWork > WebPage > FAQPage
- QAPage ([Schema.org](https://schema.org/QAPage))
  - Thing > CreativeWork > WebPage > QAPage

## Attributions

Based on / forked from:

- [HugoStructuredData](https://github.com/Baseflow/HugoStructuredData) by [Baseflow](https://github.com/Baseflow)
- [Structured-Data-JSON-LD](https://github.com/JayHoltslander/Structured-Data-JSON-LD) by [JayHoltslander](https://github.com/JayHoltslander)
