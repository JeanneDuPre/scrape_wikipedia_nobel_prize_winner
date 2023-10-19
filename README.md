# Project Nobel Laureates

## Data Collection
#### 1. The Wikipedia page containing a table of Nobel laureates from 1901 to the present was scraped.

#### 2. Subsequently, links to the Wikipedia pages of Nobel laureates and their respective names were extracted from the table and stored in a new CSV file.

#### 3. An automated process was employed to scrape the first paragraph from each Nobel laureate's Wikipedia page into another CSV file.

#### 4. A pivot table was created using pandas (intermediate level) to ensure consistent storage of names, Nobel Prize categories, and years in another CSV file.

#### 5. Another Wikipedia page containing a table of countries and their population figures (as of 2023, worldwide) was also scraped.

#### Following this, all tables were merged

## Data Cleaning
#### 1. New tables, especially derived from the first Wikipedia paragraph, were created using regex (birth date, death date, birthplace, place of death, occupation, nationality, gender, number of nationalities).
#### 2. Values were consolidated (occupation, nationality).
#### 3. The Google Maps API was utilized to obtain latitude and longitude data for the countries.

## The data was subsequently analyzed and visualized, revealing the following latent themes:
#### 1. Nobel Peace Prizes, which have been awarded since 1901, have almost been overtaken by economics, which has only been awarded since 1969 (excluding the organizations).
#### 2. In contrast to men, women are mostly writers or activists alongside physicists and chemists. Men are usually physicists, chemists, writers, doctors.
#### 3. Where is half of the world's population represented?
#### 4. TODO
#### 5. TODO
#### 6. TODO



