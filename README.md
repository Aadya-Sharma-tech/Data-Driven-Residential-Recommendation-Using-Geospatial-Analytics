# GeoNest - Data-Driven-Residential-Recommendation-Using-Geospatial-Analytics
The project builds a smart accommodation recommendation system that uses data analysis and K-Means clustering to match people with the best residential locations based on their lifestyle preferences and nearby facilities

## Intelligent Accommodation Recommendation Using Geospatial Data & Machine Learning

GeoNest AI is a data science and machine learning project that analyzes **student lifestyle preferences and geolocational data** to identify residential areas that best align with different lifestyle requirements.

The project combines **Exploratory Data Analysis (EDA), K-Means Clustering, REST APIs, geospatial analysis, and interactive mapping** to transform raw survey and location data into meaningful accommodation insights.

---

#  Problem Statement

Moving to a new city often means choosing accommodation without fully understanding the surrounding neighbourhood.

Two residential locations with similar rent or distance from a university may provide completely different lifestyles.

For example:

- A student who frequently eats outside may prefer an area with more restaurants.
- A student who cooks regularly may value easy access to grocery stores.
- A physically active student may prefer areas with gyms and fitness facilities.
- Spending capacity can influence the type of neighbourhood and amenities a student prefers.

The problem therefore becomes:

> **How can student lifestyle patterns and neighbourhood amenities be analyzed to identify residential locations that better match different types of students?**

This project approaches the problem using **K-Means Clustering** and **geospatial data analysis**.

---

#  Project Objective

The objective is to:

1. Analyze student lifestyle and food-choice data.
2. Identify meaningful behavioural patterns among students.
3. Group similar students using **K-Means Clustering**.
4. Collect residential and amenity information using a **geolocation API**.
5. Analyze the amenities surrounding different residential locations.
6. Cluster residential areas according to their amenity profiles.
7. Visualize the resulting location clusters on an interactive map.
8. Understand which types of locations may be more suitable for different student lifestyle groups.

---

#  Core Idea

The project works with two different perspectives:

### 👤 Student Perspective

Understand:

> **What kind of lifestyle does the student have?**

Examples of useful characteristics include:

- Income / spending capacity
- Eating-out behaviour
- Cooking habits
- Exercise habits
- Sports participation
- Fruit and vegetable consumption
- Amount spent on meals
- Living arrangement

###  Location Perspective

Understand:

> **What does a residential neighbourhood offer?**

Examples include:

- Restaurants
- Grocery stores
- Gyms / fitness centres
- Other relevant nearby amenities

The overall idea is:

**Student Lifestyle → Lifestyle Cluster → Amenity Requirements → Location Analysis → Suitable Residential Areas**

---

#  Project Workflow

```text
Raw Student Dataset
        ↓
Data Cleaning & Feature Selection
        ↓
Exploratory Data Analysis
        ↓
Feature Scaling
        ↓
K-Means Clustering
        ↓
Student Lifestyle Clusters
        ↓
Geolocational Data Collection
        ↓
Nearby Amenity Analysis
        ↓
Location Clustering
        ↓
Interactive Map Visualization
        ↓
Accommodation Insights
