# Zomato-Data-Analysis-and-Sentiment-Analysis

## Overview
The Zomato Customer Sentiment Analysis & Restaurant Segmentation project explores Hyderabad's unique food culture, analyzing restaurant data to extract meaningful insights. Hyderabad offers a balanced mix of cosmopolitan cuisines (Italian, Chinese, North Indian) and heritage dishes like its famous biryanis. This project aims to leverage customer reviews, restaurant metadata, and pricing details to understand consumer behavior and restaurant performance.

By performing sentiment analysis on customer reviews and clustering restaurants based on attributes like cuisine, pricing, and ratings, the project helps both customers and businesses. Customers can identify top-rated restaurants in their locality, while businesses can optimize their offerings based on data-driven insights.

## Business Problem
Zomato, an Indian restaurant aggregator and food delivery service, provides a vast collection of restaurant data, including customer reviews, ratings, and pricing details. The increasing number of restaurants in India presents both opportunities and challenges—how can customers find the best restaurants, and how can Zomato and restaurant owners enhance their services?

This project tackles these challenges through two key objectives:

## Customer Sentiment Analysis
* Analyzes customer reviews using NLP-based sentiment analysis (VADER, TextBlob).

* Identifies positive, negative, and neutral sentiments to assess restaurant reputation.

* Helps customers make informed dining decisions.

* Aids Zomato in improving user experience and helping restaurants address customer concerns.

## Restaurant Clustering & Segmentation
* Uses clustering algorithms (K-Means, Hierarchical Clustering) to group restaurants based on:

* Cuisine Type (e.g., North Indian, Chinese, Italian).

* Pricing & Value for Money analysis.

* Customer Ratings & Reviews to segment high-performing vs. low-performing restaurants.

## Dataset Description

The project uses two datasets:
* Restaurant Metadata (Res_names.csv) : Contains restaurant names, cuisine types, cost, ratings, and other metadata. Helps in clustering restaurants into segments and analyzing pricing trends.
* Restaurant Reviews (Res_reviews.csv): Contains customer reviews, ratings, and reviewer information. Used for sentiment analysis and identifying influential critics.
