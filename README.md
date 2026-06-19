# Data-Driven Business Recommendation System for Entrepreneurs and SMEs in Saudi Arabia

A web-based decision-support system that helps early-stage entrepreneurs in Saudi Arabia choose suitable business activities based on city, available capital, estimated costs, rental indicators, and competition level.

## Live Demo
https://bywn.onrender.com/

## Overview

Many beginner entrepreneurs in Saudi Arabia struggle to choose a suitable business idea because market information is scattered, difficult to compare, and not always easy to understand for non-specialists.

This project addresses that problem by transforming Saudi open data into clear, ranked business recommendations. The system allows users to select their region, city, and available investment capital, then provides suitable business activities supported by financial and market indicators.

The main goal is to reduce uncertainty and help entrepreneurs make more realistic, data-driven investment decisions.

## Key Features

- Provides ranked business recommendations based on user inputs.
- Supports city-based and capital-based business filtering.
- Estimates business suitability using financial and market indicators.
- Displays competition level, estimated costs, and capital gap or surplus.
- Uses Saudi open datasets related to commercial activity, SMEs, rent, and operating costs.
- Provides an Arabic right-to-left interface for local users.
- Helps beginner entrepreneurs compare opportunities before starting a business.

## Problem Statement

New entrepreneurs often depend on guesswork, informal advice, or expensive consulting when selecting a business idea. Although useful public data exists in Saudi Arabia, it is distributed across multiple sources and is not directly converted into simple recommendations.

This project provides a localized recommendation system that converts raw market indicators into understandable business suggestions based on the user’s selected city and available capital.

## Technologies Used

| Category | Technologies |
|---|---|
| Backend | Python, Flask |
| Data Processing | Pandas, NumPy |
| Recommendation Logic | Rule-Based Scoring |
| Frontend | HTML, CSS, JavaScript |
| Interface | Arabic RTL Design |
| Data Sources | Saudi Open Data |
| Deployment | Render |

## Dataset

The system uses several Saudi open datasets, including:

- Active Commercial Registrations 2024
- Number of SMEs 2024
- Operating Cost 2024
- Rental Indicators by City and Region

The full raw datasets are not included in this repository due to file size and data organization. Instead, this repository includes sample or processed data for demonstration purposes.

## Recommendation Approach

The recommendation engine evaluates each business activity using several indicators:

- Selected city and region
- Available investment capital
- Estimated required capital
- Estimated operating costs
- Rental cost indicators
- Competition level
- Capital surplus or capital gap

Based on these indicators, the system ranks business activities and presents the most suitable options to the user.
