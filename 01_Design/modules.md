# Modules Definitions

## Keywords Map

- input
  - single search word
- output
  - A Map describes all relationship
- Data Source List
  - ONet Center [All Occupations](https://www.onetonline.org/find/career?c=0&g=Go)

## Scrapper

- input
  - search words
  - priority
- output
  - company name
  - company desc
  - company location divided into province, city, district
  - salary level
  - position name
  - position desc
  - position requirement

## Text Analyzer

- function1: position keyword allocate
  - input
    - position name
    - position desc
    - position requirement
  - output
    - most important keyword
    - predict problem solving direction
    - bonus point

- function2: company information analysis
