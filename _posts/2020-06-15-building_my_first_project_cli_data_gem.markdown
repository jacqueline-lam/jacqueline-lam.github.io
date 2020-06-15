---
layout: post
title:      "Building my first project: CLI Data Gem 💎"
date:       2020-06-15 20:02:31 +0000
permalink:  building_my_first_project_cli_data_gem
---

**[Please read and comment on my CLI Project blog post on dev.io](https://dev.to/jacquelinelam/building-my-first-project-cli-data-gem-50m4)**
## A CLI App for Indecisive Shoppers
As an indecisive yet frugal shopper, I struggle a lot in making my purchase decisions. I love to do extensive research to find the product with the best features for its cost. 

Hence, I decided to create a gem that will provide the user with concise information about a type of product and gives the user the option to learn about the best products based on a chosen feature! — Almost like a product rater of some sort.

I visited [Outdoor Gear Lab's Best Women's Rain Jackets of 2019 website](https://www.outdoorgearlab.com/topics/clothing-womens/best-rain-jacket-womens) dozens of times this year before I finally decided on the perfect jacket for me. Once I decided to scrape from this website, I started to imagine my CLI app interface according to features that a user might be interested in, and then reverse-engineer the data that I would need to scrape from the website:

> #### Planning a CLI for Best Rain Jackets:
> * Shows a list of best female rain jackets #name - price - overall rating
> * Shows details of a chosen jacket
> * Shows the best products based on a chosen rating category

> #### So, what are the properties of a rain jacket? It has a...
>  * Name
>  * Price
>  * Description 
>  * Pros & Cons
>  * URL to full product review 
>  * Overall rating 
>  * Other rating categories (water resistance, breathability, comfort, weight, durability, and packed size)

Once I set up the basic structure of my gem and created the executable files, I started working on my Scraper class. 


**[Please read my CLI Project blog post on dev.io](https://dev.to/jacquelinelam/building-my-first-project-cli-data-gem-50m4)**
