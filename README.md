# MongoCaseStudy
## Project Overview
This repository contains the case study project aimed at designing and implementing a MongoDB database for managing a blog and performing various queries on a zip code dataset.

## Part 1: Blog Database
Design of a MongoDB database for a blog where registered users publish posts. Each author has a name, username, Twitter account, address, and contact phone numbers. Blog posts include a title, body, publication date, tags, and comments with the commenter's information and timestamp (files available in folder [exercise1](https://github.com/alexgaarciia/MongoCaseStudy/tree/main/exercise1)).

### Tasks:
1. Describe the design of the schema and explain some documents in JSON.
2. Insert records into the database.
3. Perform the following queries:
   - Retrieve all blog posts containing 'amazing' and 'extraordinary' in comments, with author and blog details.
   - Retrieve all blog posts with tags like 'Video Marketing', 'Online Marketing', 'Data Science', 'Branding'.
   - Retrieve all blog posts excluding tags like 'Video Marketing', 'Online Marketing', 'Data Science', 'Branding'.
   - Retrieve titles of blog posts written in May 2019.
   - Retrieve titles of blog posts by user "Mery123" with tags "nosql", "database", or "mongoDB" published in 2019.

## Part 2: Zipcodes Database
Utilize the zipcodes collection available at `http://media.mongodb.org/zips.json` and perform the following task (files available in folder [exercise2](https://github.com/alexgaarciia/MongoCaseStudy/tree/main/exercise2)).
1. Perform the following queries:
   - Recover the minimum value of the 'pop' field for all cities.
   - Retrieve all zip codes in the city "Springfield".
   - Retrieve the number of cities in state "GA" with a population less than or equal to 1500.
   - Update all cities in Massachusetts (state: "MA") with a new field { area : “27 340 km” }.
   - Recover all cities located between -81.000001 and 32.915592.
   - Update the populations to 50,000 for cities with a population between 45,000 and 50,000.
