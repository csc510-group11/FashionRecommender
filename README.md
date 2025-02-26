# CSC510 Project 2 - Group 11

## Link to new features video: [Demo Video](https://youtu.be/p_Uy4ipak7k)

[![Black Code Style](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=latest)](https://github.com/csc510-group11/FashionRecommender/blob/dev/README.md)
[![GitHub license](https://img.shields.io/github/license/csc510-group11/FashionRecommender)](https://github.com/csc510-group11/FashionRecommender/blob/dev/LICENSE.md)
[![Github Repo size in bytes](https://img.shields.io/github/languages/code-size/csc510-group11/FashionRecommender)](https://github.com/csc510-group11/FashionRecommender)

[![GitHub issues](https://img.shields.io/github/issues/csc510-group11/FashionRecommender)](https://github.com/csc510-group11/FashionRecommender/issues?q=is%3Aopen)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/csc510-group11/FashionRecommender)](https://github.com/csc510-group11/FashionRecommender/issues?q=is%3Aissue+is%3Aclosed)
[![Github pull requests](https://img.shields.io/github/issues-pr/csc510-group11/FashionRecommender)](https://github.com/csc510-group11/FashionRecommender/pulls)
[![Github closed pull requests](https://img.shields.io/github/issues-pr-closed/csc510-group11/FashionRecommender)](https://github.com/csc510-group11/FashionRecommender/pulls?q=is%3Apr+is%3Aclosed)

[![github workflow](https://github.com/csc510-group11/FashionRecommender/actions/workflows/style_checker.yml/badge.svg)](https://github.com/csc510-group11/FashionRecommender/actions/workflows/style_checker.yml)
[![github workflow](https://github.com/csc510-group11/FashionRecommender/actions/workflows/main.yml/badge.svg)](https://github.com/csc510-group11/FashionRecommender/actions/workflows/main.yml)

![GitHub language count](https://img.shields.io/github/languages/count/csc510-group11/FashionRecommender)

## About the Project  

### VogueX - Tailor Made, Just for You  

Ever planned the perfect outfit only to realize too late that the weather had other plans? Worry no more! VogueX is not just any fashion recommender—it’s your personal styling assistant that ensures you're dressed both stylishly and comfortably for any occasion.  

VogueX goes beyond basic recommendations by factoring in:  
✔ **Weather** – Suggesting outfits suited for the forecast.  
✔ **Season** – Recommending seasonal patterns and styles.  
✔ **Occasion** – Offering top-rated choices for special events.  

With VogueX, you can save your favorite outfits, browse shopping links for quick purchases, and enjoy a seamless fashion experience tailored just for you!  

---

## Key Features  

- **🗺️ Geolocation API** – Auto-detects location for weather-based outfit suggestions (user override available).  
- **📝 Fashion Blogger Insights** – Stay updated with famous fashion bloggers and their latest tips.  
- **🌍 Trendy Fashion Sites** – One-stop access to top fashion websites.  
- **💬 Feedback Mechanism** – Provide and review past feedback for better personalization.  
- **📤 Social Media Sharing** – Share your recommended outfits directly to social platforms.  
- **🔎 Search History** – Revisit and track past searches effortlessly.  
- **🎨 Color Palette Suggestions** – Occasion-based and culturally inspired color recommendations using Gemini API.  
- **📸 Image-Based Styling** – Upload your clothes and get personalized styling tips.  
- **👜 Accessory Recommendations** – Tailored suggestions for umbrellas, coats, glasses, and more.  
- **🔍 Advanced Search Filters** – Filter fashion recommendations by occasion, culture, and more.  
- **🔐 Google Sign-In** – Secure login and saved outfit preferences for easy access.  
- **🐳 Dockerization** – Enhanced security and reduced risks.  
- **🎛️ Robust Search Filtering** – Default values set for streamlined recommendations.  

VogueX ensures **"A style for every story"**—so let your fashion speak for itself! ✨  

This document serves as a comprehensive guide for users, offering insights into the functionalities of VogueX and encouraging active participation in its growth as an open-source project. As an open-source initiative, the community can contribute new features and improvements, making VogueX even more refined and personalized for diverse fashion needs. Additionally, it provides developers with a clear understanding of the codebase, ensuring a structured and collaborative approach to the project's continuous evolution.

## Table of Contents  

- [Why use VogueX?](#why-use-voguex)
- [What Makes VogueX Unique?](#what-makes-voguex-unique)
- [Tech Stack](#techstack-used-for-the-development-of-project)  
- [Core Functionalities](#core-functionalities-of-the-application)  
  - [Personalized search filters - Find the perfect outfit for every occasion!](#personalized-search-filters---find-the-perfect-outfit-for-every-occasion)
  - [Recommendations - Discover the latest trends and styles!](#recommendations---discover-the-latest-trends-and-styles)
  - [Favourites – Curate your personal collection of top picks!](#favourites---curate-your-personal-collection-of-top-picks)
  - [Top Fashion Blogs : Explore the leading voices in fashion and style!](#top-fashion-blogs---explore-the-leading-voices-in-fashion-and-style)
  - [Your Search Journey : Keep track of your discoveries and pick up right where you left off!](#your-search-journey---keep-track-of-your-discoveries-and-pick-up-right-where-you-left-off)
  - [Trendy Sites : Discover the most popular fashion sites and stay trendy!](#trendy-sites---discover-the-most-popular-fashion-sites-and-stay-trendy)
  - [Feedback Mechanism : Share your thoughts and help us improve your experience!](#feedback-mechanism---share-your-thoughts-and-help-us-improve-your-experience)
- [Steps for Execution](#steps-for-execution)
- [Future Scope](#future-scope)
- [Team Members](#team-members)
- [Code of Conduct](#code-of-conduct)
- [Contribution](#contribution)
- [License](#license)  

## Why Use VogueX?  

Choosing the right outfit can be challenging, especially when considering factors like weather, occasion, and personal style. VogueX eliminates the guesswork by providing **personalized fashion recommendations** tailored to your needs.  

## What Makes VogueX Unique?

- **🌦️ Weather-Aware Styling** – Never get caught off guard by unexpected rain or extreme temperatures.  
- **🎭 Occasion-Based Suggestions** – Whether it's a wedding, a business meeting, or a casual day out, VogueX helps you dress appropriately.  
- **📍 Location-Based Fashion Insights** – Recommendations adapt based on your **geolocation and seasonal trends.**  
- **🖼️ Image-Based Outfit Matching** – Upload a picture of your clothing and get personalized style combinations.  
- **🎨 Culture & Color Palette Suggestions** – Discover culturally inspired and event-appropriate color themes.  
- **🛍️ One-Click Shopping** – Direct links to online stores help you find and buy your perfect look effortlessly.  
- **📖 Search History & Feedback Mechanism** – Improve recommendations over time by tracking your preferences.  

Whether you're a fashion enthusiast or just need a quick outfit suggestion, **VogueX ensures you always step out in confidence!** 🚀  

## TechStack Used for the Development of Project

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Core Functionalities of the Application

### Personalized Search Filters - Find the perfect outfit for every occasion!

VogueX offers a wide range of search filters to help you find the perfect outfit for any occasion. Whether you're looking for a casual day out or a formal event, VogueX has you covered. With filters like weather, season, and occasion, you can easily narrow down your search and find the perfect outfit in no time.

### Recommendations - Discover the latest trends and styles!

VogueX provides personalized recommendations based on your search filters and preferences. Whether you're looking for a trendy outfit or a classic look, VogueX has something for everyone. With a wide range of options to choose from, you can easily find the perfect outfit for any occasion.

### Favourites - Curate your personal collection of top picks!

VogueX allows you to save your favorite outfits to your profile so you can easily access them later. Whether you're browsing through recommendations or creating your own outfits, you can save your top picks and curate your personal collection of outfits.

### Top Fashion Blogs - Explore the leading voices in fashion and style!

VogueX features a curated list of top fashion blogs to keep you updated on the latest trends and styles. Whether you're looking for fashion inspiration or tips on how to style your outfits, VogueX has you covered. With a wide range of blogs to choose from, you can explore the leading voices in fashion and style.

### Your Search Journey - Keep track of your discoveries and pick up right where you left off!

VogueX keeps track of your search history so you can easily revisit your past searches and discoveries. Whether you're looking for outfit recommendations or browsing through fashion blogs, you can pick up right where you left off and continue your search journey with ease.

### Trendy Sites - Discover the most popular fashion sites and stay trendy!

VogueX provides direct links to the most popular fashion sites so you can stay updated on the latest trends and styles. Whether you're looking for new outfit ideas or shopping for the latest fashion trends, VogueX has you covered. With direct links to top fashion sites, you can easily discover the most popular fashion sites and stay trendy.

### Feedback Mechanism - Share your thoughts and help us improve your experience!

VogueX features a feedback mechanism that allows you to share your thoughts and suggestions with us. Whether you have feedback on the app's features or recommendations for new functionality, we want to hear from you. With your feedback, we can improve your experience and make VogueX even better.

## Steps for execution

It's really simple to run the application on your local machine. Just follow the steps below:

Prerequisites: You will need to have Docker installed on your machine. If you don't have it installed, you can download it from [here](https://www.docker.com/products/docker-desktop).

Step 1: Git Clone the Repository

```bash
git clone https://github.com/csc510-group11/FashionRecommender.git
```

Step 2: Change working directory to the repository

```bash
cd FashionRecommender
```

Step 3: Run the following command to start the application

```bash
docker compose up -d
```

Step 4: Open the URL in your browser:

```bash
http://localhost:8000/
```

That's it! You can now enjoy using the application on your local machine.

## Future Scope

- **Better UI Enhancement**: Continuously improve the user interface for a more intuitive and visually appealing experience.
- **Personalized Chatbot**: Integrate a chatbot to provide personalized fashion advice and instant support.
- **Advanced Profile Management**: Enhance profile management features to allow users to customize their preferences and settings more effectively.
- **Calendar Integration**: Integrate with calendar apps to provide outfit recommendations for important dates and events.

## Team Members

- Md Atiqur Rahman  
- Nazia Afreen
- Sohom Datta

## Code of Conduct

Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) in all your interactions with the project.

## Contribution

Please refer the [CONTRIBUTING.md](./CONTRIBUTING.md) file for instructions on how to contribute to our repository.

## License

This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE.md) file for details.
